<template>
  <q-layout view="hHh LpR fff">
    <q-header elevated class="bg-primary text-white" height-hint="98">
      <q-toolbar align="center">
        <q-toolbar-title>
          <q-avatar>
            <img src=".././assets/home.svg">
          </q-avatar>
          Empresa
        </q-toolbar-title>
      </q-toolbar>

      <q-tabs align="center">
        <q-route-tab to="/" label="Home" />
        <q-route-tab to="/" label="Empresa" />
        <q-route-tab to="/" label="Produto" />
        <q-route-tab to="/" label="Contato" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src=".././assets/home.svg">
          </q-avatar>
          EMPRESA
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>
