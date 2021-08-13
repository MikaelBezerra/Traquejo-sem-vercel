<template>
  <nav class="bg-gray-900 w-screen static h-14">
    <div class="flex h-full inline-block items-center">
      <!-- Logo do projeto -->
      <div class="absolute left-8">
        <Logo />
      </div>
      <!-- Botão cadastro e login -->
      <div class="absolute right-8 space-x-2">
        <!-- ===================================== -->
        <button
          class="
            border-gray-900
            text-sm
            shadow
            py-0.5
            px-2
            border-2
            rounded-lg
            bg-gray-50
            p-1
          "
        >
          Acessar
        </button>
        <!-- ===================================== -->
        <button
          class="
            bg-gradient-to-r
            from-blue-400
            via-indigo-500
            to-purple-700
            text-green-50
            shadow
            text-sm
            p-1
            py-0.5
            border-2 border-gray-900
            to-purple-700
            px-2
            rounded-lg
          "
        >
          Cadastrar
        </button>
        <!-- ===================================== -->
      </div>
    </div>
  </nav>
</template>
