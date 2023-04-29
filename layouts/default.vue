<template>
  <div class="wrapper grid grid-cols-[400px_1fr] bg-slate-300 min-h-screen p-20">
    <aside class="p-20 bg-slate-200">
        <Nav />
    </aside>
    <main class="p-20 bg-slate-100">
        <slot />
    </main>
  </div>
</template>
