<template>
  <div class="map">
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m10!1m8!1m3!1d5075.441900199033!2d30.45394865149311!3d50.50215111304246!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sru!2sua!4v1615450248227!5m2!1sru!2sua"
      width="100%"
      height="446"
      style="border: 0;"
      allowfullscreen=""
      loading="lazy"
    ></iframe>
  </div>
</template>
<script>
export default {
  name: 'Map',
}
</script>
<style lang="scss" scoped>
.map {
  width: 100%;
  height: 450px;
}
</style>
