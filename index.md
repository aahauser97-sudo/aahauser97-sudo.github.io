---
layout: default
---

<section id="hero" class="relative min-h-screen flex items-center justify-center px-6 text-center overflow-hidden">
    <div class="hero-visual-bg">
        <div class="blob blob-1"></div>
        <div class="blob blob-2"></div>
        <div class="blob blob-3"></div>
    </div>
    <div class="max-w-5xl mx-auto relative z-10">
        <span class="inline-block px-4 py-2 mb-8 text-[11px] font-black tracking-[0.3em] uppercase bg-gradient-to-r from-indigo-600 to-rose-500 text-white rounded-full shadow-lg">New Release 2024</span>
        <h1 class="text-6xl md:text-[9rem] font-extrabold tracking-tighter leading-[0.85] mb-8 text-gradient-vibrant">
            Amanda <br> Lynn.
        </h1>
        <p class="text-xl md:text-3xl text-gray-600 max-w-3xl mx-auto mb-14 font-medium leading-tight">
            Experience the future of narrative. The official home of <span class="text-indigo-600 font-bold">Amanda Lynn</span>.
        </p>
        <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
            <button onclick="document.getElementById('books').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-black text-white px-12 py-5 rounded-full font-bold hover:scale-105 transition-all shadow-2xl">The Collection</button>
            <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-white/40 border border-black/10 backdrop-blur-md px-12 py-5 rounded-full font-bold hover:bg-white transition-all shadow-lg">The Author</button>
        </div>
    </div>
</section>

<section id="books" class="max-w-6xl mx-auto py-32 px-6">
    <div class="grid md:grid-cols-2 gap-16 mb-40">
        <div class="sticky top-24 self-start">
            <img src="{{ '/images/knowing-cover.png' | relative_url }}" class="rounded-[40px] shadow-2xl w-full">
        </div>
        <div class="flex flex-col justify-center">
            <h1 class="text-6xl font-extrabold mb-4 tracking-tighter">The Knowing</h1>
            <p class="text-indigo-600 mb-8 font-bold uppercase tracking-[0.2em] text-sm">Published 2024</p>
            <p class="text-xl text-gray-600 leading-relaxed mb-12 font-medium">In a future where secrets are harvested like grain...</p>
            <div class="world-node">
                <h3 class="font-bold text-2xl mb-3 tracking-tight text-indigo-600">The Archive</h3>
                <p class="text-gray-500 text-lg">Every citizen's "Knowing" is stored and indexed.</p>
            </div>
        </div>
    </div>
</section>
