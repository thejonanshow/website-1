<script lang="ts">
	import socrates from './partners/socrates.png';
	import frontmuc from './partners/munich-frontend-developers.webp';
	import seneca from './partners/seneca.png';
	import Sponsors from './Sponsors.svelte';
	const partners = [
		{
			image: frontmuc,
			link: 'https://www.meetup.com/de-DE/munich-frontend-developers/',
			name: 'Munich Frontend Developers'
		},
		{
			image: socrates,
			link: 'https://www.socrates-conference.de/',
			name: 'SoCraTes',
			sponsoring: 'August 24-27, 2023 - Hotel Park, Soltau'
		},
		{
			image: seneca,
			link: 'https://seneca.camp/',
			name: 'Seneca',
			sponsoring: 'September 22-24, 2023 - Medical Valley Center, Erlangen'
		}
	];
</script>

<Sponsors title="Our partner conferences" sponsors={partners} />
