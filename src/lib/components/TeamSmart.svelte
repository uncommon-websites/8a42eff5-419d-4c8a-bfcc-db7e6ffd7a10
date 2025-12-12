<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-sans font-bold mb-12 leading-tight">
					AI solutions for<br />
					every industry
				</h2>

				<div class="space-y-6">
					<div class="flex items-center gap-3 text-primary-400 font-medium">
						<div class="w-2 h-2 bg-primary-400 rounded-sm"></div>
						Manufacturing & Industrial
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8">
						Automate R&D analysis, modernize legacy systems, and optimize production workflows with AI agents that understand your processes.
					</p>

					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Consulting & Technology
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Financial Services
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Wellness & Healthcare
					</div>
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Operations & Logistics
					</div>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative">
                     <img src="/generated/image-confident-latin-american-operations-dire-1765563756325-1.webp" alt="Operations leader using AI" class="w-full h-full object-cover opacity-90" />
                     
                     <!-- Chat Input Overlay -->
                     <div class="absolute bottom-8 left-8 right-8 bg-white rounded-2xl p-2 shadow-2xl">
                         <div class="flex items-center gap-2 px-2 py-1">
                             <span class="text-black font-medium">Crea</span><span class="w-0.5 h-5 bg-black animate-pulse"></span>
                         </div>
                         <div class="flex justify-between items-center mt-2 px-2">
                             <div class="flex gap-4 text-gray-400">
                                 <Paperclip size={18} />
                                 <Image size={18} />
                                 <AtSign size={18} />
                                 <Smile size={18} />
                             </div>
                             <div class="w-8 h-8 bg-black rounded-full flex items-center justify-center text-white">
                                 <ArrowUp size={16} />
                             </div>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>
