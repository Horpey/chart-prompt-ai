<template>
  <div class="relative flex h-full max-w-full flex-1 overflow-hidden">
    <div class="flex h-full max-w-full flex-1 flex-col">
      <main
        class="relative h-full w-full transition-width flex flex-col overflow-hidden items-stretch flex-1"
      >
        <div class="flex-1 overflow-hidden">
          <div
            class="react-scroll-to-bottom--css-ayney-79elbk h-full dark:bg-gray-800"
          >
            <div class="react-scroll-to-bottom--css-ayney-1n7m0yu">
              <div class="flex flex-col text-sm dark:bg-gray-800">
                <div
                  class="text-gray-800 w-full mx-auto md:max-w-2xl lg:max-w-3xl md:h-full md:flex md:flex-col px-6 dark:text-gray-100"
                >
                  <h1
                    class="text-4xl font-semibold text-center mt-6 sm:mt-[20vh] ml-auto mr-auto mb-10 sm:mb-16 flex gap-2 items-center justify-center"
                  >
                    Chart Prompt AI
                  </h1>
                  <div class="md:flex items-start text-center gap-3.5">
                    <div class="flex flex-col mb-8 md:mb-auto gap-3.5 flex-1">
                      <ul
                        class="flex flex-col gap-3.5 w-full sm:max-w-md m-auto"
                      >
                        <li
                          class="w-full bg-gray-50 dark:bg-white/5 p-3 rounded-md"
                        >
                          <div class="flex flex-col gap-1">
                            <h3 class="text-lg font-semibold">
                              What is Chart Prompt AI?
                            </h3>
                            <p class="text-sm">
                              Chart Prompt AI is a tool that helps you to
                              generate charts from your data. It is a
                              no-code/low-code tool that helps you to generate
                              charts from your data.
                            </p>
                          </div>
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
                <div class="h-32 md:h-48 flex-shrink-0"></div>
              </div>
            </div>
          </div>
        </div>
        <div
          class="absolute bottom-0 left-0 w-full border-t md:border-t-0 dark:border-white/20 md:border-transparent md:dark:border-transparent md:bg-vert-light-gradient bg-white dark:bg-gray-800 md:!bg-transparent dark:md:bg-vert-dark-gradient pt-2"
        >
          <form
            class="stretch mx-2 flex flex-row gap-3 last:mb-2 md:mx-4 md:last:mb-6 lg:mx-auto lg:max-w-2xl xl:max-w-3xl"
          >
            <div
              class="relative flex h-full flex-1 items-stretch md:flex-col"
              role="presentation"
            >
              <div
                class="flex flex-col w-full py-[10px] flex-grow md:py-4 md:pl-4 relative border border-black/10 bg-white dark:border-gray-900/50 dark:text-white dark:bg-gray-700 rounded-xl shadow-xs dark:shadow-xs"
              >
                <textarea
                  id="prompt-textarea"
                  tabindex="0"
                  data-id="root"
                  rows="1"
                  placeholder="Send a message."
                  class="m-0 w-full resize-none border-0 bg-transparent p-0 pr-10 focus:ring-0 focus-visible:ring-0 dark:bg-transparent md:pr-12 pl-3 md:pl-0"
                  style="max-height: 200px; height: 24px; overflow-y: hidden"
                ></textarea
                ><button
                  class="absolute p-1 rounded-md md:bottom-3 md:p-2 md:right-3 dark:hover:bg-gray-900 dark:disabled:hover:bg-transparent right-2 disabled:text-gray-400 enabled:bg-brand-purple text-white bottom-1.5 transition-colors disabled:opacity-40"
                >
                  <span class="" data-state="closed"
                    ><svg
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 16 16"
                      fill="none"
                      class="h-4 w-4 m-1 md:m-0"
                      stroke-width="2"
                    >
                      <path
                        d="M.5 1.163A1 1 0 0 1 1.97.28l12.868 6.837a1 1 0 0 1 0 1.766L1.969 15.72A1 1 0 0 1 .5 14.836V10.33a1 1 0 0 1 .816-.983L8.5 8 1.316 6.653A1 1 0 0 1 .5 5.67V1.163Z"
                        fill="currentColor"
                      ></path></svg
                  ></span>
                </button>
              </div>
            </div>
          </form>
        </div>
      </main>
    </div>
  </div>
</template>
