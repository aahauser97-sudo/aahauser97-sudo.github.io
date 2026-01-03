---
layout: default
---

<!-- VIBRANT HERO SECTION -->
<section id="hero" class="relative min-h-screen flex items-center justify-center px-6 text-center overflow-hidden">
    <div class="hero-visual-bg">
        <div class="blob blob-1"></div>
        <div class="blob blob-2"></div>
        <div class="blob blob-3"></div>
    </div>
    
    <div class="max-w-5xl mx-auto relative z-10">
        <span class="inline-block px-4 py-2 mb-8 text-[11px] font-black tracking-[0.3em] uppercase bg-gradient-to-r from-indigo-600 to-rose-500 text-white rounded-full shadow-lg">New Release 2024</span>
        <h1 class="text-6xl md:text-[9rem] font-extrabold tracking-tighter mb-8 block">
            <span class="text-gradient-vibrant">Amanda</span> <br> 
            <span class="text-gradient-vibrant">Lynn.</span>
        </h1>
        <p class="text-lg md:text-3xl text-gray-600 max-w-3xl mx-auto mb-14 font-medium leading-tight">
            Experience the future of narrative. The official home of <span class="text-indigo-600 font-bold">Amanda Lynn</span>.
        </p>
        <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
            <button onclick="document.getElementById('books').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-black text-white px-12 py-5 rounded-full font-bold hover:scale-105 transition-all shadow-2xl shadow-indigo-500/20">The Collection</button>
            <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-white/40 border border-black/10 backdrop-blur-md text-black px-12 py-5 rounded-full font-bold hover:bg-white transition-all shadow-lg">The Author</button>
        </div>
    </div>
</section>

<!-- BOOKS SECTION -->
<section id="books" class="max-w-6xl mx-auto py-32 px-6">
    <div class="mb-20 text-center">
        <p class="text-indigo-600 font-bold text-sm mb-2 uppercase tracking-[0.2em]">Exhibition</p>
        <h2 class="text-5xl font-bold tracking-tight">The Collection.</h2>
    </div>
    
    <!-- Book 1: The Knowing -->
    <div class="grid md:grid-cols-2 gap-16 mb-48">
        <div class="sticky-container md:sticky md:top-24 self-start">
            <div class="book-image-container">
                <img src="{{ '/images/knowing-cover.png' | relative_url }}" class="rounded-[40px] shadow-2xl w-full transition-transform duration-700 hover:scale-[1.02]">
            </div>
        </div>
        <div class="flex flex-col justify-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 tracking-tighter text-gray-900">The Knowing</h1>
            <p class="text-indigo-600 mb-8 font-bold uppercase tracking-[0.2em] text-sm">Published 2024</p>
            <p class="text-xl text-gray-600 leading-relaxed mb-12 font-medium">
                In a future where secrets are harvested like grain, one girl discovers a truth that could burn the fields to the ground. 
            </p>
            <div class="world-node">
                <h3 class="font-bold text-2xl mb-3 tracking-tight text-indigo-600">The Archive</h3>
                <p class="text-gray-500 text-lg leading-relaxed">A centralized database where every citizen's "Knowing" is stored and indexed, forming the backbone of social order.</p>
            </div>
        </div>
    </div>

    <!-- Book 2: Beyond the Wall -->
    <div class="grid md:grid-cols-2 gap-16 mb-40">
        <div class="sticky-container md:sticky md:top-24 self-start">
            <div class="book-image-container">
                <img src="{{ '/images/beyond-the-wall.png' | relative_url }}" class="rounded-[40px] shadow-2xl w-full transition-transform duration-700 hover:scale-[1.02]">
            </div>
        </div>
        <div class="flex flex-col justify-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-4 tracking-tighter text-gray-900">Beyond the Wall</h1>
            <p class="text-rose-600 mb-8 font-bold uppercase tracking-[0.2em] text-sm">Coming Fall 2026</p>
            <p class="text-xl text-gray-600 leading-relaxed mb-12 font-medium">
                The wall was built to keep things out. But Sarah realized too late that it was actually built to keep them in.
            </p>
            <div class="world-node">
                <h3 class="font-bold text-2xl mb-3 tracking-tight text-rose-600">The Perimeter</h3>
                <p class="text-gray-500 text-lg leading-relaxed">A high-tech isolation barrier that hides the reality of the wasteland from the last city on Earth.</p>
            </div>
        </div>
    </div>
</section>

<!-- ABOUT SECTION -->
<section id="about" class="py-40 px-6 bg-[#fbfbfd]">
    <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center gap-12 md:gap-20">
        <div class="relative group">
            <div class="absolute -inset-4 bg-gradient-to-tr from-indigo-500 to-rose-500 rounded-full blur opacity-20 transition-all duration-500 group-hover:opacity-40"></div>
            <div class="relative w-64 h-64 md:w-96 md:h-96 rounded-full overflow-hidden shadow-2xl flex items-center justify-center bg-gray-100">
                <!-- Added site.time to force refresh of the image -->
                <img src="{{ '/images/headshot.png' | relative_url }}?v={{ site.time | date: '%s' }}" 
                     alt="Amanda Lynn"
                     class="w-full h-full object-cover transition-transform duration-700 hover:scale-110"
                     onerror="this.src='https://ui-avatars.com/api/?name=Amanda+Lynn&size=512'">
            </div>
        </div>
        <div class="max-w-xl text-center md:text-left">
            <h2 class="text-4xl md:text-5xl font-bold mb-8 tracking-tight">The Visionary.</h2>
            <p class="text-lg md:text-xl text-gray-600 leading-relaxed mb-8 font-medium">
                Amanda Lynn is a critically acclaimed novelist whose work explores the thin line between reality and perception through immersive storytelling.
            </p>
            <p class="text-lg md:text-xl text-gray-600 leading-relaxed font-medium">
                Based in the Pacific Northwest, she constructs worlds that challenge the boundaries of identity and memory.
            </p>
        </div>
    </div>
</section>
