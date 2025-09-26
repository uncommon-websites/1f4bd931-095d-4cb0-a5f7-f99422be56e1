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
	title="What we do"
	text="We deliver authentic Korean beverage experiences by combining traditional brewing heritage with contemporary brand storytelling that resonates across cultural boundaries."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Chen",
			position: "Brand Director",
			company: "Zen Beverages",
			quote:
				"Bori helped us launch an authentic Korean tea line that Gen Z actually loves.\nOur sales exceeded expectations by 40% in the first quarter.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "David Kim",
			position: "Product Development Manager",
			company: "Heritage Drinks Co",
			quote:
				"Their cultural expertise prevented us from making costly authenticity mistakes.\nWe differentiated in the crowded tea market without falling into stereotypes.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jennifer Park",
			position: "Marketing Lead",
			company: "Modern Botanicals",
			quote:
				"The traditional brewing knowledge combined with contemporary branding was exactly what we needed.\nOur Korean-inspired line became our fastest-growing segment.",
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
<AboutTeaser />
<CallToAction 
	title="Start your brand's next chapter"
	subtitle="Traditional flavor meets modern story"
	description="Bring your beverage concept to life with the cultural depth and visual clarity it needs to win on shelf. We'll help you go from idea to authentic impact—without compromise."
	imageSrc="/generated/image-a-professional-asian-american-brand-mana.webp"
	callsToAction={[
		{
			href: "/about",
			label: "Partner with us",
			variant: "primary"
		},
		{
			href: "/about",
			label: "View case studies",
			variant: "secondary"
		}
	]}
/>
