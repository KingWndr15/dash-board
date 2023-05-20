<template>
  <SideNavComponent />
  <div class="wrapper">
    <div class="header-wrapper">
      <h1>Home</h1>
      <div class="header-action">
        <button class="sign-in">Sign In</button>
        <button class="create-account">Create Account</button>
      </div>
    </div>
    <HeaderComponent />
  </div>
</template>

<script>
import SideNavComponent from "@/components/SideNavComponent.vue";
import HeaderComponent from "./components/HeaderComponent.vue";

export default {
  name: 'App',
  components: {
    SideNavComponent,
    HeaderComponent
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@100;200;300;400;500;600;700&family=IBM+Plex+Serif:wght@100;200;300;400;500;600;700&display=swap');

  * {
    margin: 0;
    padding: 0px;
    font-family: Arial, Helvetica, sans-serif;
  }

  #app {
    background: #f6f6f6;
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
  }

  h1, h2, h3, h4, h5, h6 {
    font-family: 'IBM Plex Serif';
    font-weight: 400;
    font-size: 32px;   
  }

  button {
    cursor: pointer;
    border: none;
    font-family: Arial, Helvetica, sans-serif;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 700;
    font-size: 15px;
  }

  .wrapper {
    margin-left: 200px;
    margin-top: 32px;
    width: 70%;
  }
  .header-wrapper {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    margin: 0px 0px 48px;
  }
  .header-action {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 12px;
  }

  .header-action .sign-in {
    background: #FFFFFF;
    border: 1px solid #222222;
    border-radius: 8px;
    padding: 10px 13px;
  }

  .header-action .create-account {
    background: #513DFF;
    color: #FFFFFF;    
    border: none;
    border-radius: 8px;
    padding: 10px 15px;
  }

</style>
