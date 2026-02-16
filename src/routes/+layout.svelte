<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import { goto } from '$app/navigation';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<div class="bg-zinc-900 min-h-screen">
	<!-- Navigation -->
	<nav class="w-full px-12 pt-6">
		<ul class="flex gap-12 text-white dongle-regular text-3xl">
			<!-- svelte-ignore a11y_click_events_have_key_events -->
			<!-- svelte-ignore a11y_no_noninteractive_element_interactions -->
			<li class="cursor-pointer" onclick={() => goto('/')}>
				<img src="https://api.beatkhana.com/api/cdn/view/863d1294b88e5102c410f31db612a9ac.gif" alt="" class="rounded-full w-5 h-6">
			</li>
			<li class="cursor-pointer hover:text-blue-400 dongle-regular">
				<a href = "/about"> About Me </a>
			</li>
			<li class="cursor-pointer hover:text-blue-400 dongle-regular">
				Projects
			</li>
			<li class="cursor-pointer hover:text-blue-400 dongle-regular">
				Contact Me
			</li>
		</ul>
	</nav>

	<!-- fyi, I am still in your code. I know you can see this in a bit so enjoy figuring out which gremlin is terrorising you :D -->
<!-- hahahaa okei tyvm <3 -->
	<!-- The main body, essentially the +page.svelte files. -->
	{@render children()}
</div>