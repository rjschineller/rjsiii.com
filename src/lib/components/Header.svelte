<header class="sticky top-0 z-30">
	<div class="navbar bg-base-100">
		<div class="navbar-start">
			<div class="dropdown">
				<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
				<!-- svelte-ignore a11y-label-has-associated-control -->
				<label tabindex="0" class="btn btn-ghost lg:hidden">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						class="h-5 w-5"
						fill="none"
						viewBox="0 0 24 24"
						stroke="currentColor"
						><path
							stroke-linecap="round"
							stroke-linejoin="round"
							stroke-width="2"
							d="M4 6h16M4 12h8m-8 6h16"
						/></svg
					>
				</label>
				<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
				<ul
					tabindex="0"
					class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
				>
					<li><a href="/">Home</a></li>
					<!-- <li>
						<a href="/about"> About </a>
					</li>
					<li><a href="/career">Career</a></li> -->
					<li><a href="/blog">Blog</a></li>
				</ul>
			</div>
			<a class="btn btn-ghost normal-case text-xl" href="/">rjsiii</a>
		</div>
		<div class="navbar-center hidden lg:flex">
			<ul class="menu menu-horizontal px-1">
				<li><a href="/">Home</a></li>
				<!-- <li>
					<a href="/about"> About </a>
				</li>
				<li><a href="/career">Career</a></li> -->
				<li><a href="/blog">Blog</a></li>
			</ul>
		</div>
		<!-- <div class="navbar-end">
			<div class="menu menu-normal px-1">
				<input data-toggle-theme="business" type="checkbox" class="toggle rounded-sm" checked />
			</div>
		</div> -->
	</div>
</header>
