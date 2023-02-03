<template>
    <div class="navbar-main-container">
        <div class="name-logo"> <h2>Lon Russel</h2> </div>
        <div class="nav-buttons">
            <a href="">Projects</a>
            <a href="">Experiences</a>
            <a href="">Contacts</a>
            <a href="">Resume</a>
        </div>
    </div>
        
</template>
<script>
export default {
    
}
</script>
<style>
    .navbar-main-container{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
    }
    .name-logo{
        float: left;
        padding-left: 50px;
    }
    .nav-buttons{
        display: inline-block;
        padding: 30px 50px 30px 0px;
    }

    .nav-buttons a{
        font-size: .837rem;
        font-weight: 500;
        text-decoration: none;
        color: #395144;
        margin: 5px;
    }

    .nav-buttons a:hover{
        color: #AA8B56;
    }
    
</style>