<script>
	import Nav from './Nav.svelte';
	import Main from '../components/Main.svelte';
	import './styles.css';
    import Header from '../components/Header.svelte';
</script>

<div class="app">
	<Header />
	<Nav />
	<Main>
		<slot></slot>
	</Main>
</div>

<style>
</style>
