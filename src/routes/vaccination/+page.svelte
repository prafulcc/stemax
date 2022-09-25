<svelte:head>
    <meta name="author" content="Stemax Consult Services">
    <meta name="description" content="To help your body develop immunity from a disease. Most often ordered when travelling abroad.">
    <meta property="og:image" content="/favicon.png" />
    <title>Vaccinations - Stemax Healthcare Consultancy & Clinic</title>
</svelte:head>

<script>
    const services = [
        {
            link: "/vaccination/hepatitis-b",
            title: "Hepatitis B",
            price: 55,
            description: "3 doses at 0, 1 and 6 months. Booster required every 5 years, only if exposure continued"
        },
        {

            title: "Measles, Mumps and Rubella (MMR)",
            price: 70,
            description: "2 doses provides protection for life."
        },
        {
            
            title: "Varicella (Chicken Pox)",
            price: 70,
            description: "2 doses provides protection for life."
        },
        {
            
            title: "Mantoux (Skin) Test & Reading",
            price: 70,
            description: "Initial testing, then come in for a reading 72 hours later."
        },
        {
            
            title: "BCG Tuberculosis",
            price: 45,
            description: "1 dose provides protection for life."
        },
        {
            
            title: "BCG Tuberculosis Scar Check",
            price: 35,
            description: "Taking a formal vaccination history and physically inspecting the arm for a scar to verify that person has received the BCG Tuberculosis vaccination. "
        },
        {
            
            title: "Single Broad Immune Booster",
            price: 150,
            description: "Amino Acids, B Vitamins, Magnesium, Selenium, Glutathione and Vitamin C. Dosed as Required."
        },
        {
            
            title: "Multiple Broad Immune Booster",
            price: 650,
            description: "(5 Sessions) Amino Acids, B Vitamins, Magnesium, Selenium, Glutathione and Vitamin C. Dosed as Required."
        },
        {
            
            title: "10g Vitamin C & 600mg Glutathione",
            price: 110,
            description: ""
        },
        {
            
            title: "1200mg Glutathione Only",
            price: 80,
            description: ""
        },
        {
            
            title: "Myers Cocktail",
            price: 170,
            description: ""
        },
        {
            
            title: "5mg or 1ml Vitamin B12 ",
            price: 40,
            description: "(Methylcobalamin)"
        },

    ]
</script>

<div class="bg-white">
	<div class="max-w-2xl mx-auto py-6 px-4 sm:px-6 lg:max-w-7xl lg:px-8">
        <div class="mx-1 pb-5 border-b border-gray-200">
            <h3 class="text-lg leading-6 font-medium text-gray-900">12 Vaccine Services Offered</h3>
            <p class="mt-2 text-sm text-gray-500">To help your body develop immunity from a disease. Most often ordered when travelling abroad.</p>
        </div>
        <div class="grid grid-cols-1 gap-y-4 sm:grid-cols-2 sm:gap-x-6 sm:gap-y-10 lg:grid-cols-3 lg:gap-x-8 pt-6">
            {#each services as service}
			<div class="group relative bg-white border border-gray-200 rounded-lg flex flex-col overflow-hidden hover:bg-emerald-50 hover:border-gray-300">
                <!-- <div class="aspect-w-3 aspect-h-4 bg-gray-200 sm:aspect-none h-6">
                    <img src="{service.image}" alt="" class="w-full h-full object-center object-cover sm:w-full sm:h-full -z-20">
                </div> -->
                <div class="flex-1 p-4 space-y-2 flex flex-col">
                    <a href="{service.link}" class="flex flex-row justify-between">
                        <p class="text-base font-medium text-gray-900">{service.title}</p>
                        <span class="inline-flex items-center px-2.5 py-0.5 rounded-2xl text-sm font-medium bg-green-100 text-green-800">£{service.price.toString()} </span>	
                    </a>
                    <p class="text-sm text-gray-500">{service.description}</p>
				</div>
                
                
                
			</div>
            {/each}
		</div>
	</div>
</div>