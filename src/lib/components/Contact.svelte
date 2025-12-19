<section class="w-full bg-white py-16 md:py-24" id="kontakt">
	<div class="mx-auto grid max-w-[1800px] grid-cols-1 gap-16 px-6 md:px-12 lg:grid-cols-2 lg:gap-24 lg:px-20">
		<!-- Left Column -->
		<div class="flex flex-col justify-between">
			<div>
				<h2 class="mb-8 text-3xl font-bold leading-tight tracking-tight text-black md:text-4xl">
					Gemeinsam Dein Projekt starten –<br />
					unverbindlich und kostenlos.
				</h2>
			</div>

			<div class="mt-12 lg:mt-auto">
				<p class="font-bold text-black">Bianca-Colette Riemer-Merkel</p>
				<p class="text-gray-600">Vertrieb Leitung</p>
				<a href="mailto:b.riemer-merkel@schumms.com" class="mt-1 block font-medium underline decoration-1 underline-offset-4 hover:decoration-2">
					b.riemer-merkel@schumms.com
				</a>
			</div>
		</div>

		<!-- Right Column: Form -->
		<div>
			<div class="mb-12 aspect-[4/3] w-full overflow-hidden bg-gray-100">
				<img
					src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=2576&auto=format&fit=crop"
					alt="Contact person"
					class="h-full w-full object-cover object-top filter grayscale"
				/>
			</div>

			<form class="flex flex-col gap-6">
				<div class="grid grid-cols-1 gap-6 md:grid-cols-2">
					<div class="flex flex-col gap-2">
						<label for="vorname" class="text-xs font-bold uppercase tracking-wider text-black">Vorname</label>
						<input type="text" id="vorname" placeholder="Vorname" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
					</div>
					<div class="flex flex-col gap-2">
						<label for="nachname" class="text-xs font-bold uppercase tracking-wider text-black">Nachname</label>
						<input type="text" id="nachname" placeholder="Nachname" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
					</div>
				</div>

				<div class="flex flex-col gap-2">
					<label for="email" class="text-xs font-bold uppercase tracking-wider text-black">E-Mail-Adresse</label>
					<input type="email" id="email" placeholder="E-Mail" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
				</div>

				<div class="flex flex-col gap-2">
					<label for="phone" class="text-xs font-bold uppercase tracking-wider text-black">Telefonnummer</label>
					<input type="tel" id="phone" placeholder="+49" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none" />
				</div>

				<div class="flex flex-col gap-2">
					<label for="message" class="text-xs font-bold uppercase tracking-wider text-black">Erzähl uns mehr über deine Anfrage.</label>
					<textarea id="message" rows="1" class="border-b border-gray-300 py-2 text-gray-900 placeholder-gray-400 focus:border-black focus:outline-none"></textarea>
				</div>

				<div class="mt-4 flex items-start gap-3">
					<input type="checkbox" id="privacy" class="mt-1 h-4 w-4 border-gray-300 text-black focus:ring-black" />
					<label for="privacy" class="text-xs leading-relaxed text-gray-600">
						Ich willige ein, dass meine Angaben und Daten zur Beantwortung meiner Anfrage elektronisch erhoben und verarbeitet werden. Die <a href="#" class="underline">Datenschutzerklärung</a> habe ich zur Kenntnis genommen.
					</label>
				</div>

				<button type="submit" class="mt-8 w-full bg-black py-4 px-8 text-center text-sm font-bold uppercase tracking-wider text-white transition-opacity hover:opacity-90">
					Kostenfrei beraten lassen
				</button>
			</form>
		</div>
	</div>
</section>
