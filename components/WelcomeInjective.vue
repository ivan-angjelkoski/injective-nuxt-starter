<template>
  <div class="min-h-screen grid place-items-center relative">
    <div class="absolute top-1/3 left-0 bg-blue-300 w-52 h-52 blur-[9rem]" />
    <div
      class="absolute top-1/4 right-0 bg-blue-400/50 w-52 h-52 blur-[6rem]"
    />
    <div
      class="absolute top-0 left-1/2 -translate-x-1/2 bg-blue-400/70 w-96 h-52 blur-[10rem]"
    />
    <div class="text-center space-y-9">
      <InjectiveLogo class="w-40 mx-auto animate-bounce" />
      <!-- <h1 class="text-6xl font-semibold">🧬 Create Injective App 🧬</h1> -->
      <h1 class="text-6xl font-semibold">Create Injective App</h1>
      <p>
        Learn more
        <a
          href="#"
          class="font-semibold text-yellow-400 hover:underline"
        >
          Here
        </a>
      </p>
    </div>
  </div>
</template>

<style>
body {
  @apply bg-[#151518] text-white;
}
</style>
