<template>
  <header class="skewed-bottom-right">
    <nav
      class="relative px-6 py-6 flex justify-between items-center bg-gray-900"
    >
      <a class="text-white text-3xl font-bold leading-none" href="#"
        ><img src="logo.png" alt="Tela inicial" width="70"
      /></a>
      <div class="lg:hidden">
        <button class="navbar-burger flex items-center text-white p-3">
          <svg
            class="block h-4 w-4 fill-current"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Mobile menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <ul
        class="
          hidden
          absolute
          top-1/2
          left-1/2
          transform
          -translate-y-1/2 -translate-x-1/2
          lg:flex
          lg:mx-auto
          lg:flex
          lg:items-center
          lg:w-auto
          lg:space-x-6
        "
      >
        <li>
          <a class="text-sm text-gray-300 hover:text-white" href="#">Inicio</a>
        </li>
        <li class="text-gray-800">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li><a class="text-sm text-white font-bold" href="#">Conhecer</a></li>
        <li class="text-gray-800">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <a class="text-sm text-gray-300 hover:text-white" href="#">Serviço</a>
        </li>
        <li class="text-gray-800">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <a class="text-sm text-gray-300 hover:text-white" href="#"
            >Plataforma</a
          >
        </li>
        <li class="text-gray-800">
          <svg
            class="w-4 h-4 current-fill"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            ></path>
          </svg>
        </li>
        <li>
          <a class="text-sm text-gray-300 hover:text-white" href="#">Função</a>
        </li>
      </ul>
      <a
        class="
          hidden
          lg:inline-block
          py-2
          px-6
          bg-pink-500
          hover:bg-pink-600
          text-sm text-white
          font-bold
          rounded-l-xl rounded-t-xl
          transition
          duration-200
        "
        href="#"
        >Contato</a
      >
    </nav>
    <div class="bg-gray-900 pt-12 lg:pt-20 pb-20 radius-for-skewed">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap -mx-4">
          <div
            class="
              w-full
              lg:w-1/2
              px-4
              mb-12
              md:mb-20
              lg:mb-0
              flex
              items-center
            "
          >
            <div class="w-full text-center lg:text-left">
              <div class="max-w-md mx-auto lg:mx-0">
                <h2 class="mb-3 text-4xl lg:text-5xl text-white font-bold">
                  <span>Pratica</span>
                  <span class="text-purple-600">Trabalho</span>
                </h2>
              </div>
              <div class="max-w-sm mx-auto lg:mx-0">
                <p class="mb-6 text-gray-400 leading-loose">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Pellentesque efficitur nisl sodales egestas lobortis.
                </p>
                <div>
                  <a
                    class="
                      inline-block
                      mb-3
                      lg:mb-0
                      lg:mr-3
                      w-full
                      lg:w-auto
                      py-2
                      px-6
                      leading-loose
                      bg-purple-600
                      hover:bg-purple-700
                      text-white
                      font-semibold
                      rounded-l-xl rounded-t-xl
                      transition
                      duration-200
                    "
                    href="cadastro"
                    >Cadastrar-se</a
                  ><a
                    class="
                      inline-block
                      w-full
                      lg:w-auto
                      py-2
                      px-6
                      leading-loose
                      text-white
                      font-semibold
                      bg-gray-900
                      border-2 border-gray-700
                      hover:border-gray-600
                      rounded-l-xl rounded-t-xl
                      transition
                      duration-200
                    "
                    href="#"
                    >Acessar</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="w-full lg:w-1/2 px-4 flex items-center justify-center">
            <div class="relative" style="z-index: 0">
              <img
                class="
                  h-128
                  w-full
                  max-w-lg
                  object-cover
                  rounded-3xl
                  md:rounded-br-none
                "
                src="up.jpg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="top: -2rem; right: 3rem; z-index: -1"
                src="atis-assets/elements/blue-up.svg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="bottom: -2rem; right: -2rem; z-index: -1"
                src="atis-assets/elements/wing-purple-down.svg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="top: 3rem; right: -3rem; z-index: -1"
                src="atis-assets/elements/bullets-dark-right.svg"
                alt=""
              />
              <img
                class="hidden md:block absolute"
                style="bottom: 2.5rem; left: -4.5rem; z-index: -1"
                src="atis-assets/elements/bullets-yellow-left.svg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="mr-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-900"
        viewBox="0 0 10 10"
        preserveAspectRatio="none"
      >
        <polygon fill="currentColor" points="0 0 10 0 0 10"></polygon>
      </svg>
    </div>
    <div class="hidden navbar-menu relative z-50">
      <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
      <nav
        class="
          fixed
          top-0
          left-0
          bottom-0
          flex flex-col
          w-5/6
          max-w-sm
          py-6
          px-6
          bg-white
          border-r
          overflow-y-auto
        "
      >
        <div class="flex items-center mb-8">
          <a class="mr-auto text-3xl font-bold leading-none" href="#"
            ><img
              src="https://static.shuffle.dev/uploads/files/d0/d04fba9b48bd8ec3d647db708ce5f108c20811ae/logo.png"
              alt="Tela inicial"
              width="70"
          /></a>
          <button class="navbar-close">
            <svg
              class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              ></path>
            </svg>
          </button>
        </div>
        <div>
          <ul>
            <li class="mb-1">
              <a
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-purple-50
                  hover:text-purple-600
                  rounded
                "
                href="#"
                >Inicio</a
              >
            </li>
            <li class="mb-1">
              <a
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-purple-50
                  hover:text-purple-600
                  rounded
                "
                href="#"
                >Conhecer</a
              >
            </li>
            <li class="mb-1">
              <a
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-purple-50
                  hover:text-purple-600
                  rounded
                "
                href="#"
                >Serviço</a
              >
            </li>
            <li class="mb-1">
              <a
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-purple-50
                  hover:text-purple-600
                  rounded
                "
                href="#"
                >Plataforma</a
              >
            </li>
            <li class="mb-1">
              <a
                class="
                  block
                  p-4
                  text-sm
                  font-semibold
                  text-gray-400
                  hover:bg-purple-50
                  hover:text-purple-600
                  rounded
                "
                href="#"
                >Função</a
              >
            </li>
          </ul>
        </div>
        <div class="mt-auto">
          <div class="pt-6">
            <a
              class="
                block
                px-4
                py-3
                mb-3
                leading-loose
                text-xs text-center
                font-semibold
                leading-none
                bg-gray-50
                hover:bg-gray-100
                rounded-l-xl rounded-t-xl
              "
              href="#"
              >Acessar</a
            ><a
              class="
                block
                px-4
                py-3
                mb-2
                leading-loose
                text-xs text-center text-white
                font-semibold
                bg-pink-600
                hover:bg-pink-700
                rounded-l-xl rounded-t-xl
              "
              href="#"
              >Cadastrar-se</a
            >
          </div>
          <p class="my-4 text-xs text-center text-gray-400">
            <span>© 2021 Projeto.</span>
          </p>
          <div class="text-center">
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/facebook-purple.svg" alt="" />
            </a>
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/twitter-purple.svg" alt="" />
            </a>
            <a class="inline-block px-1" href="#">
              <img src="atis-assets/social/instagram-purple.svg" alt="" />
            </a>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>
