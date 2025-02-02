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

          <a href="https://github.com/mahraibFatima/"><span
            class="flex max-w-fit p-2 rounded-md text-2xl items-center space-x-2 bg-white/20 hover:bg-white/40 cursor-pointer"><svg
              xmlns="http://www.w3.org/2000/svg" width="28" viewBox="0 0 24 24">
              <path fill="currentColor"
                d="M12 2A10 10 0 0 0 2 12c0 4.42 2.87 8.17 6.84 9.5c.5.08.66-.23.66-.5v-1.69c-2.77.6-3.36-1.34-3.36-1.34c-.46-1.16-1.11-1.47-1.11-1.47c-.91-.62.07-.6.07-.6c1 .07 1.53 1.03 1.53 1.03c.87 1.52 2.34 1.07 2.91.83c.09-.65.35-1.09.63-1.34c-2.22-.25-4.55-1.11-4.55-4.92c0-1.11.38-2 1.03-2.71c-.1-.25-.45-1.29.1-2.64c0 0 .84-.27 2.75 1.02c.79-.22 1.65-.33 2.5-.33s1.71.11 2.5.33c1.91-1.29 2.75-1.02 2.75-1.02c.55 1.35.2 2.39.1 2.64c.65.71 1.03 1.6 1.03 2.71c0 3.82-2.34 4.66-4.57 4.91c.36.31.69.92.69 1.85V21c0 .27.16.59.67.5C19.14 20.16 22 16.42 22 12A10 10 0 0 0 12 2" />
            </svg>
            <p>GitHub</p>
          </span></a>

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

    <div class="w-full h-screen  bg-[#e7ffeb50] justify-center px-20 flex mx-auto  z-[999] text-left relative flex-col">

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


        <span class="bg-white/30 rounded-xl max-w-fit p-3 hover:bg-white/40 py-2"><a
            href="https://github.com/MahraibFatima/Resume" target="_blank">

            <svg xmlns="http://www.w3.org/2000/svg" width="30" class="inline" viewBox="0 0 24 24">
              <path fill="none" stroke="#ca3939" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M3 12h18m-9-9v18m5-14L7 17M7 7l10 10" />
            </svg>

            resume</a></span>
      </div>

    </div>


    <div
      class="w-full h-screen geist bg-[#e7f1ff50] justify-center gap-4 px-20 flex text-[22px] mx-auto z-[999] text-left relative flex-col leading-loose pt-4">

      
      <NuxtImg src="img/flower.png" class="bg-flower -z-10 bottom-0 absolute right-20" width="300" />

      <span class="text-5xl fraunces">About myself</span>

      <span>I’m just a girl with a strong grip on <span
        class="bg-white/30 rounded-xl px-2 py-1 hover:bg-white/40 cursor-help">Python, C#, C/C++, SQLite3,</span> and tools like <span
        class="bg-white/30 rounded-xl px-2 py-1 hover:bg-white/40 cursor-help">TensorFlow, PyTorch, Numpy, Pandas, and Scikit-learn.</span> I’m passionate about Machine Learning and Data Structures, and I’ve cracked 200+ problems on <span
        class="bg-white/30 rounded-xl px-2 py-1 hover:bg-white/40 cursor-help">Leetcode and CodeForces.</span> I’ve also contributed to 10+ repositories in <span
        class="bg-white/30 rounded-xl px-2 py-1 hover:bg-white/40 cursor-help">GSSOC’24 and GSSOC Extd’24,</span> always diving into collaborative coding. Always learning, always growing — let’s connect and build something incredible together!</span>

        <div class="flex space-x-3"><span class="bg-white/30 rounded-xl max-w-fit p-2.5 hover:bg-white/40 py-1 mb-20"><a
            href="mailto:mahraibfatima5@gmail.com" target="_blank">

            <svg xmlns="http://www.w3.org/2000/svg" width="28" viewBox="0 0 24 24" class="inline"><path fill="#c93637" d="M13.35 20.13c-.76.69-1.93.69-2.69-.01l-.11-.1C5.3 15.27 1.87 12.16 2 8.28c.06-1.7.93-3.33 2.34-4.29c2.64-1.8 5.9-.96 7.66 1.1c1.76-2.06 5.02-2.91 7.66-1.1c1.41.96 2.28 2.59 2.34 4.29c.14 3.88-3.3 6.99-8.55 11.76z"/></svg>

            Send email</a></span>


            <span class="bg-white/30 rounded-xl  max-w-fit p-2.5 hover:bg-white/40 py-1 mb-20"><a
            href="mailto:mahraibfatima5@gmail.com" target="_blank" class="flex items-center space-x-2">

            <svg xmlns="http://www.w3.org/2000/svg" width="26" class="inline" viewBox="0 0 64 64"><path fill="#0a66c2" d="M58.5 1H5.6C3.1 1 1.1 3 1.1 5.5v53c0 2.4 2 4.5 4.5 4.5h52.7c2.5 0 4.5-2 4.5-4.5V5.4C63 3 61 1 58.5 1M19.4 53.7h-9.1V24.2h9.1zm-4.6-33.6c-3 0-5.3-2.4-5.3-5.3s2.4-5.3 5.3-5.3s5.3 2.4 5.3 5.3s-2.2 5.3-5.3 5.3m39.1 33.6h-9.1V39.4c0-3.4-.1-7.9-4.8-7.9c-4.8 0-5.5 3.8-5.5 7.6v14.6h-9.1V24.2h8.9v4.1h.1c1.3-2.4 4.2-4.8 8.7-4.8c9.3 0 11 6 11 14.2v16z"/></svg>

            <span>LinkedIn</span></a></span>
          
          
            <span class="bg-white/30 rounded-xl  max-w-fit p-2.5 hover:bg-white/40 py-1 mb-20"><a
            href="https://www.kaggle.com/code/mahraibfatima" target="_blank" class="flex items-center space-x-2">

            <svg xmlns="http://www.w3.org/2000/svg" width="26" viewBox="0 0 32 32"><path fill="#20a0ff" d="M25.099 31.812c-.025.12-.156.188-.375.188h-4.183q-.374 0-.656-.328l-6.907-8.787l-1.932 1.828v6.817c0 .313-.151.469-.463.469H7.338q-.468 0-.469-.469V.469c0-.308.157-.469.469-.469h3.245c.312 0 .463.161.463.469v19.124l8.271-8.359c.224-.224.443-.328.661-.328h4.319q.287-.002.38.239q.094.3-.047.417l-8.74 8.459l9.115 11.343c.125.141.156.276.093.48z"/></svg>

            <span>Kaggle</span></a></span>
          
          </div>

      <div class="py-6 text-[20px] decoration-wavy underline-offset-4 geist flex flex-col gap-3 absolute bottom-0">


        <span class="font-medium">Handmade by <u class="decoration-wavy underline-offset-4"><a href="https://github.com/imrofayel">Novar Zaruq</a></u> /  for Mahraib Fatima.</span>

      </div>

    </div>

  </div>
</template>

<script lang="ts" setup>

</script>

<style></style>