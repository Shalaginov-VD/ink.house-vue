<template>
  <div class="list-2">
      <picture7-view/>
      <picture8-view/>
      <picture9-view/>
      <picture10-view/>
      <picture11-view/>
      <picture12-view/>
  </div>
</template>

<script>
import Picture7 from '@/components/Picture-7.vue'
import Picture8 from '@/components/Picture-8.vue'
import Picture9 from '@/components/Picture-9.vue'
import Picture10 from '@/components/Picture-10.vue'
import Picture11 from '@/components/Picture-11.vue'
import Picture12 from '@/components/Picture-12.vue'

export default {
components: {
  "picture7-view": Picture7,
  "picture8-view": Picture8,
  "picture9-view": Picture9,
  "picture10-view": Picture10,
  "picture11-view": Picture11,
  "picture12-view": Picture12,
}
}

</script>

<style scoped>
.list-2 {
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
  .list-2 {
      max-width: 690px;
  }
}
@media (max-width: 766px) {
  .list-2 {
      max-width: 510px;
  }
}
@media (max-width: 567px) {
  .list-2 {
      max-width: 290px;
  }
}
</style>