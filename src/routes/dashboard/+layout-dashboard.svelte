<div class="grid grid-cols-12 gap-x-16 bg-whisper min-h-screen">
	<header class="col-span-3 bg-daisyBush text-center">
		<div class="mt-10 mb-24">
			<a href="/dashboard/invoices"><img src="/images/logo.svg" alt="The Dollar Holler" class="mx-auto"></a>
		</div>
		<nav>
			<ul class="list-none text-2xl font-bold font-sansSerif">
				<li><a href="/dashboard/invoices">Invoices</a></li>
				<li><a href="/dashboard/invoices">Clients</a></li>
				<li><a href="/dashboard/invoices">Settings</a></li>
				<li><a href="/dashboard/invoices">Logout</a></li>
			</ul>
		</nav>
	</header>
	<main class="col-span-8 pt-10">
		<slot />
	</main>
</div>

<style lang="postcss">
	nav ul li {
		@apply mb-6;
	}
	nav ul a {
		@apply text-white hover:text-goldenFizz
	}
</style>