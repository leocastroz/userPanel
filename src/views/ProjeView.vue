<script setup>
</script>

<template>
  <main>
    <div class="all">
      <div class="container">
        <span></span>
        <h1>Projects !</h1>
      </div>
      <div class="box">
        <p>Here are some of my <span>projects  </span> that I created along my journey as a <span>Frontend Developer.  </span></p>
        <br>
        <p>Clone Linktree</p>
        <br>
        <p>CS - FireClub</p>
        <br>
        <p>Vale Do Amazonas (status - profissional)</p>
        <br>
        <p>GTAV - FiveM (status - profissional)</p>
        <br>
        <p>Timblim (status - profissional)</p>
        <br>
        <p>Borba Locações (status - profissional)</p>
      </div>
    </div>
  </main>
</template>

<style scoped>

*{
  font-family: 'Poppins', sans-serif;
}

main{
  background-color: #131313;
  justify-content: center;
  align-items: center;
  height: 85vh;
}


.container{
  padding: 30px 0 0 30px;
  display: flex;
  justify-content: start;
  align-items: center;
}
.container span{
  width: 5px;
  height: 40px;
  background-color: #43ff69;
}

.box{
  padding: 0 0 0 30px;
}

.box span{
  color: #43ff69; 
}

.donate{
  margin-bottom: 80px;
}

.donate a{
  color: #000;
  font-weight: bold;
  text-decoration: none;
}
.donate .coffee{
  background-color: #43ff69;
  padding: 10px;
  border-radius: 3px;
}

.media a{
  color: #fff;
  text-decoration: none;
  padding: 0 20px;
}

.media a:hover{
  color: #43ff69;
}

main img{
  width: 70px;
}

main h1{
  font-size: 60px;
  margin-left: 10px;
  font-weight: bold;
  
}
</style>