<svelte:head>
    <meta name="author" content="Stemax Consult Services">
    <meta name="description" content="We specialise in providing occupational and environmental health services to businesses and we also run an outpatient day care clinic catering towards individuals.">
    <meta property="og:image" content="/favicon.png" />
    <title>Stemax Healthcare Consultancy & Clinic</title>
</svelte:head>
<script>
    const services = [
        {
            image: "https://images.unsplash.com/photo-1612278247079-6a0af8ff2dee",
            title: "Vaccinations",
            services: 16,
            description: "To help your body develop immunity from a disease. Most often ordered when travelling abroad.",
            link: "/vaccination"
        },
        {
            image: "https://images.unsplash.com/photo-1542884748-2b87b36c6b90?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80",
            title: "Occupational Health",
            services: 32,
            description: "The goal of an occupational safety and health program is to foster a safe and healthy work environment."
        },
        {
            image: "https://images.unsplash.com/photo-1626697556342-2310dbc55428?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80",
            title: "Environmental & Nutritional Health",
            services: 10,
            description: "A physician will diagnose and advise you on matters of food and nutrition and their impacts on your health."
        },
        {
            image: "https://images.unsplash.com/photo-1639772823849-6efbd173043c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80",
            title: "Blood Tests",
            services: 24,
            description: "Find and understand your disease, vitamin content, pharmaceutical drug effectiveness and organ function."
        },
        {
            image: "https://images.unsplash.com/photo-1585842378054-ee2e52f94ba2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1632&q=80",
            title: "Functional Diagnostic Testing",
            services: 8,
            description: "Many signs and symptoms of disease are nonspecific. These tests help to get you the right diagnosis."
        },
        {
            image: "https://images.unsplash.com/photo-1576670262660-05cf76d53da3",
            title: "Genova Genetic, Allergy & Antibody Testing",
            services: 34,
            description: "Clinical laboratory services for the prevention, diagnosis and treatment of complex chronic diseases."
        },

    ]
</script>

