<template>
    <div>
      <Title>{{ title }}</Title>
      <div class="flex flex-row items-center justify-end bg-green-500 mx-2">
        <div>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6 stroke-blue-900">
             <path fill-rule="evenodd" 
             d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z" clip-rule="evenodd" />
           </svg>
        </div>
        <div
        class="flex items-center font-serif font-medium cursor-pointer text-xl mx-2 h-[60px] pr-[20px] w-auto"
      >
        For hiring me contact with WhatsApp +8801741930058
      </div>
      </div>
      
      <nav>
        <ul
          class="flex flex-row items-center justify-between font-semibold bg-blue-300 mx-2 pl-[150px] text-2xl pr-[60px] p-4 h-[70px] w-auto cursor-pointer"
        >
          <li
            class="flex items-center justify-center text-red-700 text-center font-semibold font-serif rounded-full h-[68px] -ml-[130px] w-[120px]"
          >
            <NuxtLink to="/logo">Ramjan's World</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-700"
          >
            <NuxtLink to="/home">Home</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-700"
          >
            <NuxtLink to="/skills">Skills</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-700"
          >
            <NuxtLink to="/projects">Projects</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-2000"
          >
            <NuxtLink to="/upwork">Upwork</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-700"
          >
            <NuxtLink to="/fiver">Fiverr</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-700"
          >
            <NuxtLink to="/github">GitHub</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 duration-700"
          >
            <NuxtLink to="/linkedin">LinkedIn</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700" 
          >
            <NuxtLink to="/profile">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-[50px] h-[30px] stroke-stroke-blue-700">
                  <path fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 119 0 4.5 4.5 0 01-9 0zM3.751 20.105a8.25 8.25 0 0116.498 0 .75.75 0 01-.437.695A18.683 18.683 0 0112 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 01-.437-.695z" clip-rule="evenodd" />
                </svg>
            </NuxtLink>
          </li>
        </ul>
        <slot />
      </nav>
    </div>
  </template>
  
  <script setup>
  const title = useState("title", () => "Ramjans World");
  </script>
  
  <style>
  .router-link-active {
    font-weight: bold;
  }
  </style>
  html {
    -webkit-text-size-adjust: 100%;
}