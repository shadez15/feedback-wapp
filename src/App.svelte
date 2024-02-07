<script>
	import FeedbackForm from './components/FeedbackForm.svelte'
	import FeedbackList from './components/FeedbackList.svelte'
	import FeedbackStats from './components/FeedbackStats.svelte'
</script>
<head> <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Teko:wght@300;400;500;600;700&display=swap"></head>
<style>
	a{
		color: red;
		font-family: 'Teko', sans-serif;
		font-weight: 900;
	}
</style>

<main class="container">
	<FeedbackForm />
	<FeedbackStats />
	<FeedbackList />

</main>
<footer class="container">
		<p>Made with <a  href="https://svelte.dev/tutorial">Svelte</a></p>
</footer>
