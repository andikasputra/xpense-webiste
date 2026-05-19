<script lang="ts">
	import { Mail, Zap, Wallet, Layers, BarChart3, Shield, Smartphone } from 'lucide-svelte';
</script>

<!-- Hero Section -->
<section
	class="relative overflow-hidden bg-gradient-to-br from-blue-600 via-blue-500 to-indigo-600 px-4 py-20 sm:px-6 lg:px-8"
>
	<div class="mx-auto max-w-7xl">
		<div class="grid gap-12 lg:grid-cols-2 lg:gap-8">
			<!-- Left Column: Text -->
			<div class="flex flex-col justify-center">
				<h1 class="text-5xl font-bold tracking-tight text-white sm:text-6xl">
					Take Control of Your Money
				</h1>
				<p class="mt-6 text-xl text-blue-100">
					Xpense is a powerful income & expense tracker that works offline. Organize your finances
					across multiple projects and wallets with ease. Access it instantly at
					<span class="font-semibold">app.xpense.web.id</span>
				</p>
				<div class="mt-8 flex flex-wrap gap-4">
					<a
						href="https://app.xpense.web.id"
						target="_blank"
						rel="noopener noreferrer"
						class="inline-flex items-center rounded-lg bg-white px-8 py-3 font-semibold text-blue-600 shadow-lg transition hover:scale-105 hover:shadow-xl"
					>
						Launch App
					</a>
					<a
						href="#features"
						class="inline-flex items-center gap-2 rounded-lg border-2 border-white bg-transparent px-8 py-3 font-semibold text-white transition hover:bg-white hover:text-blue-600"
					>
						Explore Features
					</a>
				</div>
			</div>

			<!-- Right Column: Visual -->
			<div class="relative hidden lg:block">
				<div
					class="absolute inset-0 rotate-3 transform rounded-3xl bg-gradient-to-br from-blue-400 to-indigo-500"
				></div>
				<div class="relative rounded-3xl bg-white p-8 shadow-2xl">
					<div class="space-y-6">
						<div class="flex items-center gap-4">
							<div class="rounded-lg bg-blue-100 p-3">
								<Wallet class="text-blue-600" size={24} />
							</div>
							<div>
								<p class="text-sm font-medium text-gray-600">Total Balance</p>
								<p class="text-2xl font-bold text-gray-900">$12,450.50</p>
							</div>
						</div>
						<div class="h-px bg-gray-200"></div>
						<div class="grid grid-cols-2 gap-4">
							<div>
								<p class="text-sm text-gray-600">Income</p>
								<p class="text-xl font-bold text-green-600">+$5,200</p>
							</div>
							<div>
								<p class="text-sm text-gray-600">Expenses</p>
								<p class="text-xl font-bold text-red-600">-$1,850</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- Features Section -->
