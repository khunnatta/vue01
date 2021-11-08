<template>

<div class="main">
  <header>
    <div class="topNav">
      <img class="navLogo" src="../assets/logo.png" alt="">
      <ul class="navList">
        <li><a href="/">Home</a></li>
        <li><a href="/">List</a></li>
      </ul>
    </div>
  </header>

  <div class="part1">
    <div class="section1">
      <h1>Section1</h1>
    </div>
    <div class="section2">
      <h1>Section2</h1>
    </div>
  </div>
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Prompt:wght@200;300;400;500;600;700&display=swap');

.main {
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

header {
  width: 100%;
  background:#9fefc8;
}

.topNav{
  width: 90%;
  margin: 0 auto;
  background: #9fefc8;
  display: flex;
  flex-direction: row;
  align-items:center;
  justify-content: space-between;
}

.navLogo{
  margin: 5px 0px;
  width: 3rem;
}

.navList{
  font-family: 'Prompt', sans-serif;
  font-size: 20px;
  margin: 0;
}

a {
  text-decoration: none;
}

a:hover {
  color: #e9eceb
}

.part1{
  width: 80%;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.section1{
  width: 60%;
  height: 500px;
  border: 2px solid;
  border-color: rgba(128, 128, 128, 0.541);
  border-radius: 15px;
  margin: 10px;
}

.section2{
  width: 40%;
  height: 500px;
  border: 2px solid;
  border-color: rgba(128, 128, 128, 0.541);
  border-radius: 15px;
  margin: 10px;
}

h1{
  color: rgba(128, 128, 128, 0.75);
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
