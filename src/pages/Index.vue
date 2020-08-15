<template>
  <q-page class="flex flex-center">
     <q-card class="my-card" flat>
      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://cdn.quasar.dev/img/boy-avatar.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label>Ananas Express</q-item-label>
          <q-item-label caption>
            Audiomatic
          </q-item-label>
        </q-item-section>
      </q-item>

      <q-separator />

      <q-card-actions align="around">
        <q-btn flat round size="2.715em" color="red" icon="skip_previous" />
        <q-btn flat round size="2.715em" color="teal" icon="play_arrow" />
        <q-btn flat round size="2.715em" color="primary" icon="skip_next" />
      </q-card-actions>
      </q-card>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>

<style lang="stylus">
</style>
