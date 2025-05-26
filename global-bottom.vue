<template>
  <footer
    v-if="$nav.currentLayout !== 'cover'"
    class="absolute bottom-0 left-0 right-0 p-2 flex items-center"
  >
    <span class="ml-auto">&copy; 2025 Yuhei FUJITA <{{ $nav.currentPage }} / {{ $nav.total }}></span>
  </footer>
</template>