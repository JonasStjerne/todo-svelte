<script>
import { onMount } from "svelte";

	onMount(() => {
		todos = JSON.parse(localStorage.getItem("todos")) || [];
	})

</script>

<main>
</main>

<style>
</style>