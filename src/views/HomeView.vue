<script setup>
import { ref, computed } from "vue";
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
import IconBrandTwitter from "@/components/icons/IconBrandTwitter.vue";
import IconBrandLinkedin from "@/components/icons/IconBrandLinkedin.vue";
import IconBrandGithub from "@/components/icons/IconBrandGithub.vue";
import IconBrandNodejs from "@/components/icons/IconBrandNodejs.vue";
import IconArrowLeft from "@/components/icons/IconArrowLeft.vue";
import IconArrowRight from "@/components/icons/IconArrowRight.vue";
import IconApp from "@/components/icons/IconApp.vue";
import IconArticle from "@/components/icons/IconArticle.vue";

const projects = ref(false);
const isLarge = computed(() => {
  if (screenWidth.value >= 1500) {
    return true;
  } else {
    return true;
  }
});
const screenWidth = ref(window.innerWidth);

window.addEventListener("resize", () => {
  screenWidth.value = window.innerWidth;
});
const widthHeight = computed(() => {
  if (screenWidth.value >= 1500) {
    return { width: "2rem", height: "2rem" };
  } else {
    return { width: "1.75rem", height: "1.75rem" };
  }
});
const widthHeightLinks = computed(() => {
  if (screenWidth.value >= 1500) {
    return { width: "1.5rem", height: "1.5rem" };
  } else {
    return { width: "1.4rem", height: "1.4rem" };
  }
});
const widthHeightSub = computed(() => {
  if (screenWidth.value >= 1500) {
    return { width: "1.2rem", height: "1.2rem" };
  } else {
    return { width: "1.0rem", height: "1.0rem" };
  }
});

const widthTest = computed(() => {
  return widthHeight.value * 0.15 + "rem";
});
</script>

