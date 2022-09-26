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
		<div class="relative inline-block align-top bg-white rounded-lg text-left overflow-hidden shadow-xl transform transition-all sm:my-8 sm:align-middle sm:max-w-lg sm:w-full">
			<div class="bg-white px-4 pt-5 pb-4 sm:p-6 sm:pb-4">
				<div class="sm:flex sm:items-start">
					<div class="mt-3 px-3 sm:mt-0 sm:text-left">
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

							<div class="relative my-6">
								<div class="absolute inset-0 flex items-center" aria-hidden="true">
									<div class="w-full border-t border-gray-300"></div>
								</div>
								<div class="relative flex justify-">
									<span class="px-2 bg-white text-sm text-gray-500"></span>
								</div>
							</div>
							

							<div class="mt-3">
								<div class="mt-1 relative rounded-md shadow-sm">
									<div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
										<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5 text-gray-400">
											<path fill-rule="evenodd" d="M18.685 19.097A9.723 9.723 0 0021.75 12c0-5.385-4.365-9.75-9.75-9.75S2.25 6.615 2.25 12a9.723 9.723 0 003.065 7.097A9.716 9.716 0 0012 21.75a9.716 9.716 0 006.685-2.653zm-12.54-1.285A7.486 7.486 0 0112 15a7.486 7.486 0 015.855 2.812A8.224 8.224 0 0112 20.25a8.224 8.224 0 01-5.855-2.438zM15.75 9a3.75 3.75 0 11-7.5 0 3.75 3.75 0 017.5 0z" clip-rule="evenodd" />
										</svg>
									</div>
									<input type="text" name="name" id="name" class="border py-3 focus:ring-emerald-500 focus:border-emerald-500 block w-full pl-10 sm:text-sm border-gray-300 rounded-md" placeholder="John Smith">
								</div>
							</div>

							<div class="mt-3">
								<div class="mt-1 relative rounded-md shadow-sm">
									<div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
										<svg class="h-5 w-5 text-gray-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
											<path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z" />
											<path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z" />
										</svg>
									</div>
									<input type="email" name="email" id="email" class="border py-3 focus:ring-emerald-500 focus:border-emerald-500 block w-full pl-10 sm:text-sm border-gray-300 rounded-md" placeholder="you@example.com">
								</div>
							</div>

							<div class="mt-3 mb-3">
								<div class="mt-1 relative rounded-md shadow-sm">
									<div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
										<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-5 w-5 text-gray-400">
											<path fill-rule="evenodd" d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z" clip-rule="evenodd" />
										</svg>
									</div>
									<input type="tel" name="phone-number" id="phone-number" class="border py-3 focus:ring-emerald-500 focus:border-emerald-500 block w-full pl-10 sm:text-sm border-gray-300 rounded-md" placeholder="0759268860">
								</div>
							</div>

							
							<div class="flex items-center justify-evenly my-3">
								<div class="flex flex-col items-center gap-y-3">
									<span class="ml-3" id="annual-billing-label">
										<span class="text-sm font-medium text-gray-900">Booking For A Group? </span>
									</span>
									<!-- Enabled: "bg-indigo-600", Not Enabled: "bg-gray-200" -->
									<button type="button" class="bg-gray-200 relative inline-flex flex-shrink-0 h-6 w-11 border-2 border-transparent rounded-full cursor-pointer transition-colors ease-in-out duration-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500" role="switch" aria-checked="false" aria-labelledby="annual-billing-label">
										<!-- Enabled: "translate-x-5", Not Enabled: "translate-x-0" -->
										<span aria-hidden="true" class="translate-x-0 pointer-events-none inline-block h-5 w-5 rounded-full bg-white shadow transform ring-0 transition ease-in-out duration-200"></span>
									</button>
								</div>
	
								<div class="flex flex-col items-center gap-y-3">
									<span class="ml-3" id="annual-billing-label">
										<span class="text-sm font-medium text-gray-900">Home/ Site Visitation? </span>
									</span>
									<!-- Enabled: "bg-indigo-600", Not Enabled: "bg-gray-200" -->
									<button type="button" class="bg-gray-200 relative inline-flex flex-shrink-0 h-6 w-11 border-2 border-transparent rounded-full cursor-pointer transition-colors ease-in-out duration-200 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500" role="switch" aria-checked="false" aria-labelledby="annual-billing-label">
										<!-- Enabled: "translate-x-5", Not Enabled: "translate-x-0" -->
										<span aria-hidden="true" class="translate-x-0 pointer-events-none inline-block h-5 w-5 rounded-full bg-white shadow transform ring-0 transition ease-in-out duration-200"></span>
									</button>
								</div>
							</div>
							

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

