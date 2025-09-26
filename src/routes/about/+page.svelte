<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Cultural authenticity",
			description: "Deep roots in Korean tea brewing traditions meet modern brand thinking that resonates with today's consumers."
		},
		{
			title: "Modern shelf appeal",
			description: "Creating designs and visuals that stop the scroll and catch the eye in crowded retail spaces."
		},
		{
			title: "Market-ready strategy", 
			description: "Built-in appeal for Gen Z, Korean-American, and health-conscious consumers who seek genuine cultural experiences."
		},
		{
			title: "Heritage innovation",
			description: "Traditional ingredients like barley, omija, and yuzu reimagined with clean labels and contemporary packaging."
		}
	];
</script>

<SecondaryHero
	generating
	title="Solving world hunger"
	subtitle="one step at a time"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	generating
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our founders."
	subtitle="Bringing authentic Korean tradition to modern beverage culture."
	stakeholders={[
		{
			name: "Erica Silver",
			position: "Co-founder",
			bio: "Passionate about creating authentic beverage experiences that honor Korean heritage while appealing to contemporary tastes.",
			image: "/generated/image-professional-businesswoman-founder-portr.webp"
		},
		{
			name: "Jusung Kim",
			position: "Co-founder",
			bio: "Expert in traditional Korean brewing methods with a vision for bringing ancestral techniques to global markets.",
			image: "/generated/image-professional-korean-businessman-founder-.webp"
		},
		{
			name: "Deborah Kim",
			position: "Co-founder",
			bio: "Brand strategist focused on authentic storytelling that bridges cultural traditions with modern consumer experiences.",
			image: "/generated/image-professional-korean-american-businesswom.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to launch your next beverage?"
	subtitle="Let's build something authentic together"
	description="Join the emerging beverage brands working with us to create Korean-inspired drinks that resonate with modern consumers and stand out in crowded retail spaces."
	imageSrc="/generated/image-a-young-korean-american-woman-relaxing-i.webp"
/>
