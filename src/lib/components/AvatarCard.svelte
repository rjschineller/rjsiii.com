<script lang="ts">
	export let imgUrl: string;
	export let imgAltText: string;

	import linkedInIcon from '$lib/images/LinkedIn_icon.svg?raw';
	import githubIcon from '$lib/images/github.svg?raw';
	import gitlabIcon from '$lib/images/gitlab.svg?raw';
</script>

<div class="p-4">
	<div class="avatar">
		<div class="w-72 rounded-full">
			<img src={imgUrl} alt={imgAltText} />
		</div>
	</div>
	<div class="divider" />
	<div>
		<button class="btn btn-block btn-outline btn-info gap-1">
			<span class="h-6 w-6">{@html linkedInIcon}</span>
			LinkedIn
		</button>
		<button class="btn btn-block btn-outline btn-warning gap-1">
			<span class="h-6 w-6">{@html gitlabIcon}</span>
			GitLab
		</button>
		<button class="btn btn-block btn-outline gap-1">
			<span class="h-6 w-6">{@html githubIcon}</span>
			GitHub
		</button>
	</div>
</div>

<style>
	.btn {
		text-transform: none;
	}
</style>
