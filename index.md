---
layout: default
---

<style>
    /* Smooth Scroll Behavior */
    html { scroll-behavior: smooth; }

    /* Glassmorphism Floating Nav */
    .glass-nav {
        position: fixed;
        top: 24px;
        left: 50%;
        transform: translateX(-50%);
        z-index: 100;
        background: rgba(255, 255, 255, 0.75);
        backdrop-filter: blur(16px);
        -webkit-backdrop-filter: blur(16px);
        border: 1px solid rgba(0, 0, 0, 0.08);
        border-radius: 100px;
        padding: 10px 28px;
        display: flex;
        gap: 24px;
        box-shadow: 0 10px 40px rgba(0,0,0,0.06);
    }

    .nav-link {
        font-size: 11px;
        font-weight: 700;
        color: #666;
        text-transform: uppercase;
        letter-spacing: 0.15em;
        transition: all 0.3s ease;
    }

    .nav-link:hover { color: #4f46e5; transform: translateY(-1px); }

    /* Scroll Reveal Animation */
    .reveal {
        opacity: 0;
        transform: translateY(40px);
        transition: all 1s cubic-bezier(0.22, 1, 0.36, 1);
        will-change: transform, opacity;
    }

    .reveal.active {
        opacity: 1;
        transform: translateY(0);
    }

    /* Tactile Status Box Hover */
    .world-node {
        transition: all 0.5s cubic-bezier(0.22, 1, 0.36, 1);
        border-left: 4px solid transparent;
        background: rgba(249, 250, 251, 0.5);
    }
    
    .world-node:hover {
        background: white;
        transform: scale(1.02) translateX(8px);
        box-shadow: 0 20px 40px rgba(0,0,0,0.04);
        border-left-color: #4f46e5;
    }

    /* Shimmering Gradient Animation for Name */
    .text-gradient-vibrant {
        background: linear-gradient(135deg, #6366f1, #d946ef, #f43f5e, #6366f1);
        background-size: 300% 300%;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        animation: shimmer 12s ease infinite;
    }

    @keyframes shimmer {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    /* Polish for Book Shadows */
    .book-image-shadow {
        box-shadow: 0 30px 60px -12px rgba(0, 0, 0, 0.25), 0 18px 36px -18px rgba(0, 0, 0, 0.3);
    }
</style>

<!-- FLOATING NAVIGATION -->
<nav class="glass-nav">
    <a href="#hero" class="nav-link">Home</a>
    <a href="#books" class="nav-link">Archive</a>
    <a href="#about" class="nav-link">Author</a>
</nav>

<!-- HERO SECTION -->
<section id="hero" class="relative min-h-screen flex items-center justify-center px-6 text-center overflow-hidden">
    <div class="hero-visual-bg">
        <div class="blob blob-1"></div>
        <div class="blob blob-2"></div>
        <div class="blob blob-3"></div>
    </div>
    
    <div class="max-w-5xl mx-auto relative z-10 reveal">
        <span class="inline-block px-5 py-2 mb-10 text-[10px] font-black tracking-[0.4em] uppercase bg-black text-white rounded-full shadow-xl">Aspiring Novelist</span>
        <h1 class="text-7xl md:text-[10rem] font-extrabold tracking-tighter mb-8 block leading-[0.85]">
            <span class="text-gradient-vibrant">Amanda</span> <br> 
            <span class="text-gradient-vibrant">Lynn</span>
        </h1>
        <p class="text-xl md:text-3xl text-gray-500 max-w-2xl mx-auto mb-16 font-medium leading-tight">
            Drafting stories where <span class="text-black font-bold">survival</span> is a choice and <span class="text-black font-bold">secrets</span> are the currency.
        </p>
        <div class="flex flex-col sm:flex-row justify-center items-center gap-6">
            <button onclick="document.getElementById('books').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-black text-white px-14 py-6 rounded-full font-bold hover:scale-105 active:scale-95 transition-all shadow-2xl shadow-indigo-500/20">Explore the Works</button>
            <button onclick="document.getElementById('about').scrollIntoView({behavior:'smooth'})" class="w-full sm:w-auto bg-white/60 border border-black/10 backdrop-blur-xl text-black px-1
