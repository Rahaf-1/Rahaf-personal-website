<script lang="ts">
 export let title: string;
 export let subtitle: string;
 export let imageSrc: string;
</script>

<div class="bg-secondary shadow-xl flex flex-col sm:flex-row gap-4 p-6 ">
<div class="flex flex-col gap-16 pt-8">
<div class="flex flex-col min-w-32 border-s-8 border-primary ps-8">
<span class="font-bold text-primary text-xl">
{title}
</span>
<span>
    {subtitle}
</span>
</div>
<div class="ps-8 pb-8">
<slot />
</div>
</div>
 <!-- svelte-ignore a11y-img-redundant-alt -->
 <img src={imageSrc} alt="project picture" class="w-auto sm:w-64 object-cover"/>
    </div>