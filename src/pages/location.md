---
layout: ../layouts/Layout.astro
title: Pickup & Location
description: Visit Rancho La Capillita for hay pickup. Directions and hours.
---

<div class="container mx-auto px-4 py-8">
  <h1 class="text-3xl font-bold text-green-900 mb-6">Pickup Location</h1>
  
<div class="container mx-auto px-4 py-8">
  <h1 class="text-4xl font-bold text-ranch-green-dark mb-6">Pickup Location</h1>
  
  <div class="grid md:grid-cols-2 gap-12 items-start">
    <div>
      <p class="text-xl text-stone-700 mb-8 font-light leading-relaxed">
        We are located just off the highway, with easy turn-around access for trucks and trailers.
      </p>

      <div class="space-y-6">
        <div class="bg-ranch-light p-8 rounded-2xl border border-ranch-green/20">
            <h3 class="font-bold text-xl mb-4 text-ranch-green-dark flex items-center gap-2">
                <span class="text-2xl">📍</span> Address
            </h3>
            <address class="text-stone-700 not-italic text-lg">
            Rancho La Capillita<br />
            1234 Country Road<br />
            Yuma, AZ 85364<br />
            </address>
            <a href="https://maps.google.com" target="_blank" class="inline-block mt-4 text-ranch-green font-bold underline hover:text-ranch-green-dark">Get Directions &rarr;</a>
        </div>

        <div class="bg-white p-8 rounded-2xl border border-stone-200 shadow-sm">
            <h3 class="font-bold text-xl mb-4 text-ranch-green-dark flex items-center gap-2">
                <span class="text-2xl">🕒</span> Pickup Hours
            </h3>
            <ul class="text-stone-700 space-y-3 text-lg">
            <li class="flex justify-between border-b border-stone-100 pb-2"><span>Mon - Fri</span> <span class="font-bold">7:00 AM - 5:00 PM</span></li>
            <li class="flex justify-between border-b border-stone-100 pb-2"><span>Saturday</span> <span class="font-bold">8:00 AM - 12:00 PM</span></li>
            <li class="flex justify-between text-stone-400"><span>Sunday</span> <span>Closed</span></li>
            </ul>
        </div>
      </div>
    </div>

    <div class="bg-stone-200 rounded-2xl overflow-hidden h-96 shadow-inner flex items-center justify-center text-stone-500 border border-stone-300 relative group">
      <!-- Map Placeholder -->
      <div class="absolute inset-0 bg-stone-100 flex flex-col items-center justify-center p-8 text-center group-hover:bg-stone-50 transition-colors">
        <span class="text-6xl mb-4 opacity-50">🗺️</span>
        <p class="font-bold text-xl text-stone-400">Interactive Map</p>
        <p class="text-sm text-stone-400 mt-2">(Embed Google Maps here)</p>
      </div>
    </div>
  </div>
</div>
