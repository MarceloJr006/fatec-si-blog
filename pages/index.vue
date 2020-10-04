<template>
  <div class="container">
    <div class="card1">      
   <div class="card">
     <n-link to="./PaginasDosCards/pagina3" no-prefetch>
        <img src="https://s2.glbimg.com/_7ptw6NKzcKabtkw5mTrmW-VgeQ=/13x0:1363x767/1008x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_59edd422c0c84a879bd37670ae4f538a/internal_photos/bs/2020/I/H/bM8pGFRMOnPKvyQ6T9tw/playstation-5.jpg" alt="Avatar" style="width:100%">
            <div class="container2">
              <h4><b>PS5</b></h4> 
              <p>PS5 vai ter preços de R$ 4.500 e R$ 5.000 e chega ao Brasil dia 19 de novembro</p> 
          </div>
          </n-link>
    </div>
    </div>
     <div class="card2">
       <div class="card">
          <n-link to="./PaginasDosCards/pagina2" no-prefetch>
        <img src="https://super.abril.com.br/wp-content/uploads/2020/08/27-08_fallguys_SITE.jpg" alt="Avatar" style="width:100%">
            <div class="container2">
              <h4><b>Fall Guys</b></h4> 
              <p>'Fall Guys' se torna fenômeno ao colocar jogadores em gincanas no estilo 'Olimpíadas do Faustão'</p> 
          </div>
          </n-link>
    </div>
    </div>
    <div class="card3">
       <div class="card">
         <n-link to="./PaginasDosCards/pagina1" no-prefetch>
        <img src="https://s2.glbimg.com/gCsT4K6iBsVnRW4_2ompMBfM5bM=/0x0:1150x647/1008x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_59edd422c0c84a879bd37670ae4f538a/internal_photos/bs/2020/F/a/t2yJzNSE69nk5ZIXvCCQ/xbox-series-x-series-s.jpg" alt="Avatar" style="width:100%">
            <div class="container2">
              <h4><b>Xbox</b></h4> 
              <p>Xbox Series X vai ter preço de R$ 5 mil no Brasil e Series S vai custar R$ 3 mil</p> 
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
    grid-template-columns: repeat(5, 1fr);
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

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

.card1{
  display: grid;
  grid-column: 0/1;
  grid-row: 1/1;
}

.card2{
  display: grid;
  grid-column: 3/3;
  grid-row: 1/1;
}

.card3{
  display: grid;
  grid-column:  5/5;
  grid-row: 1/1;
}
</style>