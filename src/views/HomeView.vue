<template>
  <div id="home" class="flex flex-col-reverse md:flex-row md:space-x-6">
    <card-container class="backdrop-blur-md relative p-8 flex-grow tracking-tight">
      <img src="../assets/logo_3d_bgm.png" class="object-cover absolute  -z-20 top-0 bottom-0 left-0 right-0 h-full w-full blur-2xl bg-gray-200">
      <div class="text-4xl font-semibold mr-5 mix-blend-overlay">
        Hi, I'm Lucas. I've been designing user experiences for over 5 years.
      </div>
      <div class="text-lg text-gray-700 my-10">
        I am passionate about what I do and use my energy to develop user-first, beautiful and appealing experiences.
      </div>
      <div class="flex space-y-4 sm:space-y-0 sm:space-x-4 flex-col sm:flex-row">
        <a class="transition-all text-center bg-black bg-opacity-90 text-white p-3 rounded-xl shadow hover:bg-opacity-80 hover:mix-blend-multiply cursor-pointer grow-0 font-semibold">
            Get in touch
        </a>
        <div class="flex items-center justify-center sm:justify-start space-x-4">
          <a href="https://dribbble.com/flexusma" target="_blank" class="transition-all duration-500 bg-white p-2 rounded-xl shadow hover:bg-pink-600 hover:text-white cursor-pointer grow-0 flex items-center justify-center w-12 h-12">
            <i class="mdi mdi-basketball text-2xl"></i>
          </a>
          <a href="https://discord.gg/Tkn3asxZyp" target="_blank" class="transition-all duration-500 bg-white p-2 rounded-xl shadow hover:bg-blue-600 hover:text-white cursor-pointer grow-0 flex items-center justify-center w-12 h-12">
            <i class="mdi mdi-forum text-2xl"></i>
          </a>
          <a href="mailto:info@flexusma.de" target="_blank" class="transition-all duration-500 bg-white p-2 rounded-xl shadow hover:bg-emerald-600 hover:text-white cursor-pointer grow-0 flex items-center justify-center w-12 h-12">
            <i class="mdi mdi-at text-2xl"></i>
          </a>
        </div>
      </div>
    </card-container>
    <div class="max-h-48 md:max-h-full my-12 md:my-0">
      <img src="../assets/logo.png" class="object-cover h-full w-full md:bg-gray-50 md:rounded-2xl -my-24 md:my-0">
    </div>
  </div>

  <div id="projects" class="flex flex-col md:flex-row my-6">
    <card-container class="backdrop-blur-md relative flex-grow tracking-tight bg-blue-500 text-white my-3 md:my-0 md:mr-3 hover:-mt-1 hover:-ml-1 hover:mb-7 md:hover:mb-1 hover:mr-1">
      <div class="text-4xl font-semibold mr-5 mix-blend-hard-light m-8 mb-0">
        akazia dashboard
      </div>
      <div class="text-lg text-gray-200 m-8 mt-0">
        Billing panel dashboard
      </div>
      <div class="flex">
        <img src="../assets/akazia-dashboard.png" class="-z-20 object-cover object-left-top mt-4 ml-8 bottom-0 top-0 right-0 h-full min-w-full bg-gray-200 rounded-tl-lg">
      </div>
    </card-container>
    <card-container class="backdrop-blur-md relative flex-grow tracking-tight bg-blue-300 my-3 md:my-0 md:ml-3 hover:-mt-1 hover:-mr-1 hover:mb-7 md:hover:mb-1 hover:ml-1">
      <div class="text-4xl text-gray-800 font-semibold mr-5 mix-blend-hard-light m-8 mb-0">
        akazia admin
      </div>
      <div class="text-lg text-gray-700 m-8 mt-0">
        Billing panel administration
      </div>
      <div class="flex">
        <img src="../assets/akazia-users.png" class="-z-20 object-cover object-left-top mt-4 ml-8 bottom-0 top-0 right-0 h-full min-w-full bg-gray-200 rounded-tl-lg">
      </div>
    </card-container>
  </div>

  <div id="projects2" class="flex flex-col md:flex-row md:my-6">
    <card-container class="backdrop-blur-md relative flex-grow tracking-tight bg-blue-900 text-white my-3 md:my-0 md:mr-3 hover:-mt-1 hover:-ml-1 hover:mb-7 md:hover:mb-1 hover:mr-1">
      <div class="text-4xl font-semibold mr-5 mix-blend-hard-light m-8 mb-0">
        akazia admin
      </div>
      <div class="text-lg text-gray-200 m-8 mt-0">
        Billing panel administration - dark mode
      </div>
      <div class="flex">
        <img src="../assets/akazia-users-dark.png" class="-z-20 object-cover object-left-top mt-4 ml-8 bottom-0 top-0 right-0 h-full min-w-full bg-gray-200 rounded-tl-lg">
      </div>
    </card-container>
    <card-container class="backdrop-blur-md relative flex-grow tracking-tight bg-gray-300 my-3 md:my-0 md:ml-3 hover:-mt-1 hover:-mr-1 hover:mb-7 md:hover:mb-1 hover:ml-1">
      <div class="text-4xl text-gray-800 font-semibold mr-5 mix-blend-hard-light m-8 mb-0 ">
        vshop landing
      </div>
      <div class="text-lg text-gray-700 m-8 mt-0">
        Landing page for vshop - a webshop provider
      </div>
      <div class="flex">
        <img src="../assets/vshop-landing.png" class="-z-20 object-cover object-left-top mt-4 ml-8 bottom-0 top-0 right-0 h-full min-w-full bg-gray-200 rounded-tl-lg">
      </div>
    </card-container>
  </div>

  <div id="projects3" class="flex flex-col md:flex-row my-6">
    <card-container class="backdrop-blur-md relative flex-grow tracking-tight bg-gray-100 my-3 md:my-0 md:mr-3 hover:-mt-1 hover:-ml-1 hover:mb-7 md:hover:mb-1 hover:mr-1">
      <div class="text-4xl text-gray-800 font-semibold mr-5 mix-blend-hard-light m-8 mb-0">
        vshop dashboard
      </div>
      <div class="text-lg text-gray-700 m-8 mt-0">
        User dashboard for vshop
      </div>
      <div class="flex">
      <img src="../assets/vshop.png" class="-z-20 object-cover object-left-top mt-4 ml-8 bottom-0 top-0 right-0 h-full min-w-full bg-gray-200 rounded-tl-lg">
      </div>
    </card-container>
    <card-container class="backdrop-blur-md relative flex-grow tracking-tight bg-gray-800 text-white my-3 md:my-0 md:ml-3 hover:-mt-1 hover:-mr-1 hover:mb-7 md:hover:mb-1 hover:ml-1">
      <div class="text-4xl font-semibold mr-5 mix-blend-hard-light m-8 mb-0">
        vshop dashboard
      </div>
      <div class="text-lg text-gray-200 m-8 mt-0">
        User dashboard for vshop - dark mode
      </div>
      <div class="flex">
        <img src="../assets/vshop-dark.png" class="-z-20 object-cover object-left-top mt-4 ml-8 bottom-0 top-0 right-0 h-full min-w-full bg-gray-200 rounded-tl-lg">
      </div>
    </card-container>
  </div>

  <card-container id="contact" class="backdrop-blur-md relative p-8 flex-grow tracking-tight my-6">
    <img src="../assets/logo_3d_bgm.png" class="object-cover absolute  -z-20 top-0 bottom-0 left-0 right-0 h-full w-full blur-2xl bg-gray-200">
    <div class="text-4xl font-semibold mr-5 mix-blend-overlay">
      Let's talk!
    </div>
    <div class="text-lg text-gray-700 my-10">
      <div>Whether it's just to say hi or discuss an idea, I'm happy to talk.</div>
      <div>Feel free to message me on Matrix <span class="font-mono rounded-lg bg-white bg-opacity-10 backdrop-hue-rotate-15 text-black px-1.5 py-0.5">@flexusma:im.m4fx.de</span></div>
    </div>
    <div class="flex space-y-4 sm:space-y-0 sm:space-x-4 flex-col sm:flex-row">
      <div class="flex items-center justify-center sm:justify-start space-x-4">
        <a href="https://dribbble.com/flexusma" target="_blank" class="transition-all duration-500 bg-white p-2 rounded-xl shadow hover:bg-pink-600 hover:text-white cursor-pointer grow-0 flex items-center justify-center w-12 h-12">
          <i class="mdi mdi-basketball text-2xl"></i>
        </a>
        <a href="https://discord.gg/Tkn3asxZyp" target="_blank" class="transition-all duration-500 bg-white p-2 rounded-xl shadow hover:bg-blue-600 hover:text-white cursor-pointer grow-0 flex items-center justify-center w-12 h-12">
          <i class="mdi mdi-forum text-2xl"></i>
        </a>
        <a href="mailto:info@flexusma.de" target="_blank" class="transition-all duration-500 bg-white p-2 rounded-xl shadow hover:bg-emerald-600 hover:text-white cursor-pointer grow-0 flex items-center justify-center w-12 h-12">
          <i class="mdi mdi-at text-2xl"></i>
        </a>
      </div>
    </div>
  </card-container>

</template>

<script>
// @ is an alias to /src

import CardContainer from "@/components/Card";
export default {
  name: 'HomeView',
  components: {
    CardContainer
  }
}
</script>
