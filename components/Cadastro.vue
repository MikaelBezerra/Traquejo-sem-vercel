<template>
  <section class="relative bg-gray-800 h-screen py-20">
    <!-- Cadastro inteiro-->
    <div class="w-full flex flex-wrap items-center">
      <div class="mx-auto">
        <div class="max-w-md p-6 bg-gray-50 text-center rounded-lg">
          <form action="#">
            <span class="text-sm text-gray-500 font-semibold uppercase"
              >Cadastrar</span
            >
            <h3 class="mb-8 text-2xl font-bold font-heading">Criar Conta</h3>
            
            <input
              class="
                border-2 border-transparent
                w-full
                py-3
                pl-3
                mb-4
                bg-white
                rounded-lg
                focus:border-purple-600 focus:outline-none
              "
              type="name"
              placeholder="Nome do Usuário"
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
                focus:border-purple-600 focus:outline-none
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
                focus:border-purple-600 focus:outline-none
              "
              type="password"
              placeholder="Senha"
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
                focus:border-purple-600 focus:outline-none
              "
              type="password"
              placeholder="Confirmar senha"
            />
            <label class="inline-block mb-4">
              <input class="mr-1" type="checkbox" name="terms" value="1" />
              <span class="text-sm text-gray-500"
                >Concordar com os
                <a class="font-bold hover:underline" href="#"
                  >Termos, Privacidade</a
                >
                e
                <a class="font-bold hover:underline" href="#">Cookies</a>.</span
              >
            </label>
            <button
              class="
                w-full
                inline-block
                px-6
                p-3
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
          <span class="text-sm text-gray-500"
            >Já possui conta? Acesse
            <a class="font-bold hover:underline" href="acesso">Aqui</a>
          </span>
        </div>
      </div>
    </div>
  </section>
</template>
