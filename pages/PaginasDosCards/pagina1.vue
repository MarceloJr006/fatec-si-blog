<template>
    <div>
        <div class="containerpag1">
            <div class="imagem1">
                <img src="https://s2.glbimg.com/gCsT4K6iBsVnRW4_2ompMBfM5bM=/0x0:1150x647/1008x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_59edd422c0c84a879bd37670ae4f538a/internal_photos/bs/2020/F/a/t2yJzNSE69nk5ZIXvCCQ/xbox-series-x-series-s.jpg" alt="">
            </div>
            <div class="infonot">
                <b><u>Xbox Series X vai ter preço de R$ 5 mil no Brasil e Series S vai custar R$ 3 mil</u></b>
            </div>
            <div class="textoxbox1">
                <p>Nova geração de consoles da Microsoft vai ser lançada em novembro no país, mas empresa não divulga data específica. Pré-venda mundial, que começa nesta terça, não vale para o Brasil.
                    A Microsoft anunciou nesta segunda-feira (21) que o Xbox Series X vai ser vendido no Brasil pelo preço sugerido de R$ 4.999. Já a versão mais compacta e menos poderosa da nova geração da empresa, o Xbox Series S, custará R$ 2.999.
                    Com lançamento mundial previsto para o dia 10 de novembro, a empresa não confirma se os consoles chegam ao país na mesma data, e dá apenas o mês de novembro como previsão.
                    Além disso, o Brasil não faz parte dos países que receberão a pré-venda a partir desta terça-feira (22).
                    "Em breve compartilharemos mais detalhes sobre a pré-venda para o nosso mercado", afirmou a Microsoft ao G1 através de sua assessoria de imprensa.
                    Nos Estados Unidos, o Series X vai custar US$ 499. Já o Series S será vendido por US$ 299.
                </p>
            </div>
            <div class="atorxbox1">
                <b><p>Por G1 21/09/2020 22h00 </p></b>
            </div>
        </div>
    </div>
</template>
<style>
.containerpag1{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-row: repeat(5, 1fr);
}

.imagem1{
    grid-column: 2/3;
    grid-row: 2/2;
}
.imagem1 img{
    height: 300px;
    width: 100%;
}

.infonot{
    grid-column: 2/2;
    grid-row: 1/1;
    text-align: center;
    font-size: 30px;
}
.textoxbox1{
    grid-column: 1/4;
    grid-row: 3/3;
    text-align: center;
    padding: 3%;
}
.atorxbox1{
    grid-column: 2/2;
    grid-row: 4/4;
    text-align: center;
    padding-bottom: 3%;
}
</style>