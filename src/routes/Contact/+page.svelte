<script>
    import Input  from "$lib/components/ui/input/input.svelte";
    import Label from "$lib/components/ui/label/label.svelte";
    import Container from "$lib/components/Container.svelte";
    import Title from "$lib/components/Title.svelte";
    import Textarea from "$lib/components/ui/textarea/textarea.svelte";
    import Button from "$lib/components/ui/button/button.svelte";
</script>

<svelte:head>
  <title>
    Contact with me
  </title>
  </svelte:head>

<Container class="flex flex-col gap-16">
    <Title title="Let's Talk" />

<form class="bg-secondary p-8 flex flex-col gap-8 text-secondary-foreground"
action="https://formsubmit.co/roofaj1029@gmail.com"
method="POST"
>

    <div class=" flex flex-col gap-3" >
    <Label for="name">Full Name</Label>
    <Input required name="name" id="name" placeholder="Write your name.... "/>
    </div>
    <div class=" flex flex-col gap-3" >
        <Label for="email">Email</Label>
        <Input required name="email" type="email" id="email" placeholder="Example@gmail.com"/>
        </div>
        <div class=" flex flex-col gap-3" >
            <Label for="subject">Subject</Label>
            <Input required name="subject" id="subject" placeholder="...."/>
            </div>
            <div class=" flex flex-col gap-3" >
                <Label for="message">Message</Label>
                <Textarea rows={3} required name="message" id="message" placeholder="...."/>
                </div>
    
 <Button type="submit">
 SEND
 </Button>
</form>
</Container>