<script setup>
</script>

<template>
  <div class="min-h-screen bg-gray-200 p-4 md:p-8 flex justify-center items-center font-sans">

    <div class="grid grid-cols-1 md:grid-cols-4 md:grid-rows-3 gap-4 max-w-5xl w-full h-auto md:h-[650px]">

      <div class="bg-white p-8 rounded-3xl col-span-1 md:col-span-2 md:row-span-2 shadow-sm border border-gray-100 flex flex-col justify-center relative overflow-hidden group hover:shadow-md transition-shadow">
        <div class="z-10 relative">
          <h1 class="text-4xl md:text-5xl font-extrabold text-gray-800 mb-2 tracking-tight">Hi, I'm Dipo.</h1>
          <p class="text-xl text-gray-500 mb-6 font-medium">Software Engineer & Android Dev.</p>
          <p class="text-gray-600 leading-relaxed max-w-md">
            Membangun aplikasi fullstack dengan Python, Kotlin, dan Vue.js. Fokus pada kode yang bersih dan solusi yang efisien.
          </p>
        </div>
        <div class="absolute -right-12 -bottom-12 w-64 h-64 bg-orange-100 rounded-full opacity-50 group-hover:scale-110 transition-transform duration-700 ease-in-out"></div>
      </div>

      <a href="https://box.amalindipo.id/" target="_blank" class="bg-box-orange p-6 rounded-3xl col-span-1 md:col-span-2 md:row-span-1 shadow-md text-white relative overflow-hidden group cursor-pointer hover:brightness-110 transition-all">
        <div class="flex justify-between items-start z-10 relative h-full">
          <div class="flex flex-col justify-between h-full">
            <div>
              <span class="bg-white/20 px-3 py-1 rounded-full text-[10px] font-bold uppercase tracking-wider">Featured</span>
              <h2 class="text-3xl font-bold mt-2">BOX Inventory</h2>
            </div>
            <p class="text-orange-100 text-sm mt-2 opacity-90">Sistem manajemen barang berbasis Mobile & Web.</p>
          </div>
          <div class="text-5xl group-hover:rotate-12 transition-transform duration-300">📦</div>
        </div>
      </a>

      <a href="https://github.com/dipoengoro" target="_blank" class="bg-github p-6 rounded-3xl col-span-1 md:col-span-1 md:row-span-1 shadow-sm flex flex-col justify-between text-white hover:bg-black transition-colors group">
        <div class="text-4xl group-hover:-translate-y-1 transition-transform">🐙</div>
        <div>
          <h3 class="font-bold text-lg">GitHub</h3>
          <p class="text-gray-400 text-xs">Check my code</p>
        </div>
      </a>

      <a href="https://www.linkedin.com/in/muhdiponegoro" target="_blank" class="bg-linkedin p-6 rounded-3xl col-span-1 md:col-span-1 md:row-span-1 shadow-sm flex flex-col justify-between text-white hover:opacity-90 transition-opacity group">
        <div class="text-4xl group-hover:-translate-y-1 transition-transform">💼</div>
        <div>
          <h3 class="font-bold text-lg">LinkedIn</h3>
          <p class="text-blue-100 text-xs">Professional Profile</p>
        </div>
      </a>

      <div class="bg-white p-6 rounded-3xl col-span-1 md:col-span-2 md:row-span-1 shadow-sm border border-gray-100 flex flex-col justify-center">
        <h3 class="text-gray-400 font-bold text-xs uppercase mb-4 tracking-wider">Tech Arsenal</h3>
        <div class="flex flex-wrap gap-4 text-2xl grayscale hover:grayscale-0 transition-all duration-500">
          <span title="Python">🐍</span>
          <span title="Vue.js">🟢</span>
          <span title="Kotlin">🤖</span>
          <span title="Docker">🐳</span>
          <span title="PostgreSQL">🐘</span>
          <span title="FastAPI">⚡</span>
        </div>
      </div>

      <div class="bg-emerald-500 p-6 rounded-3xl col-span-1 md:col-span-2 md:row-span-1 shadow-sm flex items-center justify-between text-white overflow-hidden relative group">
        <div class="z-10">
          <h3 class="text-2xl font-bold">Available for Hire</h3>
          <p class="text-emerald-100 text-sm">Let's build something useful.</p>
        </div>
        <div class="text-8xl absolute -right-6 -bottom-10 opacity-20 rotate-12 group-hover:rotate-0 transition-transform duration-500">🌏</div>
      </div>

    </div>
  </div>
</template>

<style>
/* Pastikan body margin 0 biar full screen */
body { margin: 0; background-color: #f9fafb; }
</style>