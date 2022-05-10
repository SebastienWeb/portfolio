<template>
  <header class="bg-purple px-4 py-14 text-white xl:px-0">
    <div class="container mx-auto w-full">
      <div class="lg:flex lg:items-center lg:justify-between lg:pb-14">
        <img
          class="logo m-auto lg:m-0"
          src="@/assets/images/logo.svg"
          alt="Logo de Sébastien Daufresne"
        />
        <nav class="pt-8 pb-14 lg:pt-0 lg:pb-0">
          <ul class="flex justify-center gap-4 font-bold">
            <li><a href="#" class="link">Sébastien</a></li>
            <li><a href="#" class="link">Services</a></li>
            <li><a href="#" class="link">Portfolio</a></li>
            <li><a href="#" class="link">Contact</a></li>
          </ul>
        </nav>
      </div>
      <div class="lg:flex lg:justify-center">
        <div class="lg:mr-8 lg:w-1/2">
          <h1
            class="pb-10 text-center text-40 font-bold lg:text-left lg:text-58"
          >
            Design & developpe de belle applications web
          </h1>
          <p class="pb-16 text-center font-bold lg:text-left">
            Vous avez un projet ? Alors vous êtes au bon endroit !
          </p>
          <button class="shadow-lg lg:m-0">SERVICES</button>
        </div>
        <img
          class="hidden lg:block lg:w-1/3 xl:w-1/4"
          src="@/assets/images/futiriste.svg"
          alt="Undraw Futirise"
        />
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "TheHeader",
};
</script>
