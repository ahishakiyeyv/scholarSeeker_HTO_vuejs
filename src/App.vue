<template>
  <NavigationMenu/>
  <router-view/>
  
</template>
<script>
import NavigationMenu from './components/NavigationMenu.vue';
export default {
  
  components:{
    NavigationMenu
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
*{
  font-family: "Montserrat", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
  margin:0;
  padding:0;
  box-sizing: border-box;
}
:root{
  --title-color:#1A8FE3;
  --text-color:#64748B;
  --primary-color:#333;
}
::-webkit-scrollbar{
  width:5px;
}
::-webkit-scrollbar-thumb{
  background:#48B0D3;
  border-radius:10px;
}
</style>
