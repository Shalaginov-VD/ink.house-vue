<template>
  <div class="list">
      <picture-view/>
      <picture2-view/>
      <picture3-view/>
      <picture4-view/>
      <picture5-view/>
      <picture6-view/>
  </div>
</template>

<script>
import Picture from '@/components/Picture.vue'
import Picture2 from '@/components/Picture-2.vue'
import Picture3 from '@/components/Picture-3.vue'
import Picture4 from '@/components/Picture-4.vue'
import Picture5 from '@/components/Picture-5.vue'
import Picture6 from '@/components/Picture-6.vue'

export default {
components: {
  "picture-view": Picture,
  "picture2-view": Picture2,
  "picture3-view": Picture3,
  "picture4-view": Picture4,
  "picture5-view": Picture5,
  "picture6-view": Picture6,
}
}

</script>

<style scoped>
.list {
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
  .list {
      max-width: 690px;
  }
}
@media (max-width: 766px) {
  .list {
      max-width: 510px;
  }
}
@media (max-width: 567px) {
  .list {
      max-width: 290px;
  }
}
</style>