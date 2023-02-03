<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile-section">
                    <img src="../assets/profilepic.jpg" alt="">
                </div>
                <div class="social-links">
                        <div class="link">
                            <a href=""><img src="../assets/Github_black.png" alt="">
                            <h2>GitHub</h2></a>
                        </div>
                        <div class="link">
                            <a href=""><img src="../assets/LinkedIN_black.png" alt="">
                            <h2>LinkedIn</h2></a>
                        </div>
                        <div class="link">
                            <a href=""><img src="../assets/Youtube_black.png" alt="">
                            <h2>Youtube</h2></a>
                        </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about-me">
                    <h1>Hi, I'm Lon Russel</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum, tempore laudantium? 
                        Optio placeat unde esse adipisci consequuntur. 
                        Sed, eaque cupiditate? Qui harum dicta atque ipsum illo 
                        quibusdam officia praesentium magni.</p>
                </div>
                <div class="technology-section">
                    <h1>Technologies</h1>
                    <div class="logos">
                        <img src="../assets/java-script.png" alt="">
                        <img src="../assets/html-5-logo.png" alt="">
                        <img src="../assets/css-3.png" alt="">
                    </div>
                </div>
                <div class="button-container">
                    <div class="projects-button">
                        <a href="">My Projects</a>
                    </div>
                    <div class="projects-button">
                        <a href="">My Resume</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .wrapper{
        display: flex;
        justify-content: center;
    }
    img{
        height: 30px;
    }
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: rgb(205, 205, 165);
        border-radius: 25px;
        width: 80%;
        background-color: #a0d4ff;
    }
    .container-one{
        background-color: blanchedalmond;
        padding: 3%;
        width: 30%;
        border-radius: 25px;
        background-color: #507695;
    }
    .profile-section img{
        height: 5em;
        border-radius: 50%;
    }
    .link a{
        padding-left: 5%;
        font-size: 10px;
        text-decoration: none;
        color: black;
        display: flex;  
        flex-direction: row;
    }
    .link a img{
        margin-right: 5%;
        align-self: center;
    }
    .container-two{
        margin: 2.5%;
        width: 70%;
    }
    .about-me{
        text-align: left;
    }
    .button-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }
    .projects-button{
        background-color: aquamarine;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;
    }
    .projects-button a{
        text-decoration: none;
        color: black;
    }

    @media only screen and (max-width: 950px){
        .main-container{
            width: 95%;
        }
        
    }
</style>