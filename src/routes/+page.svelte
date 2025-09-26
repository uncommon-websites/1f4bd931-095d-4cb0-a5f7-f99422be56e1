<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Tradition that tastes like today"
	subtitle="Authentic Korean teas. Modern brand appeal."
	imageSrc="/generated/image-a-young-korean-american-woman-sits-at-a-.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/wholefoods.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/target.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hmart.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/traderjoes.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Why brands choose Bori"
	subtitle="Authentic Korean tradition meets modern market appeal"
	features={[
		{
			title: "Cultural authenticity guaranteed",
			description:
				"Every recipe draws from centuries-old Korean brewing traditions, validated by heritage experts. Your brand gains genuine cultural credibility that resonates with discerning consumers."
		},
		{
			title: "Gen Z storytelling mastery",
			description:
				"We craft narratives that bridge traditional heritage with contemporary values that Gen Z craves. Your beverage becomes a cultural bridge, not just a product."
		},
		{
			title: "Traditional brewing excellence",
			description:
				"Our co-founders bring authentic Korean fermentation knowledge passed down through generations. Quality and tradition flow through every batch."
		},
		{
			title: "Market differentiation strategy",
			description:
				"Stand out in the $47B global tea market with positioning that avoids generic Asian stereotypes. We help you claim authentic cultural space competitors can't replicate."
		},
		{
			title: "Cross-cultural appeal design",
			description:
				"Visual identity that honors Korean aesthetics while appealing to diverse American palates. Your brand speaks to heritage seekers and modern consumers alike."
		},
		{
			title: "Quality assurance process",
			description:
				"Every beverage undergoes rigorous testing to ensure authentic taste profiles meet modern food safety standards. Tradition and reliability in every sip."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
