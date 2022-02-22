<script>
	import Icon from 'svelte-awesome'
	import { faHome } from '@fortawesome/free-solid-svg-icons'
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

Icon should show here: <Icon data={faHome} slot='button'
							 class='w-5 h-5 ml-2 -mr-1'
							 aria-hidden='true' />
