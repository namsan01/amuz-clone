<template>
  <div class="sticky top-0 z-50 backdrop-blur-[30px] h-[88px] py-[24px] bg-blue-200">
    <div class="flex justify-between items-center">
      <h1 class="text-[30px] text-center">amuz</h1>
      <nav>
        <button class="text-gray-500 w-10 h-10 relative focus:outline-none" @click="toggleMenu">
          <span class="sr-only">Open main menu</span>
          <div
            class="block w-5 absolute left-1/2 top-1/2 transform -translate-x-1/2 -translate-y-1/2"
          >
            <span
              aria-hidden="true"
              class="block absolute h-0.5 w-5 bg-current transform transition duration-500 ease-in-out"
              :class="{ 'rotate-45': isOpen, ' -translate-y-1.5': !isOpen }"
            ></span>
            <span
              aria-hidden="true"
              class="block absolute h-0.5 w-5 bg-current transform transition duration-500 ease-in-out"
              :class="{ 'opacity-0': isOpen }"
            ></span>
            <span
              aria-hidden="true"
              class="block absolute h-0.5 w-5 bg-current transform transition duration-500 ease-in-out"
              :class="{ '-rotate-45': isOpen, ' translate-y-1.5': !isOpen }"
            ></span>
          </div>
        </button>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderTop',
  data() {
    return {
      isOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.isOpen = !this.isOpen
    }
  }
}
</script>

<style scoped></style>
