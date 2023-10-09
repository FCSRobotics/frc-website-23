<script lang="ts">
	export let name: string;
	export let src: string;
	export let bio: string | undefined | null;
	export let alt: string;
</script>

<div class="person">
	<img {src} {alt} />
	<p class="name">{name}</p>
	{#if bio != undefined && bio != null && bio != ""}
		<p class="bio">{bio}</p>
	{/if}
</div>

<style>
	.person {
		width: 100%;
		height: 100%;
	}
	img {
		width: 100%;
		border-radius: 3vw;
	}

	.name {
		font-size: max(1.2vw, 1.2rem);
		font-weight: bold;
	}

	@media (max-width: 1000px) {
		.name {
			display: none;
		}
		.bio {
			display: none;
		}
	}
</style>
