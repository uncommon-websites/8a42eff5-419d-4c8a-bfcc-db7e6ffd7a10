<script lang="ts">
	import { onMount } from 'svelte';
</script>

<section class="relative pt-32 pb-20 overflow-hidden bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="max-w-4xl">
			<h1 class="text-6xl md:text-7xl lg:text-[5.5rem] leading-[1.1] font-sans font-bold tracking-tight mb-8">
				Transform operations with <span class="text-primary-500">intelligent agents</span>
			</h1>

			<p class="text-xl text-gray-400 max-w-2xl mb-10 leading-relaxed font-light font-sans">
				Automate workflows and extract actionable insights from your data. 
				See results in 4 weeks with AI solutions built for Latin American enterprises.
			</p>

			<div class="flex flex-wrap gap-4 mb-20">
				<a href="#contact" class="bg-primary-600 hover:bg-primary-700 text-white px-8 py-4 rounded-full font-medium transition-colors text-base inline-block">
					Start a 4-week pilot
				</a>
				<a href="mailto:contacto@cunda.io" class="bg-white/10 hover:bg-white/20 border border-white/10 text-white px-8 py-4 rounded-full font-medium transition-colors text-base inline-block">
					Contact us
				</a>
			</div>
		</div>
	</div>

	<!-- Hero Image Container with Perspective -->
	<div class="relative w-full max-w-[1400px] mx-auto px-6 perspective-container">
		<div class="relative transform-3d hero-image-container origin-top opacity-90 hover:opacity-100 transition-opacity duration-700">
			<!-- Dashboard Mockup -->
			<div class="rounded-xl overflow-hidden border border-white/10 shadow-2xl bg-[#0a0a0a] aspect-[16/10] relative">
				<!-- Top bar -->
				<div class="h-10 bg-[#111] border-b border-white/5 flex items-center px-4 gap-2">
                    <div class="flex gap-2">
                        <div class="w-3 h-3 rounded-full bg-red-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500/20"></div>
                    </div>
                    <div class="mx-auto w-1/3 h-6 bg-white/5 rounded-md text-[10px] flex items-center justify-center text-gray-500 font-mono">
                        cunda.io/dashboard
                    </div>
				</div>
				<!-- Content Mockup -->
				<div class="flex h-full">
                    <!-- Sidebar -->
                    <div class="w-64 border-r border-white/5 bg-[#0f0f0f] p-4 hidden md:block">
                        <div class="space-y-4">
                            <div class="h-8 w-full bg-white/5 rounded"></div>
                            <div class="space-y-2 mt-8">
                                <div class="h-4 w-3/4 bg-white/5 rounded opacity-50"></div>
                                <div class="h-4 w-1/2 bg-white/5 rounded opacity-50"></div>
                                <div class="h-4 w-2/3 bg-white/5 rounded opacity-50"></div>
                            </div>
                        </div>
                    </div>
                    <!-- Main Content -->
                    <div class="flex-1 p-8 bg-[#0a0a0a]">
                        <div class="flex justify-between items-end mb-8">
                            <div>
                                <div class="h-10 w-64 bg-white/10 rounded mb-2"></div>
                                <div class="h-4 w-48 bg-white/5 rounded"></div>
                            </div>
                            <div class="h-10 w-32 bg-blue-500/20 rounded"></div>
                        </div>
                        
                        <div class="grid grid-cols-3 gap-6 mb-8">
                            <div class="bg-[#111] p-4 rounded-lg border border-white/5 h-32"></div>
                            <div class="bg-[#111] p-4 rounded-lg border border-white/5 h-32"></div>
                            <div class="bg-[#111] p-4 rounded-lg border border-white/5 h-32"></div>
                        </div>

                        <div class="bg-[#111] rounded-lg border border-white/5 h-64 w-full p-6 relative overflow-hidden">
                             <!-- Chart Mockup -->
                             <div class="absolute bottom-0 left-0 right-0 h-32 bg-gradient-to-t from-blue-500/10 to-transparent"></div>
                             <svg class="w-full h-full text-blue-500/50" viewBox="0 0 100 50" preserveAspectRatio="none">
                                 <path d="M0 50 L10 40 L20 45 L30 30 L40 35 L50 20 L60 25 L70 15 L80 20 L90 10 L100 5 V50 H0 Z" fill="currentColor" />
                             </svg>
                        </div>
                    </div>
                </div>

				<!-- Gradient Overlay -->
				<div class="absolute inset-0 bg-gradient-to-t from-black/40 via-transparent to-transparent pointer-events-none"></div>
			</div>
		</div>
	</div>
    
    <!-- Client Logos -->
    <div class="max-w-[1400px] mx-auto px-6 mt-20">
        <p class="text-center text-sm text-gray-500 mb-8 uppercase tracking-wider">Trusted by leading Chilean enterprises</p>
        <div class="flex flex-wrap justify-center md:justify-between items-center gap-8 opacity-50 grayscale hover:grayscale-0 transition-all duration-500">
            <span class="text-xl font-bold font-sans">Elecmetal</span>
            <span class="text-xl font-bold font-sans">Inforum</span>
            <span class="text-xl font-bold font-sans">BeeMagnetic</span>
            <span class="text-xl font-bold font-sans">Microsoft</span>
        </div>
    </div>
</section>

<style>
	.perspective-container {
		perspective: 2000px;
	}
	.transform-3d {
		transform: rotateX(20deg) scale(0.9);
        transform-style: preserve-3d;
	}
</style>
