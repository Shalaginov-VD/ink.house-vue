<template>
  <div class="list-3">
      <picture13-view/>
      <picture14-view/>
      <picture15-view/>
      <picture16-view/>
      <picture17-view/>
      <picture18-view/>
  </div>
</template>

<script>
import Picture13 from '@/components/Picture-13.vue'
import Picture14 from '@/components/Picture-14.vue'
import Picture15 from '@/components/Picture-15.vue'
import Picture16 from '@/components/Picture-16.vue'
import Picture17 from '@/components/Picture-17.vue'
import Picture18 from '@/components/Picture-18.vue'

export default {
components: {
  "picture13-view": Picture13,
  "picture14-view": Picture14,
  "picture15-view": Picture15,
  "picture16-view": Picture16,
  "picture17-view": Picture17,
  "picture18-view": Picture18,
}
}

</script>

<style scoped>
.list-3 {
  margin-top: 30px;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 70px;
  max-width: 1110px;
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  padding-left: 5vw;
  padding-right: 5vw;
}
@media (max-width: 1250px) {
  .list-3 {
      max-width: 690px;
  }
}
@media (max-width: 766px) {
  .list-3 {
      max-width: 510px;
  }
}
@media (max-width: 567px) {
  .list-3 {
      max-width: 290px;
  }
}
</style>