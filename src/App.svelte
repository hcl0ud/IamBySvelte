<script>
	import Aside from "./components/Aside.svelte";
	import Header from "./components/Header.svelte";
	import Section from "./components/Section.svelte";
	import Article from "./views/Home.svelte";
</script>

<main>
	<Aside />
	<Header />
	<Section>
		<Article title="안녕하세요" content="이것은 테스트용입니다." />
	</Section>
</main>

<style lang="scss">
	@import "./assets/css/App.scss";
</style>