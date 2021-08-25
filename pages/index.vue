<template>
  <div>
    <div>Observe that @hzzt/v-lazy-image renders in dev and production builds:</div>
    <v-lazy-image src="https://placekitten.com/400/200" />

    <div>But @command-tab/place-kitten renders in dev, but does not render when doing <code>nuxt build</code>:</div> 
    <place-kitten :width="400" :height="200" />
  </div>
</template>

<script>
export default {}
</script>
