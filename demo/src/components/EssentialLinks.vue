<template>
  <q-list>
    <q-item clickable to="/docs">
      <q-item-section avatar>
        <q-icon name="bolt" />
      </q-item-section>
      <q-item-section>
        <q-item-label>QMediaPlayer docs</q-item-label>
        <q-item-label caption>Documentation</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable to="/demo">
      <q-item-section avatar>
        <q-icon name="bolt" />
      </q-item-section>
      <q-item-section>
        <q-item-label>QMediaPlayer demo</q-item-label>
        <q-item-label caption>Interactively play with properties</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable to="/examples">
      <q-item-section avatar>
        <q-icon name="bolt" />
      </q-item-section>
      <q-item-section>
        <q-item-label>QMediaPlayer examples</q-item-label>
        <q-item-label caption>Examples of how to do it</q-item-label>
      </q-item-section>
    </q-item>
    <q-separator />
    <q-item clickable tag="a" target="_blank" href="https://github.com/quasarframework/app-extension-qmediaplayer">
      <q-item-section avatar>
        <q-icon name="bolt" />
      </q-item-section>
      <q-item-section>
        <q-item-label>QMediaPlayer home</q-item-label>
        <q-item-label caption>@quasar/qmediaplayer</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable tag="a" target="_blank" href="https://github.com/quasarframework/app-extension-qmarkdown">
      <q-item-section avatar>
        <q-icon name="bolt" />
      </q-item-section>
      <q-item-section>
        <q-item-label>QMarkdown home</q-item-label>
        <q-item-label caption>@quasar/qmarkdown</q-item-label>
      </q-item-section>
    </q-item>
    <q-separator />
    <q-item clickable tag="a" target="_blank" href="http://quasar.dev">
      <q-item-section avatar>
        <q-icon name="school"></q-icon>
      </q-item-section>
      <q-item-section>
        <q-item-label>Docs</q-item-label>
        <q-item-label caption>quasar.dev</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable tag="a" target="_blank" href="https://github.com/quasarframework/">
      <q-item-section avatar>
        <q-icon name="code"></q-icon>
      </q-item-section>
      <q-item-section>
        <q-item-label>Github</q-item-label>
        <q-item-label caption>github.com/quasarframework</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable tag="a" target="_blank" href="http://chat.quasar.dev">
      <q-item-section avatar>
        <q-icon name="chat"></q-icon>
      </q-item-section>
      <q-item-section>
        <q-item-label>Discord Chat Channel</q-item-label>
        <q-item-label caption>chat.quasar.dev</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable tag="a" target="_blank" href="https://forum.quasar.dev">
      <q-item-section avatar>
        <q-icon name="record_voice_over"></q-icon>
      </q-item-section>
      <q-item-section>
        <q-item-label>Forum</q-item-label>
        <q-item-label caption>forum.quasar.dev</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable tag="a" target="_blank" href="https://twitter.com/quasarframework">
      <q-item-section avatar>
        <q-icon name="rss_feed"></q-icon>
      </q-item-section>
      <q-item-section>
        <q-item-label>Twitter</q-item-label>
        <q-item-label caption>@quasarframework</q-item-label>
      </q-item-section>
    </q-item>
    <q-item clickable tag="a" target="_blank" href="https://github.com/quasarframework/app-extension-qmediaplayer">
      <q-item-section avatar>
        <q-icon name="movie"></q-icon>
      </q-item-section>
      <q-item-section>
        <q-item-label>QMediaPlayer home</q-item-label>
        <q-item-label caption>@quasar/app-extension-qmediaplayer</q-item-label>
      </q-item-section>
    </q-item>
  </q-list>
</template>

<script>
export default {
  name: 'EssentialLinks',
  data () {
    return {}
  }
}
</script>

<style>
</style>
