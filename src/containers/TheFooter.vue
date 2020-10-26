<template>
  <CFooter :fixed="false">
    <div>
      <a href="https://coreui.io" target="_blank">teste</a>
      <span class="ml-1">&copy; {{new Date().getFullYear()}} MarcosJesus.</span>
    </div>
    <div class="mfs-auto">
      <span class="mr-1" target="_blank">teste</span>
      <a href="https://coreui.io/vue">MarcosJesus</a>
    </div>
  </CFooter>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>
