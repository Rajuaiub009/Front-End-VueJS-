<template>
  <NavBar/>
<div class="container"></div>
<div class="row">
    <div class="col-md-12">
        <div>
            <router-view></router-view>
        </div>
    </div>
</div>
</template>

<script>
import NavBar from './components/NavBar.vue';

export default {
    name: 'App',
    components: {
      NavBar,

    },
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
