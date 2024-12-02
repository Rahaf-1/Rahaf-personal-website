<script>
 import Button from "$lib/components/ui/button/button.svelte";
  </script>

<svelte:head>
  <title>
     About Me
  </title>
  </svelte:head>

<div class="flex justify-end pb-[28rem]  lg:pb-0 ">
    <div class="bg-secondary relative w-full lg:w-[60vw] min-h-[40vh] lg:min-h-[calc(100vh-10.5rem)] flex justify-center items-center pb-20 ">
      <div class="bg-[#fff9ef] shadow-[0_10px_60px_-15px_rgba(0,0,0,0.7)] w-[20rem] absolute lg:start-10 lg:-translate-x-full flex flex-col items-center gap-2 pt-16 justify-between self-bottom lg:self-start translate-y-[110%] lg:translate-y-[15%] max-w-[85vw] ">
     <!-- svelte-ignore a11y-img-redundant-alt -->
     <img src="/profilei.png" class="rounded-full w-60" alt="personal picture" />
    <div class="flex flex-col items-center  gap-2 ">
      <h1 class=" font-bold text-4xl text-[#4c6763] ">
        Rahaf
            </h1>
            <hr class="w-20 border-1 border-[#4c6763]">
            <h2 class="text-[#4c6763]">
              Software Engineer Student
            </h2>
    </div>
<div class="w-full flex justify-evenly p-2 m-5">
  <Button variant="circle" size="icon" href="https://x.com/imrahaf_5">
  <svg xmlns="http://www.w3.org/2000/svg" class=" w-4 fill-background" viewBox="0 0 24 24"><path  d="m17.687 3.063l-4.996 5.711l-4.32-5.711H2.112l7.477 9.776l-7.086 8.099h3.034l5.469-6.25l4.78 6.25h6.102l-7.794-10.304l6.625-7.571zm-1.064 16.06L5.654 4.782h1.803l10.846 14.34z"/></svg>
</Button>

<Button variant="circle" size="icon" href="">
  <svg xmlns="http://www.w3.org/2000/svg" class=" w-4 fill-background" viewBox="0 0 24 24"><path  d="M18.336 18.339h-2.665v-4.177c0-.996-.02-2.278-1.39-2.278c-1.389 0-1.601 1.084-1.601 2.205v4.25h-2.666V9.75h2.56v1.17h.035c.358-.674 1.228-1.387 2.528-1.387c2.7 0 3.2 1.778 3.2 4.092v4.714M7.004 8.575a1.546 1.546 0 0 1-1.548-1.549a1.548 1.548 0 1 1 1.547 1.549m1.336 9.764H5.667V9.75H8.34zM19.67 3H4.33C3.594 3 3 3.58 3 4.297v15.406C3 20.42 3.594 21 4.328 21h15.339C20.4 21 21 20.42 21 19.703V4.297C21 3.581 20.4 3 19.666 3z"/></svg>
</Button>



</div>
      </div>
      <div class="mx-10 max-w-[30rem] flex flex-col gap-8 pt-28">
        <h1 class="text-8xl font-bold">
          Hello
        </h1>
        <h4 class="text-4xl">
         Here's who I am & what I do
        </h4>
        <div class="flex gap-4">
        <Button href="/Contact" variant="outline" class="w-36">
          Contact
        </Button>
        <Button href="/Projects" variant="outline" class="w-36">
          Projects
        </Button>
        </div>
        <div>
          <p class="font-semibold">
            Welcome to My Website!
          </p>
          <p>
            Hi, I’m Rahaf! I’m a Software Engineering student at Umm Al-Qura University and a designer at the UQU Computing Club. I’m passionate about front-end development and currently exploring the world of UX/UI design.
            In my free time, I enjoy drawing and expressing creativity through art. I’m excited to share my journey and interests with you. Let’s connect and be friends!
          </p>
        </div>
      </div>
    </div>
</div>

