<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-blue-grey-10">
      <q-toolbar>

        <q-toolbar-title>
          Music Stream
        </q-toolbar-title>

        <div>Quasar v{{ $q.version }}</div>
      </q-toolbar>
    </q-header>

    <q-footer elevated  class="bg-blue-grey-10">
      <q-toolbar>
        <q-card class="my-card full-width bg-transparent" flat >
          <q-card-actions align="around">
            <q-btn flat round size="1.95em" color="white" icon="skip_previous" />
            <q-btn flat round size="1.95em" color="white" icon="play_arrow" />
            <q-btn flat round size="1.95em" color="white" icon="skip_next" />
          </q-card-actions>
          </q-card>
      </q-toolbar>
    </q-footer>


    <q-page-container>
      <router-view />
    </q-page-container>
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
