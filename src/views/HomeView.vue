<script setup>
import { media } from "vue-media";
import IconBrandEth from "@/components/icons/IconBrandEth.vue";
import IconBrandGit from "@/components/icons/IconBrandGit.vue";
import IconBrandJavascript from "@/components/icons/IconBrandJavascript.vue";
import IconBrandReact from "@/components/icons/IconBrandReact.vue";
import IconBrandNpm from "@/components/icons/IconBrandNpm.vue";
import IconBrandSvelte from "@/components/icons/IconBrandSvelte.vue";
import IconBrandTailwind from "@/components/icons/IconBrandTailwind.vue";
import IconBrandVue from "@/components/icons/IconBrandVue.vue";
import IconBrandVscode from "@/components/icons/IconBrandVscode.vue";
import IconBrandVite from "@/components/icons/IconBrandVite.vue";
</script>

<template>
  <div
    class="h-screen w-screen p-0 m-0 bg-local sm:bg-cover bg-no-repeat bg-center transition-all ease-in-out duration-100 relative"
    style="background-image: url(/images/web3permain.png)"
  >
    <Transition>
      <div class="text-gray-300 font-mono flex flex-col overflow-hidden">
        <div>
          <span
            class="absolute 2xl:ml-[18.5%] ml-[8%] 2xl:mt-16 sm:mt-14 mt-8 text-[2rem] 2xl:text-[2.6rem] font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-orange-500"
            >Per Pettersen</span
          >
          <p
            class="absolute 2xl:ml-[22.9%] ml-[23%] sm:ml-[12.9%] 2xl:mt-28 2xl:text-sm text-[0.6rem] mt-[4.3rem] sm:mt-[6rem]"
          >
            - <span class="font-extrabold text-purple-300">Web 3 </span
            ><span class="text-[0.6rem]">developer</span>
            -
          </p>
          <div
            class="absolute 2xl:ml-[18.5%] m-[6%] 2xl:mt-48 mt-28 2xl:w-[19%] 2xl:text-md text-xs sm:ml-[5%] xl:max-w-xl"
          >
            <span class="font-extrabold text-purple-200"
              >I've always been drawn to the power of technology to change the
              world.</span
            >
            <br /><br />As a full-stack developer, I've dedicated my dev career
            to understanding the potential of decentralized technologies and how
            they can empower people to take control of their own data and
            assets.<br /><br />
            My passion for blockchain technology led me to start my personal
            blog, where I share my thoughts on the intersection of
            <span class="text-cyan-200 font-bold">Web3</span>,
            <span class="text-rose-200 font-bold">Blockchain</span>, and
            <span class="text-orange-200 font-bold">AI</span>.

            <article
              class="animate-background 2xl:mt-20 rounded-xl bg-gradient-to-r mt-6 from-rose-200 via-purple-300 to-orange-500 bg-[length:400%_400%] p-[0.11rem] shadow-xl transition [animation-duration:_6s] hover:shadow-sm dark:shadow-gray-700/25"
            >
              <div class="rounded-[10px] bg-white p-4 dark:bg-gray-900 sm:p-4">
                <time
                  datetime="2022-10-10"
                  class="block text-xl text-gray-200 dark:text-orange-300 mb-2"
                >
                  Tools
                </time>
                <div
                  class="flex flex-row flex-wrap w-full gap-x-2 gap-y-2 justify-center"
                >
                  <div
                    class="flex flex-row items-center text-cyan-300 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandEth
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Solidity
                  </div>
                  <div
                    class="flex flex-row items-center text-yellow-100 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandJavascript
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Javascript
                  </div>
                  <div
                    class="flex flex-row items-center text-teal-300 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandVue
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Vue.js3
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandVite
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Vite
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandTailwind
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />TailwindCSS
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandGit
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Git
                  </div>
                  <div
                    class="flex flex-row items-center text-purple-300 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandVscode
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Vscode
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandSvelte
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />Svelte
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandReact
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />React
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
                  >
                    <IconBrandNpm
                      class=""
                      style="width: 2.5rem; height: 2.5rem"
                    />
                  </div>
                </div>
              </div>
            </article>
          </div>
        </div>
      </div>
    </Transition>
    <!-- <div class="static right-0 w-12 h-12 ml-[16%] mt-24 text-white bg-gray-600">
      Menu
    </div> -->
  </div>
</template>

<style scoped>
.h-screen {
  height: 100vh;
}
.w-screen {
  width: 100vw;
}
.p-0 {
  padding: 0;
}
.m-0 {
  margin: 0;
}

/* we will explain what these classes do next! */
.v-enter-active,
.v-leave-active {
  transition: opacity 0.5s ease;
}
.v-enter-from,
.v-leave-to {
  opacity: 0;
}
.small {
  @apply w-[1.5rem] h-[1.5rem];
}
.big {
  @apply w-[2.5rem] h-[2.5rem];
}
</style>
