<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-sans font-bold mb-6">
				Intelligent agents that<br />
				transform your operations
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				From workflow automation to data analysis, our AI solutions deliver measurable results in weeks, not months.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Automate -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Automate Workflows</h3>
					<p class="text-gray-400 text-sm">Eliminate manual tasks and streamline operations</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <!-- Abstract representation of workflow -->
                         <div class="w-full h-full border border-white/5 rounded-lg bg-[#0a0a0a] p-6 relative">
                             <div class="absolute top-1/2 left-8 -translate-y-1/2 text-gray-500 text-sm font-mono">
                                 Building your workflow<br/>
                                 Viewing in canvas >
                             </div>
                             <!-- Lines/Nodes -->
                             <div class="absolute right-12 top-12 bottom-12 w-1/3 border-l border-white/5 dashed"></div>
                             <div class="absolute right-12 top-1/2 w-8 h-px bg-white/10"></div>
                             <div class="absolute right-4 top-1/2 w-8 h-8 rounded bg-white/5 border border-white/10"></div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Create -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Generate Insights</h3>
					<p class="text-gray-400 text-sm">Transform data into actionable business intelligence</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <!-- Top stats row -->
                    <div class="flex gap-4 mb-6">
                        <div class="bg-blue-500/10 p-4 rounded w-1/3 border border-blue-500/20">
                            <div class="text-xs text-blue-300 mb-1">Revenue</div>
                            <div class="text-xl font-bold text-blue-400">14% ↗</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Productivity</div>
                            <div class="text-xl font-bold text-white">64%</div>
                        </div>
                         <div class="bg-white/5 p-4 rounded w-1/3 border border-white/10">
                            <div class="text-xs text-gray-400 mb-1">Efficiency</div>
                            <div class="text-xl font-bold text-white">7%</div>
                        </div>
                    </div>
                    
                    <!-- Chart -->
                    <div class="flex-1 w-full relative mt-4">
                         <svg class="w-full h-full overflow-visible" viewBox="0 0 100 50" preserveAspectRatio="none">
                             <!-- Grid lines -->
                             <line x1="0" y1="10" x2="100" y2="10" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="25" x2="100" y2="25" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             <line x1="0" y1="40" x2="100" y2="40" stroke="#333" stroke-width="0.5" stroke-dasharray="2 2" />
                             
                             <!-- Lines -->
                             <path d="M0 45 C 20 40, 40 30, 60 25 S 80 15, 100 5" fill="none" stroke="#3b82f6" stroke-width="2" />
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30" fill="none" stroke="#10b981" stroke-width="2" />
                             
                             <!-- Area under curve (fake) -->
                             <path d="M0 48 C 20 45, 40 40, 60 38 S 80 35, 100 30 V 50 H 0 Z" fill="#10b981" fill-opacity="0.1" />
                         </svg>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Analyze -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Develop Solutions</h3>
					<p class="text-gray-400 text-sm">Build custom applications with AI-accelerated development</p>
				</div>
                
                 <!-- Mockup Content - Code Editor Look -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 font-mono text-[10px] leading-relaxed text-gray-400 shadow-inner">
                    <div class="flex gap-1.5 mb-4 border-b border-white/5 pb-2">
                        <div class="w-2 h-2 rounded-full bg-red-500/50"></div>
                        <div class="w-2 h-2 rounded-full bg-yellow-500/50"></div>
                        <div class="w-2 h-2 rounded-full bg-green-500/50"></div>
                    </div>
                    <div class="space-y-1">
                        <div class="text-purple-400">from <span class="text-white">future_import</span> import <span class="text-yellow-300">annotations</span></div>
                        <div class="text-purple-400">from <span class="text-white">typing</span> import <span class="text-yellow-300">List, Optional</span></div>
                        <br/>
                         <div class="text-purple-400">class <span class="text-yellow-300">DataAnalyzer</span>:</div>
                         <div class="pl-4 text-gray-600">"""Analyzer for processing large datasets"""</div>
                         <div class="pl-4 text-purple-400">def <span class="text-blue-400">__init__</span>(self, data: List[Any]):</div>
                         <div class="pl-8 text-white">self.data = data</div>
                         <div class="pl-8 text-white">self.processed = False</div>
                         <div class="pl-4 text-purple-400">def <span class="text-blue-400">analyze</span>(self):</div>
                         <div class="pl-8 text-white">if not self.data:</div>
                         <div class="pl-12 text-purple-400">return <span class="text-orange-400">None</span></div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Act -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Integrate Systems</h3>
					<p class="text-gray-400 text-sm">Connect ERPs, CRMs, and legacy systems seamlessly</p>
				</div>
                
                 <!-- Mockup Content - Action Card -->
                <div class="flex-1 relative flex items-center justify-center">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-xl p-5 w-full shadow-2xl relative">
                        <!-- Glow effect -->
                        <div class="absolute -inset-1 bg-gradient-to-r from-blue-500/20 to-purple-500/20 blur opacity-50"></div>
                        
                        <div class="relative bg-[#1a1a1a] rounded-xl">
                            <div class="flex items-center gap-3 mb-4">
                                <div class="w-8 h-8 rounded bg-white/10 flex items-center justify-center shrink-0">
                                    <div class="w-4 h-4 bg-white rotate-45"></div>
                                </div>
                                <div>
                                    <div class="font-medium text-xs text-white">Meeting with Vandelay Inc. finished</div>
                                    <div class="text-[10px] text-gray-500">Update Salesforce after meeting</div>
                                </div>
                            </div>
                            <div class="h-1.5 w-full bg-white/10 rounded-full overflow-hidden">
                                <div class="h-full bg-blue-500 w-2/3"></div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Card 5: Find -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Train Teams</h3>
					<p class="text-gray-400 text-sm">Knowledge transfer for autonomous AI use</p>
				</div>
                
                 <!-- Mockup Content - Search/Result -->
                <div class="flex-1 relative flex flex-col gap-4">
                    <div class="bg-[#1a1a1a] rounded-lg p-4 text-xs text-gray-300 border border-white/5">
                        Sure thing! Here's an overview I've made for you.
                    </div>
                    
                    <div class="flex-1 bg-gradient-to-br from-[#1a1a1a] to-black border border-white/10 rounded-lg overflow-hidden flex flex-col">
                         <div class="relative h-32 bg-gradient-to-r from-purple-500/20 to-blue-500/20 flex items-center justify-center">
                             <div class="text-center">
                                 <div class="text-xs font-semibold text-white">Personalized course</div>
                                 <div class="text-[10px] text-gray-400">8 cards</div>
                             </div>
                         </div>
                         <div class="p-4 flex items-center justify-between mt-auto">
                             <div class="text-[10px] text-gray-500">Updated 2m ago</div>
                             <button class="bg-white text-black text-[10px] font-bold px-3 py-1.5 rounded-full flex items-center gap-1 hover:bg-gray-200 transition-colors">
                                 <Play size={10} fill="currentColor" /> Play
                             </button>
                         </div>
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
