<svelte:head>
	<title>Real Estate Svelte & TailwindCSS Template: Modern Home & Property Listings</title>
	<meta name="description" content="Elevate your real estate website with our Svelte & TailwindCSS template. Designed for a user-friendly experience, customizable property listings, and high-quality user interface." />

</svelte:head>

<header class="mb-12">
	<nav class="bg-gray-100 py-3 fixed w-full z-20 top-0 left-0">
		<div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
			<a href="/" class="flex items-center">
				<span class="self-center text-2xl font-semibold whitespace-nowrap">Logo</span>
			</a>
			<div class="flex md:order-2">
				<button
					type="button"
					class="text-white bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg md:text-lg px-6 py-2 text-center mr-3 md:mr-0"
					>Login</button
				>
				<button
					data-collapse-toggle="navbar-sticky"
					type="button"
					class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200"
					aria-controls="navbar-sticky"
					aria-expanded="false"
				>
					<span class="sr-only">Open main menu</span>
					<svg
						class="w-5 h-5"
						aria-hidden="true"
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 17 14"
					>
						<path
							stroke="currentColor"
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M1 1h15M1 7h15M1 13h15"
						/>
					</svg>
				</button>
			</div>
			<div
				class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
				id="navbar-sticky"
			>
				<ul
					class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-gray-100 rounded-lg md:flex-row md:space-x-8 md:mt-0 md:border-0"
				>
					<li>
						<a
							href="/"
							class="block py-2 pl-3 pr-4 text-white bg-purple-700 rounded md:bg-transparent md:text-purple-700 md:p-0"
							aria-current="page">Home</a
						>
					</li>
					<li>
						<a
							href="#property"
							class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
							>Property</a
						>
					</li>
					<li>
						<a
							href="#"
							class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
							>About</a
						>
					</li>
					<li>
						<a
							href="#service"
							class=" block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
							>Service</a
						>
					</li>
					<li>
						<a
							href="#contact"
							class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
							>Contact</a
						>
					</li>
				</ul>
			</div>
		</div>
	</nav>
</header>
<main class="bg-gray-100">
	<section id="hero" class=" px-6 pt-12">
		<div
			class="grid max-w-screen-xl py-8 mx-auto lg:gap-8 xl:gap-0 lg:py-0 lg:pt-16 lg:grid-cols-12"
		>
			<div class="mr-auto place-self-center lg:col-span-7">
				<h1
					class="max-w-2xl mb-4 text-4xl font-extrabold tracking-tight leading-none md:text-5xl xl:text-6xl"
				>
					Real Estate Svelte
					<span class="underline underline-offset-2 decoration-8 decoration-purple-400"
						>Template</span
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

	<section id="contact" class="px-6 py-12">
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
						class="w-full px-3 py-3 text-sm text-gray-900 bg-white border-0 focus:ring-0"
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
</main>

