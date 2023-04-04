<script>
	import AvatarCard from '$lib/components/AvatarCard.svelte';
	import imgHeadShot from '$lib/images/rjs_headshot.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="rjsiii.com home" />
</svelte:head>

<section class="hero min-h-screen">
	<div class="hero-content flex-col lg:flex-row">
		<AvatarCard imgUrl={imgHeadShot} imgAltText="rjsiii" />
		<div class="lg:pl-10">
			<h1 class="text-center lg:text-left md:text-5xl font-bold">Hey there, I'm Richard.</h1>
			<p class="py-6">
 				Website is currently under construction, but will get there soon enough!
			</p>
		</div>
	</div>
</section>

<style>
</style>
