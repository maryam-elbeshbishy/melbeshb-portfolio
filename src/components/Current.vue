<template>
    <div class="outer">

        <h1>What am I currently working on?</h1>
        <img src="../assets/Images/CurrentWorking.png" alt="Clip Art">

        <p>
        Currently, I am <b>working on learning Unity</b>, more specifically <b>Virtual Reality Development</b>. 
        Right now I am in my first steps of learning. I've understood how to make a new project, and set up 
        the packages and settings required to work with the Quest 2 -- I plan to <b>make a template</b> in the future to 
        make this process easy. Now I am learning how to create hand animations with button interactions. The <b>end goal 
        is to create a simple maze</b> so that I can get a grasp on how Unity works, and expand it to some sort of 
        escape room, since those games are quite interesting to me. 
        <br>
        <br>
        In the <b>future I also want to create a rock climbing wall</b> (mostly because I enjoy heights and am curious to know 
        how far up I can build the wall). I also want to steer away from only games, and <b>create immersive visual arts 
        projects</b>, so that users are able to experience arts in a new way. Because I would like to create these art pieces
        <b>I would like to learn Blender</b>, so that I have a new tool under my belt.
        <br>
        <br> 
        <b>More here:</b> Youtube video link 
        </p>
    </div>  
</template>

<script>

export default ({
    name: 'CurrentPage',

    components: {

    },
})
</script>

<style scoped>
.outer{
    padding-top: 5vh;
    padding-bottom: 10vh;
    padding-left: 30vh;
    padding-right: 30vh;
    background-color: rgb(34, 34, 34);
    color: rgb(255, 255, 255);
}
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: flex-start;
}
img{
    margin: 3vh;
    margin-bottom: 6vh;
    height: 50vh;
    border-radius: 1vh;
    box-shadow: 3px 3px 8px 3px rgba(127, 5, 38, 0.672); 
}
p {
    font-size: 2.5vh;
    text-align: justify;
}
</style>
