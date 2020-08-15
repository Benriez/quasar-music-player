<template>
  <q-page class="">
    <q-card class="col" flat bordered>
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
        <q-item-section>
          <q-card flat class="my-card">
              <q-card-actions align="right">
              <q-btn flat round color="red" icon="favorite" />
              <q-btn flat round color="blue-grey-10" icon="thumb_down" />
              <q-btn flat round color="blue-grey-10 " icon="more_vert" />
            </q-card-actions>
          </q-card>
        </q-item-section>
      </q-item>
      <q-separator />
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
