<script>
export default {
  props: {
    story: {
      type: Object,
      required: true
    }
  }
}
</script>
<template>
  <div class="flex h-auto">
    <div class="flex flex-col bg-white rounded-xl dark:bg-neutral-900">
      <div class="flex-auto p-4 md:p-6">
        <p class="text-base italic md:text-lg text-gray-800 dark:text-neutral-200">
          " {{ story.desc }}"
        </p>
      </div>

      <div class="p-4 bg-gray-100 rounded-b-xl md:px-7 dark:bg-neutral-800">
        <div class="flex items-center gap-x-3">
          <div class="shrink-0">
            <img
              class="size-8 sm:h-[2.875rem] sm:w-[2.875rem] rounded-full"
              :src="story.image"
              alt="Avatar"
            />
          </div>

          <div class="grow">
            <p class="text-sm sm:text-base font-semibold text-gray-800 dark:text-neutral-200">
              {{ story.name }}
            </p>
            <p class="text-xs text-gray-500 dark:text-neutral-400">{{ story.job }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
