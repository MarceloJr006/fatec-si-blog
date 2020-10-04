<template>
  <div>
      <div class="containerpublicar">
          <div class="cabecapubli">
          <section>
        <b-field horizontal label="Título" >
            <b-input name="Título" expanded placeholder="Título"></b-input>
        </b-field>

        <b-field horizontal label="Autor">
            <b-input name="nome" placeholder="Nome" expanded></b-input>
            <b-input name="email" type="email" placeholder="email@email.com" expanded></b-input>
        </b-field>

        <b-field horizontal label="Tema">
            <b-select placeholder="Selecione um tema">
                <option value="1">Lançamentos</option>
                <option value="2">Games</option>
                <option value="3">Eventos</option>
                <option value="4">Outros</option>
            </b-select>
        </b-field>

        <b-field horizontal label="Mensagem">
            <b-input type="textarea"></b-input>
        </b-field>

        <b-field horizontal>
            <p class="control">
                <button class="button is-primary">
                  Enviar
                </button>
            </p>
        </b-field>

         </section>
          </div>
          <div class="textopublic">
              <b>Poste sua nóticia aqui</b>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.containerpublicar{
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(5, 1fr);
}

.cabecapubli{
    grid-column: 2/4;
    grid-row: 2/4;
}

.textopublic{
    grid-column: 2/4;
    grid-row: 1/1;
    text-align: center;
    font-size: 40px;
}
</style>