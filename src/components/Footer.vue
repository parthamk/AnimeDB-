<template>
  <div>
    <div id="footer" class="mt-3 p-4 text-center flex-none">
      <h3 class="text-base font-medium tracking-normal text-gray-900">
        Developed and maintained with ❤️ by
        <span
          ><a
            class="border-b-2 border-gray-100 hover:border-b-2 hover:border-green-500"
            href="https://github.com/parthamk"
            target="_blank"
            >@parthamk</a
          ></span
        >
        © 2024
      </h3>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style>
html,
body {
  height: 100%;
}

body {
  min-height: 100vh;
}
/* #footer {
  position: sticky;
  top: 100%;
} */
</style>
