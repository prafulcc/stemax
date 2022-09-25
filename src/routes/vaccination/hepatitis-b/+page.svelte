<svelte:head>
    <meta name="author" content="Stemax Consult Services">
    <meta name="description" content="Hepatitis B is a type of hepatitis, a viral infection not usually transmitted via contaminated water but rather via bodily fluids.">
    <meta property="og:image" content="/favicon.png" />
    <title>Hepatitis B Vaccination - Stemax Healthcare Consultancy & Clinic</title>
</svelte:head>

<script>
	let shown = false;
</script>

<div class="py-16 xl:py-36 px-4 sm:px-6 lg:px-8 bg-white overflow-hidden">
	<div class="max-w-max lg:max-w-7xl mx-auto">
		<div class="relative z-10 mb-8 md:mb-2 md:px-6">
			<div class="text-base max-w-prose lg:max-w-none">
				<h2 class="leading-6 text-emerald-600 font-semibold tracking-wide uppercase">Vaccinations</h2>
				<p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Hepatitis B</p>
			</div>
		</div>
		<div class="relative">
			<div class="relative md:bg-white md:p-6">
				<div class="lg:grid lg:grid-cols-2 lg:gap-12">
					<div class="prose prose-emerald prose-lg text-gray-500 lg:max-w-none">
						<p>Hepatitis B is a type of hepatitis, a viral infection which can cause damage to the liver. Unlike hepatitis A, the hepatitis B virus is not usually transmitted via contaminated water but rather via bodily fluids such as blood or via contaminated needles.</p>
						<br>
						<p>Possible hepatitis B symptoms are feeling or being sick, rash, joint pain, loss of appetite, tiemeraldness and headache as well as flu-like symptoms. Some patients also develop a yellowing of skin and eyes, which is called jaundice. The infection can persist for a long time and become chronic hepatitis B, resulting in liver cancer, damage and failure.</p>
					</div>
					<div class="mt-6 flex lg:justify-center text-xs">
						<div class="bg-emerald-50 overflow-hidden rounded border border-emerald-900 w-80 h-36">
							<div class="px-5 py-4 text-emerald-900">
								<h3 class="font-bold ">Price Guide</h3>
								<ul class="list-disc px-8 py-4">
									<li>3 doses required.</li>
									<li>£55 per dose administered at the clinic.</li>
									<li>£60 per dose administered at your home or business.</li>
								</ul>
							</div>
						</div>
					</div>
				</div>
				<div on:click={() => shown = true } class="mt-8 inline-flex rounded-md shadow">
					<span class="flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-white bg-emerald-600 hover:bg-emerald-700"> Book Appointment </span>
				</div>
			</div>
		</div>
	</div>
</div>
<div class="bg-gray-50">
	<div class="max-w-7xl mx-auto py-12 px-4 divide-y divide-gray-200 sm:px-6 lg:py-16 lg:px-8">
		<h2 class="text-3xl font-extrabold text-gray-900">Frequently asked questions</h2>
		<div class="mt-8">
			<dl class="divide-y divide-gray-200">

				<div class="pt-6 pb-8 md:grid md:grid-cols-12 md:gap-8">
					<dt class="text-base font-medium text-gray-900 md:col-span-5">When would I need a vaccination?</dt>
					<dd class="mt-2 md:mt-0 md:col-span-7">
						<p class="text-base text-gray-500">Hepatitis B occurs in all parts of the world. In some areas, however, there is an increased risk due to the infection being widespread.</p>
						<br>
						<p class="text-base text-gray-500">Hepatitis B risk areas include parts of eastern Europe, Africa, South and Central America, South East Asia, Russia, India, China as well as some South Pacific Islands.</p>
						<br>
						<p class="text-base text-gray-500">Those thought to have a continued high risk of infection should consider having a booster after 5 years. Boosters may be needed after exposure to the infection. If you think you have been exposed to hepatitis B please seek medical attention urgently.</p>
						<br>
						<p class="text-base text-gray-500">If you are planning to travel to any of these destinations, your travel nurse can advise on whether you require a hepatitis B vaccine. </p>
					</dd>
				</div>

				<div class="pt-6 pb-8 md:grid md:grid-cols-12 md:gap-8">
					<dt class="text-base font-medium text-gray-900 md:col-span-5">Do I need a booster?</dt>
					<dd class="mt-2 md:mt-0 md:col-span-7">
						<p class="text-base text-gray-500">Only if you’re at high risk of contracting Hepatitis B, or continually exposed to the pathogen.</p>
						<br>
						<p class="text-base text-gray-500">You may then only need a booster jab 5 years after primary immunisation.</p>
					</dd>
				</div>

				<div class="pt-6 pb-8 md:grid md:grid-cols-12 md:gap-8">
					<dt class="text-base font-medium text-gray-900 md:col-span-5">Age Restrictions</dt>
					<dd class="mt-2 md:mt-0 md:col-span-7">
						<p class="text-base text-gray-500">No age restrictions. Can be given at birth, if deemed necessary.</p>
					</dd>
				</div>
				
			</dl>
		</div>
	</div>
</div>

<div hidden={!shown} class="fixed z-10 inset-0 overflow-y-auto" aria-labelledby="modal-title" role="dialog" aria-modal="true">
	<div class="flex items-end justify-center min-h-screen pt-4 px-4 pb-20 text-center sm:block sm:p-0">
		<div class="fixed inset-0 bg-emerald-900 bg-opacity-75 transition-opacity" aria-hidden="true"></div>
		<!-- <span class="hidden sm:inline-block sm:align-middle sm:h-screen" aria-hidden="true">&#8203;</span> -->

		<div class="relative inline-block align-bottom bg-white rounded-lg text-left overflow-hidden shadow-xl transform transition-all sm:my-8 sm:align-middle sm:max-w-lg sm:w-full">
			<div class="bg-white px-4 pt-5 pb-4 sm:p-6 sm:pb-4">
				<div class="sm:flex sm:items-start">
					<div class="mt-3 px-3 sm:mt-0 sm:ml-4 sm:text-left">
						<h3 class="text-lg leading-6 font-medium text-gray-900" id="modal-title">Book Hepatitis B Vaccination</h3>
						<div class="mt-2">
							<p class="text-sm text-gray-500 list-disc">
									<li>3 doses required.</li>
									<li>£55 per dose administered at the clinic.</li>
									<li>£60 per dose administered at your home or business.</li>
							</p>
							<br>
							<p class="text-sm text-gray-500">
								A link to book will be emailed to you and an SMS reminder will be sent 24 hours before your appointment.
							</p>
						</div>
					</div>
				</div>
			</div>
			<div class="bg-gray-100 px-4 py-3 sm:px-6 sm:flex sm:flex-row-reverse">
				<button type="button" class="w-full inline-flex justify-center rounded-md border border-transparent shadow-sm px-4 py-2 bg-emerald-600 text-base font-medium text-white hover:bg-emerald-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-emerald-500 sm:ml-3 sm:w-auto sm:text-sm">Submit</button>
				<button on:click={() => shown = false } type="button" class="mt-3 w-full inline-flex justify-center rounded-md border border-gray-300 shadow-sm px-4 py-2 bg-white text-base font-medium text-gray-700 hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-emerald-500 sm:mt-0 sm:ml-3 sm:w-auto sm:text-sm">Cancel</button>
			</div>
		</div>
	</div>
</div>

