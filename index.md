---
layout: default
title: Manifest - Turn your app idea into a profitable online business
description: Transform your app idea into a thriving SaaS business. Manifest provides the tools, guidance, and community to help entrepreneurs build, launch, and grow successful software products.
---

<style>
  body {
    overflow-x: hidden;
  }

  @keyframes gradientShift {
    0% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
    100% {
      background-position: 0% 50%;
    }
  }

  .animated-gradient {
    background: linear-gradient(-45deg, #f8fafc, #f1f5f9, #e2e8f0, #f8fafc, #f1f5f9);
    background-size: 400% 400%;
    animation: gradientShift 15s ease infinite;
  }

  /* Showcase Carousel */
  @keyframes scrollLeft {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }

  .showcase-track {
    animation: scrollLeft 40s linear infinite;
    width: fit-content;
  }

  .showcase-track-reverse {
    animation: scrollRight 40s linear infinite;
    width: fit-content;
  }

  .showcase-track:hover,
  .showcase-track-reverse:hover {
    animation-play-state: paused;
  }

  @keyframes scrollRight {
    0% { transform: translateX(-50%); }
    100% { transform: translateX(0); }
  }

  .showcase-card {
    transition: transform 0.3s ease;
  }

  .showcase-card:hover {
    transform: scale(1.05);
    z-index: 20;
  }

  /* Showcase Modal */
  .showcase-modal {
    display: none;
    position: fixed;
    inset: 0;
    z-index: 100;
    align-items: center;
    justify-content: center;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(8px);
  }

  .showcase-modal.active {
    display: flex;
  }

  .showcase-modal-content {
    position: relative;
    max-width: 90vw;
    max-height: 90vh;
  }

  .showcase-modal-content img {
    max-width: 100%;
    max-height: 80vh;
    border-radius: 12px;
    box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
  }

  .showcase-modal-info {
    text-align: center;
    margin-top: 16px;
  }

  .showcase-modal-close {
    position: absolute;
    top: -48px;
    right: 0;
    color: #1f2937;
    font-size: 32px;
    cursor: pointer;
    opacity: 0.7;
    transition: opacity 0.2s;
    line-height: 1;
  }

  .showcase-modal-close:hover {
    opacity: 1;
  }
</style>


<!-- Light hero section -->
<div class="animated-gradient relative overflow-hidden min-h-screen flex items-center -mt-16 pt-16">

  <div class="relative mx-auto w-full max-w-[900px] px-4 sm:px-0 py-20">
    <div class="text-center space-y-8 mb-16">
      <!-- Badge/tag -->
      <div class="inline-flex items-center px-4 py-2 bg-gray-900/10 text-gray-700 rounded-full text-sm font-medium mb-4">
        <svg class="w-4 h-4 mr-2" fill="currentColor" viewBox="0 0 20 20">
          <path fill-rule="evenodd" d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z" clip-rule="evenodd"></path>
        </svg>
        The AI app builder for entrepreneurs.
      </div>

      <h1 class="text-6xl sm:text-7xl lg:text-8xl font-extrabold text-gray-900 leading-tight">
        Generate a <span class="bg-gradient-to-r from-emerald-500 to-teal-600 bg-clip-text text-transparent">SaaS web app</span> that earns money while you sleep.
      </h1>

      <p class="text-2xl sm:text-3xl text-gray-600 max-w-5xl mx-auto leading-relaxed">
        Build, publish, and launch fully-functioning apps that attract paying subscribers. <span class="font-semibold text-gray-900">No coding necessary.</span>
      </p>

      <!-- Social proof -->
      <div class="flex items-center justify-center space-x-6 text-sm text-gray-600 pt-4">
        <div class="flex items-center">
          <svg class="w-4 h-4 mr-1 text-emerald-500" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
          </svg>
          <span>Built in minutes</span>
        </div>
        <div class="flex items-center">
          <svg class="w-4 h-4 mr-1 text-emerald-500" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
          </svg>
          <span>Payments included</span>
        </div>
        <div class="flex items-center">
          <svg class="w-4 h-4 mr-1 text-emerald-500" fill="currentColor" viewBox="0 0 20 20">
            <path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path>
          </svg>
          <span>Deploy instantly</span>
        </div>
      </div>
    </div>

    <div class="text-center">
      <a href="https://app.madewithmanifest.com/login?onboarding=1" class="inline-flex items-center bg-gray-900 hover:bg-gray-800 text-white font-semibold px-10 py-5 rounded-lg text-xl transition-all duration-200 shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
        Generate your first SaaS web app
        <svg class="ml-3 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"></path>
        </svg>
      </a>

      <!-- Additional CTA info -->
      <p class="mt-4 text-sm text-gray-500">
        Free to start • No credit card required
      </p>
    </div>
  </div>

</div>

<!-- Showcase Carousel Section -->
<div class="bg-gray-100 py-16 overflow-hidden">
  <div class="text-center mb-10 px-4">
    <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 mb-3">
      Apps built with Manifest
    </h2>
    <p class="text-gray-600 text-lg">
      Start generating revenue today with an app built for your niche!
    </p>
  </div>

  <!-- Carousel Container -->
  <div class="relative">
    <!-- Gradient fade edges -->
    <div class="absolute left-0 top-0 bottom-0 w-16 sm:w-32 bg-gradient-to-r from-gray-100 to-transparent z-10 pointer-events-none"></div>
    <div class="absolute right-0 top-0 bottom-0 w-16 sm:w-32 bg-gradient-to-l from-gray-100 to-transparent z-10 pointer-events-none"></div>

    <!-- Scrolling track -->
    <div class="showcase-track flex py-4">
      <!-- First set of 8 cards -->
      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-1.png" alt="AV Checkout" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$29/month</span>
          <div class="text-white text-sm font-medium">AV Checkout - Equipment tracking for schools</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-2.png" alt="VoiceFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$19/month</span>
          <div class="text-white text-sm font-medium">VoiceFlow - AI audio for social media creators</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-3.png" alt="YogaFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$39/month</span>
          <div class="text-white text-sm font-medium">YogaFlow - Class scheduling for yoga studios</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-4.png" alt="Plan Every Day" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$12/month</span>
          <div class="text-white text-sm font-medium">Plan Every Day - Calendar-first task manager</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-5.png" alt="Crescendo" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$24/month</span>
          <div class="text-white text-sm font-medium">Crescendo - Progress tracker for music teachers</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-6.png" alt="EcoField" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$49/month</span>
          <div class="text-white text-sm font-medium">EcoField - Field surveys for ecologists</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-7.png" alt="ClimbHub" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$79/month</span>
          <div class="text-white text-sm font-medium">ClimbHub - Membership management for gyms</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-8.png" alt="Ultimate Scoreboard" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$15/month</span>
          <div class="text-white text-sm font-medium">Ultimate Scoreboard - Digital scoreboard app</div>
        </div>
      </div>

      <!-- Duplicate set for infinite scroll -->
      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-1.png" alt="AV Checkout" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$29/month</span>
          <div class="text-white text-sm font-medium">AV Checkout - Equipment tracking for schools</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-2.png" alt="VoiceFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$19/month</span>
          <div class="text-white text-sm font-medium">VoiceFlow - AI audio for social media creators</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-3.png" alt="YogaFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$39/month</span>
          <div class="text-white text-sm font-medium">YogaFlow - Class scheduling for yoga studios</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-4.png" alt="Plan Every Day" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$12/month</span>
          <div class="text-white text-sm font-medium">Plan Every Day - Calendar-first task manager</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-5.png" alt="Crescendo" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$24/month</span>
          <div class="text-white text-sm font-medium">Crescendo - Progress tracker for music teachers</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-6.png" alt="EcoField" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$49/month</span>
          <div class="text-white text-sm font-medium">EcoField - Field surveys for ecologists</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-7.png" alt="ClimbHub" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$79/month</span>
          <div class="text-white text-sm font-medium">ClimbHub - Membership management for gyms</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-8.png" alt="Ultimate Scoreboard" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$15/month</span>
          <div class="text-white text-sm font-medium">Ultimate Scoreboard - Digital scoreboard app</div>
        </div>
      </div>
    </div>

    <!-- Second row - scrolling opposite direction -->
    <div class="showcase-track-reverse flex py-4">
      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-1.png" alt="AV Checkout" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$29/month</span>
          <div class="text-white text-sm font-medium">AV Checkout - Equipment tracking for schools</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-2.png" alt="VoiceFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$19/month</span>
          <div class="text-white text-sm font-medium">VoiceFlow - AI audio for social media creators</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-3.png" alt="YogaFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$39/month</span>
          <div class="text-white text-sm font-medium">YogaFlow - Class scheduling for yoga studios</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-4.png" alt="Plan Every Day" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$12/month</span>
          <div class="text-white text-sm font-medium">Plan Every Day - Calendar-first task manager</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-5.png" alt="Crescendo" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$24/month</span>
          <div class="text-white text-sm font-medium">Crescendo - Progress tracker for music teachers</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-6.png" alt="EcoField" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$49/month</span>
          <div class="text-white text-sm font-medium">EcoField - Field surveys for ecologists</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-7.png" alt="ClimbHub" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$79/month</span>
          <div class="text-white text-sm font-medium">ClimbHub - Membership management for gyms</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-8.png" alt="Ultimate Scoreboard" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$15/month</span>
          <div class="text-white text-sm font-medium">Ultimate Scoreboard - Digital scoreboard app</div>
        </div>
      </div>

      <!-- Duplicate set for infinite scroll -->
      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-1.png" alt="AV Checkout" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$29/month</span>
          <div class="text-white text-sm font-medium">AV Checkout - Equipment tracking for schools</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-2.png" alt="VoiceFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$19/month</span>
          <div class="text-white text-sm font-medium">VoiceFlow - AI audio for social media creators</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-3.png" alt="YogaFlow" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$39/month</span>
          <div class="text-white text-sm font-medium">YogaFlow - Class scheduling for yoga studios</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-4.png" alt="Plan Every Day" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$12/month</span>
          <div class="text-white text-sm font-medium">Plan Every Day - Calendar-first task manager</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-5.png" alt="Crescendo" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$24/month</span>
          <div class="text-white text-sm font-medium">Crescendo - Progress tracker for music teachers</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-6.png" alt="EcoField" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$49/month</span>
          <div class="text-white text-sm font-medium">EcoField - Field surveys for ecologists</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-7.png" alt="ClimbHub" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$79/month</span>
          <div class="text-white text-sm font-medium">ClimbHub - Membership management for gyms</div>
        </div>
      </div>

      <div class="showcase-card flex-shrink-0 w-72 sm:w-96 mx-2 sm:mx-4 relative rounded-xl overflow-hidden shadow-2xl cursor-pointer">
        <img src="/assets/showcase/site-8.png" alt="Ultimate Scoreboard" class="w-full h-52 sm:h-64 object-cover">
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-transparent"></div>
        <div class="absolute bottom-0 left-0 right-0 p-4">
          <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-sm rounded-full text-white font-bold text-lg mb-2">$15/month</span>
          <div class="text-white text-sm font-medium">Ultimate Scoreboard - Digital scoreboard app</div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="bg-gray-100 relative overflow-hidden" style="padding-top: 80px; padding-bottom: 40px;">


<!-- specify payment -->
{% include typewriter-window.html 
  left_bg_gradient="from-[#5186ED] to-[#416CC0]"
  left_title="Describe what you want built."
  left_text_color="text-white"
  right_title="Manifest will convert it into a fully-functioning web app."
  right_subtitle="No code necessary. The app will be ready for users to sign up, pay for access, and experience your incredible idea come-to-life!"
  image_src="/assets/iphone-blue.png"
  image_alt="Stripe phone"
  image_position_top="350px"
  image_container_width="45%"
  image_left_offset="0px"
  mobile_image_container_class="relative overflow-hidden"
  mobile_image_container_style="margin-top: 40px; height: 500px;"
  mobile_image_class="absolute top-0 right-[-5%]"
  mobile_image_style="width: 120%;"
%}




<!-- specify payment -->
{% include double-window.html 
  left_bg_gradient="from-[#58A55D] to-[#478E4B]"
  left_title="Set the price of your app."
  left_text_color="text-white"
  right_title="Specify when &amp; how much your users should pay to access your app."
  right_subtitle="Monthly, annually, one-time or one time payments. Specify multiple tiers for different levels of functionality."
  image_src="/assets/select-how-users-pay.png"
  image_alt="Stripe phone"
  image_position_top="400px"
  image_container_width="50%"
  image_left_offset="-5px"
  mobile_image_container_class="relative overflow-hidden"
  mobile_image_container_style="margin-top: 40px; height: 500px;"
  mobile_image_class="absolute top-0 right-[-5%]"
  mobile_image_style="width: 120%;"
%}



<!-- <div class="relative mx-auto w-full max-w-[800px] px-4 sm:px-0 my-24">
  <div class="bg-white rounded-lg relative flex flex-col min-h-[480px] sm:min-h-[750px]">
    
    <div class="absolute mx-auto" style="width: 120%; left: -10%; top: -60px; z-index: 1;">
      <img src="/assets/manifest-will-build-it.png" alt="Manifest will build it" class="w-full">
    </div>
    <div class="flex-grow"></div>
    <div class="relative w-full py-12 px-8 sm:px-12 text-3xl sm:text-4xl font-bold text-center" style="z-index: 2;">
      And Manifest’s AI will build it before your eyes.
    </div>
  </div>
</div>
 -->





<!-- double window with stripe image on right -->
{% include double-window.html 
  left_bg_gradient="from-[#DAA939] to-[#B6923D]"
  left_title="Database, storage, payments, log in &amp; more. <br /><br />All handled for you."
  left_text_color="text-white"
  right_title="No need to setup connections &amp; integrations."
  right_subtitle="All the tricky stuff is taken care of automagically."
  image_src="/assets/ipad-pick-plan.png"
  image_alt="Stripe phone"
  image_position_top="300px"
  image_container_width="80%"
  image_left_offset="235px"
  mobile_image_container_class="relative overflow-hidden"
  mobile_image_container_style="margin-top: 40px; height: 500px;"
  mobile_image_class="absolute top-0 right-[-5%]"
  mobile_image_style="width: 120%;"
%}

<!-- double window with stripe image on right -->
{% include double-window.html
  left_bg_gradient="from-[#4C56C0] to-[#3F47A6]"
  left_title="Subscriptions baked into every app you build."
  left_text_color="text-white"
  right_title="Simply connect your Stripe account to start receiving payments."
  right_subtitle="Money users pay you will go into your Stripe account, allowing you to transfer it out to your bank account."
  image_src="/assets/purple-stripe.png"
  image_alt="Stripe phone"
  image_position_top="350px"
%}

<!-- FAQ Section -->
<div class="relative mx-auto w-full max-w-[800px] px-4 sm:px-0 py-24">
  <h2 class="text-3xl sm:text-4xl font-bold text-gray-900 text-center mb-12">
    Frequently Asked Questions
  </h2>

  <div class="space-y-4">
    <!-- FAQ Item 1 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">How is Manifest different from other app builders like Base44, Lovable, Replit, Bolt, etc.?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">Many app builders focus on prototypes, internal tools, or experiments. Manifest is built specifically for entrepreneurs who want to launch real products that generate revenue.</p>
        <p class="text-gray-600 leading-relaxed mt-3">Every Manifest app comes with subscriptions and payments already built in, so you can start charging users without stitching together third-party tools or custom billing logic. Instead of getting stuck at the "how do I monetize this?" stage, you can move from idea to working app to paying customers in one place.</p>
      </div>
    </div>

    <!-- FAQ Item 2 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">What happens if my business outgrows Manifest?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">Our goal is to support you long-term. Apps built on Manifest can scale to support large user bases and meaningful revenue.</p>
        <p class="text-gray-600 leading-relaxed mt-3">That said, we believe you should always have options. You can export your data at any time, and much of your app's generated code is accessible. If you eventually decide to migrate, a developer can help recreate or extend your app elsewhere. We're building Manifest to grow with you — but not lock you in.</p>
      </div>
    </div>

    <!-- FAQ Item 3 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">Do I have access to the code Manifest generates?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">Yes. The custom code generated for your app is visible in the Code tab, where you can review it, copy it, and make edits.</p>
        <p class="text-gray-600 leading-relaxed mt-3">Some shared infrastructure is proprietary, but the unique parts of your app are accessible. This gives you transparency, flexibility, and the ability to involve a developer if you ever want deeper customization.</p>
      </div>
    </div>

    <!-- FAQ Item 4 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">Who owns my app?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">You do. Your app, brand, and intellectual property are 100% yours — not Manifest's.</p>
      </div>
    </div>

    <!-- FAQ Item 5 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">Does Manifest take a percentage of my revenue?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">No. Manifest does not take a cut of your customer payments. When your customers pay you, that revenue goes directly to you.</p>
      </div>
    </div>

    <!-- FAQ Item 6 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">Can a developer edit code directly?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">Yes. Each app includes a Code section where developers can make direct edits to the source code.</p>
        <p class="text-gray-600 leading-relaxed mt-3">Most updates can be handled through AI or design tools, but having direct code access gives you flexibility if you want to fine-tune behavior or bring in technical help.</p>
      </div>
    </div>

    <!-- FAQ Item 7 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">Does Manifest create web apps or mobile apps?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">Manifest creates modern web apps that work across desktop, tablet, and mobile browsers.</p>
        <p class="text-gray-600 leading-relaxed mt-3">These are not native app-store apps (iOS/Android), but they are responsive and mobile-friendly. Many founders start with a web app first and later decide whether a native mobile app makes sense.</p>
      </div>
    </div>

    <!-- FAQ Item 8 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">Is AI the only way to modify my app?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">No. AI is the fastest way to build and update your app, but it's not the only way.</p>
        <p class="text-gray-600 leading-relaxed mt-3">You can also use Design mode to click into your app and make visual changes without writing prompts. This gives you both conversational control and direct editing tools.</p>
      </div>
    </div>

    <!-- FAQ Item 9 -->
    <div class="bg-white rounded-lg shadow-sm border border-gray-200 overflow-hidden">
      <button class="faq-toggle w-full px-6 py-5 text-left flex items-center justify-between hover:bg-gray-50 transition-colors">
        <span class="text-lg font-semibold text-gray-900 pr-4">What kind of businesses is Manifest best suited for?</span>
        <svg class="faq-icon w-5 h-5 text-gray-500 flex-shrink-0 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
      </button>
      <div class="faq-content hidden px-6 pb-5">
        <p class="text-gray-600 leading-relaxed">Manifest is best for founders who want to launch and monetize a software product without building a full engineering team from day one.</p>
        <p class="text-gray-600 leading-relaxed mt-3">Common use cases include SaaS tools, marketplaces, membership products, internal tools you plan to sell, and niche software for specific communities. If your goal is to test an idea quickly and start charging customers, Manifest is designed for that path.</p>
      </div>
    </div>
  </div>
</div>

<!-- Showcase Modal -->
<div id="showcaseModal" class="showcase-modal">
  <div class="showcase-modal-content">
    <span class="showcase-modal-close">&times;</span>
    <img id="showcaseModalImg" src="" alt="">
    <div class="showcase-modal-info">
      <span id="showcaseModalPrice" class="inline-block px-4 py-2 bg-gray-900 rounded-full text-white font-bold text-xl mb-2"></span>
      <div id="showcaseModalName" class="text-gray-900 text-lg font-medium mt-2"></div>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const faqToggles = document.querySelectorAll('.faq-toggle');

  faqToggles.forEach(toggle => {
    toggle.addEventListener('click', function() {
      const content = this.nextElementSibling;
      const icon = this.querySelector('.faq-icon');

      // Toggle content visibility
      content.classList.toggle('hidden');

      // Rotate icon
      icon.classList.toggle('rotate-180');
    });
  });

  // Showcase Modal
  const modal = document.getElementById('showcaseModal');
  const modalImg = document.getElementById('showcaseModalImg');
  const modalPrice = document.getElementById('showcaseModalPrice');
  const modalName = document.getElementById('showcaseModalName');
  const closeBtn = document.querySelector('.showcase-modal-close');

  document.querySelectorAll('.showcase-card').forEach(card => {
    card.addEventListener('click', function() {
      const img = this.querySelector('img');
      const price = this.querySelector('.text-lg.font-bold, span.font-bold').textContent;
      const name = this.querySelector('.text-sm.font-medium').textContent;

      modalImg.src = img.src;
      modalImg.alt = img.alt;
      modalPrice.textContent = price;
      modalName.textContent = name;
      modal.classList.add('active');
      document.body.style.overflow = 'hidden';
    });
  });

  function closeModal() {
    modal.classList.remove('active');
    document.body.style.overflow = '';
  }

  closeBtn.addEventListener('click', closeModal);
  modal.addEventListener('click', function(e) {
    if (e.target === modal) closeModal();
  });
  document.addEventListener('keydown', function(e) {
    if (e.key === 'Escape') closeModal();
  });
});
</script>

<!-- Final CTA Section -->
<div class="relative mx-auto w-full max-w-[900px] px-4 sm:px-0 py-24">
  <div class="text-center space-y-8">
    <h2 class="text-4xl sm:text-5xl lg:text-6xl font-bold text-gray-900 leading-tight">
      Ready to bring your idea to life?
    </h2>
    <p class="text-xl sm:text-2xl text-gray-600 max-w-2xl mx-auto">
      Join the entrepreneurs who are turning their ideas into thriving SaaS businesses.
    </p>
    <div class="pt-4">
      <a href="https://app.madewithmanifest.com/login?onboarding=1" class="inline-flex items-center bg-gray-900 hover:bg-gray-800 text-white font-semibold px-10 py-5 rounded-lg text-xl transition-all duration-200 shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">
        Start building for free
        <svg class="ml-3 w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"></path>
        </svg>
      </a>
      <p class="mt-4 text-sm text-gray-500">
        No credit card required
      </p>
    </div>
  </div>
</div>

</div>