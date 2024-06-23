<template>
  <!-- 모달 start -->
  <div
    class="fixed right-0 top-0 duration-300 w-screen h-screen px-[80px] opacity-100 z-30"
    v-if="isOpen"
  >
    <div class="w-full h-full bg-[#1c1c1c]">
      <div class="inner absolute left-[27vw]" style="top: 50%; transform: translateY(-50%)">
        <div class="flex flex-col font-bold text-3xl sm:text-5xl space-y-[36px]">
          <a href="https://amuz.co.kr/works" class="hover:pl-[30px] duration-300 flex items-center">
            <span class="hover:text-blue-500 font-semibold mr-4 poppins text-[80px]">Works</span>
            <span
              class="num text-[36px] rounded-full bg-blue-500 bg-opacity-100 px-[22px] py-[10px] font-semibold text-white ring-1 ring-inset ring-blue-700/10 poppins align-middle mt-3"
              style="border: 2px solid rgb(67, 117, 255)"
              >20</span
            >
          </a>
          <a href="https://amuz.co.kr/about" class="hover:pl-[30px] duration-300 flex items-center">
            <span class="hover:text-blue-500 font-semibold mr-4 poppins text-[80px]">About Us</span>
          </a>
          <a
            href="https://amuz.co.kr/contact"
            class="hover:pl-[30px] duration-300 flex items-center"
          >
            <span class="hover:text-blue-500 font-semibold mr-4 poppins text-[80px]">Contact</span>
          </a>
          <a
            href="https://amuz.co.kr/service"
            class="hover:pl-[30px] duration-300 flex items-center"
          >
            <span class="hover:text-blue-500 font-semibold mr-4 poppins text-[80px]">Services</span>
          </a>
        </div>
        <div class="flex items-center mt-[100px] font-medium">
          <a
            href="https://amuz.co.kr/crew"
            class="group items-center gap-2 text-[40px] inline-block !pl-0"
          >
            <span class="group-hover:text-blue-500 duration-300 poppins font-medium"
              >Amuz Crew
            </span>
          </a>

          <a href="https://amuz.co.kr/hiring" class="group flex items-center gap-2 text-[40px]">
            <span class="group-hover:text-blue-500 duration-300 poppins font-medium">Hiring</span>
          </a>
          <a href="https://amuz.co.kr/news" class="group flex items-center gap-2 text-[40px]">
            <span class="group-hover:text-blue-500 duration-300 poppins font-medium">News</span>
          </a>
        </div>
      </div>
    </div>
    <div class="sns-wrap">
      <ul class="w-full sns-wrap flex items-center gap-8">
        <li>
          <a href="https://blog.naver.com/amuz_official" target="_blank"
            ><svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32">
              <g id="그룹_47937" data-name="그룹 47937" transform="translate(-1453 -116)">
                <path
                  id="Icon_awesome-blog"
                  data-name="Icon awesome-blog"
                  d="M9.568,13.982A1.333,1.333,0,0,0,8,15.3v2.787A1.33,1.33,0,0,0,8.929,19.3,2.657,2.657,0,1,1,5.334,21.79V8.077A1.327,1.327,0,0,0,4,6.75H1.334A1.327,1.327,0,0,0,0,8.077V21.79a8,8,0,1,0,9.568-7.808Z"
                  transform="translate(1461 113.25)"
                  fill="#fff"
                ></path>
                <rect
                  id="사각형_25208"
                  data-name="사각형 25208"
                  width="32"
                  height="32"
                  transform="translate(1453 116)"
                  fill="none"
                ></rect>
              </g></svg
          ></a>
        </li>
        <li>
          <a href="https://www.instagram.com/amuz_official/" target="_blank"
            ><svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 32 32">
              <g id="그룹_47936" data-name="그룹 47936" transform="translate(-1525 -116)">
                <path
                  id="패스_2687"
                  data-name="패스 2687"
                  d="M8.847,2H20.54a6.854,6.854,0,0,1,6.847,6.847V20.54a6.854,6.854,0,0,1-6.847,6.847H8.847A6.854,6.854,0,0,1,2,20.54V8.847A6.854,6.854,0,0,1,8.847,2ZM20.54,25.387a4.852,4.852,0,0,0,4.847-4.847V8.847A4.852,4.852,0,0,0,20.54,4H8.847A4.852,4.852,0,0,0,4,8.847V20.54a4.852,4.852,0,0,0,4.847,4.847Z"
                  transform="translate(1526.613 117)"
                  fill="#fff"
                ></path>
                <path
                  id="패스_2688"
                  data-name="패스 2688"
                  d="M16.741,10.935a5.708,5.708,0,0,1,.834.062,5.677,5.677,0,0,1,1.72,10.687,5.7,5.7,0,0,1-2.551.606,5.678,5.678,0,0,1,0-11.355Zm0,9.355a3.678,3.678,0,0,0,3.636-4.217,3.677,3.677,0,0,0-3.1-3.1,3.7,3.7,0,0,0-.541-.04,3.678,3.678,0,0,0,0,7.355Z"
                  transform="translate(1524.615 115.03)"
                  fill="#fff"
                ></path>
                <path
                  id="패스_2689"
                  data-name="패스 2689"
                  d="M26.25,9.75h0"
                  transform="translate(1521.488 115.512)"
                  fill="none"
                  stroke="#fff"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                ></path>
                <rect
                  id="사각형_25209"
                  data-name="사각형 25209"
                  width="32"
                  height="32"
                  transform="translate(1525 116)"
                  fill="none"
                ></rect>
              </g></svg
          ></a>
        </li>
      </ul>
    </div>
  </div>
  <!-- 모달 end -->

  <!-- 헤더부분 start -->
  <div
    class="sticky top-0 z-50 backdrop-blur-[30px] h-[88px] py-[24px] bg-[#1c1c1c80]"
    :class="{
      'border-b-black border-b-[1.5px]': !isOpen && !isScrolled,
      'border-none': isScrolled
    }"
  >
    <div class="flex justify-between items-center">
      <h1 class="text-[30px] text-center">amuz</h1>
      <nav>
        <button class="w-10 h-10 relative focus:outline-none" @click="toggleMenu">
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
  <!-- 헤더부분 end -->
</template>

<script>
export default {
  name: 'HeaderTop',
  data() {
    return {
      isOpen: false,
      isScrolled: false
    }
  },
  methods: {
    toggleMenu() {
      this.isOpen = !this.isOpen
    },
    handleScroll() {
      this.isScrolled = window.scrollY > 0
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll)
  },
  beforeUnmount() {
    window.removeEventListener('scroll', this.handleScroll)
  }
}
</script>

<style scoped>
.group {
  padding: 0 27px;
}
.sns-wrap {
  position: absolute;
  bottom: 40px;
  left: 85%;
}
.sns-wrap ul {
  ul {
    margin-bottom: 80px;
    justify-content: right;
  }
}
</style>
