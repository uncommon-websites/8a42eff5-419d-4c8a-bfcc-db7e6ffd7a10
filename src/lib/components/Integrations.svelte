<script lang="ts">
    // Simple SVG paths for icons would be better, but for now using colored squares/circles to mimic brand colors
    const integrations = [
        { name: 'SAP', color: 'bg-blue-500' },
        { name: 'Salesforce', color: 'bg-blue-400' },
        { name: 'Microsoft 365', color: 'bg-orange-500' },
        { name: 'WhatsApp', color: 'bg-green-500' },
        { name: 'Gmail', color: 'bg-red-500' },
        { name: 'Outlook', color: 'bg-blue-500' },
        { name: 'PostgreSQL', color: 'bg-blue-600' },
        { name: 'Supabase', color: 'bg-green-600' },
        { name: 'OpenAI', color: 'bg-gray-700' },
        { name: 'Vercel', color: 'bg-black' },
        { name: 'GitHub', color: 'bg-white' },
        { name: 'Stripe', color: 'bg-purple-500' },
        { name: 'Zendesk', color: 'bg-green-400' },
        { name: 'HubSpot', color: 'bg-orange-500' },
        { name: 'Slack', color: 'bg-purple-500' },
        { name: 'Teams', color: 'bg-indigo-500' }
    ];

    const security = [
        'Row-level security', 'Secure authentication', 'Data encryption', 'Access control', 
        'Microsoft certified', 'GDPR compliant', 'Secure APIs', 'Data privacy', 
        'Audit trails', 'Role-based access', 'Secure deployment', 'Backup systems'
    ];
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6 text-center">
		<h2 class="text-4xl md:text-5xl lg:text-6xl font-sans font-bold mb-6">
			Connect everything,<br />
			secure by design
		</h2>
		<p class="text-gray-400 text-lg max-w-2xl mx-auto mb-20">
			Seamlessly integrate with your existing systems—from ERPs to CRMs to legacy databases—with enterprise-grade security.
		</p>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
            <!-- Integrations -->
			<div>
                <div class="inline-block bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Connect your business systems
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                    {#each integrations as tool}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-lg {tool.color} mb-3 flex items-center justify-center opacity-80 group-hover:opacity-100 transition-opacity">
                                <!-- Simple icon placeholder -->
                            </div> 
                            <span class="text-[10px] text-gray-400 font-medium">{tool.name}</span>
                        </div>
                    {/each}
                </div>
            </div>

            <!-- Security -->
			<div>
                <div class="inline-block bg-primary-600 text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Enterprise-grade security
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                     {#each security as item}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-full border border-white/20 mb-3 flex items-center justify-center text-white/50 group-hover:text-white transition-colors">
                                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                    <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>
                                </svg>
                            </div> 
                            <span class="text-[10px] text-gray-400 text-center leading-tight font-medium">{item}</span>
                        </div>
                    {/each}
                </div>
            </div>
		</div>
	</div>
</section>
