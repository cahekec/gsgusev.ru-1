<template>
  <div class="gusev-fok">

    <!-- Breadcrumb -->
    <section class="gs-container gs-container_center">
      <ol class="gs-breadcrumb">
        <li class="gs-breadcrumb__list-item"> <router-link class="gs-breadcrumb__link" :to="{ name: 'Home' }"> GS Гусев </router-link> </li>
        <li class="gs-breadcrumb__list-item gs-breadcrumb__list-item_active"> ФОК
            <span class="gs-breadcrumb__hidden-small-text"> города Гусева</span>
        </li>
      </ol>
    </section>

    <!-- Well -->
    <section class="gs-container gs-container_center">
        <p class="gs-well">
            Гусевский ФОК крут. Там есть тренажерный зал, бассейн, теннис, секции, каток и еще много всего.
            Идеальное место, где можно отлично провести время.
        </p>
    </section>

    <!-- Thumbnail -->
    <section class="gs-container gs-container_center gs-container_padding-bottom">
        <div class="gs-thumbnail">
            <div class="gs-thumbnail__caption gs-thumbnail__caption_text-center">
                <h4>Рецепция ФОК</h4>
                <p>8 (4012) 36-22-24</p>
                <CallButton phone="84012362224"/>
            </div>
        </div>
    </section>

  </div>
</template>

<script>

import CallButton from '../components/CallButton'

export default {
  name: 'GusevFok',
  components: {
    CallButton
  }
}
</script>

<style lang="scss" scoped>

@import '../assets/scss/gusev-fok.scss';

</style>
