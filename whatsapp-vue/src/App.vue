<template>
  <div>
    <section class="section">
      <div class="container">
        <div class="columns">
          <div class="column is-3 lista-de-conversas">
            <div class="barra-superior" />
          </div>
          <div class="column conversa-ativa">
            <div class="barra-superior">
              <span>Usuário</span>
            </div>
            
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<style scoped>

.columns{
  min-height: 800px;
  box-shadow: 0 3rem 3rem -1rem rgba(10,10,10,.2);
}

.column{
  padding: 0;
}
.lista-de-conversas{
  background-color: white;;
}
.conversa-ativa{
  background: #E5DDD5;
}
.barra-superior{
  margin: 0;
  height: 50px;
  background: #EDEDED;
  border-right: 1px solid #E1E1E1;
  border-bottom: 1px solid rgb(200, 200, 200);
}
.barra-superior span {
  line-height: 50px;
  margin-left: 25px;
  font-weight: 500;
}
</style>