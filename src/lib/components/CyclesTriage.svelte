<section class="py-24 border-t border-white/5">
  <div class="max-w-[1200px] mx-auto px-6 grid grid-cols-1 md:grid-cols-2 gap-12">
    <!-- Practice Areas Card -->
    <div>
      <h3 class="text-2xl font-medium mb-3">Practice area analytics</h3>
      <p class="text-gray-400 mb-8">Track workload and performance across different practice areas and matter types.</p>
      
      <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[350px] relative overflow-hidden flex flex-col">
        <div class="flex items-center justify-between mb-6">
            <div class="flex items-center gap-2">
                <span class="text-white font-medium">Q4 2024</span>
            </div>
            <div class="flex items-center gap-4 text-xs">
                <div class="flex items-center gap-1.5 text-gray-400"><span class="w-1.5 h-1.5 rounded-full bg-gray-500"></span> M&A</div>
                <div class="flex items-center gap-1.5 text-primary-400"><span class="w-1.5 h-1.5 rounded-full bg-primary-500"></span> Litigation</div>
                <div class="flex items-center gap-1.5 text-secondary-400"><span class="w-1.5 h-1.5 rounded-full bg-secondary-500"></span> Compliance</div>
            </div>
        </div>
        
        <!-- Graph Mockup -->
        <div class="flex-1 relative w-full">
            <!-- Grid Lines -->
            <div class="absolute inset-0 flex flex-col justify-between pointer-events-none">
                <div class="w-full h-[1px] bg-white/5"></div>
                <div class="w-full h-[1px] bg-white/5"></div>
                <div class="w-full h-[1px] bg-white/5"></div>
                <div class="w-full h-[1px] bg-white/5"></div>
            </div>
            
            <!-- Lines -->
            <svg class="w-full h-full overflow-visible" preserveAspectRatio="none">
                <!-- M&A Line (Gray) -->
                <path d="M0,80 C50,80 100,75 150,70 C200,65 250,60 300,60 C350,60 400,60 450,60" fill="none" stroke="#6b7280" stroke-width="2" stroke-dasharray="4 4" />
                
                <!-- Litigation Line (Primary) -->
                <path d="M0,100 C50,90 100,80 150,60 C200,40 250,30 300,20 C350,15 400,10 450,5" fill="none" stroke="oklch(0.606 0.25 292.717)" stroke-width="2" />
                
                <!-- Compliance Line (Secondary) -->
                <path d="M0,100 C50,100 100,95 150,85 C200,75 250,60 300,40 C350,25 400,15 450,10" fill="none" stroke="oklch(0.696 0.17 162.48)" stroke-width="2" />
            </svg>
            
            <!-- Hover Effect (Vertical Line) -->
            <div class="absolute top-0 bottom-0 left-2/3 w-[1px] bg-white/20"></div>
            <div class="absolute top-[10%] left-2/3 -translate-x-1/2 w-2 h-2 bg-secondary-500 rounded-full ring-4 ring-black"></div>
            <div class="absolute top-[20%] left-2/3 -translate-x-1/2 w-2 h-2 bg-primary-500 rounded-full ring-4 ring-black"></div>
        </div>
      </div>
    </div>

    <!-- Matter Prioritization Card -->
    <div>
      <h3 class="text-2xl font-medium mb-3">Matter prioritization</h3>
      <p class="text-gray-400 mb-8">Review and prioritize incoming matters, client requests, and urgent legal work.</p>
      
      <div class="bg-[#0e1012] border border-white/10 rounded-xl p-6 h-[350px] relative overflow-hidden">
        <div class="text-sm font-medium text-white mb-4">New Matter Intake</div>
        
        <div class="bg-[#1a1c1e] border border-white/10 rounded-lg p-4 shadow-xl relative z-10">
            <div class="text-sm text-white mb-1">Urgent: Regulatory compliance inquiry</div>
            <div class="flex items-center gap-2 text-xs text-gray-500 mb-4">
                <span class="w-4 h-4 rounded-full bg-primary-500 flex items-center justify-center text-white text-[10px]">GC</span>
                <span>General Counsel - Acme Corp</span>
            </div>
            
            <div class="flex items-start gap-3 p-3 bg-white/5 rounded border border-white/5 mb-3">
                <div class="w-1 h-full bg-red-500 rounded-full"></div>
                <div class="text-xs text-gray-400">
                    <span class="text-red-400">Deadline:</span> 48 hours<br/>
                    SEC inquiry regarding Q3 financial disclosures
                </div>
            </div>
            
            <div class="text-xs text-gray-600 italic">Requires immediate review of 10-Q filing and supporting documentation...</div>
        </div>
        
        <!-- Action Menu Mockup -->
        <div class="absolute top-1/2 left-1/2 -translate-x-1/2 translate-y-10 bg-[#252729] border border-white/10 rounded-lg shadow-2xl p-1 w-48 z-20">
            <div class="flex items-center gap-2 px-2 py-1.5 hover:bg-white/10 rounded cursor-pointer text-xs text-white">
                <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M11.28 6.78a.75.75 0 0 0-1.06-1.06L7.25 8.69 5.78 7.22a.75.75 0 0 0-1.06 1.06l2 2a.75.75 0 0 0 1.06 0l3.5-3.5Z"/></svg>
                Assign to team
            </div>
             <div class="flex items-center gap-2 px-2 py-1.5 hover:bg-white/10 rounded cursor-pointer text-xs text-white">
                <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M8 1a1 1 0 0 1 1 1v2.586l1.707-1.707a1 1 0 0 1 1.414 1.414L10.414 6H13a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2.586l1.707 1.707a1 1 0 0 1-1.414 1.414L9 10.414V13a1 1 0 0 1-2 0v-2.586l-1.707 1.707a1 1 0 0 1-1.414-1.414L5.586 9H3a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h2.586L3.879 3.293a1 1 0 0 1 1.414-1.414L7 3.586V2a1 1 0 0 1 1-1z"/></svg>
                Use Harvey Assistant
            </div>
             <div class="flex items-center gap-2 px-2 py-1.5 hover:bg-white/10 rounded cursor-pointer text-xs text-white">
                <svg viewBox="0 0 16 16" class="w-3 h-3 fill-current"><path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.75.75 0 1 1 1.06 1.06L9.06 8l3.22 3.22a.75.75 0 1 1-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 0 1-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"/></svg>
                Refer out
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
