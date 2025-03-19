<template>
  <div>
    This Page Is About Me.
  </div>

  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>

<script>
  function enableCustomLayout () {
    setPageLayout('another')
  }

  useHead({
    'title': 'About' 
  })
</script>

