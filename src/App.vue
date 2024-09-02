<script setup>
import addNewPost from "./components/addNewPost.vue";
import footeer from "./components/footeer.vue";
import HeaderS from "./components/headerS.vue";
import New from "./components/new.vue";
import PostsList from "/src/components/PostsList.vue";


</script>

<template >
    <New />
     <HeaderS />
     <div class="container">
        <addNewPost />
         <PostsList ></PostsList>
     </div>
     <footeer></footeer>
</template>
   
<style scoped>

.container  {
    max-width: 1200px;
    margin: auto;
    padding: 20px 20px;
}

.title__own {
    text-align: center;
    color: rgb(12, 14, 12);
    font-size: 50px;
    font-family: "log";
}

@font-face {
    font-family: "log" ;
    src: url("/src/components/fonts/Rubik-VariableFont_wght.ttf");
}

</style>
