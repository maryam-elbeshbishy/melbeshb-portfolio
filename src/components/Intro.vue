<template>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="flex-container">
        <div><img src="../assets/Images/ProfileImage.jpg" alt="Image of Maryam Elbeshbishy"></div>
        <div>
            <h1>Maryam <br>Elbeshbishy</h1>
            <h2>4th Year Computer Science Student </h2>
            <h2>Toronto Metropolitan University (Ryerson University)</h2>
        </div>
    </div>
</body>
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
    padding-top: 8vw;
    padding-bottom: 8vw;
}
div{
    background-color: rgb(34, 34, 34);
    color: white;
    padding: 2vw;
    text-align: left;
}
img{
    width:25vw;
    height: auto;
    border-radius: 50%;
    
}
h1{
    font-size: 4vw;
    color: rgb(207, 59, 98)
}
h2 { 
    font-size: 1.5vw
}


</style>