<template>
  <div
    class="h-screen w-screen p-0 m-0 sm:bg-cover bg-no-repeat bg-right transition-transform ease-in duration-100 relative overflow-auto"
    style="background-image: url(/images/web3permain80.png)"
  >
    <Transition>
      <div
        class="sm:absolute xl:w-[20.85%] mx-auto w-[99%] my-auto bg-gray-800 bg-transparent xl:ml-[17.6%] md:w-[24rem] sm:w-[24rem] transition-all duration-200 ease-out"
      >
        <div
          class="h-full flex flex-col w-full text-gray-200 sm:pt-12 pt-10 xl:px-3 sm:px-5 px-6 font-mono xl:bg-opacity-0 sm:bg-opacity-90 sm:bg-gray-900"
        >
          <div class="">
            <span
              class="mt-8 text-[2rem] 2xl:text-[2.6rem] font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-orange-500 xl:text-"
              >Per Pettersen</span
            >
          </div>
          <div>
            <p class="text-[0.6rem]">
              <span
                class="font-extrabold text-orange-300 text-[0.6rem] 2xl:text-xs"
                >Web 3 </span
              ><span class="text-[0.6rem] 2xl:text-xs">developer | </span
              ><span
                class="text-purple-200 2xl:text-xs text-[0.6rem] font-extrabold"
                >Blockchain </span
              ><span class="text-[0.6rem] 2xl:text-xs">Educator</span>
            </p>
          </div>
          <div
            class="leading-5 mt-10 2xl:text-[1rem] 2xl:leading-5 text-[0.85rem]"
          >
            <span class="font-extrabold text-purple-200 xl:text-purple-300"
              >I've always been drawn to the power of technology to change the
              world.</span
            ><span class="2xl:text-gray-300">
              <br /><br />As a full-stack developer, I've dedicated my dev
              career to understanding the potential of decentralized
              technologies and how they can empower people to take control of
              their own data and assets.<br /><br />
              My passion for blockchain technology led me to start my personal
              blog, where I share my thoughts on the intersection of
            </span>
            <span class="text-cyan-200 font-bold">Web3</span>,
            <span class="text-rose-200 font-bold">Blockchain</span>, and
            <span class="text-orange-200 font-bold">AI</span>.
          </div>
          <div>
            <article
              class="animate-background 2xl:mt-10 rounded-xl bg-gradient-to-r mt-6 from-rose-200 via-purple-300 to-orange-500 bg-[length:400%_400%] p-[0.11rem] shadow-xl transition [animation-duration:_6s] hover:shadow-sm shadow-gray-700/25"
            >
              <div class="rounded-[10px] p-4 bg-gray-900 sm:p-4">
                <time
                  datetime="2022-10-10"
                  class="block text-xl text-orange-300 mb-2"
                >
                  Skills
                </time>
                <div
                  class="flex flex-row flex-wrap w-full 2xl:gap-x-1 2xl:gap-y-1 gap-y-0.5 gap-x-0.5"
                >
                  <div
                    class="flex flex-row items-center text-cyan-300 cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandEth :style="widthHeight" />Solidity
                  </div>
                  <div
                    class="flex flex-row items-center text-yellow-100 cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandJavascript :style="widthHeight" />Javascript
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandGit :style="widthHeight" />Git
                  </div>

                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandVite :style="widthHeight" />Vite
                  </div>
                  <div
                    class="flex flex-row items-center text-teal-300 cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandVue :style="widthHeight" />Vue.js
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandTailwind :style="widthHeight" />TailwindCSS
                  </div>

                  <div
                    class="flex flex-row items-center text-purple-300 cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandVscode :style="widthHeight" />Vscode
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandSvelte :style="widthHeight" />Svelte
                  </div>

                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandNodejs :style="widthHeight" />Nodejs
                  </div>
                  <div
                    class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                  >
                    <IconBrandNpm :style="widthHeight" />
                  </div>
                </div>
              </div>
            </article>
            <div class="flex flex-col gap-x-2 justify-center">
              <article
                class="animate-background 2xl:mt-5 rounded-xl bg-gradient-to-r mt-6 bg-[length:400%_400%] p-[0.11rem] shadow-xl transition [animation-duration:_6s] hover:shadow-sm shadow-gray-700/25 duration-500 hover:bg-gray-800 cursor-pointer w-full"
              >
                <div
                  class="rounded-[10px] p-4 bg-gray-900 sm:p-4 h-full border border-purple-500 border-opacity-10"
                >
                  <time
                    datetime="2022-10-10"
                    class="block text-xl text-purple-400 mb-2"
                  >
                    Projects
                  </time>
                  <div
                    class="flex flex-col flex-wrap w-fit md:gap-x-2 md:gap-y-2 gap-y-0.5 gap-x-0.5 text-sm"
                  >
                    <a
                      href="https://aivoice.perpettersen.no/"
                      target="_blank"
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >VoiceAIlity - Voice of ChatGPT3</span
                      >
                    </a>
                    <a
                      href="https://vuecryptoportfolio.netlify.app/"
                      target="_blank"
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >Crypto and Stock portfolio🔥</span
                      >
                    </a>

                    <a
                      href="https://www.pdpkrypto.no"
                      target="_blank"
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >PDPkrypto landing page🔥</span
                      >
                    </a>
                    <a
                      href="https://vue-walletconnect-web3.netlify.app/"
                      target="_blank"
                      class="flex flex-row items-center text-gray-200 cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >Web3 boilerplate, API</span
                      >
                    </a>
                    <a
                      href="https://ppcode.dev"
                      target="_blank"
                      class="flex flex-row items-center text-gray-200 cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >Open AI chat app</span
                      >
                    </a>
                    <a
                      href="https://jscheatsheet.netlify.app/"
                      target="_blank"
                      class="flex flex-row items-center text-gray-200 cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >JS cheatsheet</span
                      >
                    </a>
                    <a
                      href="https://aitextly.netlify.app/"
                      target="_blank"
                      class="flex flex-row items-center text-gray-200 cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >AI Tools App</span
                      >
                    </a>
                    <a
                      href="https://pokemonv1.netlify.app/"
                      target="_blank"
                      class="flex flex-row items-center text-gray-200 cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconApp :style="widthHeightSub" /><span class="ml-0.5"
                        >Pokemon V1 😎</span
                      >
                    </a>
                  </div>
                </div>
              </article>
              <article
                class="animate-background 2xl:mt-5 rounded-xl bg-gradient-to-r mt-6 bg-[length:400%_400%] p-[0.11rem] shadow-xl [animation-duration:_6s] hover:shadow-sm shadow-gray-700/25 transition-all duration-500 hover:bg-gray-800 cursor-pointer 2xl:w-full w-full mb-6"
              >
                <div
                  class="rounded-[10px] p-4 bg-gray-900 sm:p-4 border border-cyan-500 border-opacity-10"
                >
                  <time
                    datetime="2022-10-10"
                    class="block text-xl text-cyan-400 mb-2"
                  >
                    Blog - <span class="text-xs">Comming soon</span>
                  </time>
                  <div
                    class="flex flex-col flex-wrap w-fit md:gap-x-2 md:gap-y-2 gap-y-0.5 gap-x-0.5 text-sm"
                  >
                    <a
                      href="https://dev.to/web3per/the-revolutionary-technology-of-blockchain-and-web3-ckc"
                      target="_blank"
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconArticle :style="widthHeightSub" />
                      <span class="ml-0.5">Blockchain and Web3</span>
                    </a>
                    <a
                      href="https://dev.to/web3per/from-ethernet-to-ethereum-a-journey-through-the-evolution-of-internet-technology-part-1-243a"
                      target="_blank"
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in"
                    >
                      <IconArticle :style="widthHeightSub" />
                      <span class="ml-0.5"
                        >From Ethernet to Ethereum: Part 1</span
                      >
                    </a>

                    <div
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in text-red-300"
                    >
                      <IconArticle :style="widthHeightSub" />
                      <span class="ml-0.5">How to prompt - AI - comming</span>
                    </div>
                    <div
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in text-red-300"
                    >
                      <IconArticle :style="widthHeightSub" />
                      <span class="ml-0.5"
                        >Ethereum scaling solut. - comming</span
                      >
                    </div>
                    <div
                      class="flex flex-row items-center cursor-pointer hover:opacity-70 ease-in text-red-300"
                    >
                      <IconArticle :style="widthHeightSub" />
                      <span class="ml-0.5">Polkadot - tech - comming</span>
                    </div>
                  </div>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div></Transition
    >

    <Transition> <div></div></Transition>
    <!-- <div
      class="absolute 2xl:ml-[33.4%] m-[75.4%] 2xl:mt-[46rem] -bottom-44 2xl:w-[19%] 2xl:text-md text-xs sm:ml-[5%] text-orange-200 opacity-70"
    >
      <IconArrowRight v-bind:class="{ 'h-16 w-16': isLarge }" />
    </div>
    <div
      class="absolute 2xl:ml-[18.5%] m-[8.5%] 2xl:mt-[46rem]  2xl:w-[19%] 2xl:text-md text-xs sm:ml-[5%] text-purple-300 opacity-70"
    >
      <IconArrowLeft v-bind:class="{ 'h-16 w-16': isLarge }" />
    </div> -->
    <Transition>
      <article
        class="absolute right-1 top-0 2xl:mr-24 sm:mr-4 animate-background mt-1 mr-1 rounded-xl bg-gradient-to-r from-orange-600 via-teal-300 to-purple-500 bg-[length:400%_400%] p-[0.11rem] shadow-xl transition [animation-duration:_6s] hover:shadow-sm shadow-gray-700/25"
      >
        <div class="rounded-[10px] p-1 bg-gray-900 sm:p-1">
          <time datetime="2022-10-10" class="block text-xl text-purple-300">
          </time>
          <div class="flex flex-row flex-wrap w-full gap-y-0.5 gap-x-0.5">
            <a
              href="https://twitter.com/web3perp"
              target="_blank"
              class="flex flex-row items-center text-cyan-300 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
            >
              <IconBrandTwitter class="" :style="widthHeightLinks" />
            </a>
            <a
              href="https://github.com/kodevasse"
              target="_blank"
              class="flex flex-row items-center text-yellow-100 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
            >
              <IconBrandGithub class="" :style="widthHeightLinks" />
            </a>
            <a
              href="https://www.linkedin.com/in/per-pettersen-876435202/"
              target="_blank"
              class="flex flex-row items-center text-blue-300 cursor-pointer hover:opacity-70 transition-all duration-300 ease-in"
            >
              <IconBrandLinkedin class="" :style="widthHeightLinks" />
            </a>
          </div>
        </div>
      </article>
    </Transition>

    <!-- <div class="text-white">
      A normal text and a helper dropdown
      <div class="dropdown dropdown-end">
        <label tabindex="0" class="btn btn-circle btn-ghost btn-xs text-info">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            class="w-4 h-4 stroke-current"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
            ></path>
          </svg>
        </label>
        <div
          tabindex="0"
          class="card compact dropdown-content shadow bg-yellow-300 bg-opacity-70 rounded-box w-64"
        >
          <div class="card-body">
            <h2 class="card-title">You needed more info?</h2>
            <p>Here is a description!</p>
          </div>
        </div>
      </div>
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

@media (min-width: 1000px) {
  .my-element {
    margin-left: calc(10% - screenWidth.value * 1px);
  }
}
</style>