<section id="features" class="bg-white px-4 py-20 sm:px-6 lg:px-8">
	<div class="mx-auto max-w-7xl">
		<div class="mb-16 text-center">
			<h2 class="mb-4 text-4xl font-bold text-gray-900">Powerful Features</h2>
			<p class="text-xl text-gray-600">Everything you need to manage your finances effectively</p>
		</div>

		<div class="grid gap-8 md:grid-cols-2 lg:grid-cols-3">
			<!-- Feature: Multiple Projects -->
			<div class="group relative">
				<div
					class="absolute inset-0 rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 opacity-0 blur transition duration-300 group-hover:opacity-100"
				></div>
				<div
					class="relative rounded-2xl border border-gray-200 bg-white p-8 transition hover:border-transparent"
				>
					<div
						class="mb-4 inline-flex h-12 w-12 items-center justify-center rounded-lg bg-blue-100"
					>
						<Layers class="text-blue-600" size={24} />
					</div>
					<h3 class="mb-2 text-xl font-bold text-gray-900">Multiple Projects</h3>
					<p class="text-gray-600">
						Create separate projects for different areas of your life - personal, business,
						investments, or more.
					</p>
				</div>
			</div>

			<!-- Feature: Multi-Wallet Support -->
			<div class="group relative">
				<div
					class="absolute inset-0 rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 opacity-0 blur transition duration-300 group-hover:opacity-100"
				></div>
				<div
					class="relative rounded-2xl border border-gray-200 bg-white p-8 transition hover:border-transparent"
				>
					<div
						class="mb-4 inline-flex h-12 w-12 items-center justify-center rounded-lg bg-green-100"
					>
						<Wallet class="text-green-600" size={24} />
					</div>
					<h3 class="mb-2 text-xl font-bold text-gray-900">Multiple Wallets</h3>
					<p class="text-gray-600">
						Track different accounts - savings, checking, credit cards, cash - all in one place.
					</p>
				</div>
			</div>

			<!-- Feature: Smart Categories -->
			<div class="group relative">
				<div
					class="absolute inset-0 rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 opacity-0 blur transition duration-300 group-hover:opacity-100"
				></div>
				<div
					class="relative rounded-2xl border border-gray-200 bg-white p-8 transition hover:border-transparent"
				>
					<div
						class="mb-4 inline-flex h-12 w-12 items-center justify-center rounded-lg bg-purple-100"
					>
						<BarChart3 class="text-purple-600" size={24} />
					</div>
					<h3 class="mb-2 text-xl font-bold text-gray-900">Smart Categories</h3>
					<p class="text-gray-600">
						Organize transactions with custom categories for better insights and analysis.
					</p>
				</div>
			</div>

			<!-- Feature: Offline Mode -->
			<div class="group relative">
				<div
					class="absolute inset-0 rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 opacity-0 blur transition duration-300 group-hover:opacity-100"
				></div>
				<div
					class="relative rounded-2xl border border-gray-200 bg-white p-8 transition hover:border-transparent"
				>
					<div
						class="mb-4 inline-flex h-12 w-12 items-center justify-center rounded-lg bg-orange-100"
					>
						<Zap class="text-orange-600" size={24} />
					</div>
					<h3 class="mb-2 text-xl font-bold text-gray-900">Offline Support</h3>
					<p class="text-gray-600">
						Work without internet. Your data is stored locally and syncs when you're back online.
					</p>
				</div>
			</div>

			<!-- Feature: Real-time Insights -->
			<div class="group relative">
				<div
					class="absolute inset-0 rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 opacity-0 blur transition duration-300 group-hover:opacity-100"
				></div>
				<div
					class="relative rounded-2xl border border-gray-200 bg-white p-8 transition hover:border-transparent"
				>
					<div class="mb-4 inline-flex h-12 w-12 items-center justify-center rounded-lg bg-red-100">
						<BarChart3 class="text-red-600" size={24} />
					</div>
					<h3 class="mb-2 text-xl font-bold text-gray-900">Real-time Analytics</h3>
					<p class="text-gray-600">
						Get instant insights into your spending patterns with beautiful charts and reports.
					</p>
				</div>
			</div>

			<!-- Feature: Data Privacy -->
			<div class="group relative">
				<div
					class="absolute inset-0 rounded-2xl bg-gradient-to-r from-blue-600 to-indigo-600 opacity-0 blur transition duration-300 group-hover:opacity-100"
				></div>
				<div
					class="relative rounded-2xl border border-gray-200 bg-white p-8 transition hover:border-transparent"
				>
					<div
						class="mb-4 inline-flex h-12 w-12 items-center justify-center rounded-lg bg-indigo-100"
					>
						<Shield class="text-indigo-600" size={24} />
					</div>
					<h3 class="mb-2 text-xl font-bold text-gray-900">Privacy First</h3>
					<p class="text-gray-600">
						Your financial data stays on your device. We never collect or share your information.
					</p>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- Benefits Section -->
