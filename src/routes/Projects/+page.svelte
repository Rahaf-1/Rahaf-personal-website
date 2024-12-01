<script>
    import Container from "$lib/components/Container.svelte";
    import ProjectCard from "$lib/components/ProjectCard.svelte";
    import Title from "$lib/components/Title.svelte";
   
    

</script>
<Container class="flex flex-col gap-14">
   <Title title="Projects" />
   <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero et aperiam qui veniam nisi sequi, omnis architecto magnam magni nobis quis numquam ut veritatis iste ipsa excepturi, consequuntur similique dolorem?
   </p>
  <ProjectCard title="Rahaf" subtitle="Software Engineer Student" imageSrc="/project1.jpg">
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur id illum quibusdam suscipit quidem quis adipisci et ut, aliquam cum, deleniti labore quaerat, reiciendis quo enim sunt fugiat voluptatibus. Quos.
    </p>
  </ProjectCard>
  <ProjectCard title="Rahaf" subtitle="Software Engineer Student" imageSrc="/project2.jpg">
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur id illum quibusdam suscipit quidem quis adipisci et ut, aliquam cum, deleniti labore quaerat, reiciendis quo enim sunt fugiat voluptatibus. Quos.
    </p>
  </ProjectCard>
</Container>