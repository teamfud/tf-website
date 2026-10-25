<script lang="ts">
	import fud from '$lib/assets/fud.png';
	import wabbit from '$lib/assets/wabbit.png';
	import elmer from '$lib/assets/elmer.png';
</script>

<main class="flex min-h-screen w-full items-center justify-center p-4 pt-16">
	<div class="flex max-w-2xs min-w-sm flex-col items-center justify-center">
		<img
			src={fud}
			alt="fud"
			class="mb-8 rounded-2xl border-2 transition-all hover:rotate-12 hover:border-16"
		/>

		<h1 class="mb-4 font-display text-6xl">hi, we're team fud :)</h1>
		<p class="w-full text-2xl leading-10">
			we make smart tools for stupid teams and stupid tools for smart teams.
		</p>

		<h2 class="mt-8 font-display text-4xl">our flagship tools</h2>
		<div class="mt-4 flex flex-col items-center text-xl">
			<h3 class="mt-6 text-center font-display text-3xl text-accent underline">
				<a href="https://github.com/teamfud/wabbit">wabbit</a>
			</h3>
			<img src={wabbit} alt="elmer" class="mb-4 w-32 rounded-2xl border-2" />
			<p class="mt-2 text-xl">
				a tool that uses rootkit tactics and ebpf, and abuses cgroups to prevent other rootkits from
				acheiving persistence.
			</p>
			<aside>
				<p class="mt-4 text-xl">"it's good idea"</p>
				<p class="mr-6 text-center text-accent">- oleg l</p>
			</aside>

			<h3 class="mt-6 text-center font-display text-3xl text-accent underline">
				<a href="https://github.com/teamfud/elmer">elmer</a>
			</h3>
			<img src={elmer} alt="elmer" class="mb-4 w-32 rounded-2xl border-2" />
			<p class="mt-2 text-xl">
				a custom logging daemon that spots suspicious activity and alerts whoever is in charge
			</p>
			<aside>
				<p class="mt-4 text-xl">"guys are we larpers"</p>
				<p class="mr-6 text-center text-accent">- ben tover</p>
			</aside>

			<h2 class="mt-8 font-display text-4xl">comp day suite</h2>

			<h3 class="mt-6 text-center font-display text-3xl text-accent underline">
				<a href="https://github.com/teamfud/vault">vault</a>
			</h3>
			<p class="mt-2 text-xl">
				password store that autogenerates hashes and organizes by host, for competitions
			</p>

			<h3 class="mt-6 text-center font-display text-3xl text-accent underline">
				<a href="https://github.com/teamfud/moat">moat</a>
			</h3>
			<p class="mt-2 text-xl">firewall rule templating system for competitions</p>

			<p class="mt-32 text-muted">made with fear, uncertainty and doubt by team fud :)</p>
		</div>
	</div>
</main>
