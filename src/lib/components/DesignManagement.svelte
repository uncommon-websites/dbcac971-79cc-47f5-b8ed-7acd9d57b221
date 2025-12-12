<script>
</script>

<section class="bg-gray-900 text-white py-24 overflow-hidden relative">
  <!-- Background gradient effect -->
  <div class="absolute inset-0 bg-gradient-to-b from-gray-800 to-black opacity-100"></div>
  
  <div class="relative max-w-[1200px] mx-auto px-6 text-center">
    <h2 class="text-5xl font-bold mb-6 tracking-tight leading-tight">
      Powerful Order<br>Management Dashboard
    </h2>
    <p class="text-gray-300 text-lg max-w-2xl mx-auto mb-16 leading-relaxed">
      Track every drink order from request to delivery. BarBoards gives you complete visibility into your bar operations, helping you identify bottlenecks and optimize service during peak hours.
    </p>

    <!-- UI Mockup -->
    <div class="bg-white rounded-xl shadow-2xl overflow-hidden text-left text-gray-900 mx-auto max-w-[1000px] border border-blue-400/30">
      <!-- Window Controls -->
      <div class="bg-gray-50 border-b border-gray-200 px-4 py-3 flex items-center gap-2">
        <div class="flex gap-1.5">
          <div class="w-3 h-3 rounded-full bg-red-400"></div>
          <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
          <div class="w-3 h-3 rounded-full bg-green-400"></div>
        </div>
        <div class="ml-4 flex items-center gap-2 text-xs font-medium text-gray-600 bg-white px-2 py-1 rounded border border-gray-200 shadow-sm">
           <span class="w-3 h-3 bg-gray-800 rounded-full flex items-center justify-center text-[8px] text-white">🍸</span>
           Main Bar
           <span class="text-gray-400">▼</span>
        </div>
      </div>

      <div class="flex h-[500px]">
        <!-- Sidebar -->
        <div class="w-48 bg-gray-50 border-r border-gray-200 p-3 flex flex-col gap-1">
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🕒</span> Recent orders
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-900 bg-white shadow-sm border border-gray-200 rounded cursor-pointer">
            <span class="opacity-70">🍸</span> Active orders
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">✅</span> Completed
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">⏱️</span> Pending
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📊</span> Analytics
          </div>
          <div class="flex items-center gap-2 px-2 py-1.5 text-xs font-medium text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
            <span class="opacity-70">📋</span> All orders
          </div>
          
          <div class="mt-auto text-[10px] text-gray-400 px-2">127 orders today</div>
        </div>

        <!-- Main List -->
        <div class="flex-1 bg-white flex flex-col">
          <div class="border-b border-gray-100 p-3">
             <div class="relative">
                <span class="absolute left-2 top-1.5 text-gray-400 text-xs">🔍</span>
                <input type="text" placeholder="Search orders..." class="w-full bg-gray-50 border border-gray-200 rounded pl-7 pr-3 py-1 text-xs focus:outline-none focus:border-blue-500">
             </div>
          </div>
          <div class="flex-1 overflow-y-auto">
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-emerald-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-emerald-100 text-emerald-600 rounded flex items-center justify-center text-[8px]">12</div>
                   <span class="text-xs font-medium text-gray-700">Table 12 • 2 Old Fashioned, 1 Margarita</span>
                </div>
                <div class="text-[10px] text-emerald-600 group-hover:text-emerald-700">Ready</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 bg-amber-50/50 cursor-pointer">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-amber-100 text-amber-600 rounded flex items-center justify-center text-[8px]">8</div>
                   <span class="text-xs font-medium text-gray-900">Table 8 • 3 Mojito, 1 Espresso Martini</span>
                </div>
                <div class="text-[10px] text-amber-600">In Progress</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-blue-100 text-blue-600 rounded flex items-center justify-center text-[8px]">5</div>
                   <span class="text-xs font-medium text-gray-700">Table 5 • 2 Cosmopolitan, 1 Manhattan</span>
                </div>
                <div class="text-[10px] text-blue-600 group-hover:text-blue-700">New</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-blue-100 text-blue-600 rounded flex items-center justify-center text-[8px]">3</div>
                   <span class="text-xs font-medium text-gray-700">Table 3 • 4 Negroni</span>
                </div>
                <div class="text-[10px] text-blue-600 group-hover:text-blue-700">New</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">15</div>
                   <span class="text-xs font-medium text-gray-700">Table 15 • 2 Gin & Tonic, 1 Aperol Spritz</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-gray-600">Pending</div>
             </div>
             <div class="flex items-center justify-between px-4 py-2 border-b border-gray-50 hover:bg-blue-50 cursor-pointer group">
                <div class="flex items-center gap-2">
                   <div class="w-4 h-4 bg-gray-200 rounded flex items-center justify-center text-[8px]">7</div>
                   <span class="text-xs font-medium text-gray-700">Table 7 • 3 Whiskey Sour</span>
                </div>
                <div class="text-[10px] text-gray-400 group-hover:text-gray-600">Pending</div>
             </div>
          </div>
        </div>

        <!-- Right Panel -->
        <div class="w-80 bg-white border-l border-gray-200 flex flex-col">
          <div class="p-3 border-b border-gray-100 flex justify-between items-center">
             <span class="text-[10px] font-bold text-gray-400 uppercase tracking-wider">Order Detail</span>
             <button class="text-[10px] border border-gray-200 rounded px-2 py-1 hover:bg-gray-50 flex items-center gap-1">
                <span>✓</span> Mark Complete
             </button>
          </div>
          
          <div class="p-4 flex-1 overflow-y-auto">
             <div class="text-[10px] font-bold text-gray-400 uppercase tracking-wider mb-2">Order Timeline</div>
             
             <!-- Timeline Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-gray-200">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-amber-400"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">In Progress</span>
                   <span class="text-[10px] text-gray-400">2 min ago</span>
                </div>
                <div class="text-[10px] text-gray-600">
                   Sarah started preparing drinks
                </div>
             </div>

             <!-- Timeline Item -->
             <div class="mb-4 relative pl-4 border-l-2 border-blue-500">
                <div class="absolute -left-[5px] top-0 w-2 h-2 rounded-full bg-blue-500"></div>
                <div class="flex justify-between items-start mb-1">
                   <span class="text-xs font-bold text-gray-900">Order Received</span>
                   <span class="text-[10px] text-gray-400">5 min ago</span>
                </div>
                <div class="text-[10px] text-gray-600 mb-2">
                   Server: Michael T. • Table 8
                </div>
                <span class="inline-block px-1.5 py-0.5 bg-blue-100 text-blue-700 text-[9px] rounded font-medium">Current Status</span>
             </div>

             <div class="mt-6 text-[10px] font-bold text-gray-400 uppercase tracking-wider mb-2">Order Items</div>
             
             <!-- Order Items -->
             <div class="space-y-2">
                <div class="bg-gray-50 rounded p-2">
                   <div class="flex justify-between items-start mb-1">
                      <span class="text-xs font-bold text-gray-900">3x Mojito</span>
                   </div>
                   <div class="text-[10px] text-gray-500">
                      Extra mint on 1
                   </div>
                </div>
                
                <div class="bg-gray-50 rounded p-2">
                   <div class="flex justify-between items-start mb-1">
                      <span class="text-xs font-bold text-gray-900">1x Espresso Martini</span>
                   </div>
                   <div class="text-[10px] text-gray-500">
                      No sugar rim
                   </div>
                </div>
             </div>
          </div>
          
          <div class="p-3 border-t border-gray-100 bg-gray-50 flex justify-between items-center">
             <div class="flex items-center gap-2 text-[10px] text-gray-500">
                <span>Table 8</span>
             </div>
             <div class="flex gap-2">
                <button class="bg-white border border-gray-200 text-gray-700 text-[10px] px-2 py-1 rounded hover:bg-gray-50">View Details</button>
                <button class="bg-black text-white text-[10px] px-2 py-1 rounded hover:bg-gray-800">Complete</button>
             </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Bottom Integration Info -->
    <div class="mt-12 flex items-center justify-center gap-4 bg-[#1E293B] rounded-lg p-4 max-w-4xl mx-auto border border-gray-700">
       <div class="flex items-center gap-4 border-r border-gray-600 pr-4">
          <div class="w-8 h-8 bg-white rounded flex items-center justify-center font-bold text-black text-xs">📱</div>
          <div class="w-8 h-8 bg-green-600 rounded flex items-center justify-center font-bold text-white text-xs">🖥️</div>
          <div class="w-8 h-8 bg-blue-600 rounded flex items-center justify-center font-bold text-white text-xs">📺</div>
       </div>
       <p class="text-xs text-gray-400 text-left flex-1">
          BarBoards works seamlessly across all your devices. Access order dashboards from tablets, phones, or dedicated display screens. Your entire team stays synchronized in real-time.
       </p>
       <button class="bg-black text-white px-3 py-1.5 rounded text-xs font-semibold hover:bg-gray-800">Get started</button>
    </div>
  </div>
</section>
