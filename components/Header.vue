<template>
  <header class="bg-blue-100 flex relative z-20 items-center overflow-hidden">
    <div class="container mx-auto px-6 flex relative py-16">
      <div class="sm:w-2/3 lg:w-2/5 flex flex-col relative z-20">
        <span
          class="
            w-20
            h-2
            bg-gradient-to-r
            from-green-400
            via-blue-500
            to-purple-500
            mb-12
          "
        >
        </span>
        <h1
          class="
            font-bebas-neue
            uppercase
            text-6xl
            sm:text-8xl
            font-black
            flex flex-col
            leading-none
            text-purple-700
          "
        >
          Freelancer
          <span class="text-5xl sm:text-7xl"> Pratica </span>
        </h1>
        <p class="text-sm sm:text-base text-gray-700">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laudantium
          sed fuga nostrum quam voluptates vel quibusdam necessitatibus, placeat
          odio voluptatum veritatis, temporibus commodi sit autem nobis
          repudiandae. Id, architecto ratione!
        </p>
        <div class="flex mt-8">
          <a
            href="#"
            class="
              uppercase
              py-2
              px-4
              rounded-lg
              bg-purple-500
              border-2 border-transparent
              text-white text-md
              mr-4
              hover:bg-purple-600
            "
          >
            Conectar-se
          </a>
          <a
            href="#"
            class="
              uppercase
              py-2
              px-4
              rounded-lg
              bg-transparent
              border-2 border-purple-500
              text-purple-500
              hover:bg-purple-500
              hover:text-white
              text-md
            "
          >
            Conhecer
          </a>
        </div>
      </div>
      <div class="hidden sm:block sm:w-1/3 pl-20 lg:w-3/5 pl-20 relative">
        <img src="up.jpg" class="max-w-xs md:max-w-sm m-auto" />
      </div>
    </div>
  </header>
</template>
