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
    padding-top: 2vw;
    padding-bottom: 2vw;
    padding-left: 1vw;
    padding-right: 1vw;
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
    height: 1.5vw;
}
.projImg{
    margin: 1vw;
    margin-bottom: 1vw;
    box-shadow: 3px 3px 8px 2px rgba(117, 4, 53, 0.842); 
    height: 12vw;
    border-radius: 10%;
}
h1{
    font-size: 3vw;
}
.item{ 
    margin: 0.5vw;
    padding: 0.5vw;
    max-width: 16vw;
}
h2{ 
    font-size: 1.5vw;
}
a{
    padding: 0.5vw
}
h4{ 
    font-size: 1.1vw;
    color: rgb(207, 59, 98)
}
p{ 
    font-size: 1.0vw;
    text-align: justify;
}

</style>
