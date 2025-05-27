<script>
	import { page } from '$app/state';
</script>

<svelte:head>
	<title>Get started with your new Trezor</title>
</svelte:head>

<div class="min-h-screen bg-white flex flex-col">
	<!-- Green banner -->
	<div class="bg-green-700 text-white text-center py-2 text-sm">
		Need help setting up your Trezor hardware wallet? Check out Trezor Expert.
	</div>

	<!-- Navigation -->
	<nav class="flex items-center justify-between px-6 py-4">
		<div class="flex items-center">
			<a href="/" class="text-2xl font-bold">TREZOR</a>
		</div>
		<div class="flex items-center space-x-6">
			<a href="/products" class="text-gray-600">Products</a>
			<a href="/app" class="text-gray-600">App</a>
			<a href="/coins" class="text-gray-600">Coins</a>
			<a href="/learn" class="text-gray-600">Learn & Support</a>
			<select class="bg-transparent">
				<option>USD</option>
			</select>
			<a href="/cart" class="text-gray-600">Cart (0)</a>
			<button class="bg-green-700 text-white px-4 py-2 rounded">Get your Trezor</button>
		</div>
	</nav>

	<!-- Main Content -->
	<main class="max-w-6xl mx-auto px-6 py-12 flex-grow">
		<h1 class="text-5xl font-bold mb-2">Get started</h1>
		<h2 class="text-5xl font-bold mb-8">with your new Trezor</h2>
		<p class="text-gray-600 mb-8">Download the Trezor Suite app and follow the steps to get started.</p>

		<div class="flex gap-4 mb-16">
			<button class="bg-green-700 text-white px-6 py-3 rounded">Download for desktop</button>
			<button class="bg-gray-100 text-gray-800 px-6 py-3 rounded">Continue in browser</button>
			<button class="bg-gray-100 text-gray-800 px-6 py-3 rounded">More</button>
		</div>

		<h2 class="text-4xl font-bold mb-12">This is how it works</h2>

		<div class="grid grid-cols-2 gap-8 mb-16">
			<div class="bg-gray-50 p-8 rounded-lg">
				<div class="flex items-center gap-4 mb-4">
					<span class="bg-gray-200 w-8 h-8 rounded-full flex items-center justify-center">1</span>
					<h3 class="text-xl font-bold">Download Trezor Suite</h3>
				</div>
				<p class="text-gray-600">Download Trezor Suite for desktop for the best experience, or click "Continue in browser" to open the web app.</p>
			</div>

			<div class="bg-gray-50 p-8 rounded-lg">
				<div class="flex items-center gap-4 mb-4">
					<span class="bg-gray-200 w-8 h-8 rounded-full flex items-center justify-center">2</span>
					<h3 class="text-xl font-bold">Install the app</h3>
				</div>
				<p class="text-gray-600">Install the desktop app on your computer. This step isn't necessary for web app users.</p>
			</div>

			<div class="bg-gray-50 p-8 rounded-lg">
				<div class="flex items-center gap-4 mb-4">
					<span class="bg-gray-200 w-8 h-8 rounded-full flex items-center justify-center">3</span>
					<h3 class="text-xl font-bold">Set up your Trezor</h3>
				</div>
				<p class="text-gray-600">Plug in your device and follow the steps to set up your Trezor hardware wallet. This takes about 15 minutes.</p>
			</div>

			<div class="bg-gray-50 p-8 rounded-lg">
				<div class="flex items-center gap-4 mb-4">
					<span class="bg-gray-200 w-8 h-8 rounded-full flex items-center justify-center">4</span>
					<h3 class="text-xl font-bold">Move your coins</h3>
				</div>
				<p class="text-gray-600">You're ready to protect your crypto securely. Check our guide to learn how to transfer your assets from an exchange to your Trezor.</p>
			</div>
		</div>

		<h2 class="text-4xl font-bold mb-12">Prefer expert guidance?</h2>

		<div class="flex gap-8 items-center">
			<div class="w-1/2">
				<img src="https://images.pexels.com/photos/4226140/pexels-photo-4226140.jpeg" alt="Expert guidance" class="rounded-lg w-full">
			</div>
			<div class="w-1/2">
				<h3 class="text-3xl font-bold mb-6">Get started with Trezor Expert</h3>
				<ul class="space-y-4 mb-8">
					<li class="flex items-center gap-2">
						<span class="text-green-700">✓</span>
						Personal 1:1 guide for Trezor hardware wallet setup
					</li>
					<li class="flex items-center gap-2">
						<span class="text-green-700">✓</span>
						60-minute live, online Trezor Expert Onboarding Session in English
					</li>
					<li class="flex items-center gap-2">
						<span class="text-green-700">✓</span>
						Available for all Trezor hardware wallets
					</li>
				</ul>
				<button class="bg-green-700 text-white px-6 py-3 rounded">Buy for USD 99</button>
				<p class="text-sm text-gray-500 mt-4">*It's necessary to have a Trezor device with you for this session</p>
			</div>
		</div>
	</main>

	<!-- Footer -->
	<footer class="bg-[#0C1810] text-white py-16">
		<div class="max-w-6xl mx-auto px-6">
			<div class="grid grid-cols-5 gap-8 mb-12">
				<div>
					<div class="mb-8">
						<a href="/" class="text-2xl font-bold text-white">TREZOR</a>
						<p class="text-sm text-gray-400 mt-2">a part of SatoshiLabs Group</p>
					</div>
				</div>
				<div>
					<h4 class="font-bold mb-4">Products</h4>
					<ul class="space-y-2 text-sm text-gray-400">
						<li><a href="/trezor-safe-3">Trezor Safe 3</a></li>
						<li><a href="/trezor-safe-5">Trezor Safe 5</a></li>
						<li><a href="/model-one">Model One</a></li>
						<li><a href="/model-t">Model T</a></li>
						<li><a href="/trezor-keep">Trezor Keep</a></li>
						<li><a href="/trezor-expert">Trezor Expert</a></li>
						<li><a href="/compare">Compare wallets</a></li>
						<li><a href="/trezor-suite">Trezor Suite</a></li>
						<li><a href="/accessories">All products & accessories</a></li>
					</ul>
				</div>
				<div>
					<h4 class="font-bold mb-4">Learn</h4>
					<ul class="space-y-2 text-sm text-gray-400">
						<li><a href="/supported-coins">Supported coins</a></li>
						<li><a href="/blog">Blog</a></li>
						<li><a href="/wallet-apps">Third-party wallet apps</a></li>
						<li><a href="/security">Privacy and Security</a></li>
						<li><a href="/about">About us</a></li>
						<li><a href="/support">Support</a></li>
						<li><a href="/knowledge-base">Knowledge Base</a></li>
						<li><a href="/forum">Forum</a></li>
					</ul>
				</div>
				<div>
					<h4 class="font-bold mb-4">Other</h4>
					<ul class="space-y-2 text-sm text-gray-400">
						<li><a href="/faq">FAQs</a></li>
						<li><a href="/terms">Terms of Use</a></li>
						<li><a href="/affiliate">Affiliate Program</a></li>
						<li><a href="/reseller">Reseller Program</a></li>
						<li><a href="/resellers">Resellers</a></li>
						<li><a href="/github">GitHub</a></li>
						<li><a href="/press">Press & Media</a></li>
						<li><a href="/careers">Careers</a></li>
					</ul>
				</div>
				<div>
					<h4 class="font-bold mb-4">Follow us</h4>
					<div class="flex gap-4">
						<a href="/twitter" class="text-gray-400 hover:text-white">X</a>
						<a href="/reddit" class="text-gray-400 hover:text-white">Reddit</a>
						<a href="/instagram" class="text-gray-400 hover:text-white">Instagram</a>
						<a href="/facebook" class="text-gray-400 hover:text-white">Facebook</a>
						<a href="/tiktok" class="text-gray-400 hover:text-white">TikTok</a>
					</div>
				</div>
			</div>
			<div class="flex justify-between items-center pt-8 border-t border-gray-800">
				<p class="text-sm text-gray-400">Copyright belongs to Trezor company s.r.o. All rights reserved.</p>
				<button class="text-sm text-gray-400">Cookies +</button>
			</div>
		</div>
	</footer>
</div>

<style>
	:global(body) {
		margin: 0;
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;
	}
</style>