<script setup>
import darkLogo from '/img/dark-theme-logo.png'
</script>
<template>
  <footer class="bg-[#071f51] border-gray-200 pt-8 pb-16">
    <div class="max-w-screen-xl mx-auto p-4">
      <div class="md:flex md:justify-between">
        <div class="mb-6 md:mb-0">
          <a href="https://flowbite.com" class="flex items-center">
            <img :src="darkLogo" class="mr-3 h-8" alt="FlowBite Logo" />
          </a>
          <div class="my-4 w-3/4">
            <p class="text-gray-300">Jogja Office</p>
            <p class="text-gray-400">
              Jl. Kresna, Gamping Kidul, Ambarketawang, Kec. Gamping, Kabupaten Sleman, DIY 55294
            </p>
          </div>
          <div class="my-4 w-3/4">
            <p class="text-gray-300">Jakarta Office</p>
            <p class="text-gray-400">
              Cibis Nine Building Lantai 11 Jl. TB Simatupang No. 2 Jakarta Selatan
            </p>
          </div>
        </div>
        <div class="grid grid-cols-2 gap-8 sm:gap-6 sm:grid-cols-3">
          <div>
            <h2 class="mb-6 text-sm font-semibold uppercase text-white">Bootcamp</h2>
            <ul class="text-gray-400">
              <li class="mb-4">
                <a href="" class="hover:underline">DevOps</a>
              </li>
              <li class="mb-4">
                <a href="" class="hover:underline">Quality Assurance</a>
              </li>
              <li class="mb-4">
                <a href="" class="hover:underline">Full Stack Developer</a>
              </li>
              <li class="mb-4">
                <a href="" class="hover:underline">Project Manager</a>
              </li>
            </ul>
          </div>
          <div>
            <h2 class="mb-6 text-sm font-semibold uppercase text-white">SISTEM</h2>
            <ul class="text-gray-400">
              <li class="mb-4">
                <a href="" class="hover:underline">Tentang Kami</a>
              </li>
              <li class="mb-4">
                <a href="" class="hover:underline">Events</a>
              </li>
              <li class="mb-4">
                <a href="" class="hover:underline">FAQ</a>
              </li>
            </ul>
          </div>
          <div>
            <h2 class="mb-6 text-sm font-semibold uppercase text-white">Ikuti Kami</h2>
            <ul class="text-gray-400">
              <li class="mb-4">
                <a href="#" class="hover:underline">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="lucide lucide-instagram"
                  >
                    <rect width="20" height="20" x="2" y="2" rx="5" ry="5" />
                    <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />
                    <line x1="17.5" x2="17.51" y1="6.5" y2="6.5" />
                  </svg>
                </a>
              </li>
              <li class="mb-4">
                <a href="#" class="hover:underline flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="#ADF08D"
                    stroke="currentColor"
                    stroke-width="0"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="lucide lucide-phone text-[#ADF08D] me-2"
                  >
                    <path
                      d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"
                    />
                  </svg>
                  +62 811-269-086</a
                >
              </li>
              <li class="mb-4">
                <a href="#" class="hover:underline flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="20"
                    height="20"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="lucide lucide-mail text-[#ADF08D] me-2"
                  >
                    <rect width="20" height="16" x="2" y="4" rx="2" />
                    <path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7" />
                  </svg>
                  putro@solutionlabs.id</a
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterMenu'
}
</script>
