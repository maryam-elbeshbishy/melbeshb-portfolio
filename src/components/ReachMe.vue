<template>
<div class="outer">
    <div class="flex-container">
        <h1>Contact Info and More!</h1>
    </div>

    <div class="flex-container">
        <figure class="item">
            <a href = "https://github.com/maryam-elbeshbishy">
            <img src="../assets/contactImg/GitHub.png" alt="Clip Art">
            </a>
            <figcaption class="caption">maryam-elbeshbishy</figcaption>
        </figure>

        <figure class="item">
            <a href = "https://www.linkedin.com/in/melbeshb/">
            <img src="../assets/contactImg/linkedIn.png" alt="Clip Art">
            </a>
            <figcaption class="caption">Maryam Elbeshbishy</figcaption>
        </figure>

        <figure class="item">
            <a href="tel:647-620-6733">
            <img src="../assets/contactImg/phone.png" alt="Clip Art">
            </a>
            <figcaption class="caption">647-620-6733</figcaption>
        </figure>

        <figure class="item">
            <a href = "mailto: maryam.elbeshbishy@ryerson.ca">
            <img src="../assets/contactImg/gmail.png" alt="Clip Art">
            </a>
            <figcaption class="caption">maryam.elbeshbishy@ryerson.ca</figcaption>
        </figure>

        <figure class="item">
            <a href="https://docs.google.com/document/d/11hOwx_vTrcj7g-eYgEt-gRve9jIjdRzK/edit?usp=sharing&ouid=111486397393515675101&rtpof=true&sd=true">
            <img src="../assets/contactImg/resume.png" alt="Clip Art">
            </a>
            <figcaption class="caption">Resume</figcaption>
        </figure>
	</div>	
</div>

</template>

<script>

export default {
    name: 'ReachMe',

}
</script>

<style scoped>
a{ 
    margin: 1vw;
    padding: 1vw;
}
.item {
    vertical-align: top;
    display: inline-block;
    text-align: center;
    width: 15vw;
    margin: 1vw;
    padding: 0vw;
}
.caption{ 
    font-size: 1vw
}
.outer{
    padding-top: 2vw;
    padding-bottom: 2vw;
    padding-left: 2vw;
    padding-right: 2vw;
    background-color: rgb(34, 34, 34);
    color: rgb(255, 255, 255);
}
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    align-items: flex-start;
}
.flex-container img{
    height: 4vw;
}
h1{
    font-size: 3vw;
}

</style>
