<template>
    <div class="flex-container">
        <div><img src="../assets/Images/ProfileImage.jpg" alt="Image of Maryam Elbeshbishy"></div>
        <div>
            <h1>Maryam <br>Elbeshbishy</h1>
            <h2>3rd Year Computer Science Student </h2>
            <h2>Toronto Metropolitan University (Ryerson University)</h2>
        </div>
    </div>
</template> 

<script>

export default ({
    name: 'IntroPage',

    components: {

    },
})
</script>

<style scoped>
/* flexbox properties */
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    padding: 12vh;
}
div{
    background-color: rgb(34, 34, 34);
    color: white;
    padding: 5vh;
    text-align: left;
}
img{
    width:55vh;
    height: 55vh;
    border-radius: 50%;
    
}
h1{
    font-size: 10vh;
    color: rgb(207, 59, 98)
}

</style>
