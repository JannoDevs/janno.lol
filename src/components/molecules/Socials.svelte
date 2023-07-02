<script>
	import Social from '../atoms/Social.svelte';
	import { user } from '../../util/discord';
</script>

<div class="socials-container">
	<Social icon="github" tip="jannodevs" link="https://github.com/jannodevs" />
	<Social icon="discord" tip={user.username} link={`https://discord.com/users/${user.id}`} />
	<Social icon="email" tip="email@janno.lol" link="mailto:email@janno.lol" />
	<Social icon="kofi" tip="janno" link="https://ko-fi.com/janno" />
</div>

<style>
	.socials-container {
		display: flex;
		gap: 0.75rem;
	}
</style>
