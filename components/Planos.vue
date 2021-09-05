<template>
  <section>
    <div class="skew skew-top mr-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-900"
        viewBox="0 0 10 10"
        preserveAspectRatio="none"
      >
        <polygon fill="currentColor" points="0 0 10 10 0 10"></polygon>
      </svg>
    </div>
    <div class="skew skew-top ml-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-900"
        viewBox="0 0 10 10"
        preserveAspectRatio="none"
      >
        <polygon fill="currentColor" points="0 10 10 0 10 10"></polygon>
      </svg>
    </div>
    <div class="py-20 bg-gray-900 radius-for-skewed">
      <div class="container mx-auto px-4">
        <div class="max-w-2xl mx-auto text-center mb-16">
          <span class="text-purple-600 font-bold">Serviços</span>
          <h2
            class="mb-2 text-4xl lg:text-5xl font-bold font-heading text-white"
          >
            Planos
          </h2>
          <p class="mb-6 text-gray-500">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          </p>
          <div class="inline-block py-1 px-1 bg-gray-800 rounded-lg">
            <button
              class="
                mr-1
                text-sm
                py-2
                px-4
                text-gray-500
                hover:text-gray-400
                font-bold
              "
            >
              Mes
            </button>
            <button
              class="
                text-sm
                py-2
                px-4
                text-white
                bg-purple-600
                rounded-lg
                shadow-md
                font-bold
              "
            >
              Ano
            </button>
          </div>
        </div>
        <div class="flex flex-wrap -mx-4">
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8 lg:mb-0">
            <div class="p-8 bg-white shadow rounded">
              <h4 class="mb-2 text-2xl font-bold font-heading">Simples</h4>
              <span class="text-6xl font-bold">R$40</span>
              <p class="mt-3 mb-6 text-gray-500 leading-loose">
                Revisar uma pagina
              </p>
              <ul class="mb-6 text-gray-500">
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>Erros ortograficos</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>Rescrever</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
              </ul>
              <a
                class="
                  inline-block
                  text-center
                  py-2
                  px-4
                  w-full
                  rounded-l-xl rounded-t-xl
                  bg-pink-600
                  hover:bg-pink-700
                  text-white
                  font-bold
                  leading-loose
                  transition
                  duration-200
                "
                href="#"
                >Aceitar</a
              >
            </div>
          </div>
          <div class="w-full md:w-1/2 lg:w-1/3 px-4 mb-8 lg:mb-0">
            <div class="p-8 bg-purple-600 shadow rounded">
              <h4 class="mb-2 text-2xl font-bold text-white">Intermediario</h4>
              <span class="text-6xl font-bold text-white">R$80</span>
              <span class="text-gray-50 text-xs">/mes</span>
              <p class="mt-3 mb-6 leading-loose text-gray-50">
                Trabalho completo por um mês
              </p>
              <ul class="mb-6 text-gray-50">
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-purple-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>suporte</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-purple-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-purple-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-purple-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-purple-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
              </ul>
              <a
                class="
                  inline-block
                  text-center
                  py-2
                  px-4
                  w-full
                  rounded-l-xl rounded-t-xl
                  bg-white
                  hover:bg-gray-100
                  font-bold
                  leading-loose
                  transition
                  duration-200
                "
                href="#"
                >Aceitar</a
              >
            </div>
          </div>
          <div class="w-full lg:w-1/3 px-4">
            <div class="p-8 bg-white shadow rounded">
              <h4 class="mb-2 text-2xl font-bold font-heading">Proficional</h4>
              <span class="text-6xl font-bold">R$2000</span>
              <span class="text-gray-400 text-xs">/Ano</span>
              <p class="mt-3 mb-6 text-gray-500 leading-loose">
                Mimos e tudo mais
              </p>
              <ul class="mb-6 text-gray-500">
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
                <li class="mb-2 flex">
                  <svg
                    class="mr-2 w-5 h-5 text-green-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                  <span>lorem</span>
                </li>
              </ul>
              <a
                class="
                  inline-block
                  text-center
                  py-2
                  px-4
                  w-full
                  rounded-l-xl rounded-t-xl
                  bg-pink-600
                  hover:bg-pink-700
                  text-white
                  font-bold
                  leading-loose
                  transition
                  duration-200
                "
                href="#"
                >Aceitar</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="skew skew-bottom mr-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-900"
        viewBox="0 0 10 10"
        preserveAspectRatio="none"
      >
        <polygon fill="currentColor" points="0 0 10 0 0 10"></polygon>
      </svg>
    </div>
    <div class="skew skew-bottom ml-for-radius">
      <svg
        class="h-8 md:h-12 lg:h-20 w-full text-gray-900"
        viewBox="0 0 10 10"
        preserveAspectRatio="none"
      >
        <polygon fill="currentColor" points="0 0 10 0 10 10"></polygon>
      </svg>
    </div>
  </section>
</template>
