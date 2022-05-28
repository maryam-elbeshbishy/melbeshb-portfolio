<template>
<div class = "outer">
    <div class="flex-container">
        <h1>Now you might be wondering...who am I?</h1> 
    </div> 
    <div class="flex-container">
        <div class="item">
        <img src="../assets/Images/School2.png" alt="School"> 
        <p>Having been at Toronto Metropolitan for 3 years now, I can say with confidence that it has been a <b>great learning
        experience</b>, both through classes and through the relationships I've made. Besides attending class, I have made
        it a goal to get <b>involved in student life</b>, through the clubs sepcifically. I am an avid advocate for encouraging 
        women to join the computer science field, and decided become a part of the <b>Women in Computer Science</b> and <b>
        Undergraduate Women In Stem </b> community in my past semesters.</p>
    
        </div>

        <div class="item">
        <img src="../assets/Images/Hobbies2.png" alt="Hobbies">    
        <p>Apart from school, I like to engage my <b>creative side through drawing </b>. I enjoy abstract art as well as art that includes 
        geometry and I hope to be able to use both my art and technical skills to create elevated artworks. <b>I also enjoy cubing</b>
        (like the infamous <b>Rubicks Cube</b>), with my fastest record being ~41 seconds! Recently, I have become <b>interested in creating 
        videos</b> to document my learning process of technical skills, to serve as memories of far I've come, but I have 
        got a long way to go with learning video editing before I can master it.
        </p>
        
        </div>
        
        <div class="item">
        <img src="../assets/Images/Aspirations2.png" alt="Aspirations"> 
        <p>In terms of my goals, the most important rule is that <b>I enjoy the work I do</b>. I was interested in web development, from the courses I had taken,
            until I got the Quest 2 (VR headset). After playing a few games in virtual Reality, I realized that the potential to 
            create games or appliations that are useful (visualization/ education) was huge.I started doing research on Virtual
            Reality Dev, and now made it my <b>goal to work in the VR/AR/XR development field</b>. The first step I've taken is to learn Unity, which you can learn 
            about in the next section!
         </p>
        </div>
        
    </div>
</div>
    
</template>
   
<script>

export default ({
    name: 'AboutMe',

    components: {

    },
})
</script>

<style scoped>
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: flex-start;
}
.flex-container img{
    width: 30vh;
    height: 30vh;
    margin-right: 1vh;
    padding: 1vh;
}
h1{
    font-size: 6vh;
}
p {
    font-size: 2.5vh;
    text-align: justify;
    
}
.item{ 
    max-width: 25vw;
}
.outer{
    padding-top: 5vh;
    padding-bottom: 10vh;
    padding-left: 10vh;
    padding-right: 10vh;
    background-color: rgb(255, 249, 251);
    color: rgb(34, 34, 34);
}
</style>
