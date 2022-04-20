<script setup lang="ts">
const Router = useRouter()
</script>

<template>
  <div w="100%" class="h-[calc(100%-55px)]">
    <h3 text-30px mb-6>
      练习册
    </h3>
    <div flex justify-center>
      <ul>
        <li list-circle cursor-pointer class="hover:text-blue" @click="Router.push('/dir/promise')">
          手写Promise
        </li>
      </ul>
    </div>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
