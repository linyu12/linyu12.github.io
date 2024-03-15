<script lang="ts">
	import Section from './components/Section.svelte';
	import Title from './components/Title.svelte';
	import Type from './components/Type.svelte';
	import About from './components/About.svelte';
	import Education from './components/Education.svelte';
	import Skills from './components/Skills.svelte';
	import Extracurricular from './components/Extracurricular.svelte';
	import Header from './components/Header.svelte';
	import Contact from './components/Contact.svelte';
	import Wave from './components/Wave.svelte';
	/*import Cat from './components/Cat.svelte';*/
</script>

<main>
	<Section>
		<Type>Hello World!</Type>
	</Section>
	
	<Section >
		<Header />
	</Section>

	<!--<Cat/>-->

	<Section>
		<Title>About Me</Title>
		<About />
	</Section>


	<Section>
		<Title>Education</Title>
		<Education />
	</Section>

	<Section>
		<Title>Skills</Title>
		<Skills />
	</Section>

	<Section>
		<Title>Extracurricular Activities</Title>
		<Extracurricular />
	</Section>

	<Section>
		<Title>Contact</Title>
		<Contact/>
	</Section>

	<Wave/>


</main>

<style>
	main {
		/*text-align: center;*/
		padding: 1em;
		margin: 0 auto;
		background-color: #232946 ;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
	layout{
		left:30%
	}

</style>
