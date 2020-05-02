<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">nuxt-tailwind14-element-example</h1>
      <h2 class="subtitle">My fabulous Nuxt.js project</h2>
      <div class="bg-gray-200 hover:bg-gray-300 py-2 mb-4 border border-gray-700 hover:border-gray-900 rounded">
        <div class="font-bold">This is styled with tailwindcss!</div>
        <div>tailwindcss v1.4, purge mode in prod build is not purging Element-UI css... 🤘</div>
      </div>
      <div>
        <el-card class="box-card">
          <div slot="header" class="clearfix">
            <span class="font-extrabold">Element-UI Card (also with tailwind class `font-extrabold`)</span>
            <el-button style="float: right; padding: 3px 0" type="text">Operation button</el-button>
          </div>
          <div v-for="o in 4" :key="o" class="text item">{{'List item ' + o }}</div>
        </el-card>
      </div>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
        <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
  }
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
