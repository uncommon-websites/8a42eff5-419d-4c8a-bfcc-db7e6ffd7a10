<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
            <!-- UI Mockup -->
			<div class="bg-[#0f0f0f] rounded-xl p-12 border border-white/5 relative overflow-hidden h-[600px] flex items-center justify-center">
                <div class="w-full max-w-sm bg-white rounded-xl shadow-2xl overflow-hidden text-black">
                    <div class="p-2 border-b border-gray-100 flex justify-between items-center">
                        <div class="flex items-center gap-2 px-2">
                            <div class="w-4 h-4 rounded-full bg-gray-200"></div>
                            <span class="text-sm font-medium">Auto</span>
                        </div>
                        <div class="text-xs text-gray-400 px-2">Auto</div>
                    </div>
                    
                    <div class="p-2">
                        <div class="flex items-start gap-3 p-3 bg-gray-50 rounded-lg mb-1">
                            <div class="w-4 h-4 rounded-full border border-gray-300 mt-1 flex items-center justify-center">
                                <div class="w-2 h-2 bg-black rounded-full"></div>
                            </div>
                            <div>
                                <div class="text-sm font-medium">Auto</div>
                                <div class="text-xs text-gray-500">The most suitable model for the job</div>
                            </div>
                            <Check size={16} class="ml-auto text-black" />
                        </div>

                        <div class="flex items-start gap-3 p-3 hover:bg-gray-50 rounded-lg mb-1 opacity-50">
                            <div class="w-4 h-4 rounded-full border border-gray-300 mt-1"></div>
                            <div>
                                <div class="text-sm font-medium">GPT-4</div>
                                <div class="text-xs text-gray-500">Flagship GPT model for complex tasks</div>
                            </div>
                        </div>

                        <div class="flex items-start gap-3 p-3 hover:bg-gray-50 rounded-lg mb-1 opacity-50">
                            <div class="w-4 h-4 rounded-full border border-gray-300 mt-1"></div>
                            <div>
                                <div class="text-sm font-medium">Claude Sonnet 3.5</div>
                                <div class="text-xs text-gray-500">Anthropic's flagship model, industry-leading for coding tasks</div>
                            </div>
                        </div>
                        
                         <div class="flex items-start gap-3 p-3 hover:bg-gray-50 rounded-lg mb-1 opacity-50">
                            <div class="w-4 h-4 rounded-full border border-gray-300 mt-1"></div>
                            <div>
                                <div class="text-sm font-medium">Claude Haiku 3.5</div>
                                <div class="text-xs text-gray-500">Fast responses with near-frontier intelligence</div>
                            </div>
                        </div>

                         <div class="flex items-start gap-3 p-3 hover:bg-gray-50 rounded-lg opacity-50">
                            <div class="w-4 h-4 rounded-full border border-gray-300 mt-1"></div>
                            <div>
                                <div class="text-sm font-medium">GPT-4o mini</div>
                                <div class="text-xs text-gray-500">Balanced for speed and cost efficiency</div>
                            </div>
                        </div>
                    </div>
                </div>
			</div>

            <!-- Text Content -->
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-sans font-bold mb-6 leading-tight">
					Flexible AI models<br />
					for every use case
				</h2>
				<p class="text-gray-400 text-lg max-w-md">
					We leverage the best AI models for each task—from OpenAI to Claude—ensuring optimal performance and cost efficiency.
				</p>
			</div>
		</div>
	</div>
</section>
