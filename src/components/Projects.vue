/* eslint-disable */
<template>
<div class="outer">
    <div class="flex-container">
        <h1>Projects!</h1>
    </div>

    <div class="flex-container">
        <h2>Collection of recent projects and skills</h2>
    </div>

    <div class="flex-container">
    
        <figure class="item" v-for="item in items" :key="item.id">
            <img class="projImg" :src="require(`../assets/ProjectsImg/${item.image}`)" alt="PROJECT IMAGE"/>

            <figcaption class="caption">
                <h2> 
                    <a :href="item.github">
                    <img class="link" src="../assets/Images/githubLogoBlack.png">
                    </a>
                    <b>{{item.title}}</b>
                </h2>
                <h4>{{item.tools}}</h4>
                <p>
                {{item.description}}</p>
                
            </figcaption>
        </figure>

	</div>	
</div>

</template>

<script>
import ProjectItems from '../assets/Projects.json'
export default {
    name: 'ProjectsPage',
    data() {
        return {
            items: ProjectItems,
        }
    }
}
</script>

<style scoped>
div.item {
    vertical-align: top;
    display: inline-block;
    text-align: center;
}
.outer{
    padding-top: 5vh;
    padding-bottom: 5vh;
    padding-left: 1vh;
    padding-right: 1vh;
    background-color: rgb(255, 249, 251);;
    color: rgb(34, 34, 34);
}
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: flex-start;
}
.link{ 
    height: 3vh;
}
.projImg{
    margin: 3vh;
    margin-bottom: 1vh;
    box-shadow: 3px 3px 8px 2px rgba(117, 4, 53, 0.842); 
    height: 25vh;
    border-radius: 10%;
}
h1{
    font-size: 6vh;
}
.item{ 
    padding: 2vh;
    max-width: 15vw;
}
a{
    padding: 1vh
}
h4{ 
    color: rgb(207, 59, 98)
}
p{ 
    text-align: justify;
}

</style>
