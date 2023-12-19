<template>
  <div>
    <BaseHero />
    <BaseMain />
    <BaseFooter />
  </div>
</template>

<script>
import BaseHero from '@/components/BaseHero.vue';
import BaseMain from '@/components/BaseMain.vue';
import BaseFooter from '@/components/BaseFooter.vue';
export default {
  components: {
    BaseHero,
    BaseMain,
    BaseFooter
  }
}
</script>

<style>

</style>
