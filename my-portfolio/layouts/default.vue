<template>
    <div>
      <Title>{{ title }}</Title>
      <div
        class="flex flex-row items-center justify-end bg-green-500 font-serif font-medium cursor-pointer text-xl mx-2 h-[60px] pr-[20px] w-auto"
      >
        For hiring me contact with WhatsApp +8801741930058
      </div>
      <nav>
        <ul
          class="flex flex-row items-center justify-between text-2xl font-semibold bg-blue-300 mx-2 pl-[150px] pr-[60px] p-4 h-[70px] w-auto cursor-pointer"
        >
          <li
            class="flex items-center justify-center text-red-700 text-center font-semibold font-serif rounded-full h-[68px] -ml-[130px] w-[120px]"
          >
            <NuxtLink to="/logo">Ramjan's World</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/home">Home</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/skills">Skills</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/projects">Projects</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/upwork">Upwork</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/fiver">Fiver</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/github">GitHub</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/linkedin">LinkedIn</NuxtLink>
          </li>
          <li
            class="text-violet-900 hover:text-blue-700 border-b-[3px] border-blue-300 hover:border-blue-500 transition duration-500"
          >
            <NuxtLink to="/profile">Profile</NuxtLink>
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
  