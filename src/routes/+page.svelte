<script>
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte'
	import PopCategory from '../components/PopCategory.svelte';
</script>

<Header />
<main class="home">
	<section class="home__pop">
		<div class="container">
			<div class="row">
				<PopCategory />
				<PopCategory />
				<PopCategory />
				<PopCategory />
				<PopCategory />
			</div>
		</div>
	</section>

</main>
<Footer />

<style style lang="scss">
	.home {
		&__pop {
			.row {
				display: grid;
				grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
			}
		}
	}
</style>
