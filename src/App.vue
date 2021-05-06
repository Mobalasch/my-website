<template>
    <router-view>
      <Navigation></Navigation>
    </router-view>
</template>
<script>
import Navigation from './components/Navigation'
export default {
  components: {
    'Navigation': Navigation
  }
}
</script>
