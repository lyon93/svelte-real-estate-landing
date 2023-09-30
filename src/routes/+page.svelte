<svelte:head>
	<title>Real Estate Svelte & TailwindCSS Template: Modern Home & Property Listings</title>
	<meta
		name="description"
		content="Real Estate Template with Svelte and TailwindCss"
	/>
</svelte:head>

<section id="hero" class=" px-6 pt-12 bg-gray-100">
	<div class="grid max-w-screen-xl py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-0 lg:pt-16 lg:grid-cols-12">
		<div class="mr-auto place-self-center lg:col-span-7">
			<h1
				class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl"
			>
				Real Estate Svelte
				<span class="underline underline-offset-2 decoration-8 decoration-purple-400">Template</span
				>
			</h1>
			<p class="max-w-2xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl">
				Real Estate Svelte Template is a free, open source template made by <a
					class="text-purple-400"
					href="https://x.com/melu1s"><strong>@melu1s</strong></a
				>. Feel free to use it for your next project.
			</p>

			<form>
				<label
					for="default-search"
					class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label
				>
				<div class="relative">
					<div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="28"
							height="28"
							viewBox="0 0 28 28"
							fill="none"
						>
							<path
								d="M13.6668 14.9774C15.5452 14.9774 17.0679 13.4547 17.0679 11.5763C17.0679 9.69799 15.5452 8.17529 13.6668 8.17529C11.7885 8.17529 10.2658 9.69799 10.2658 11.5763C10.2658 13.4547 11.7885 14.9774 13.6668 14.9774Z"
								stroke="#AEAEAE"
								stroke-width="2.26736"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
							<path
								d="M13.667 2.50684C11.2616 2.50684 8.95476 3.46236 7.25391 5.16321C5.55306 6.86406 4.59753 9.1709 4.59753 11.5763C4.59753 13.7212 5.05327 15.1247 6.29805 16.6778L13.667 25.1804L21.0359 16.6778C22.2807 15.1247 22.7364 13.7212 22.7364 11.5763C22.7364 9.1709 21.7809 6.86406 20.08 5.16321C18.3792 3.46236 16.0723 2.50684 13.667 2.50684V2.50684Z"
								stroke="#AEAEAE"
								stroke-width="2.26736"
								stroke-linecap="round"
								stroke-linejoin="round"
							/>
						</svg>
					</div>
					<input
						type="search"
						id="default-search"
						class="block w-full p-4 pl-12 md:p-6 md:pl-12 text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-purple-500 focus:border-purple-500"
						placeholder="Search by Location"
						required
					/>
					<button
						type="submit"
						class="text-white absolute right-1.5 bottom-1.5 md:bottom-2.5 bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg text-sm md:text-lg px-3 md:px-10 py-3"
						>Search</button
					>
				</div>
			</form>
		</div>
		<div class="hidden lg:mt-0 lg:col-span-5 lg:flex">
			<img src="/images/house1.png" width="auto" height="100" alt="House" />
		</div>
	</div>
</section>

