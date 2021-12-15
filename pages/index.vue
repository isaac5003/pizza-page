<template>
  <div>
    <nav class="w-full p-5 sticky top-0 bg-white/95">
      <div class="flex items-center justify-between">
        <div>LOGO</div>
        <div class="block">
          <ul class="flex space-x-8 text-sm font-sans">
            <li><a href="">Menú</a></li>
            <li><a href="">Shop</a></li>
            <li><a href="">Order</a></li>
          </ul>
        </div>
        <div class="items-notification flex gap-4">
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              />
            </svg>
          </div>
          <div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
              />
            </svg>
          </div>
        </div>
      </div>
    </nav>
    <div class="w-full flex p-10 bg-slate-100">
      <div class="w-1/2 p-4">
        <div class="text-6xl font-medium">
          <span class="block">Feel Better</span
          ><span class="block pt-4">With Good Food</span>
        </div>
        <div class="pt-10 text-gray-400 text-xl tracking-wide">
          <p class="block">Just confirm your order and enjoy our</p>
          <p>delicius fastest delivery.</p>
        </div>
        <div class="flex pt-12 gap-8">
          <button
            class="
              py-2
              px-7
              rounded-full
              text-sm
              font-semibold
              text-white
              bg-gradient-to-r
              from-rose-600
              to-rose-500
              hover:shadow-lg hover:shadow-rose-500
              tracking-wider
              hover:-translate-y-1
              hover:scale-110
              hover:delay-200
              hover:duration-150
            "
          >
            Order Now
          </button>
        </div>
      </div>
      <div class="w-1/2 p-8">
        <img src="../assets/images/pizza.png" alt="" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "nameDefault",
  components: {},
  fetch() {},
  data() {
    return {
      bell: '<svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" /></svg>',
    };
  },
  methods: {},
  computed: {},
};
</script>