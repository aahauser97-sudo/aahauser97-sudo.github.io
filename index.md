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
        <span class="inline-block px-4 py-2 mb-8 text-[11px] font-black tracking-[0.3em] uppercase bg-gradient-to-r from-indigo-600 to-rose-500 text-white rounded-full shadow-lg">Looking for an Agent</span>
        <h1 class="text-6xl md:text-[9rem] font-extrabold tracking-tighter mb-8 block">
            <span class="text-gradient-vibrant">Amanda</span> <br> 
            <span class="text-gradient-vibrant">Lynn</span>
        </h1>
        <p class="text-lg md:text-3xl text-gray-600 max-w-3xl mx-auto mb-14 font-medium leading-tight">
            The official place to learn about the ongoing works of <span class="text-indigo-600 font-bold">Amanda Lynn</span>.
        </p>
        <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
            <button onclick="document.getElementById('books').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-black text-white px-12 py-5 rounded-full font-bold hover:scale-105 transition-all shadow-2xl shadow-indigo-500/20">Works in Progress</button>
            <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-white/40 border border-black/10 backdrop-blur-md text-black px-12 py-5 rounded-full font-bold hover:bg-white transition-all shadow-lg">The Author</button>
        </div>
    </div>
</section>

<!-- BOOKS SECTION -->
<section id="books" class="max-w-6xl mx-auto py-32 px-6">
    <div class="mb-20 text-center">
        <p class="text-indigo-600 font-bold text-sm mb-2 uppercase tracking-[0.2em]">Exhibition</p>
        <h2 class="text-5xl font-bold tracking-tight">Works in Progress.</h2>
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
            <p class="text-indigo-600 mb-8 font-bold uppercase tracking-[0.2em] text-sm">Completed Draft 2025</p>
            
            <div class="text-xl text-gray-600 leading-relaxed mb-12 font-medium">
                <p class="mb-6">
                    Secrets can be ripped straight from your mind, and while some in society possess fragments of that power, only Jackson Vanderlin wields it absolutely. In the ashes of a post-apocalyptic world, his reign of perfect knowledge has created a fragile peace - one built on fear, surveillance, and the absence of lies. To the world, he is untouchable. To his daughter, Willow, he is both father and oppressor.
                </p>
                <p>
                    But when her older brother fails to inherit Jackson’s abilities and Willow begins to manifest them instead, she is thrust into a succession she never wanted. Her path isn’t rebellion - it’s a desperate search for truth in a world where truth itself has been weaponized. And what she uncovers challenges everything she believes about power and loyalty, revealing that even tyranny can be born of conviction, and that morality lives in dangerous shades of gray. If Willow dares to expose what she’s learned, she risks not only destroying her family, but unraveling the precarious stability of a society already on the brink.
                </p>
            </div>

            <div class="world-node">
                <h3 class="font-bold text-2xl mb-3 tracking-tight text-indigo-600">Status</h3>
                <p class="text-gray-500 text-lg leading-relaxed">Manuscript ready for agent review. Please contact Amanda Lynn at amandalynn.author@gmail.com for a copy of the manuscript if interested. Only serious inquiries from accredited agents.</p>
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
            <p class="text-rose-600 mb-8 font-bold uppercase tracking-[0.2em] text-sm">Manuscript Coming Fall 2026</p>
            
            <!-- FIXED TEXT BLOCK -->
            <div class="text-xl text-gray-600 leading-relaxed mb-12 font-medium">
                <p class="mb-6">
                    In an impoverished world where ruthless rules keep the poor desperate, Sorrel has one goal - keep her younger sister, Livia, alive.
                </p>
                <p class="mb-6">
                    Millennia ago, towering walls were raised to protect humanity from the creatures beyond. Inside them, survival is scarce. Outside them, it is impossible.
                </p>
                <p class="mb-6">
                    When a single, devastating mistake forces both Sorrel and her sister beyond the walls, Sorrel realizes just how far she'll go to keep her sister alive. The monsters are worse than they had ever imagined.
                </p>
                <p class="mb-6">
                    To keep her sister alive, Sorrel must do the unthinkable.
                </p>
                <p>
                    She must become the very thing the walls were built to keep out.
                </p>
            </div>

            <div class="world-node">
                <h3 class="font-bold text-2xl mb-3 tracking-tight text-rose-600">Status</h3>
                <p class="text-gray-500 text-lg leading-relaxed">Manuscript estimated completion date: Fall 2026</p>
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
                <img src="{{ '/images/headshot.png' | relative_url }}?v={{ site.time | date: '%s' }}" 
                     alt="Amanda Lynn"
                     class="w-full h-full object-cover transition-transform duration-700 hover:scale-110"
                     onerror="this.src='https://ui-avatars.com/api/?name=Amanda+Lynn&size=512'">
            </div>
        </div>
        <div class="max-w-xl text-center md:text-left">
            <h2 class="text-4xl md:text-5xl font-bold mb-8 tracking-tight">Aspiring Published Author</h2>
            <div class="text-lg md:text-xl text-gray-600 leading-relaxed font-medium">
                <p class="mb-6">
                    Amanda Lynn is an aspiring novelist whose love of storytelling began early. One of her first memories of capturing an audience comes from fourth grade, during standardized testing week, when her class built a fort of desks and turned out the lights. They gathered round as Amanda improsives ghost stories on the spot.
                </p>
                <p>
                    Based in DC, Amanda's brings her vivid imagination and dream-driven ideas to life in thick journals, always with the help of her trustie dog companion warming her lap as she writes.
                </p>
            </div>
        </div>
    </div>
</section>