<section id="service" class="px-6 bg-white py-12">
	<h2 class="font-bold text-2xl md:text-4xl lg:text-5xl text-center">Service</h2>
	<div
		class="grid max-w-screen-xl grid-cols-1 place-items-center px-4 py-8 mx-auto gap-8 xl:gap-0 lg:py-16 md:grid-cols-3"
	>
		<div class="flex flex-col space-y-2 items-start px-6 py-6">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				width="55"
				height="58"
				viewBox="0 0 55 58"
				fill="none"
				class="text-indigo-500"
			>
				<path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M45.2856 28.6429C45.2856 30.5749 46.8164 32.1469 48.6979 32.1469C49.6466 32.1469 50.4166 32.9376 50.4166 33.9119V40.2681C50.4166 45.6431 46.1587 50.0155 40.9246 50.0155H14.0777C8.84352 50.0155 4.58331 45.6431 4.58331 40.2681V33.9119C4.58331 32.9376 5.35331 32.1469 6.30206 32.1469C8.18581 32.1469 9.71665 30.5749 9.71665 28.6429C9.71665 26.7602 8.24769 25.3435 6.30206 25.3435C5.84602 25.3435 5.4106 25.1576 5.08748 24.8258C4.76435 24.494 4.58331 24.0445 4.58331 23.5786L4.5879 17.0152C4.5879 11.6403 8.84581 7.2655 14.08 7.2655H40.92C46.1541 7.2655 50.4144 11.6403 50.4144 17.0152L50.4166 23.3738C50.4166 23.8398 50.2356 24.2916 49.9148 24.6211C49.5916 24.9529 49.1562 25.1388 48.6979 25.1388C46.8164 25.1388 45.2856 26.7108 45.2856 28.6429ZM32.6607 30.1797L35.3626 27.4781C35.8324 27.0121 35.9951 26.325 35.7912 25.6896C35.5895 25.0542 35.0624 24.6024 34.4253 24.5106L30.6922 23.9505L29.0216 20.477C28.7351 19.8793 28.153 19.5075 27.5045 19.5051H27.4999C26.8537 19.5051 26.2716 19.8769 25.9805 20.4747L24.3099 23.9505L20.5837 24.5082C19.9397 24.6024 19.4126 25.0542 19.2087 25.6896C19.007 26.325 19.1697 27.0121 19.6372 27.4781L22.3391 30.1797L21.702 33.9991C21.592 34.658 21.851 35.3122 22.378 35.7052C22.676 35.9241 23.022 36.037 23.3726 36.037C23.6407 36.037 23.9112 35.9688 24.1587 35.8346L27.4999 34.032L30.8343 35.8299C31.4118 36.1476 32.097 36.0982 32.6218 35.7029C33.1512 35.3122 33.4101 34.658 33.3001 33.9991L32.6607 30.1797Z"
					fill="currentColor"
				/>
			</svg>
			<h3 class="font-bold text-lg">Best Price</h3>
			<p class="text-gray-500">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.
			</p>
		</div>
		<div class="flex flex-col space-y-2 items-start px-6 py-6">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				width="51"
				height="51"
				viewBox="0 0 51 51"
				fill="none"
				class="text-indigo-500"
			>
				<path
					fill-rule="evenodd"
					clip-rule="evenodd"
					d="M7.4375 21.6358C7.4375 12.0527 15.6057 4.30713 25.4861 4.30713C35.3943 4.30713 43.5625 12.0527 43.5625 21.6358C43.5625 26.4648 41.7711 30.948 38.8227 34.7479C35.57 38.9395 31.5608 42.5914 27.0482 45.458C26.0153 46.1205 25.0832 46.1705 23.9497 45.458C19.4113 42.5914 15.4022 38.9395 12.1773 34.7479C9.22671 30.948 7.4375 26.4648 7.4375 21.6358ZM19.5377 22.1754C19.5377 25.3857 22.2098 27.9106 25.4861 27.9106C28.7645 27.9106 31.4622 25.3857 31.4622 22.1754C31.4622 18.9901 28.7645 16.3422 25.4861 16.3422C22.2098 16.3422 19.5377 18.9901 19.5377 22.1754Z"
					fill="currentColor"
				/>
			</svg>
			<h3 class="font-bold text-lg">Construction</h3>
			<p class="text-gray-500">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.
			</p>
		</div>
		<div class="flex flex-col space-y-2 items-start px-6 py-6">
			<svg
				xmlns="http://www.w3.org/2000/svg"
				width="42"
				height="42"
				viewBox="0 0 42 42"
				fill="none"
				class="text-indigo-500"
			>
				<path
					d="M20.6679 0.65332C16.1173 14.2562 8.26773 31.1598 0 41.6277L20.6679 33.3768L41.3844 41.6277C33.1182 31.1598 25.263 14.2562 20.6679 0.65332Z"
					fill="currentColor"
				/>
			</svg>
			<h3 class="font-bold text-lg">Design</h3>
			<p class="text-gray-500">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.
			</p>
		</div>
	</div>
</section>

<section id="contact" class="px-6 py-12 bg-gray-100">
	<div class="grid max-w-screen-xl grid-cols-1 px-4 py-8 mx-auto gap-3 lg:py-16 md:grid-cols-2">
		<img
			src="/images/house2.png"
			class="h-full lg:w-10/12"
			width="auto"
			height="200"
			alt="A House"
		/>
		<div>
			<h3 class="font-bold text-2xl">Find the right one for you!</h3>
			<p class="font-light text-sm py-2 mb-3 text-gray-500">
				Schedule a consultation with an agent
			</p>
			<form>
				<div class="mb-6 flex flex-col md:flex-row gap-5">
					<input
						type="text"
						id="firstName"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="First Name"
						required
					/>
					<input
						type="text"
						id="lastName"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="Last Name"
						required
					/>
				</div>
				<div class="mb-6 flex flex-col md:flex-row gap-5">
					<input
						type="email"
						id="email"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="Email address"
						required
					/>
					<input
						type="tel"
						id="lastName"
						class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-purple-500 focus:border-purple-500 block w-full p-2.5"
						placeholder="Phone Number"
						required
					/>
				</div>
				<textarea
					id="comment"
					rows="4"
					class="w-full px-3 py-3 text-sm text-gray-900 bg-gray-50 border rounded-lg border-gray-300 focus:ring-0"
					placeholder="Description"
					required
				/>
				<p class="font-light text-gray-500 mb-6">We don't send you spam</p>
				<button
					type="button"
					class="w-full text-white bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg text-sm px-4 py-4 text-center mr-3 md:mr-0"
					>Contact Us</button
				>
			</form>
		</div>
	</div>
</section>
