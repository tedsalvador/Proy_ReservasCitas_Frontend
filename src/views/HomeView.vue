<script setup>
const redirectToLogin = () => {
  window.location.href = 'http://localhost:5173/auth/login';}
</script>

<template>
   <main class="flex items-center justify-center h-screen">
    <h1 class="text-7xl cursor-pointer hover:text-blue-500"
        @dblclick="redirectToLogin">
    Reserva Citas App</h1>
  </main>
</template>