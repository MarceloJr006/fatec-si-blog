<template>
    <div>
        <div class="containerpag2">
            <div class="imagem2">
                <img src="https://super.abril.com.br/wp-content/uploads/2020/08/27-08_fallguys_SITE.jpg" alt="">
            </div>
            <div class="infonot">
                <b><u>'Fall Guys' se torna fenômeno ao colocar jogadores em gincanas no estilo 'Olimpíadas do Faustão'</u></b>
            </div>
            <div class="textoxbox2">
                <p>Semana Pop deste sábado (15) fala sobre game multiplayer que se tornou sucesso na quarentena.
                    Em duas semanas, um game multiplayer independente se tornou o grande fenômeno da quarentena ao colocar jogadores em gincanas no melhor estilo "Olimpíadas do Faustão". O Semana Pop deste sábado (15) explica como "Fall Guys: Ultimate knockout" conseguiu tamanho sucesso, levando bonequinhos desengonçados e coloridos ao gênero de battle royales. Assista ao vídeo acima.
                    O Semana Pop vai ao ar toda semana, com o resumo do tema está bombando no mundo do entretenimento. Pode ser sobre música, cinema, games, internet ou só a treta da semana mesmo. Está disponível em vídeo e podcast.
                </p>
            </div>
            <div class="atorxbox2">
                <b><p>Por Cesar Soto, G1 - 15/08/2020 06h00 </p></b>
            </div>
        </div>
    </div>
</template>
<style>
.containerpag2{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-row: repeat(5, 1fr);
}

.imagem2{
    grid-column: 2/3;
    grid-row: 2/2;
}
.imagem2 img{
    height: 300px;
    width: 100%;
}

.infonot{
    grid-column: 2/2;
    grid-row: 1/1;
    text-align: center;
    font-size: 30px;
}
.textoxbox2{
    grid-column: 1/4;
    grid-row: 3/3;
    text-align: center;
    padding: 3%;
}
.atorxbox2{
    grid-column: 2/2;
    grid-row: 4/4;
    text-align: center;
    padding-bottom: 3%;
}
</style>