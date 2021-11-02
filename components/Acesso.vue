<template>
  <section class="relative bg-gray-800 h-screen py-20">
    <!-- Cadastro inteiro-->
    <div class="w-full flex flex-wrap items-center">
      <div class="mx-auto">
        <div class="max-w-md p-6 bg-gray-50 text-center rounded-lg">
          <form action="#">
            <span class="text-sm text-gray-500 font-semibold uppercase"
              >Acessar</span
            >
            <h3 class="mb-8 text-2xl font-bold font-heading">Conta</h3>
            <input
              class="
                border-2 border-transparent
                w-full
                py-3
                pl-3
                mb-4
                bg-white
                rounded-lg
                focus:border-purple-600
                focus:outline-none
              "
              type="email"
              placeholder="Endereço de Email"
            />
            <input
              class="
                border-2 border-transparent
                w-full
                py-3
                pl-3
                mb-4
                bg-white
                rounded-lg
                focus:border-purple-600
                focus:outline-none
              "
              type="password"
              placeholder="Senha"
            />

            <button
              class="
                w-full
                inline-block
                px-6
                py-3
                mr-4
                text-sm text-white
                font-bold
                leading-loose
                bg-purple-600
                hover:bg-purple-600
                rounded
                transition
                duration-200
              "
            >
              Continuar
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
