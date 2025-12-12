<script>
</script>

<section class="bg-[#0B0F19] text-white py-24">
  <div class="max-w-[1200px] mx-auto px-6">
    <div class="text-center mb-16">
      <h2 class="text-5xl font-bold mb-6 tracking-tight">
        Digital Menu Management
      </h2>
      <p class="text-gray-400 text-lg max-w-2xl mx-auto leading-relaxed">
        Update your drink menu instantly across all stations. No more reprinting menus or staff confusion. Changes go live immediately, keeping everyone informed.
      </p>
    </div>

    <!-- BOM UI Mockup -->
    <div class="bg-white rounded-lg overflow-hidden shadow-2xl mb-20 text-gray-900 mx-auto max-w-[1000px]">
      <!-- Window Header -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-2 flex items-center justify-between">
         <div class="flex items-center gap-2">
            <span class="text-xs font-semibold text-gray-700">Cocktail Menu - Spring 2025</span>
         </div>
         <div class="flex items-center gap-3">
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>👁️</span> View
            </div>
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>📊</span> All categories
            </div>
            <div class="flex items-center gap-1 text-xs text-gray-500 bg-white border border-gray-200 px-2 py-1 rounded">
               <span>⬇️</span> Export PDF
            </div>
            <button class="text-gray-400 hover:text-gray-600">✕</button>
         </div>
      </div>

      <!-- Table Header -->
      <div class="grid grid-cols-12 bg-gray-50 border-b border-gray-200 text-[10px] font-bold text-gray-500 uppercase tracking-wider py-2 px-4">
         <div class="col-span-1">Status</div>
         <div class="col-span-1">ID</div>
         <div class="col-span-1">Cat</div>
         <div class="col-span-3">Drink Name</div>
         <div class="col-span-2">Main Spirit</div>
         <div class="col-span-1">Price</div>
         <div class="col-span-1">Prep</div>
         <div class="col-span-1">Pop</div>
         <div class="col-span-1">Category</div>
      </div>

      <!-- Table Body - Empty State / Search for effect -->
      <div class="h-[400px] bg-white relative">
         <!-- Search Overlay Effect -->
         <div class="absolute top-4 left-4 right-4 bg-white border border-gray-200 shadow-sm rounded p-2 flex items-center gap-2 max-w-md z-10">
            <span class="text-gray-400">🔍</span>
            <span class="text-sm text-gray-900">Atl|</span>
            <div class="w-[1px] h-4 bg-blue-500 animate-pulse"></div>
         </div>
         
         <!-- Blurred/Faded rows to simulate content behind search -->
         <div class="opacity-30 pointer-events-none">
             {#each Array(8) as _, i}
             <div class="grid grid-cols-12 border-b border-gray-100 py-3 px-4 text-xs text-gray-600">
                <div class="col-span-1 flex items-center"><div class="w-2 h-2 rounded-full bg-green-500 mr-2"></div> Make</div>
                <div class="col-span-1">-</div>
                <div class="col-span-1">{i + 1}</div>
                <div class="col-span-2 font-mono">310-221{i}</div>
                <div class="col-span-3">Component Name {i + 1}</div>
                <div class="col-span-1">A</div>
                <div class="col-span-1">{Math.floor(Math.random() * 10) + 1}</div>
                <div class="col-span-1">EA</div>
                <div class="col-span-1">Mech</div>
             </div>
             {/each}
         </div>
      </div>
    </div>

    <!-- Features Grid -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-x-12 gap-y-16 text-left">
       <!-- Feature 1 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="4" y="4" width="6" height="6" rx="1"/><rect x="14" y="4" width="6" height="6" rx="1"/><rect x="4" y="14" width="6" height="6" rx="1"/><path d="M14 17h6"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Menu Categories</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Organize drinks by category, spirit type, or popularity. Drag and reorder items to match your bar's flow and priorities.
          </p>
       </div>

       <!-- Feature 2 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20h9"/><path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Instant Updates</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Make changes to your menu and see them reflected immediately across all bar stations. No delays, no confusion.
          </p>
       </div>

       <!-- Feature 3 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21.5 2v6h-6"/><path d="M2.5 22v-6h6"/><path d="M2 11.5a10 10 0 0 1 18.8-4.3L21.5 8"/><path d="M22 12.5a10 10 0 0 1-18.8 4.2L2.5 16"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Version History</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Track all menu changes over time. Easily revert to previous versions or see what drinks were popular in past seasons.
          </p>
       </div>

       <!-- Feature 4 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 9h16"/><path d="M4 15h16"/><path d="M10 3L8 21"/><path d="M16 3l-2 18"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Recipe Management</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Store complete recipes with ingredients, measurements, and preparation notes. Ensure consistency across all bartenders.
          </p>
       </div>

       <!-- Feature 5 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Prep Time Tracking</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Set estimated prep times for each drink. Help bartenders prioritize orders and manage customer expectations during rush hours.
          </p>
       </div>

       <!-- Feature 6 -->
       <div>
          <div class="flex items-center gap-3 mb-3">
             <div class="text-gray-400">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 16V8a2 2 0 0 0-1-1.73l-7-4a2 2 0 0 0-2 0l-7 4A2 2 0 0 0 3 8v8a2 2 0 0 0 1 1.73l7 4a2 2 0 0 0 2 0l7-4A2 2 0 0 0 21 16z"/><polyline points="3.27 6.96 12 12.01 20.73 6.96"/><line x1="12" y1="22.08" x2="12" y2="12"/></svg>
             </div>
             <h3 class="text-lg font-bold text-white">Seasonal Menus</h3>
          </div>
          <p class="text-sm text-gray-400 leading-relaxed">
             Create and save seasonal menu variations. Switch between summer cocktails and winter warmers with a single click.
          </p>
       </div>
    </div>
  </div>
</section>
