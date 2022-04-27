<template>
  <Headertodolist />

  <PostComponent />

  <FootertodoList/>
</template>

<script>
import PostComponent from './components/PostComponent.vue'
import Headertodolist from './components/HeadertodoList.vue'

export default {
  name: 'App',
    components: {
      PostComponent,
      Headertodolist,
    }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: whitescale;
  text-align: center;
  color: hwb(211 79% 7%);
  /* margin-bottom: 20px; */
}

</style>
