<script>
export default {
  props: {
    course: {
      type: Object,
      required: true
    }
  }
}
</script>

<template>
  <div
    class="rounded-lg border border-gray-200 bg-white shadow-sm dark:border-gray-700 dark:bg-gray-800 max-w-72"
  >
    <div class="w-full">
      <a href="#">
        <img class="w-full dark:hidden" :src="course.image" alt="" />
        <img class="w-full hidden dark:block" :src="course.image" alt="" />
      </a>
    </div>
    <div class="p-6">
      <a
        href="#"
        class="text-lg font-semibold leading-tight text-gray-900 hover:underline dark:text-white"
        >{{ course.title }}</a
      >

      <ul class="mt-2 flex items-center gap-4">
        <li class="flex items-center gap-2">
          <p class="text-sm font-medium text-gray-500 dark:text-gray-400">{{ course.classType }}</p>
        </li>

        <li class="flex items-center gap-2">
          <p class="text-sm font-medium text-gray-500 dark:text-gray-400">{{ course.duration }}</p>
        </li>
      </ul>

      <div class="mt-4 flex items-center gap-2">
        <div class="flex -space-x-2">
          <img
            class="inline-block size-8 rounded-full ring-2 ring-white dark:ring-neutral-900"
            src="https://images.unsplash.com/photo-1568602471122-7832951cc4c5?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=2&w=300&h=300&q=80"
            alt="Avatar"
          />
          <img
            class="inline-block size-8 rounded-full ring-2 ring-white dark:ring-neutral-900"
            src="https://images.unsplash.com/photo-1531927557220-a9e23c1e4794?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=2&w=300&h=300&q=80"
            alt="Avatar"
          />
          <img
            class="inline-block size-8 rounded-full ring-2 ring-white dark:ring-neutral-900"
            src="https://images.unsplash.com/photo-1541101767792-f9b2b1c4f127?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&&auto=format&fit=facearea&facepad=3&w=300&h=300&q=80"
            alt="Avatar"
          />
        </div>
        <p class="text-md font-medium leading-tight text-gray-900 dark:text-white">
          {{ course.subs }} <span class="text-xl font-bold">+</span>
        </p>
      </div>
      <a
        class="mt-4 inline-flex items-center gap-x-1 text-sm font-semibold rounded-lg border border-transparent text-blue-600 decoration-2 hover:text-blue-700 hover:underline focus:underline focus:outline-none focus:text-blue-700 disabled:opacity-50 disabled:pointer-events-none dark:text-blue-500 dark:hover:text-blue-600 dark:focus:text-blue-600"
        href="#"
      >
        Daftar Sekarang
        <svg
          class="shrink-0 size-4"
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path d="m9 18 6-6-6-6"></path>
        </svg>
      </a>
    </div>
  </div>
</template>