<section class="bg-gradient-to-br from-gray-50 to-gray-100 px-4 py-20 sm:px-6 lg:px-8">
	<div class="mx-auto max-w-7xl">
		<div class="grid items-center gap-12 lg:grid-cols-2">
			<!-- Left: Benefits List -->
			<div>
				<h2 class="mb-8 text-4xl font-bold text-gray-900">Why Choose Xpense?</h2>

				<div class="space-y-6">
					<div class="flex gap-4">
						<div class="flex-shrink-0">
							<div class="flex h-10 w-10 items-center justify-center rounded-lg bg-blue-600">
								<span class="font-bold text-white">✓</span>
							</div>
						</div>
						<div>
							<h3 class="text-lg font-semibold text-gray-900">Complete Financial Control</h3>
							<p class="mt-2 text-gray-600">
								Manage all aspects of your finances in one unified platform.
							</p>
						</div>
					</div>

					<div class="flex gap-4">
						<div class="flex-shrink-0">
							<div class="flex h-10 w-10 items-center justify-center rounded-lg bg-green-600">
								<span class="font-bold text-white">✓</span>
							</div>
						</div>
						<div>
							<h3 class="text-lg font-semibold text-gray-900">Works Anywhere, Anytime</h3>
							<p class="mt-2 text-gray-600">
								Track expenses on the go, even without an internet connection.
							</p>
						</div>
					</div>

					<div class="flex gap-4">
						<div class="flex-shrink-0">
							<div class="flex h-10 w-10 items-center justify-center rounded-lg bg-purple-600">
								<span class="font-bold text-white">✓</span>
							</div>
						</div>
						<div>
							<h3 class="text-lg font-semibold text-gray-900">Simple Yet Powerful</h3>
							<p class="mt-2 text-gray-600">
								Intuitive interface that's easy to use, but packed with advanced features.
							</p>
						</div>
					</div>

					<div class="flex gap-4">
						<div class="flex-shrink-0">
							<div class="flex h-10 w-10 items-center justify-center rounded-lg bg-orange-600">
								<span class="font-bold text-white">✓</span>
							</div>
						</div>
						<div>
							<h3 class="text-lg font-semibold text-gray-900">100% Private & Secure</h3>
							<p class="mt-2 text-gray-600">
								Your data belongs to you. No tracking, no ads, no data selling.
							</p>
						</div>
					</div>

					<div class="flex gap-4">
						<div class="flex-shrink-0">
							<div class="flex h-10 w-10 items-center justify-center rounded-lg bg-indigo-600">
								<span class="font-bold text-white">✓</span>
							</div>
						</div>
						<div>
							<h3 class="text-lg font-semibold text-gray-900">Always Free</h3>
							<p class="mt-2 text-gray-600">
								All features are free forever. No hidden charges or premium upgrades.
							</p>
						</div>
					</div>
				</div>
			</div>

			<!-- Right: Feature Showcase -->
			<div class="relative">
				<div class="rounded-2xl border border-gray-200 bg-white p-8 shadow-xl">
					<div class="mb-6 flex items-center gap-2">
						<Smartphone class="text-blue-600" size={28} />
						<h3 class="text-2xl font-bold text-gray-900">Access Anywhere, Anytime</h3>
					</div>
					<p class="mb-6 text-gray-600">
						Access Xpense from any device with a web browser. Whether you're on your phone, tablet,
						or desktop, your financial data is always available. Just visit
						<span class="font-semibold text-blue-600">app.xpense.web.id</span> to get started.
					</p>
					<div class="space-y-4">
						<div class="rounded-lg bg-blue-50 p-4">
							<p class="text-sm font-semibold text-blue-900">🌐 Web-Based</p>
							<p class="mt-1 text-sm text-blue-800">
								Access your finances from any browser, no installation needed
							</p>
						</div>
						<div class="rounded-lg bg-green-50 p-4">
							<p class="text-sm font-semibold text-green-900">📱 Responsive Design</p>
							<p class="mt-1 text-sm text-green-800">
								Perfect experience on mobile, tablet, or desktop
							</p>
						</div>
						<div class="rounded-lg bg-purple-50 p-4">
							<p class="text-sm font-semibold text-purple-900">⚡ Instant Access</p>
							<p class="mt-1 text-sm text-purple-800">
								No app store needed, works with just a web link
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<!-- Use Cases Section -->
<section class="bg-white px-4 py-20 sm:px-6 lg:px-8">
	<div class="mx-auto max-w-7xl">
		<div class="mb-16 text-center">
			<h2 class="mb-4 text-4xl font-bold text-gray-900">Who Uses Xpense?</h2>
			<p class="text-xl text-gray-600">Perfect for any financial tracking need</p>
		</div>

		<div class="grid gap-6 md:grid-cols-2 lg:grid-cols-3">
			<!-- Use Case 1 -->
			<div
				class="rounded-xl border border-blue-200 bg-gradient-to-br from-blue-50 to-indigo-50 p-6"
			>
				<h3 class="mb-2 text-xl font-bold text-gray-900">💰 Personal Finance</h3>
				<p class="text-gray-700">
					Track daily expenses, income, and manage your household budget effectively.
				</p>
			</div>

			<!-- Use Case 2 -->
			<div
				class="rounded-xl border border-green-200 bg-gradient-to-br from-green-50 to-emerald-50 p-6"
			>
				<h3 class="mb-2 text-xl font-bold text-gray-900">🏢 Freelancers</h3>
				<p class="text-gray-700">
					Separate projects for different clients and track income per project.
				</p>
			</div>

			<!-- Use Case 3 -->
			<div
				class="rounded-xl border border-purple-200 bg-gradient-to-br from-purple-50 to-pink-50 p-6"
			>
				<h3 class="mb-2 text-xl font-bold text-gray-900">👨‍👩‍👧‍👦 Family Budget</h3>
				<p class="text-gray-700">
					Manage shared expenses and track spending across family members.
				</p>
			</div>

			<!-- Use Case 4 -->
			<div
				class="rounded-xl border border-orange-200 bg-gradient-to-br from-orange-50 to-red-50 p-6"
			>
				<h3 class="mb-2 text-xl font-bold text-gray-900">🎯 Side Hustlers</h3>
				<p class="text-gray-700">Keep track of multiple income streams and business expenses.</p>
			</div>

			<!-- Use Case 5 -->
			<div class="rounded-xl border border-cyan-200 bg-gradient-to-br from-cyan-50 to-blue-50 p-6">
				<h3 class="mb-2 text-xl font-bold text-gray-900">🏠 Home Projects</h3>
				<p class="text-gray-700">
					Track renovation or home improvement project budgets and spending.
				</p>
			</div>

			<!-- Use Case 6 -->
			<div
				class="rounded-xl border border-yellow-200 bg-gradient-to-br from-yellow-50 to-amber-50 p-6"
			>
				<h3 class="mb-2 text-xl font-bold text-gray-900">✈️ Travel Planning</h3>
				<p class="text-gray-700">
					Create a project for each trip and track expenses across different currencies.
				</p>
			</div>
		</div>
	</div>
