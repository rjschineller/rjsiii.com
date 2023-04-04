<script lang="ts">
	export let imgUrl: string;
	export let imgAltText: string;

	import linkedInIcon from '$lib/images/LinkedIn_icon.svg?raw';
	import githubIcon from '$lib/images/github.svg?raw';
	import gitlabIcon from '$lib/images/gitlab.svg?raw';
</script>

<div class="p-4 grid content-center">
	<div class="avatar justify-center">
		<div class="w-72 rounded-full">
			<img src={imgUrl} alt={imgAltText} />
		</div>
	</div>
	<div class="divider" />
	<div class="space-y-2">
		<a href="https://www.linkedin.com/in/rjschineller/" target="_blank" rel="noreferrer" class="btn btn-block btn-outline btn-info gap-1">
			<span class="h-6 w-6">{@html linkedInIcon}</span>
			LinkedIn
		</a>
		<a href="https://gitlab.com/RJSchineller" target="_blank" rel="noreferrer" class="btn btn-block btn-outline btn-warning gap-1">
			<span class="h-6 w-6">{@html gitlabIcon}</span>
			GitLab
		</a>
		<a href="https://github.com/rjschineller" target="_blank" rel="noreferrer" class="btn btn-block btn-outline gap-1">
			<span class="h-6 w-6">{@html githubIcon}</span>
			GitHub
		</a>
	</div>
</div>

<style>
	.btn {
		text-transform: none;
	}
</style>
