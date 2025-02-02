<template>
  <div class="flex flex-col w-full h-full justify-center items-center">

    <div class="h-screen w-full flex items-center justify-center flex-col relative">
      <h1 class="opacity-90">Mahraib Fatima</h1>

      <NuxtImg src="img/flowers2.webp" class="blur-[1px] bg-flower -z-10 absolute" width="400" height="400" />
    </div>

    <div class="w-full h-screen bg-[#f0e7ff43] items-center justify-center flex mx-auto  z-[999] text-center relative">

      <NuxtImg src="img/butterfly.png" class="bg-flower -z-10 absolute top-0 right-0" width="300" />

      <div class="text-[#000000] w-3/4 text-3xl text-left leading-[2.7rem] geist">
        <p class="drop-shadow-sm">I'm a dedicated technologist with a deep fascination for Machine Learning and AI
          innovation.
          My passion drives me to explore
          the frontiers of MLOps and Reinforcement Learning, turning complex challenges into elegant
          solutions.</p>

        <span class="flex gap-3 py-4">

          <span
            class="flex max-w-fit p-2 rounded-md text-2xl items-center space-x-2 bg-white/20 hover:bg-white/40 cursor-pointer"><svg
              xmlns="http://www.w3.org/2000/svg" width="28" viewBox="0 0 24 24">
              <path fill="currentColor"
                d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5c.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34c-.46-1.16-1.11-1.47-1.11-1.47c-.91-.62.07-.6.07-.6c1 .07 1.53 1.03 1.53 1.03c.87 1.52 2.34 1.07 2.91.83c.09-.65.35-1.09.63-1.34c-2.22-.25-4.55-1.11-4.55-4.92c0-1.11.38-2 1.03-2.71c-.1-.25-.45-1.29.1-2.64c0 0 .84-.27 2.75 1.02c.79-.22 1.65-.33 2.5-.33s1.71.11 2.5.33c1.91-1.29 2.75-1.02 2.75-1.02c.55 1.35.2 2.39.1 2.64c.65.71 1.03 1.6 1.03 2.71c0 3.82-2.34 4.66-4.57 4.91c.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2" />
            </svg>
            <p>GitHub</p>
          </span>

          <span
            class="flex max-w-fit p-2 rounded-md text-2xl items-center space-x-2 bg-white/20 hover:bg-white/40 cursor-pointer"><svg
              xmlns="http://www.w3.org/2000/svg" width="28" viewBox="0 0 24 24">
              <path fill="#0085ff"
                d="M12 11.388c-.906-1.761-3.372-5.044-5.665-6.662c-2.197-1.55-3.034-1.283-3.583-1.033C2.116 3.978 2 4.955 2 5.528c0 .575.315 4.709.52 5.4c.68 2.28 3.094 3.05 5.32 2.803c-3.26.483-6.157 1.67-2.36 5.898c4.178 4.325 5.726-.927 6.52-3.59c.794 2.663 1.708 7.726 6.444 3.59c3.556-3.59.977-5.415-2.283-5.898c2.225.247 4.64-.523 5.319-2.803c.205-.69.52-4.825.52-5.399c0-.575-.116-1.55-.752-1.838c-.549-.248-1.386-.517-3.583 1.033c-2.293 1.621-4.76 4.904-5.665 6.664" />
            </svg>
            <p>Bluesky</p>
          </span>
        </span>

      </div>

      <NuxtImg src="img/flower.png" class="bg-flower -z-10 absolute bottom-0" width="300" />
    </div>

    <div class="w-full h-screen  bg-[#e7f4ff43] justify-center px-20 flex mx-auto  z-[999] text-left relative flex-col">

      <NuxtImg src="img/butterflies.png" class="bg-flower right-8 -z-10 absolute top-0" width="400" />

      <span class="text-5xl fraunces">Projects</span>

      <div class="py-6 text-[22px] underline-offset-4 geist flex flex-col gap-3">
        <span>1. <u class="decoration-wavy">Jarvis</u>: an program to perform various tasks based on voice commands.

          <span class="flex py-4 space-x-2 text-lg"><span
              class="bg-white/20 rounded-full p-3 py-1 hover:bg-white/40 cursor-help">python, speech recognition,
              pyttsx3, OpenCV, wikipedia, os, sys, webbrowser</span>

            <span class="bg-white/20 rounded-full p-3 hover:bg-white/40 py-1"><a
                href="https://github.com/mahraibFatima/Jarvis" target="_blank">GitHub</a></span></span>
        </span>


        <span>2. <u class="decoration-wavy">Spotify Playlist Downloader</u>: CLI app that will download playlist by just
          providing it's URL.

          <span class="flex py-4 space-x-2 text-lg"><span
              class="bg-white/20 rounded-full p-3 py-1 hover:bg-white/40 cursor-help">python, Spotify Web API,
              YouTube-dl, pandas, ffmpeg, Git</span>

            <span class="bg-white/20 rounded-full p-3 hover:bg-white/40 py-1"><a
                href="https://github.com/MahraibFatima/spotifyPlaylistDownloader"
                target="_blank">GitHub</a></span></span>
        </span>


        <span>3. <u class="decoration-wavy">Rudder</u>: Wine Prediction end to end ML model

          <span class="flex py-4 space-x-2 text-lg"><span
              class="bg-white/20 rounded-full p-3 py-1 hover:bg-white/40 cursor-help">CI/CD pipeline, model predictions,
              deployment</span>

            <span class="bg-white/20 rounded-full p-3 hover:bg-white/40 py-1"><a
                href="https://github.com/MahraibFatima/rudder" target="_blank">GitHub</a></span></span>
        </span>
      </div>

    </div>

  </div>
</template>

<script lang="ts" setup>


</script>

<style></style>