<template>
	<header class="fixed w-full">
		<nav class="border-gray-200 bg-white py-2.5 dark:bg-gray-900">
			<div
				class="mx-auto flex max-w-screen-xl flex-wrap items-center justify-between px-4">
				<a href="#" class="flex items-center">
					<span
						class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
						>Clean Web Solutions</span
					>
					<span class="ml-6">
						<button
							id="dropdownNavbarLink"
							data-dropdown-toggle="dropdownNavbar"
							class="hidden sm:flex flex w-full items-center justify-between rounded py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-100 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white dark:focus:text-white md:w-auto md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-blue-700 md:dark:hover:bg-transparent">
							CH
							<svg
								class="ml-1 h-5 w-5"
								aria-hidden="true"
								fill="currentColor"
								viewBox="0 0 20 20"
								xmlns="http://www.w3.org/2000/svg">
								<path
									fill-rule="evenodd"
									d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
									clip-rule="evenodd"></path>
							</svg>
						</button>
					</span>
				</a>
				<div class="flex gap-6">
					<div class="flex lg:order-2">
						<!-- <a href="#" class="text-gray-800 dark:text-white hover:bg-gray-50 focus:ring-4 focus:ring-gray-300 font-medium rounded-lg text-sm px-4 lg:px-5 py-2 lg:py-2.5 sm:mr-2 dark:hover:bg-gray-700 focus:outline-none dark:focus:ring-gray-800">Log in</a> -->
						<!-- <a
						href="https://themesberg.com/product/tailwind-css/landing-page"
						class="rounded-lg outline-white bg-blue-700 px-4 py-2 text-sm font-medium text-white hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800 sm:mr-2 lg:mr-0 lg:px-5 lg:py-2.5"
						>Kontakt</a
					> -->
						<button
							type="button"
							class="hidden sm:block mr-2 lg:mr-0 rounded-lg border border-gray-300 bg-white px-5 py-2 text-base font-medium text-gray-900 hover:bg-gray-100 focus:outline-none focus:ring-4 focus:ring-gray-200 dark:border-gray-600 dark:bg-gray-800 dark:text-gray-400 dark:hover:border-gray-600 dark:hover:bg-gray-700 dark:focus:ring-gray-700">
							Kontakt
						</button>

						<button
							data-collapse-toggle="mobile-menu-2"
							type="button"
							class="ml-1 inline-flex items-center rounded-lg p-2 text-sm text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600 lg:hidden"
							aria-controls="mobile-menu-2"
							aria-expanded="false">
							<span class="sr-only">Open main menu</span>
							<svg
								class="h-6 w-6"
								fill="currentColor"
								viewBox="0 0 20 20"
								xmlns="http://www.w3.org/2000/svg">
								<path
									fill-rule="evenodd"
									d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
									clip-rule="evenodd"></path>
							</svg>
							<svg
								class="hidden h-6 w-6"
								fill="currentColor"
								viewBox="0 0 20 20"
								xmlns="http://www.w3.org/2000/svg">
								<path
									fill-rule="evenodd"
									d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
									clip-rule="evenodd"></path>
							</svg>
						</button>
					</div>
					<div
						class="hidden w-full items-center justify-between lg:order-1 lg:flex lg:w-auto"
						id="mobile-menu-2">
						<ul
							class="mt-4 flex flex-col font-medium lg:mt-0 lg:flex-row lg:space-x-8">
							<!-- <li>
								<a
									href="#"
									class="block rounded bg-blue-700 py-2 pl-3 pr-4 text-white dark:text-white lg:bg-transparent lg:p-0 lg:text-blue-700"
									aria-current="page"
									>Home</a
								>
							</li> -->
							<li>
								<a
									href="#"
									class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white lg:border-0 lg:p-0 lg:hover:bg-transparent lg:hover:text-blue-700 lg:dark:hover:bg-transparent lg:dark:hover:text-white"
									>Leistungen</a
								>
							</li>
							<li>
								<a
									href="#"
									class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white lg:border-0 lg:p-0 lg:hover:bg-transparent lg:hover:text-blue-700 lg:dark:hover:bg-transparent lg:dark:hover:text-white"
									>Über uns</a
								>
							</li>
							<li>
								<a
									href="#"
									class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white lg:border-0 lg:p-0 lg:hover:bg-transparent lg:hover:text-blue-700 lg:dark:hover:bg-transparent lg:dark:hover:text-white"
									>Branchen</a
								>
							</li>
							<li>
								<a
									href="#"
									class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white lg:border-0 lg:p-0 lg:hover:bg-transparent lg:hover:text-blue-700 lg:dark:hover:bg-transparent lg:dark:hover:text-white"
									>Ablauf</a
								>
							</li>
							
						</ul>
					</div>
				</div>
			</div>
		</nav>
	</header>
</template>

<script>
	export default {};
</script>

<style scoped></style>
