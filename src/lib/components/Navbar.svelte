<script>
    // @ts-nocheck

    import Button from "./ui/button/button.svelte";
    import { page } from "$app/stores";
    import * as Sheet from "$lib/components/ui/sheet";
    import ThemeSwitch from "./ThemeSwitch.svelte";

    const links = [
        {
            text: "HOME",
            href: "/",
        },
        {
            text: "ABOUT",
            href: "/About",
        },
        {
            text: "PROJECTS",
            href: "/Projects",
        },
        {
            text: "CONTACT",
            href: "/Contact",
        },
    ];

    let isSheetOpen = false;
</script>

<header
class="text-secondary-foreground py-8 px-6 flex justify-between items-center mx-auto"
>
    <div>
        <Button href="/" variant="primary">
            <svg
                class=" w-12 h-auto ms-2"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 256 256"
                ><path
                    fill="currentColor"
                    d="M240 128a15.79 15.79 0 0 1-10.5 15l-63.44 23.07L143 229.5a16 16 0 0 1-30 0l-23.06-63.44L26.5 143a16 16 0 0 1 0-30l63.44-23.06L113 26.5a16 16 0 0 1 30 0l23.07 63.44L229.5 113a15.79 15.79 0 0 1 10.5 15"
                /></svg
            >
        </Button>
    </div>
    <!-- icon check -->
    <Sheet.Root bind:open={isSheetOpen}>
        <div class=" flex me-2">
                <ThemeSwitch  />
            <Sheet.Trigger>
                <Button size="icon" variant="primary">
                    <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="w-10 h-auto"
                        viewBox="0 0 24 24"
                        ><g fill="none"
                            ><path
                                d="M24 0v24H0V0zM12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035q-.016-.005-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427q-.004-.016-.017-.018m.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093q.019.005.029-.008l.004-.014l-.034-.614q-.005-.019-.02-.022m-.715.002a.02.02 0 0 0-.027.006l-.006.014l-.034.614q.001.018.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01z"
                            /><path
                                fill="currentColor"
                                d="M20 18a1 1 0 0 1 .117 1.993L20 20H4a1 1 0 0 1-.117-1.993L4 18zm0-7a1 1 0 1 1 0 2H4a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H4a1 1 0 0 1 0-2z"
                            /></g
                        ></svg
                    >
                </Button></Sheet.Trigger
            >
        </div>
        
        <Sheet.Content class="flex flex-col justify-center">
            {#each links as link}
                <Button
                    class=" text-xl {$page.url.pathname == link.href &&
                        'bg-primary text-secondary'}"
                    href={link.href}
                    variant=" "
                    on:click={() => (isSheetOpen = false)}
                    >{link.text}
                </Button>
            {/each}
        </Sheet.Content>
    </Sheet.Root>
</header>

