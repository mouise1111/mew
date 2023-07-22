<script></script>

<nav class="flex flex-row items-center justify-between px-64 py-8 text-2xl text-blue-900">
	<div>
		<h1 class="font-extrabold text-black">Mew</h1>
	</div>
	<div class="flex flex-row gap-16">
		<a href="#home">Home</a>
		<a href="#About">About</a>
		<a href="#services">Services</a>
		<a href="#Facilties">Facilties</a>
	</div>
	<div>
		<button
			class="px-8 py-4 transition-transform border-2 border-blue-900 rounded-2xl hover:bg-blue-800 hover:text-white"
		>
			<a href="#Contact">Contact</a>
		</button>
	</div>
</nav>

<section class="py-32">
	<img src="/paw.png" alt="paw icon of a dog" id="paw-image" />
	<img src="/star.png" alt="star icon" id="star-image" />
	<img src="/rings.png" alt="ring design for dierenkliniek" id="rings-image" />
	<div class="flex flex-row gap-x-32">
		<div class="relative">
			<img src="/cathero.png" alt="" class="border-4 border-l-0 border-white rounded-3xl" />
			<img src="/doghero.png" alt="" class="border-4 border-white rounded-3xl" id="doghero" />
		</div>
		<div class="flex flex-col justify-center w-2/4 gap-16">
			<h1 class="text-6xl font-bold text-blue-900">We take care of your pet and help them grow</h1>
			<h4 class="text-xl">
				Best pets are waiting for adoption. Find out the perfect one you will like it. It's our
				promise.
			</h4>
			<div class="flex flex-row items-center gap-4">
				<button class="px-8 py-4 text-lg text-white bg-orange-600 rounded-2xl">Contact us</button>
				<div>pictures of ...</div>
			</div>
		</div>
	</div>
</section>
<section class="my-32">
	<div class="flex justify-center px-32 text-3xl">
		<div
			class="flex flex-col items-center content-center w-3/5 px-24 mt-16 text-white align-middle transition-transform bg-orange-600 rounded-bl-lg py-28 lg:flex-row rounded-tl-3xl bg-gradient-to-r to-orange-400 from-orange-500 hover:to-orange-500 hover:from-orange-400"
		>
			<div class="flex flex-col items-center w-1/3 gap-4">
				<h3>Adopted</h3>
				<h3 class="slackey">2500+</h3>
			</div>
			<div class="flex flex-col items-center w-1/3 gap-4 border-white border-x-4">
				<h3>Customers</h3>
				<h3 class="slackey">1850+</h3>
			</div>
			<div class="flex flex-col items-center w-1/3 gap-4">
				<h3>Testimonials</h3>
				<h3 class="slackey">1100+</h3>
			</div>
		</div>
		<div
			class="flex flex-col justify-center w-2/5 gap-4 px-8 text-white border-8 border-b-0 border-white bg-sky-400 rounded-t-3xl rounded-br-xl"
		>
			<p class="py-4 text-2xl border-b-2 border-white">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet eum voluptatem inventore a.
				Eligendi molestias in, dicta dignissimos iure eveniet voluptatum itaque.
			</p>
			<div class="flex flex-row justify-between">
				<div class="">
					<h5 class="slackey">Arno De Bakker</h5>
				</div>
				<div class="w-16 h-16 bg-gray-300 border-2 border-white rounded-full" />
			</div>
		</div>
	</div>
</section>

<section class="px-32">
	<div class="flex justify-between text-lg lg:flex-row">
		<div class="flex flex-col w-1/2">
			<h1 class="mb-8 text-5xl text-blue-900">Lets book a call and stay connected</h1>
			<div class="flex flex-row gap-8 mb-8 font-semibold text-blue-950">
				<div class="flex flex-row items-center gap-4">
					<div>
						<img src="/check.png" alt="" />
					</div>
					<div>Vaccination Service</div>
				</div>
				<div class="flex flex-row items-center gap-4">
					<div>
						<img src="/check.png" alt="" />
					</div>
					<div>Veterinary Service</div>
				</div>
			</div>
			<p class="mb-8 font-light">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
				labore et dolore magna aliqua. Ut enim ad minim velit esse cillum dolore eu fugiat nulla
				pariatur.
			</p>
			<div class="flex flex-row">
				<div>
					<button
						class="px-8 py-4 font-semibold text-white transition-transform bg-orange-500 rounded-2xl"
					>
						<a href="/book">Book a Schedule</a>
					</button>
				</div>
				<div class="flex flex-row">
					<img src="/call.png" alt="bel nu voor ..." />
					<p class="underline">Emergency Call</p>
				</div>
			</div>
		</div>
		<div>
			<img src="/doc-holding-dog.png" alt="" />
		</div>
	</div>
</section>

<style>
	#doghero {
		position: absolute;
		bottom: -80px;
		right: -50px;
	}

	#paw-image {
		position: absolute;
		left: 132px;
		top: 800px;
		z-index: 1;
	}

	#star-image {
		position: absolute;
		top: 300px;
		left: 570px;
	}

	#rings-image {
		position: absolute;
		bottom: 200px;
		right: 400px;
	}

	.slackey {
		font-family: 'slackey';
	}
</style>
