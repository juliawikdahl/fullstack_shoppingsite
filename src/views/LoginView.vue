<template>
    <div>
      <h1>Välkommen till inloggningssidan</h1>
      <LoginForm />
    </div>
  </template>
  
  <script>
  import LoginForm from '@/components/users/LoginForm.vue';
  
  export default {
    name: 'LoginView',
    components: {
      LoginForm
    }
  };
  </script>
  
  <style scoped>
  /* Lägg till valfri styling här */
  </style>
  