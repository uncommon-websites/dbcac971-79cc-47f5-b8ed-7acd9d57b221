<script>
  const features = [
    "Real-time order tracking", "Kitchen-bar synchronization", "Digital menu updates", "Staff coordination tools", "Order priority flagging", "Table management",
    "Inventory tracking", "Low stock alerts", "Supplier management", "Recipe management", "Prep time tracking", "Order analytics",
    "Complete order history", "Staff messaging", "Special request notes", "POS integration", "Multi-station displays", "Mobile access",
    "Seasonal menu switching", "Version history", "Instant menu changes", "Category organization", "Drag-and-drop ordering", "Custom drink fields",
    "Order modification tracking", "Service time analytics", "Peak hour optimization", "Staff performance metrics", "Customer wait time tracking", "VIP table flagging",
    "Automated reordering", "Supplier portal access", "Stock level monitoring", "Ingredient tracking", "Waste reduction analytics", "Cost management",
    "Team permissions", "Role-based access", "Shift scheduling", "Multi-location support", "Cloud backup", "Offline mode",
    "Drink popularity tracking", "Sales analytics", "Revenue reporting", "Inventory cost tracking", "Profit margin analysis", "Export reports",
    "Touch-screen optimized", "Tablet support", "Phone notifications", "Display board management", "Custom color coding", "Sound alerts",
    "Recipe consistency", "Bartender notes", "Training mode", "Onboarding tools", "Help documentation", "24/7 support"
  ];
</script>

<section class="pt-24 pb-12 bg-white text-center overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-6">
    <h2 class="text-5xl font-bold mb-16 tracking-tight text-gray-900 leading-tight">
      ...And Much,<br>Much More.
    </h2>

    <div class="flex flex-wrap justify-center gap-x-4 gap-y-3 text-xs text-gray-400 max-w-6xl mx-auto mb-32 opacity-70">
       {#each features as feature}
         <span class="hover:text-gray-900 transition-colors cursor-default">{feature}</span>
         <span class="text-gray-300">•</span>
       {/each}
    </div>

    <!-- CTA Section -->
    <div class="max-w-2xl mx-auto mb-24">
       <!-- Device Image Placeholder -->
       <div class="w-64 h-64 mx-auto mb-8 bg-gray-100 rounded-3xl shadow-2xl flex items-center justify-center relative border-4 border-gray-200">
          <div class="absolute inset-2 bg-gray-800 rounded-2xl flex flex-col items-center justify-center overflow-hidden">
             <!-- Screen -->
             <div class="w-full h-1/2 bg-black flex items-center justify-center border-b border-gray-700">
                <span class="text-4xl">✌️</span>
             </div>
             <!-- Keys -->
             <div class="w-full h-1/2 grid grid-cols-3 gap-1 p-2 bg-gray-700">
                <div class="bg-orange-500 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
             </div>
          </div>
       </div>
       
       <p class="text-lg text-gray-600 mb-8 leading-relaxed">
          Ready to transform your bar operations and deliver faster, better service? Get started with BarBoards today.
       </p>
       <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm">
          Get started
       </button>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-[#0B0F19] text-white py-12 border-t border-gray-800">
     <div class="max-w-[1200px] mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
        <div class="flex items-center gap-2">
           <div class="w-5 h-5 bg-white text-black rounded flex items-center justify-center">
              <svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <rect x="3" y="3" width="18" height="18" rx="2" stroke="currentColor" stroke-width="2"/>
                  <line x1="3" y1="9" x2="21" y2="9" stroke="currentColor" stroke-width="2"/>
                  <line x1="9" y1="9" x2="9" y2="21" stroke="currentColor" stroke-width="2"/>
              </svg>
           </div>
           <span class="font-bold text-sm">BarBoards © 2025</span>
           <span class="text-gray-500 text-xs ml-2">Built for hospitality professionals</span>
        </div>
        
        <div class="flex items-center gap-6 text-xs text-gray-400">
           <a href="#" class="hover:text-white">Sign in</a>
           <a href="#" class="hover:text-white">Get started</a>
           <a href="#" class="hover:text-white">Terms</a>
           <a href="#" class="hover:text-white">Privacy</a>
           <a href="#" class="hover:text-white">Twitter</a>
        </div>
     </div>
  </footer>
</section>
