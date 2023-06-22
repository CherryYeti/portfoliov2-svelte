<script>
    import Title from "../title.svelte";
    import Card from "../card.svelte";
</script>

<div class='projects' id='projects'>
    <Title text='Projects' />
    <div class='cards'>
      <Card
        link='https://github.com/CherryYeti/FireStarter'
        img='fs.png'
        name='FireStarter (Archived due to lack of time)'
        description='FireStarter is a free and open source Discord bot used to start, stop and manage options on your minecraft servers using Node.js'
      />
      <Card
        link='https://github.com/CherryYeti/portfoliov2'
        img='snippet.png'
        name='This Portfolio'
        description='This portfolio was created entirely from scratch in react in a few days.'
      />
      <Card
        link='https://github.com/CherryYeti'
        img='github.png'
        name='My Github'
        description='You can visit my github to see the source code for all of my projects'
      />
    </div>
  </div>
<style>
    .projects {
    margin-top: 40px;
}
.cards {
    margin-left: 10%;
    margin-right: 10%;
    display: grid;
    grid-template-columns: auto auto auto;
    column-gap: 70px;
    row-gap: 15px;
}
@media screen and (max-width:874px) {
    .cards{
        grid-template-columns: 1fr;
    }
}
</style>