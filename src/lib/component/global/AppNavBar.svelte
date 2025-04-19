<script>
	import BurgerMenuSvg from '$lib/asset/image/svg/burger-menu-svg.svelte';
</script>

<div class="navbar bg-base-100 shadow-sm">
	<div class="navbar-start">
		<div class="dropdown">
			<div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
				<div class="h-5 w-5">
					<svelte:component this={BurgerMenuSvg} />
				</div>
			</div>
			<ul
				class="menu menu-sm dropdown-content bg-base-100 rounded-box z-1 mt-3 w-52 p-2 shadow"
			>
				<li><a href="/app/website-dashboard/about-website">About Us</a></li>
			</ul>
		</div>
		<a href="/" class="btn btn-ghost text-xl">pte.mari.software</a>
	</div>
	<div class="navbar-center hidden lg:flex">
		<ul class="menu menu-horizontal px-1">
			<li><a href="/app/website-dashboard/about-website">about</a></li>
		</ul>
	</div>
	<div class="navbar-end">
		<a href="/app/website-dashboard/donate-website" class="btn btn-primary"
			>donate</a
		>
	</div>
</div>
