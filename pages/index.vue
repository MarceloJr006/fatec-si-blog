<template>
  <div class="container">
    <div class="card1">      
   <div class="card">
     <n-link to="/about" no-prefetch>
        <img src="img_avatar.png" alt="Avatar" style="width:100%">
            <div class="container2">
              <h4><b>John Doe</b></h4> 
              <p>Architect & Engineer</p> 
          </div>
          </n-link>
    </div>
    </div>
     <div class="card2">
       <div class="card">
          <n-link to="/inicio" no-prefetch>
        <img src="img_avatar.png" alt="Avatar" style="width:100%">
            <div class="container2">
              <h4><b>John Doe</b></h4> 
              <p>Architect & Engineer</p> 
          </div>
          </n-link>
    </div>
    </div>
    <div class="card3">
       <div class="card">
         <n-link to="./PaginasDosCards/pagina1" no-prefetch>
        <img src="img_avatar.png" alt="Avatar" style="width:100%">
            <div class="container2">
              <h4><b>John Doe</b></h4> 
              <p>Architect & Engineer</p> 
          </div>
          </n-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
  .container{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    grid-gap: 10px; 
  }
.container2{
    text-align: center;
}


.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 100%;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 100%;
}
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.card1{
  display: grid;
  grid-column: 1/1;
  grid-row: 1/1;
}

.card2{
  display: grid;
  grid-column: 3/3;
  grid-row: 1/1;
}

.card3{
  display: grid;
  grid-column: 5/5;
  grid-row: 1/1;
}
</style>