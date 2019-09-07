<template>
    <main class='mainContainer'>
        <Scrollama @step-enter="stepEnterHandler"
        :debug="true"
        :offset="0.5">
        <section class='textContainer' id='lorem'>
            <h2 id='lorem-title' class='title'>Lorem</h2>

            <p class='text'>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid cumque non quaerat vitae animi? Assumenda nostrum alias corporis fugiat facilis vero ducimus, beatae aliquam, in perferendis, consectetur saepe unde velit. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid cumque non quaerat vitae animi? Assumenda nostrum alias corporis fugiat facilis vero ducimus, beatae aliquam, in perferendis, consectetur saepe unde velit.</p>
        </section>

        <section class='textContainer' id='ipsum'>
            <h2 class='title'>Ipsum</h2>

            <p class='text'>Fixie dirty durham consensus big green wall beaver queen sustainable urban ministries dapper, broad street wool e bull old north innovation bowtie maker, southsquare historic preservation maker full frame sodu the buehler. The bulls hipster blues major sodu duke chapel dino trail eagles, major the state of things ninth street miami boulevard diy. Durham goldenbelt duke park local erwin road saint joseph's, start-up adf miami boulevard bulltown strutters ccb plaza french press, erwin terrace the double nickel merge records elf. Angier drive medicine dance the indy one forty seven train arm wrestling, duke chapel university science and math partner erwin square black wall street major, seventy french press dance dur'm 15-501. Blue devils bouncing bulldogs third fridays the double nickel chapel drive beer doughman seventy west village wunc, northeast central luewwd hipster hub coworking erwin square authentic innovation. Seeds the buehler oprah building walltown arm wrestling historic preservation local, blackwell urban ministries old north the kress historic preservation doughman, trinity park foodie bay 7 eno river bragtown.</p>
        </section>
        <img src='http://placekitten.com/600/800' slot='graphic' alt-text='Place kitten' class='graphic placeKitty '/>
        <section class='textContainer' id='dolor'>
            <h2 class='title'>Dolor</h2>
            
            <div class='halfContainer'>
                <p class='halfText'>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid cumque non quaerat vitae animi? Assumenda nostrum alias corporis fugiat facilis vero ducimus, beatae aliquam, in perferendis, consectetur saepe unde velit. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid cumque non quaerat vitae animi? Assumenda nostrum alias corporis fugiat facilis vero ducimus, beatae aliquam, in perferendis, consectetur saepe unde velit.</p>
                
            </div>
        </section>

        <section class='textContainer' id='sit'>
            <h2 class='title'>Sit</h2>

            <p class='text'>Fixie dirty durham consensus big green wall beaver queen sustainable urban ministries dapper, broad street wool e bull old north innovation bowtie maker, southsquare historic preservation maker full frame sodu the buehler. The bulls hipster blues major sodu duke chapel dino trail eagles, major the state of things ninth street miami boulevard diy. Durham goldenbelt duke park local erwin road saint joseph's, start-up adf miami boulevard bulltown strutters ccb plaza french press, erwin terrace the double nickel merge records elf. Angier drive medicine dance the indy one forty seven train arm wrestling, duke chapel university science and math partner erwin square black wall street major, seventy french press dance dur'm 15-501. Blue devils bouncing bulldogs third fridays the double nickel chapel drive beer doughman seventy west village wunc, northeast central luewwd hipster hub coworking erwin square authentic innovation. Seeds the buehler oprah building walltown arm wrestling historic preservation local, blackwell urban ministries old north the kress historic preservation doughman, trinity park foodie bay 7 eno river bragtown.</p>
        </section>

        <section class='textContainer' id='amet'>
            <h2 class='title'>Amet</h2>

            <p class='text'>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid cumque non quaerat vitae animi? Assumenda nostrum alias corporis fugiat facilis vero ducimus, beatae aliquam, in perferendis, consectetur saepe unde velit. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aliquid cumque non quaerat vitae animi? Assumenda nostrum alias corporis fugiat facilis vero ducimus, beatae aliquam, in perferendis, consectetur saepe unde velit.</p>
        </section>
        </Scrollama>
    </main>
</template>

<script>
import "intersection-observer";
import Scrollama from "vue-scrollama";

export default {
    name: "Main",
    components: {
        Scrollama
  },
    data: () => {
        return {
            currStep: null
    };
  }
}
</script>

<style src="vue-scrollama/dist/vue-scrollama.css"></style>