</section>

<!-- CTA Section -->
<section
	id="download"
	class="bg-gradient-to-r from-blue-600 to-indigo-600 px-4 py-20 sm:px-6 lg:px-8"
>
	<div class="mx-auto max-w-4xl text-center">
		<h2 class="mb-4 text-4xl font-bold text-white">Ready to Take Control?</h2>
		<p class="mb-8 text-xl text-blue-100">
			Start managing your finances better today. Access Xpense directly from your browser and enjoy
			powerful expense tracking that works offline.
		</p>
		<div class="flex flex-wrap justify-center gap-4">
			<a
				href="https://app.xpense.web.id"
				target="_blank"
				rel="noopener noreferrer"
				class="inline-flex items-center gap-2 rounded-lg bg-white px-8 py-4 font-semibold text-blue-600 shadow-lg transition hover:scale-105 hover:shadow-xl"
			>
				<span class="text-lg">🚀</span>
				Start Using Xpense
			</a>
			<a
				href="#features"
				class="inline-flex items-center gap-2 rounded-lg border-2 border-white bg-transparent px-8 py-4 font-semibold text-white transition hover:bg-white hover:text-blue-600"
			>
				Learn More
			</a>
		</div>
	</div>
</section>

<!-- Footer -->
<footer class="bg-gray-900 px-4 py-12 text-gray-400 sm:px-6 lg:px-8">
	<div class="mx-auto max-w-7xl">
		<div class="mb-8 grid gap-8 md:grid-cols-4">
			<div>
				<h3 class="mb-4 text-lg font-bold text-white">Xpense</h3>
				<p class="text-sm">Your personal income & expense tracker with offline support.</p>
			</div>
			<div>
				<h4 class="mb-4 font-semibold text-white">Product</h4>
				<ul class="space-y-2 text-sm">
					<li><a href="#features" class="transition hover:text-white">Features</a></li>
					<li><a href="#" class="transition hover:text-white">Pricing</a></li>
					<li><a href="#" class="transition hover:text-white">FAQ</a></li>
				</ul>
			</div>
			<div>
				<h4 class="mb-4 font-semibold text-white">Company</h4>
				<ul class="space-y-2 text-sm">
					<li><a href="#" class="transition hover:text-white">About</a></li>
					<li><a href="#" class="transition hover:text-white">Blog</a></li>
					<li><a href="#" class="transition hover:text-white">Contact</a></li>
				</ul>
			</div>
			<div>
				<h4 class="mb-4 font-semibold text-white">Legal</h4>
				<ul class="space-y-2 text-sm">
					<li><a href="#" class="transition hover:text-white">Privacy</a></li>
					<li><a href="#" class="transition hover:text-white">Terms</a></li>
				</ul>
			</div>
		</div>

		<div class="border-t border-gray-800 pt-8">
			<div class="flex flex-col items-center justify-between md:flex-row">
				<p class="text-sm">&copy; 2024 Xpense. All rights reserved.</p>
				<div class="mt-4 flex gap-6 md:mt-0">
					<a href="#" class="text-gray-400 transition hover:text-white">
						<svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24"
							><path
								d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2s9 5 20 5a9.5 9.5 0 00-9-5.5c4.75 2.25 7-7 7-7"
							/></svg
						>
					</a>
					<a href="#" class="text-gray-400 transition hover:text-white">
						<svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24"
							><path
								d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24h-6.657l-5.07-6.61-5.848 6.61H2.18l7.732-8.835L1.254 2.25h6.554l4.596 6.084 5.313-6.084zM17.15 18.75h1.828L5.293 3.75H3.36z"
							/></svg
						>
					</a>
					<a href="#" class="text-gray-400 transition hover:text-white">
						<svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24"
							><path
								d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v 3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
							/></svg
						>
					</a>
				</div>
			</div>
		</div>
	</div>
</footer>
