<template>
  <div class="h-full bg-gray-400 p-4">
    <h1 class="py-4 text-xl font-bold">Lista de Practicas</h1>
    <div class="grid grid-cols-3 gap-4">
      <div class="col-span-1 grid gap-4">
        <NuxtLink
          to="/basics"
          class="rounded-md bg-gray-100 p-4 hover:cursor-pointer hover:bg-gray-200"
          >Uso Basico</NuxtLink
        >
        <NuxtLink
          to="/multicolumn"
          class="rounded-md bg-gray-100 p-4 hover:cursor-pointer hover:bg-gray-200"
          >Multi-Column Layout</NuxtLink
        >
        <!-- <NuxtLink
          to=""
          class="rounded-md bg-gray-100 p-4 hover:cursor-pointer hover:bg-gray-200"
          >holy-grail</NuxtLink
        > -->
        <!-- <NuxtLink
          to=""
          class="rounded-md bg-gray-100 p-4 hover:cursor-pointer hover:bg-gray-200"
          >masonry</NuxtLink
        > -->
        <!-- <NuxtLink
          to=""
          class="rounded-md bg-gray-100 p-4 hover:cursor-pointer hover:bg-gray-200"
          >portfolio</NuxtLink
        > -->
        <!-- <NuxtLink
          to=""
          class="rounded-md bg-gray-100 p-4 hover:cursor-pointer hover:bg-gray-200"
          >twelve-col</NuxtLink
        > -->
      </div>
    </div>
  </div>
</template>
<script setup></script>
