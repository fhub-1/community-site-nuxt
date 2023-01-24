<template>
    <nav class="bg-gray-800 p-6">
      <div class="container mx-auto flex items-center justify-between">
        <div class="w-1/3 text-left">
          <nuxt-link to="/" class="text-white text-lg">My Community Site</nuxt-link>
        </div>
        <div class="w-1/3 text-center">
          <nuxt-link to="/topics/javascript" class="text-white text-lg">JavaScript</nuxt-link>
          <nuxt-link to="/topics/python" class="text-white text-lg">Python</nuxt-link>
          <nuxt-link to="/topics/ruby" class="text-white text-lg">Ruby</nuxt-link>
        </div>
      </div>
    </nav>
  </template>
  