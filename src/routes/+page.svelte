<script>
// @ts-nocheck

    import Button from "$lib/components/ui/button/button.svelte";
</script>

<div class="flex flex-row items-center justify-center pt-16">
    <svg
        class=" w-12 h-auto mt-2 mr-5 fill-primary/60"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 256 256"
        ><path
            fill="primary"
            d="M240 128a15.79 15.79 0 0 1-10.5 15l-63.44 23.07L143 229.5a16 16 0 0 1-30 0l-23.06-63.44L26.5 143a16 16 0 0 1 0-30l63.44-23.06L113 26.5a16 16 0 0 1 30 0l23.07 63.44L229.5 113a15.79 15.79 0 0 1 10.5 15"
        /></svg
    >
    <div class="font-extrabold text-center text-5xl md:text-7xl">
        Hi. I'm Rahaf
    </div>
    <svg
        class=" w-12 h-auto mt-2 ml-5 fill-primary/60"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 256 256"
        ><path
            fill="primary"
            d="M240 128a15.79 15.79 0 0 1-10.5 15l-63.44 23.07L143 229.5a16 16 0 0 1-30 0l-23.06-63.44L26.5 143a16 16 0 0 1 0-30l63.44-23.06L113 26.5a16 16 0 0 1 30 0l23.07 63.44L229.5 113a15.79 15.79 0 0 1 10.5 15"
        /></svg
    >
</div>
<div class="pt-4 text-lg text-center">
    I'm a software engineering student, interested in UX/UI desing & front-end web development
</div>
<div class="flex flex-row items-center justify-center pt-5">
        <Button href="/Projects" class="h-7 w-36 rounded-full mr-20 bg-primary/60">
            <svg
                xmlns="http://www.w3.org/2000/svg"
                class=" h-5 w-5 rotate-90 me-0 fill-background"
                viewBox="0 0 24 24"
                ><path
                    d="M8.53 10.53a.75.75 0 1 1-1.06-1.06l4-4a.75.75 0 0 1 1.06 0l4 4a.75.75 0 1 1-1.06 1.06l-2.72-2.72v9.69a.75.75 0 0 1-1.5 0V7.81z"
                /></svg
            >
            <div class="flex-1 text-center text-xs text-background">
                see my project
               </div>
        </Button>
    <Button href="/About" class="h-7 w-36 rounded-full ml-20 bg-primary/60">
        <svg
            xmlns="http://www.w3.org/2000/svg"
            class=" w-5 h-5 rotate-90 me-1 fill-background"
            viewBox="0 0 24 24"
            ><path
    
                d="M8.53 10.53a.75.75 0 1 1-1.06-1.06l4-4a.75.75 0 0 1 1.06 0l4 4a.75.75 0 1 1-1.06 1.06l-2.72-2.72v9.69a.75.75 0 0 1-1.5 0V7.81z"
            /></svg
        >
        <div class="flex-1 text-center text-xs text-background">
            more about me
           </div>

    </Button>
</div>
