<template>
  <div
    class="dark flex-shrink-0 overflow-x-hidden bg-gray-900"
    style="width: 260px"
  >
    <div class="h-full w-[260px]">
      <div class="flex h-full min-h-0 flex-col">
        <div
          class="scrollbar-trigger relative h-full w-full flex-1 items-start border-white/20"
        >
          <h2
            style="
              position: absolute;
              border: 0px;
              width: 1px;
              height: 1px;
              padding: 0px;
              margin: -1px;
              overflow: hidden;
              clip: rect(0px, 0px, 0px, 0px);
              white-space: nowrap;
              overflow-wrap: normal;
            "
          >
            Chat history
          </h2>
          <nav
            class="flex h-full w-full flex-col p-2"
            aria-label="Chat history"
          >
            <div class="mb-1 flex flex-row gap-2">
              <a
                class="flex p-3 items-center gap-3 transition-colors duration-200 text-white cursor-pointer text-sm rounded-md border border-white/20 hover:bg-gray-500/10 h-11 flex-shrink-0 flex-grow"
              >
                <svg
                  stroke="currentColor"
                  fill="none"
                  stroke-width="2"
                  viewBox="0 0 24 24"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="h-4 w-4"
                  height="1em"
                  width="1em"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <line x1="12" y1="5" x2="12" y2="19"></line>
                  <line x1="5" y1="12" x2="19" y2="12"></line></svg
                >Add Database</a
              >
            </div>

            <div
              class="flex-col flex-1 transition-opacity duration-500 overflow-y-auto"
            >
              <div class="flex flex-col gap-2 pb-2 text-gray-100 text-sm">
                <div>
                  <span
                    ><div
                      class="relative"
                      data-projection-id="1"
                      style="height: auto; opacity: 1"
                    >
                      <div
                        class="sticky top-0 z-[16]"
                        data-projection-id="2"
                        style="opacity: 1"
                      >
                        <h3
                          class="h-9 pb-2 pt-3 px-3 text-xs text-gray-500 font-medium text-ellipsis overflow-hidden break-all bg-gray-900"
                        >
                          All Database
                        </h3>
                      </div>
                      <ol>
                        <li
                          class="relative z-[15]"
                          data-projection-id="3"
                          style="opacity: 1; height: auto"
                        >
                          <a
                            class="flex py-3 px-3 items-center gap-3 relative rounded-md hover:bg-[#2A2B32] cursor-pointer break-all )} )} hover:pr-4 bg-gray-900 group"
                            ><svg
                              stroke="currentColor"
                              fill="none"
                              stroke-width="2"
                              viewBox="0 0 24 24"
                              stroke-linecap="round"
                              stroke-linejoin="round"
                              class="h-4 w-4"
                              height="1em"
                              width="1em"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"
                              ></path>
                            </svg>
                            <div
                              class="flex-1 text-ellipsis max-h-5 overflow-hidden break-all relative"
                            >
                              Databse 1
                              <div
                                class="absolute inset-y-0 right-0 w-8 z-10 bg-gradient-to-l from-gray-900 group-hover:from-[#2A2B32]"
                              ></div></div
                          ></a>
                        </li>
                      </ol></div></span
                  ><span></span><span></span>
                </div>
              </div>
            </div>
            <div class="border-t border-white/20 pt-2">
              <div class="group relative" data-headlessui-state="">
                <button
                  class="flex w-full items-center gap-2.5 rounded-md px-3 py-3 text-sm transition-colors duration-200 hover:bg-gray-800 group-ui-open:bg-gray-800"
                  id="headlessui-menu-button-:r8:"
                  type="button"
                  aria-haspopup="true"
                  aria-expanded="false"
                  data-headlessui-state=""
                >
                  <div
                    class="grow overflow-hidden text-ellipsis whitespace-nowrap text-left text-white"
                  >
                    Opeyemi Adeniran
                  </div>
                </button>
              </div>
            </div>
          </nav>
        </div>
      </div>
    </div>
  </div>
</template>
