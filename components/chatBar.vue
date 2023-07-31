<template>
  <div class="relative flex h-full w-full flex-1 flex-col">
    <div
      class="absolute bottom-0 left-0 w-full border-t md:border-t-0 dark:border-white/20 md:border-transparent md:dark:border-transparent bg-white dark:bg-gray-800 md:!bg-transparent dark:md:bg-vert-dark-gradient pt-2 md:pl-2 md:w-[calc(100%-.5rem)]"
    >
      <form
        class="stretch mx-2 flex flex-row gap-3 last:mb-2 md:mx-4 md:last:mb-6 lg:mx-auto lg:max-w-2xl xl:max-w-3xl"
      >
        <div class="relative flex h-full flex-1 items-stretch md:flex-col">
          <input
            type="text"
            class="self-stretch px-7 py-4 bg-white rounded-lg shadow border border-gray-300 justify-start items-center gap-2 inline-flex"
            placeholder="Ask me Anything"
          />
          <button type="submit" class="btn-primary">
            <div class="w-5 h-5 relative">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="white"
              >
                <path
                  d="M3.478 2.405a.75.75 0 00-.926.94l2.432 7.905H13.5a.75.75 0 010 1.5H4.984l-2.432 7.905a.75.75 0 00.926.94 60.519 60.519 0 0018.445-8.986.75.75 0 000-1.218A60.517 60.517 0 003.478 2.405z"
                />
              </svg>
            </div>
          </button>
        </div>
      </form>
      <div></div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
