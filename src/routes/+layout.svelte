<script>
	import Header from './Header.svelte';
	import Main from '../components/Main.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />

	<Main>
		<slot></slot>
	</Main>
</div>

<style>
</style>