<footer class="bg-[#001246]">
	<div class="mx-auto w-full max-w-screen-xl p-4 py-6 lg:py-8">
		<div class="md:flex md:justify-between">
			<div class="mb-6 md:mb-0">
				<span class="text-white font-bold text-3xl">Logo</span>

				<ul class="text-gray-400 font-medium mt-3 space-y-2">
					<li class="flex items-center gap-1">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="15"
							height="14"
							viewBox="0 0 15 14"
							fill="none"
						>
							<path
								d="M7.49998 1.16669C5.04998 1.16669 2.83331 3.04502 2.83331 5.95002C2.83331 7.80502 4.26248 9.98669 7.11498 12.5009C7.33665 12.6934 7.66915 12.6934 7.89081 12.5009C10.7375 9.98669 12.1666 7.80502 12.1666 5.95002C12.1666 3.04502 9.94998 1.16669 7.49998 1.16669ZM7.49998 7.00002C6.85831 7.00002 6.33331 6.47502 6.33331 5.83335C6.33331 5.19169 6.85831 4.66669 7.49998 4.66669C8.14165 4.66669 8.66665 5.19169 8.66665 5.83335C8.66665 6.47502 8.14165 7.00002 7.49998 7.00002Z"
								fill="#BDBDBD"
							/>
						</svg>
						<p class="text">Street Name, City Name</p>
					</li>
					<li class="flex items-center gap-1">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="15"
							height="14"
							viewBox="0 0 15 14"
							fill="none"
						>
							<path
								d="M4.36167 6.29417C5.20167 7.945 6.555 9.2925 8.20583 10.1383L9.48917 8.855C9.64667 8.6975 9.88 8.645 10.0842 8.715C10.7375 8.93083 11.4433 9.0475 12.1667 9.0475C12.4875 9.0475 12.75 9.31 12.75 9.63083V11.6667C12.75 11.9875 12.4875 12.25 12.1667 12.25C6.68917 12.25 2.25 7.81083 2.25 2.33333C2.25 2.0125 2.5125 1.75 2.83333 1.75H4.875C5.19583 1.75 5.45833 2.0125 5.45833 2.33333C5.45833 3.0625 5.575 3.7625 5.79083 4.41583C5.855 4.62 5.80833 4.8475 5.645 5.01083L4.36167 6.29417Z"
								fill="#BDBDBD"
							/>
						</svg>
						<a href="tel:9051290512">+9051290512</a>
					</li>
					<li class="flex items-center gap-1">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							width="15"
							height="14"
							viewBox="0 0 15 14"
							fill="none"
						>
							<path
								d="M12.1667 2.33334H2.83335C2.19169 2.33334 1.67252 2.85834 1.67252 3.50001L1.66669 10.5C1.66669 11.1417 2.19169 11.6667 2.83335 11.6667H12.1667C12.8084 11.6667 13.3334 11.1417 13.3334 10.5V3.50001C13.3334 2.85834 12.8084 2.33334 12.1667 2.33334ZM12.1667 4.66668L7.50002 7.58334L2.83335 4.66668V3.50001L7.50002 6.41668L12.1667 3.50001V4.66668Z"
								fill="#BDBDBD"
							/>
						</svg>
						<a href="mailto:contact@company.com">contact@company.com</a>
					</li>
				</ul>
			</div>

			<div class="grid grid-cols-2 gap-8 sm:gap-6 sm:grid-cols-2">
				<div>
					<h2 class="mb-6 text-sm font-semibold uppercase text-white">Legal</h2>
					<ul class=" text-gray-400 font-medium">
						<li class="mb-4">
							<a href="#" class="hover:underline">Privacy Policy</a>
						</li>
						<li>
							<a href="#" class="hover:underline">Terms &amp; Conditions</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
		<hr class="my-6 sm:mx-auto border-gray-700 lg:my-8" />
		<div class="sm:flex sm:items-center sm:justify-between">
			<span class="text-sm sm:text-center text-gray-400"
				>© 2023 <a href="#" class="hover:underline">Company Name™</a>. All Rights Reserved.
			</span>
			<div class="flex mt-4 space-x-5 sm:justify-center sm:mt-0">
				<a href="#" class="text-gray-500 hover:text-white">
					<svg
						class="w-4 h-4"
						aria-hidden="true"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 8 19"
					>
						<path
							fill-rule="evenodd"
							d="M6.135 3H8V0H6.135a4.147 4.147 0 0 0-4.142 4.142V6H0v3h2v9.938h3V9h2.021l.592-3H5V3.591A.6.6 0 0 1 5.592 3h.543Z"
							clip-rule="evenodd"
						/>
					</svg>
					<span class="sr-only">Facebook page</span>
				</a>

				<a href="#" class="text-gray-500 hover:text-white">
					<svg
						class="w-4 h-4"
						aria-hidden="true"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 20 17"
					>
						<path
							fill-rule="evenodd"
							d="M20 1.892a8.178 8.178 0 0 1-2.355.635 4.074 4.074 0 0 0 1.8-2.235 8.344 8.344 0 0 1-2.605.98A4.13 4.13 0 0 0 13.85 0a4.068 4.068 0 0 0-4.1 4.038 4 4 0 0 0 .105.919A11.705 11.705 0 0 1 1.4.734a4.006 4.006 0 0 0 1.268 5.392 4.165 4.165 0 0 1-1.859-.5v.05A4.057 4.057 0 0 0 4.1 9.635a4.19 4.19 0 0 1-1.856.07 4.108 4.108 0 0 0 3.831 2.807A8.36 8.36 0 0 1 0 14.184 11.732 11.732 0 0 0 6.291 16 11.502 11.502 0 0 0 17.964 4.5c0-.177 0-.35-.012-.523A8.143 8.143 0 0 0 20 1.892Z"
							clip-rule="evenodd"
						/>
					</svg>
					<span class="sr-only">Twitter page</span>
				</a>

				<a href="#" class="text-gray-500 hover:text-white">
					<svg
						class="w-4 h-4"
						aria-hidden="true"
						xmlns="http://www.w3.org/2000/svg"
						fill="currentColor"
						viewBox="0 0 20 20"
					>
						<path
							fill-rule="evenodd"
							d="M10 0a10 10 0 1 0 10 10A10.009 10.009 0 0 0 10 0Zm6.613 4.614a8.523 8.523 0 0 1 1.93 5.32 20.094 20.094 0 0 0-5.949-.274c-.059-.149-.122-.292-.184-.441a23.879 23.879 0 0 0-.566-1.239 11.41 11.41 0 0 0 4.769-3.366ZM8 1.707a8.821 8.821 0 0 1 2-.238 8.5 8.5 0 0 1 5.664 2.152 9.608 9.608 0 0 1-4.476 3.087A45.758 45.758 0 0 0 8 1.707ZM1.642 8.262a8.57 8.57 0 0 1 4.73-5.981A53.998 53.998 0 0 1 9.54 7.222a32.078 32.078 0 0 1-7.9 1.04h.002Zm2.01 7.46a8.51 8.51 0 0 1-2.2-5.707v-.262a31.64 31.64 0 0 0 8.777-1.219c.243.477.477.964.692 1.449-.114.032-.227.067-.336.1a13.569 13.569 0 0 0-6.942 5.636l.009.003ZM10 18.556a8.508 8.508 0 0 1-5.243-1.8 11.717 11.717 0 0 1 6.7-5.332.509.509 0 0 1 .055-.02 35.65 35.65 0 0 1 1.819 6.476 8.476 8.476 0 0 1-3.331.676Zm4.772-1.462A37.232 37.232 0 0 0 13.113 11a12.513 12.513 0 0 1 5.321.364 8.56 8.56 0 0 1-3.66 5.73h-.002Z"
							clip-rule="evenodd"
						/>
					</svg>
					<span class="sr-only">Dribbble account</span>
				</a>
			</div>
		</div>
	</div>
</footer>
