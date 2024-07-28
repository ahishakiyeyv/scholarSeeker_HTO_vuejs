<template>  
  <section class="section1">
    <div class="leftSide">
      <h1>Download app, Start drive, Earn money!</h1>
      <p>Download ScholrSeeker mobile app from playstore, create an account, apply for scholarship and find a fully funded scholarship outside your country. Get started</p>
      <div class="actionBtn">
        <button>Click me</button>
        <button>Click me</button>
      </div>
    </div>
    <div class="rightSide">
      <img src="@/assets/images/home-mock.png" alt="App screenshot">
    </div>
  </section>
  
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  
  data () {
    return{
    }
  },
  
}
</script>
<style scoped>
.section1{
  padding:11.5rem 4rem 8rem 8rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border:1px solid red;
}
.leftSide{
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  width:30rem;
  border:1px solid red;
}
.leftSide h1{
  font-size: 2rem;
}
.leftSide p{
  font-size: 1rem;
  line-height: 1.5rem;
}
.rightSide img{
  height:100px;
}
.actionBtn{
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>