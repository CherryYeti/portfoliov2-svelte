<script>
	import Hero from '../components/sections/hero.svelte';
    import About from '../components/sections/about.svelte';
    import Projects from '../components/sections/projects.svelte';
    import Footer from '../components/footer.svelte';
	import './page.css';
</script>

<div class="app">
	<Hero />
    <About />
    <Projects />
    <Footer />
</div>

<style>
	.app {
		background-image: url('background.jpg');
		min-width: 100%;
		min-height: 100%;
		background-size: cover;
		background-position: center;
	}
</style>
