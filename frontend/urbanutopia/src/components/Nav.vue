<template>
    <nav>
        <img :src="logo" alt="" class="img">
        <div class="btns">
            <a href="">login</a>
        </div>
    </nav>
</template>


<script>
import logo from '@/assets/UrbanUtopia-logo.png'; // Adjust path according to your project structure

export default {
  data() {
    return {
      logo: logo
    } 
  }
}
</script>

<style scoped>
    nav {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        margin: 0;
        background-color: black;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding-right: 1%;
    }

    .img {
        height: 8%;
        width: 8%;
    }

    .btns a {
        text-decoration: none;
        color: white;
    }
</style>
