<template>
    <div class='header shadow-lg grid justify-items-stretch grid-cols-9 gap-4 items-center flex-grow'>
        <h3 class="cornerTitle text-white col-span-1">*Please note: The Benji Foundation is not a real charity.</h3>
        <NuxtLink to="/" class="font-medium text-white col-start-7 col-span-1 responsive-font">Home</NuxtLink>
        <NuxtLink to="/about" class="font-medium text-white col-start-8 col-span-1 responsive-font">About</NuxtLink>
        <NuxtLink to="/donate" class="font-medium text-white col-start-9 col-span-1 responsive-font">Donate</NuxtLink>
    </div>
</template>

<style>

.header {
    position: fixed;
    height: 55px;
    top: 0;
    width: 100%;
    padding: 0px 10px;
    background-color: #132A3A;
}

.cornerTitle {
    text-transform: uppercase;
    font-size: calc(4px + 0.2vw)
}

.responsive-font {
    font-size: calc(9px + 0.4vw);
    width: auto;
}

a.nuxt-link-active {
  font-weight: bold;
}
/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
  color: #00c58e;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
