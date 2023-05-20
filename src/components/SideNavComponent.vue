<template>
    <nav>
        <div class="nav-primary">
            <!-- logo -->
            <img src="@/assets/images/logo.svg" alt="" class="logo">

            <div class="links mt-2">
                <div class="home">
                    <img src="@/assets/icons/home-icon.svg" alt="">
                    <p>Home</p>
                </div>

                <div>
                    <img src="@/assets/icons/work-icon.svg" alt="">
                    <p>Apprenticeships</p>
                </div>
                
                <div>
                    <img src="@/assets/icons/book-icon.svg" alt="">
                    <p>Courses</p>
                </div>

                <div>
                    <img src="@/assets/icons/bolt-icon.svg" alt="">
                    <p>MicroTasks</p>
                </div>
            </div>
        </div>

        <button class="feedback">
            <img src="@/assets/icons/colored-icons/feedback-icon.svg" alt="">
            <p>Feedback</p>
        </button>
    </nav>
</template>

<script>
    export default {
        name: 'SideNavComponent'
    }
</script>

<style>
    nav {
        /* position: relative; */
        position: absolute;
        width: 200px;
        height: 100%;
        background: #fff;
        display: flex;
        align-items: center;
        justify-content: space-between;
        flex-direction: column;
        left: 0px;
        top: 0px;
    }
    nav .nav-primary {
        display: flex;
        align-items: flex-start;
        justify-content: flex-start;
        flex-direction: column;
        width: 85%;
        gap: 29px;
        margin-top: 30px;
    }
    nav .nav-primary .logo {
        width: 30px;
    }
    
    nav .nav-primary .links {
        display: flex;
        align-items: flex-start;
        justify-content: space-between;
        gap: 30px;
        flex-direction: column;
    }
    
    nav .nav-primary .links div {
        display: flex;
        align-items: center;
        justify-content: flex-end;
        gap: 16px;
        cursor: pointer;
    }
    
    nav .nav-primary .links div p { 
        color: #727272;
        font-weight: 700;
    }
    
    nav .nav-primary .links div p:hover {
        cursor: pointer;
    }

    nav .nav-primary .links .home p {
        color: #222222;
    }

    nav button {
        padding: 12px 30px;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 8px;
        margin-bottom: 20px;
        border: none;
        background: #EFEEFF;
        border-radius: 8px;
        color: #3634A3;
    }
</style>