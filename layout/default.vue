<template>
    <div>
      <header>
        <nuxt-link to="/">Home</nuxt-link>
      </header>
      <main>
        <nuxt />
      </main>
      <footer>
        Copyright © {{ new Date().getFullYear() }}
      </footer>
    </div>
  </template>
  