<template>
  <section class="section">

 
    <b-carousel>
      <b-carousel-item>
        <b-image class="image" src="https://i0.statig.com.br/bancodeimagens/0r/5c/z3/0r5cz3q69zwc7uo6j9r1dtd82.jpg"></b-image>
      </b-carousel-item>
      <b-carousel-item>
        <b-image class="image" src="https://cf.shopee.com.br/file/ba982c26c0910c0de5be09e34163a370"></b-image>
      </b-carousel-item>      
      <b-carousel-item>
        <b-image class="image" src="https://i.pinimg.com/originals/74/ce/71/74ce716aaa0871130c7318b591a062ea.jpg"></b-image>
      </b-carousel-item>  
       <b-carousel-item>
        <b-image class="image" src="https://images-americanas.b2w.io/produtos/1606130352/imagens/cap-bonito-chapeu-gato-traje-cosplay-filhote-de-cachorro-gatos-caes-engracado-perna-de-frango-laco-de-cabelo-cabeca-desgaste-pet-chapeu/1606130352_1_large.jpg"></b-image>
      </b-carousel-item> 
    </b-carousel>

    <div class="columns mt-5">
      <div class="column is-6">
        <article class="notification is-primary">
          <p class="title">Oi</p>
          <p class="subtitle">:)</p>
          <router-link :to="{ path: '/imagens' }">Clica</router-link>
        </article>
      </div>
      <div class="column is-6">
        <article class="notification is-info">
          <p class="title">Gatos de chapéu</p>
          <p class="subtitle">:/</p>
          <router-link :to="{ path: '/imagens' }">Aqui não</router-link>
        </article>
      </div>      
    </div>

    <div class="columns mt-4">
      <div class="column is-4">
        <article class="notification is-primary has-text-centered">
          <p class="title">Mais gatos de chapéu</p>
          <p class="subtitle">:o</p>
        </article>
      </div>
      <div class="column is-4">
        <article class="notification is-info has-text-centered">
          <p class="title">Bleh</p>
          <p class="subtitle">;)</p>
        </article>
      </div>
      <div class="column is-4">
        <article class="notification is-primary has-text-centered">
          <p class="title">Bluh</p>
          <p class="subtitle">:(</p>
        </article>
      </div>            
    </div>    



  </section>
</template>