<div class="">
	<div class="max-w-2xl lg:max-w-7xl mx-auto pt-6 px-4 sm:py-6 sm:px-6 lg:px-8">
		<div class="relative rounded-lg overflow-hidden">
			<div class="absolute inset-0">
				<img src="map.png" alt="" class="w-full h-full object-center object-cover">
			</div>
			<div class="relative bg-gray-900 bg-opacity-75 py-16 px-6 sm:py-16 sm:px-12 lg:px-16">
				<div class="relative max-w-3xl mx-auto flex flex-col items-center text-center">
					<h2 class="text-3xl font-extrabold tracking-tight text-white sm:text-4xl">
                        <span class="hidden text-xl tracking-wider sm:inline lg:block">Healthcare Consultancy</span>
                        <span class="block sm:inline">Based in</span>
						<span class="block sm:inline underline">Milton Keynes</span>
					</h2>
					<p class="mt-3 text-xl text-white">
                        Unit F, Old Stratford Business Park
                        Falcon Drive, Old Stratford
                        Milton Keynes
                        MK19 6FG</p>
					<a target="_blank" href="https://www.google.com/maps/dir//Old+Stratford+Business+Park,+Falcon+Dr,+Old+Stratford,+Milton+Keynes+MK19+6FG,+UK/@52.066276,-0.869368,679m/data=!3m1!1e3!4m17!1m7!3m6!1s0x4877017de09987bb:0x59f55bb389577615!2sOld+Stratford+Business+Park,+Falcon+Dr,+Old+Stratford,+Milton+Keynes+MK19+6FG,+UK!3b1!8m2!3d52.066247!4d-0.8674838!4m8!1m0!1m5!1m1!1s0x4877017de09987bb:0x59f55bb389577615!2m2!1d-0.8674838!2d52.066247!3e3?hl=en-US" class="mt-8 w-full block bg-emerald-500 border border-transparent rounded py-3 px-8 text-base font-medium text-white hover:bg-emerald-800 sm:w-auto">Navigate Google Maps</a>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="">
	<div class="max-w-2xl mx-auto py-6 px-4 sm:px-6 lg:max-w-7xl lg:px-8">
        <div class="mx-1 pb-5 border-b border-gray-200">
            <h3 class="text-lg leading-6 font-medium text-gray-900">120+ Healthcare Services Offered</h3>
            <p class="mt-2 text-sm text-gray-500">Though we specialise in providing occupational and environmental health services to businesses and we also run an outpatient day care clinic catering towards individuals.</p>
        </div>
        <div class="grid grid-cols-1 gap-y-4 sm:grid-cols-2 sm:gap-x-6 sm:gap-y-10 lg:grid-cols-3 lg:gap-x-8 pt-6">
            {#each services as service}
			<div class="group relative bg-white border border-gray-200 rounded-lg flex flex-col overflow-hidden hover:bg-emerald-50 hover:border-gray-300">
                <div class="aspect-w-3 aspect-h-4 bg-gray-200 sm:aspect-none h-24">
                    <img src="{service.image}" alt="" class="w-full h-full object-center object-cover sm:w-full sm:h-full -z-20">
                </div>
                <div class="flex-1 p-4 space-y-2 flex flex-col">
                    <div class="flex-1 flex flex-col justify-end">
                        <p class="text-base font-medium text-gray-900">{service.title}</p>
                    </div>
					<div class="text-sm font-medium text-gray-900">
                        <a href="{service.link}">
                            <span aria-hidden="true" class="absolute inset-0"></span>
                            <p class="text-sm italic text-emerald-800 ">{service.services.toString()} Services</p>
							
						</a>
					</div>
					<p class="text-sm text-gray-500">{service.description}</p>
				</div>
                
			</div>
            {/each}
		</div>
	</div>
</div>

<div class="">
	<div class="max-w-2xl lg:max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
        <div class="mx-1 pb-5 border-b border-gray-200">
            <h3 class="text-lg leading-6 font-medium text-gray-900">Notable Clients</h3>
            <p class="mt-2 max-w-4xl text-sm text-gray-500">All these companies trust us, so hopefully you can too.</p>
        </div>
		<div class="mx-1 grid grid-cols-1 gap-8 lg:grid-cols-7 py-12">
			<div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/tuple-logo-gray-400.svg" alt="Tuple">
			</div>
			<div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/mirage-logo-gray-400.svg" alt="Mirage">
			</div>
			<div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/statickit-logo-gray-400.svg" alt="StaticKit">
			</div>
			<div class="col-span-1 flex justify-center md:col-span-3 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/transistor-logo-gray-400.svg" alt="Transistor">
			</div>
			<div class="col-span-1 flex justify-center md:col-span-3 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/workcation-logo-gray-400.svg" alt="Workcation">
			</div>
            <div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/tuple-logo-gray-400.svg" alt="Tuple">
			</div>
			<div class="col-span-1 flex justify-center md:col-span-2 lg:col-span-1">
				<img class="h-12 brightness-200 invert hover:opacity-50" src="https://tailwindui.com/img/logos/mirage-logo-gray-400.svg" alt="Mirage">
			</div>
		</div>
	</div>
</div>

<div class="">
	<div class="max-w-2xl lg:max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
        <div class="space-y-4 sm:grid sm:grid-cols-3 sm:items-start sm:gap-6 sm:space-y-0 pt-6">
            <div class="aspect-w-3 aspect-h-2 sm:aspect-w-1 sm:aspect-h-4">
                <img class="object-cover shadow-3xl rounded-lg" src="ijeh.jpg" alt="">
            </div>
            <div class="sm:col-span-2">
                <div class="space-y-4">
                    <div class="text-lg leading-6 font-medium space-y-1">
                        <h3>Dr. Cyprel Ijeh</h3>
                        <p class="text-emerald-600">Lead Consultant</p>
                    </div>
                    <div class="text-lg">
                        <p class="text-gray-500">Dr Cyprel Ijeh is a GMC and Swedish Medical Council (Socialstyrelsen) registered practitioner.</p>
                        <p class="pt-5 text-gray-500">He has a huge amount of experience in treating Lyme, mould toxicity, heavy metal toxicity, multiple chemical sensitivity among many other complex illnesses related to ones interaction with the environment.</p>
                        <p class="pt-5 text-gray-500">He specialises in using both a conventional and integrative functional medicine approach.</p>
                        <p class="pt-5 text-gray-500">A fellow of the Royal Society of Public health, Chartered Management Institute and WHO Collaborating centre for Advocacy and Training in Pharmacovigilance. A member of British Medical Association, British Society for Ecological Medicine (BSEM), World Medical Association and The British Toxicology Society.</p>
                    </div>
                    <ul class="flex space-x-5">
                        <li>
                            <a target="_blank" href="/" class="text-gray-400 hover:text-gray-500">
                                <span class="sr-only">Twitter</span>
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                                    <path d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84" />
                                </svg>
                            </a>
                        </li>
                        <li>
                            <a target="_blank" href="/" class="text-gray-400 hover:text-gray-500">
                                <span class="sr-only">LinkedIn</span>
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" aria-hidden="true">
                                    <path fill-rule="evenodd" d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z" clip-rule="evenodd" />
                                </svg>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
	</div>
</div>