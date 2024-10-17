<template>
  <h1>First Vue Project</h1>
  <div>
    <FirstComponent />
    <SecondComponent />
    <ThirdComponent />
  </div>
</template>

<script>
import FirstComponent from '@/components/FirstComponent.vue';
import SecondComponent from '@/components/SecondComponent.vue';
import ThirdComponent from '@/components/ThirdComponent.vue';

export default {
  name: 'App',
  components: {
    FirstComponent,
    SecondComponent,
    ThirdComponent,
  },
};
</script>

<!--Global style-->
<style>
h1, div {
  font-family: arial;
}
</style>

<!--Scoped style-->
<style scoped>
h1 {
  color: blue;
}
</style>
