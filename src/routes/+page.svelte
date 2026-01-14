<script lang="ts">
	import { onMount } from 'svelte';

	let scrollY = 0;
</script>

<svelte:window bind:scrollY />

<div class="font-sans text-gray-900 antialiased selection:bg-primary-200 selection:text-primary-900">
	<!-- Hero Section -->
	<section class="relative min-h-screen w-full bg-gradient-to-b from-gray-950 via-gray-900 to-white text-white px-6 md:px-12 lg:px-24 pt-32 pb-24 flex flex-col justify-between">
		<div class="max-w-5xl">
			<h1 class="font-serif text-5xl md:text-7xl lg:text-8xl leading-[1.1] md:leading-[1.1] tracking-tight">
				Transform your startup idea into a functional digital product.
			</h1>
			<p class="mt-8 text-xl md:text-2xl text-gray-300 max-w-3xl">
				Taylor Labs combines thoughtful design with solid engineering to bring your vision to life.
			</p>
		</div>

		<div class="mt-24 flex gap-4">
			<a href="#services" class="inline-flex items-center justify-center px-6 py-3 bg-primary-500 hover:bg-primary-600 text-white rounded-md text-sm font-medium transition-colors duration-300">
				See our services
			</a>
			<a href="#contact" class="inline-flex items-center justify-center px-6 py-3 border border-white/30 rounded-md text-sm font-medium hover:bg-white hover:text-gray-950 transition-colors duration-300 backdrop-blur-sm">
				Get in touch
			</a>
		</div>
	</section>

    <!-- Services Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24" id="services">
        <div class="mb-12 md:mb-16">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900">What we do</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl">
            <!-- Service 1: Website Design & Development -->
            <div class="space-y-4">
                <h3 class="font-serif text-2xl text-gray-900">Website Design & Development</h3>
                <p class="text-gray-600 leading-relaxed">
                    Professional websites that establish credibility and attract customers.
                </p>
            </div>

            <!-- Service 2: Software Development -->
            <div class="space-y-4">
                <h3 class="font-serif text-2xl text-gray-900">Software Development</h3>
                <p class="text-gray-600 leading-relaxed">
                    Custom software solutions built with clean code and solid engineering.
                </p>
            </div>

            <!-- Service 3: Rapid Prototyping -->
            <div class="space-y-4">
                <h3 class="font-serif text-2xl text-gray-900">Same-Day Mockups</h3>
                <p class="text-gray-600 leading-relaxed">
                    See your vision come to life before development begins.
                </p>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="bg-white px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <h2 class="font-serif text-3xl md:text-4xl text-gray-900 mb-12">How we work</h2>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl">
            <!-- Discovery -->
            <div class="space-y-3">
                <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center mb-4">
                    <span class="text-xl font-bold text-primary-600">1</span>
                </div>
                <h3 class="text-lg font-semibold text-gray-900">Discovery</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We understand your vision and create a clear roadmap.
                </p>
            </div>

            <!-- Design -->
            <div class="space-y-3">
                <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center mb-4">
                    <span class="text-xl font-bold text-primary-600">2</span>
                </div>
                <h3 class="text-lg font-semibold text-gray-900">Design</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We craft intuitive interfaces with same-day mockups.
                </p>
            </div>

            <!-- Development -->
            <div class="space-y-3">
                <div class="w-10 h-10 bg-primary-100 rounded-lg flex items-center justify-center mb-4">
                    <span class="text-xl font-bold text-primary-600">3</span>
                </div>
                <h3 class="text-lg font-semibold text-gray-900">Development</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We build fast, reliable solutions with clean code.
                </p>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <div class="mb-12">
            <h2 class="font-serif text-3xl md:text-4xl text-gray-900">Why work with Taylor Labs</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl">
            <!-- Reason 1 -->
            <div class="space-y-3">
                <h3 class="text-lg font-semibold text-gray-900">Fast Turnaround</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    Same-day mockups and rapid development cycles.
                </p>
            </div>

            <!-- Reason 2 -->
            <div class="space-y-3">
                <h3 class="text-lg font-semibold text-gray-900">Technical Expertise</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    Computer science training with hands-on development experience.
                </p>
            </div>

            <!-- Reason 3 -->
            <div class="space-y-3">
                <h3 class="text-lg font-semibold text-gray-900">Direct Communication</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    Work directly with the founder throughout your project.
                </p>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="px-6 md:px-12 lg:px-24 py-12">
        <div class="bg-gradient-to-br from-primary-50 to-primary-100 rounded-2xl p-8 md:p-16 lg:p-20 border border-primary-200">
            <h3 class="font-serif text-2xl md:text-3xl text-gray-900 mb-4">Ready to bring your idea to life?</h3>
            <p class="text-gray-700 mb-8 max-w-md">Let's talk about your project. Get a same-day response and see how we can help transform your vision into reality.</p>
            
            <div class="flex flex-col sm:flex-row gap-4">
                <a href="mailto:hello@taylorlabs.co" class="inline-flex items-center justify-center px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-md text-sm font-medium transition-colors">
                    Email us
                </a>
                <a href="tel:+13602071844" class="inline-flex items-center justify-center px-6 py-3 bg-white border border-primary-300 hover:border-primary-400 text-gray-900 rounded-md text-sm font-medium transition-colors">
                    Call or text
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="relative bg-gradient-to-b from-gray-900 via-gray-800 to-gray-950 pt-32 pb-48 px-6 md:px-12 lg:px-24 overflow-hidden">
        <div class="max-w-4xl relative z-10">
            <h2 class="font-serif text-4xl md:text-5xl lg:text-6xl text-white leading-tight mb-8">
                Technical expertise meets thoughtful design.
            </h2>
            <p class="text-xl md:text-2xl text-gray-300 leading-relaxed">
                Taylor Labs was founded by Evan Taylor, who studied Computer Science at Cal Poly with a passion for building exceptional digital experiences. We combine solid engineering fundamentals with modern design principles to create websites and software solutions that help businesses thrive.
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-950 text-gray-300 px-6 md:px-12 lg:px-24 pt-24 pb-12 relative overflow-hidden" id="contact">
        <div class="relative z-10">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-24">
                <div class="col-span-1 md:col-span-2">
                    <h3 class="text-3xl md:text-4xl font-serif text-white mb-6">Let's work together</h3>
                    <p class="text-gray-400 mb-8 max-w-lg">
                        Whether you're just starting out or ready to scale, we're here to help bring your digital product to life.
                    </p>
                </div>
                
                <div class="space-y-4">
                    <h4 class="font-medium text-white">San Luis Obispo, CA</h4>
                    <div class="pt-4 text-sm space-y-2">
                        <p>
                            <a href="mailto:hello@taylorlabs.co" class="hover:text-primary-400 transition-colors">
                                hello@taylorlabs.co
                            </a>
                        </p>
                        <p>
                            <a href="tel:+13602071844" class="hover:text-primary-400 transition-colors">
                                (360) 207-1844
                            </a>
                        </p>
                        <p class="mt-4 text-gray-500">
                            2261 Market Street #86329<br>
                            San Francisco, CA 94114
                        </p>
                    </div>
                </div>
            </div>

            <div class="flex flex-col md:flex-row justify-between items-start md:items-center border-t border-gray-800 pt-8 gap-4">
                <div class="mb-4 md:mb-0">
                    <span class="text-2xl font-serif text-white">Taylor Labs</span>
                </div>
                
                <div class="flex gap-6 text-xs font-medium">
                    <a href="https://linkedin.com" target="_blank" rel="noopener noreferrer" class="hover:text-primary-400 transition-colors">LinkedIn</a>
                    <a href="https://twitter.com" target="_blank" rel="noopener noreferrer" class="hover:text-primary-400 transition-colors">Twitter</a>
                </div>
            </div>

            <div class="flex flex-col md:flex-row justify-between text-xs text-gray-500 mt-12 gap-2">
                <p>© 2024 Taylor Labs. All rights reserved.</p>
                <p>Modern websites and custom software solutions.</p>
            </div>
        </div>
    </footer>
</div>

<style>
    /* Custom utility for vertical writing mode */
    .writing-vertical-rl {
        writing-mode: vertical-rl;
    }
</style>

