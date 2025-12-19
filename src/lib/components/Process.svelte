<section class="w-full bg-white py-16 md:py-24">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-16 px-6 md:px-12 lg:grid-cols-2 lg:gap-24 lg:px-20">
		<!-- Left Column -->
		<div class="flex flex-col justify-between">
			<div>
				<h2 class="mb-8 text-4xl font-bold leading-tight tracking-tight text-black md:text-5xl lg:text-6xl">
					Wir machen komplexe<br />
					Bürogestaltung einfach.
				</h2>
				<p class="mb-8 max-w-md text-lg leading-relaxed text-gray-800">
					Mit unserem Gestaltungsprozess begleiten wir dich Schritt für Schritt in die Zukunft.
				</p>
				<a href="#" class="text-lg font-medium text-black underline decoration-1 underline-offset-4 hover:decoration-2">
					One Pager herunterladen
				</a>
			</div>
		</div>

		<!-- Right Column: Steps -->
		<div>
			<div class="flex flex-col">
				{#each [
					{ id: 1, title: 'Space & Selection' },
					{ id: 2, title: 'Consulting & Workshops' },
					{ id: 3, title: 'Concept & Planning' },
					{ id: 4, title: 'Consulting & Construction' },
					{ id: 5, title: 'Furniture Advisor' },
					{ id: 6, title: 'Ongoing Support' }
				] as step}
					<div class="group flex cursor-pointer items-center justify-between border-b border-gray-200 py-6 transition-colors hover:bg-gray-50">
						<div class="flex items-center gap-6">
							<div class="flex h-8 w-8 items-center justify-center rounded-full bg-black text-sm font-bold text-white">
								{step.id}
							</div>
							<span class="text-xl font-medium text-gray-900">{step.title}</span>
						</div>
						<svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" class="text-gray-400 transition-transform group-hover:rotate-90 group-hover:text-black">
							<line x1="12" y1="5" x2="12" y2="19"></line>
							<line x1="5" y1="12" x2="19" y2="12"></line>
						</svg>
					</div>
				{/each}
			</div>

			<div class="mt-12">
				<button class="w-full bg-black py-4 px-8 text-center text-sm font-bold uppercase tracking-wider text-white transition-opacity hover:opacity-90 md:w-auto">
					Kostenfrei beraten lassen
				</button>
			</div>
		</div>
	</div>
</section>
