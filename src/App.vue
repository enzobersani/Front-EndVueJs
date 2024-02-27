<template>
    <section class="grid gap-4 sm:grid-cols-2 md:grid-cols-3 container mx-auto">
      <p v-for="item in list" :key="item.id">{{ item.tittle }}</p>
      <h1 className="text-3xl font-bold underline">
        Hello world!
      </h1>
    </section>
  </template>
  
  <script>
  export default {
    setup(){
      const list = [
        {id: 1, tittle: "Tailwind CSS"},
        {id: 2, tittle: "Tailwind CSS"},
        {id: 3, tittle: "Tailwind CSS"},
        {id: 4, tittle: "Tailwind CSS"},
        {id: 5, tittle: "Tailwind CSS"},
        {id: 6, tittle: "Tailwind CSS"},
        {id: 7, tittle: "Tailwind CSS"},
        {id: 8, tittle: "Tailwind CSS"},
        {id: 9, tittle: "Tailwind CSS"},
      ];
  
      return { list };
    }
  };
  </script>
  
  <style>
  
  </style>