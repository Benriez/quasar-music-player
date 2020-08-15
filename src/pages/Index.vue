<template>
  <q-page class="">
    <q-card 
      v-for="post in posts"
      :key="post.id"
      class="col q-mt-xs justify-end" 
      flat 
      bordered>

      <q-item>
        <q-item-section avatar>
          <q-avatar>
            <img src="https://cdn.quasar.dev/img/boy-avatar.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label>{{post.title}}</q-item-label>
          <q-item-label caption>
            {{post.artist}}
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
    name: 'index',
    data(){
      return {
        posts: [
          {
            id: 1,
            date: '1597493296770',
            artist: 'Audiomatic',
            title: 'Pineapple Express',
            from: 'Benny'
          },
          {
            id: 2,
            date: '1597493296770',
            artist: 'Neelix',
            title: 'Makeup',
            from: 'Ozan'
          },
          {
            id: 3,
            date: '1597493296770',
            artist: 'Whats my age again',
            title: 'Blink-182',
            from: 'Axel'
          }
        ]
      }
    }
  }
</script>

<style lang="stylus">
</style>
