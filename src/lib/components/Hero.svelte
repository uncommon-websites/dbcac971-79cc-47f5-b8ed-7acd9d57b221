<script>
</script>

<section class="pt-20 pb-16 text-center max-w-[1200px] mx-auto px-6">
  <h1 class="text-6xl font-bold tracking-tight text-gray-900 mb-6 leading-[1.1]">
    Real-Time Communication<br>for High-Volume Bars
  </h1>
  <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto leading-relaxed">
    BarBoards connects your bar and kitchen staff instantly, eliminating order confusion and keeping your high-volume venue running smoothly.
  </p>
  <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm mb-20 cursor-pointer">
    Get started
  </button>

  <!-- Bar Display Board Visualization -->
  <div class="relative w-full aspect-[2/1] bg-gradient-to-br from-gray-900 to-gray-800 rounded-xl overflow-hidden flex items-center justify-center border border-gray-700">
    <!-- Digital Display Board -->
    <div class="relative w-full max-w-4xl h-full p-8">
       <!-- Display Header -->
       <div class="bg-black/40 backdrop-blur-sm rounded-lg p-4 mb-4 border border-gray-700">
          <div class="flex items-center justify-between">
             <div class="text-white font-bold text-lg">ACTIVE ORDERS</div>
             <div class="text-gray-400 text-sm">Station 3 • 7:42 PM</div>
          </div>
       </div>
       
       <!-- Order Cards Grid -->
       <div class="grid grid-cols-3 gap-4">
          <!-- Order 1 -->
          <div class="bg-emerald-500/20 backdrop-blur-sm border-2 border-emerald-500 rounded-lg p-4 shadow-lg">
             <div class="text-emerald-400 font-bold text-sm mb-2">TABLE 12</div>
             <div class="text-white text-xs space-y-1">
                <div>2x Old Fashioned</div>
                <div>1x Margarita</div>
             </div>
             <div class="mt-3 text-emerald-300 text-xs">Ready to serve</div>
          </div>
          
          <!-- Order 2 -->
          <div class="bg-amber-500/20 backdrop-blur-sm border-2 border-amber-500 rounded-lg p-4 shadow-lg">
             <div class="text-amber-400 font-bold text-sm mb-2">TABLE 8</div>
             <div class="text-white text-xs space-y-1">
                <div>3x Mojito</div>
                <div>1x Espresso Martini</div>
             </div>
             <div class="mt-3 text-amber-300 text-xs">In progress</div>
          </div>
          
          <!-- Order 3 -->
          <div class="bg-blue-500/20 backdrop-blur-sm border-2 border-blue-500 rounded-lg p-4 shadow-lg">
             <div class="text-blue-400 font-bold text-sm mb-2">TABLE 5</div>
             <div class="text-white text-xs space-y-1">
                <div>2x Cosmopolitan</div>
                <div>1x Manhattan</div>
             </div>
             <div class="mt-3 text-blue-300 text-xs">New order</div>
          </div>
       </div>
    </div>
    
    <div class="absolute inset-0 bg-gradient-to-t from-gray-900 via-transparent to-transparent pointer-events-none opacity-50"></div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mt-20 text-left">
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">01</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Instant Updates</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Digital menu changes go live immediately across all stations. No more reprinting menus or confused staff about what's available.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">02</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Kitchen-Bar Sync</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Real-time communication between kitchen and bar staff. Orders, modifications, and timing updates flow seamlessly between teams.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">03</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Staff Coordination</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Keep your entire team on the same page during peak hours. Bartenders know exactly what's needed and when, reducing wait times.
      </p>
    </div>
  </div>
</section>
