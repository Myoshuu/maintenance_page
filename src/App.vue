<template>
  <div class="content flex justify-center items-center flex-col">
    <img
      class="object-fill w-1/4 lg:w-1/4 md:w-2/4 sm:w-3/4"
      src="@/assets/maintenance.jpg"
      alt=""
    />
    <div class="flex items-center gap-2">
      <fa class="text-4xl text-red-600" :icon="['fas', 'circle-exclamation']" />
      <p class="md:text-4xl lg:text-4xl font-semibold sm:text-2xl">
        Under Maintenance
      </p>
    </div>
    <span class="text-base sm:text-sm"
      >Copyright &copy; {{ new Date().getFullYear() }}</span
    >
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Montserrat";
}

.content {
  width: 100vw;
  height: 100vh;
}
</style>