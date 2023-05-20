<template>
    <div class="container">
        <div class="text-area">
            <p class="title">Welcome to Acadium</p>
            <h1 class="content">Start your digital marketing career</h1>
            <p class="description">Gain the skills, work experience, and resources you need to start your career in digital marketing online.</p>

            <div class="buttons">
                <button class="career-button">Launch My Career <img src="@/assets/icons/arrow-left.svg" alt=""></button>
                <button class="business-button"><img src="@/assets/icons/building-icon.svg" alt=""> I'm a Business</button>
            </div>
        </div>
       <div class="image">
       </div> 
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style>

    .container {
        padding: 40px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        border-radius: 16px;
        background: #fff;
    }

    .text-area {
        display: flex;
        align-items: flex-start;
        justify-content: flex-start;
        flex-direction: column;
        gap: 12px;
    }

    .text-area .title {
        font-weight: 700;
        font-size: 14px;    
        text-transform: uppercase;
        color: #727272;
    }

    .text-area .description {
        color: #444444;
    }
    
    .text-area .buttons {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 10px;
        margin-top: 12px;
    }

    .text-area .career-button {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 20px;
        background: #513DFF;
        border-radius: 12px;
        padding: 12px 12px 12px 25px;
        color: #FFFFFF;
    }

    .text-area .business-button {
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 10px;
        border: 1px solid #444444;
        background: #FFFFFF;
        border-radius: 12px;
        padding:  8px 25px;  
    }

    .image {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 128px;
        height: 128px;
        background-image: url(@/assets/images/hero.png);
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
    }
</style>