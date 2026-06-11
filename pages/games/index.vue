<template>
  <main class="min-h-screen bg-black text-white p-10">
    <h1 class="text-4xl font-bold mb-8">
      遊戲列表
    </h1>

    <div class="grid md:grid-cols-3 gap-6">

      <NuxtLink
        to="/games/snake"
        class="border border-red-500 p-6 rounded-xl"
      >
        <h2 class="text-2xl font-bold">
          貪食蛇
        </h2>
      </NuxtLink>

    </div>
  </main>
</template>