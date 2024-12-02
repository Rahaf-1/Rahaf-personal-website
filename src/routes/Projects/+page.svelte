<script>
    import Container from "$lib/components/Container.svelte";
    import ProjectCard from "$lib/components/ProjectCard.svelte";
    import Title from "$lib/components/Title.svelte";
    import Button from "$lib/components/ui/button/button.svelte";
   
</script>
<svelte:head>
  <title>
    Projects
  </title>
  </svelte:head>


<Container class="flex flex-col gap-14">
   <Title title="Projects" />
   
  <ProjectCard title="Calculator" subtitle="" imageSrc="/project1.jpg">
    <p class="pb-5">
      This calculator has a clean, minimalist design with a soft pink color scheme and rounded edges. It features circular buttons for numbers and operations, including addition, subtraction, multiplication, division, percentage, clear, and equals. A rectangular display at the top shows inputs and results, and the standout red buttons for key functions add clear visual contrast.
    </p>
    <Button href="https://calculator-made-by-rahaf.netlify.app/" class="flex w-36">
     Try it
    </Button>
  </ProjectCard>
  <ProjectCard title="To Do List" subtitle="" imageSrc="/project2.jpg">
    <p class="pb-5">
      This to-do list features a clean lavender design with sections for remaining and completed tasks. Users can add tasks with a date and time, mark them as done with checkboxes, and delete them easily. It’s simple, organized, and user-friendly.
    </p>
    <Button href="https://to-do-list-by-rahaf.netlify.app/" class="flex w-36">
      Try it
     </Button>
  </ProjectCard>
</Container>