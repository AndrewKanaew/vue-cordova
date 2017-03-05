<template>
  <div>
    <ui-toolbar
      :brand="this.title"
      remove-brand-divider
      text-color="black"
      :raised="true">
    </ui-toolbar>
    <ui-alert
      :dismissible="false">
    This is a Vue.js/Webpack/Cordova/Keen-UI boilerplate project
    </ui-alert>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      title: 'Vue Cordova Keen-UI Boilerplate'
    }
  }
}
</script>
