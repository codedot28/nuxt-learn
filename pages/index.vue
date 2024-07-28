<template>
  <q-page padding>
    <div class="q-my-xl tex-center">
      <div>All Courses</div>
      <p class="q-mt-sm text-grey-8">웹 개발 입문부터 실전까지 실습해보기!</p>
    </div>
    <div class="row q-col-gutter-lg">
      <div v-for="n in 3" :key="n" class="col-12 col-md-4 col-sm-6">
        <CourseCard />
      </div>
    </div>
  </q-page>
</template>

<script setup lang="ts"></script>

<style scoped></style>
