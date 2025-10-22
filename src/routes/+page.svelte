<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Predictable Bitcoin yield through transparent credit markets"
	subtitle="Ring-fenced lending strategies connecting institutional Bitcoin treasuries with vetted trading counterparties under enforceable legal agreements."
	imageSrc="/generated/image-a-cozy-indoor-caf-environment-with-a-div.webp"
	callsToAction={[
		{ href: "/contact", label: "Get started" },
		{ href: "/about", label: "Learn more" }
	]}
/>
<LogoScroller
	label="Trusted by Bitcoin treasury leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/microstrategy.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/galaxy.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/coinbase.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/marathondhn.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Why Nexio exists"
	text="Bitcoin treasuries hold over $180 billion in assets that generate no return. Traditional DeFi markets offer unpredictable rates that spike overnight, while OTC lending hides counterparty risk behind opaque agreements. Nexio bridges this gap with ring-fenced credit markets that deliver fixed-rate Bitcoin yield through transparent, legally-backed lending to vetted trading firms."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "Chief Financial Officer",
			company: "Quantum Asset Management",
			quote:
				"Nexio transformed our Bitcoin treasury from idle capital into predictable yield. The ring-fenced vault structure gave our board the transparency they needed to approve BTC lending, and we're now generating 6.2% fixed returns with full on-chain visibility into collateralization.",
			image: "/generated/image-professional-asian-woman-cfo-headshot-bu.webp"
		},
		{
			name: "Rashid Al-Mansouri",
			position: "Head of Treasury Operations",
			company: "Citadel Family Office",
			quote:
				"After 2022, we refused to touch opaque OTC lending. Nexio's transparent counterparty vetting and enforceable legal covenants reduced our risk assessment time from weeks to days, while native BTC funding eliminated the FX friction that was costing us 40 basis points per cycle.",
			image: "/generated/image-professional-middle-eastern-man-treasury.webp"
		},
		{
			name: "Ayana Williams",
			position: "Director of Digital Assets",
			company: "Meridian Treasury Partners",
			quote:
				"The secondary liquidity feature was game-changing. We deployed $12M into a 6-month term but needed early exit after 3 months—Nexio's marketplace allowed us to exit at fair value without disrupting the borrower's positions. That flexibility made our CFO confident approving larger allocations.",
			image: "/generated/image-professional-black-woman-finance-directo.webp"
		}
	]}
/>

<Features
	title="Built for institutional Bitcoin treasuries"
	subtitle="Transparent credit infrastructure that delivers predictable yield without compromising control or visibility"
	features={[
		{
			title: "Ring-fenced strategy vaults",
			description:
				"Each lending vault is tied to a single, measurable strategy like CME basis or delta-neutral funding. Your BTC never crosses between strategies, ensuring transparent risk isolation and eliminating commingled pool exposure."
		},
		{
			title: "Predictable fixed-term yields",
			description:
				"Lock in transparent coupons with fixed terms that CFOs can budget around. No floating rate surprises or utilization-driven spikes—just the predictable BTC-denominated income treasuries need to justify balance sheet allocation."
		},
		{
			title: "Vetted counterparties under legal agreements",
			description:
				"All borrowers are KYC'd trading firms operating under signed legal covenants with enforceable recourse. Real-time on-chain visibility shows collateralization status and covenant compliance, replacing opaque OTC counterparty risk."
		},
		{
			title: "On-chain transparency with programmable rails",
			description:
				"Monitor utilization, collateral levels, and strategy performance in real time through on-chain reporting. Programmable infrastructure delivers the auditability treasurers demand with the control DeFi can't provide."
		},
		{
			title: "Native BTC funding for borrowers",
			description:
				"Trading desks access transparent BTC credit lines without FX friction or USD swap costs. Under-collateralized lines for top-tier desks mirror traditional credit markets, delivering efficient capital for market-making and basis strategies."
		},
		{
			title: "Secondary liquidity for lenders",
			description:
				"Exit positions early without disrupting borrower operations through secondary market liquidity. Maintain treasury flexibility while your BTC generates predictable yield in ring-fenced credit structures."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Turn idle Bitcoin into predictable yield"
	subtitle="Join the pilot program"
	description="Our proof-of-concept launches next month with vetted market-making desks and institutional lenders. Ring-fenced vaults, transparent collateralization, and enforceable legal agreements—delivered through the fixed-income infrastructure treasuries actually need."
	imageSrc="/generated/image-a-confident-finance-executive-sits-at-a-.webp"
	callsToAction={[
		{ href: "/contact", label: "Request early access", variant: "primary" },
		{ href: "/about", label: "Learn about our approach", variant: "secondary" }
	]}
/>
