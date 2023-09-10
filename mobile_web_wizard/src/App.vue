<template>
    <div id="app">
      <AppHeader /> 
      <AppServices /> 
      <AppAbout />
      <AppContact />
      <AppGallery />
    </div>
  </template>
  
  <script>
  import AppHeader from './components/AppHeader.vue';
  import AppServices from './components/AppServices.vue';
  import AppAbout from './components/AppAbout.vue';
  import AppContact from './components/AppContact.vue';
  import AppGallery from './components/AppGallery.vue';
  
  export default {
    components: {
      AppHeader,
      AppServices,
      AppAbout,
      AppContact,
      AppGallery
    },
  };
  </script>
  
  <style>
  /* Add your global styles here */
  </style>
  