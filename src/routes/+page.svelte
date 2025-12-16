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
			<a href="#services" class="inline-flex items-center justify-center px-6 py-3 bg-primary-500 hover:bg-primary-600 text-white rounded-full text-sm font-medium transition-colors duration-300">
				See our services
			</a>
			<a href="#contact" class="inline-flex items-center justify-center px-6 py-3 border border-white/30 rounded-full text-sm font-medium hover:bg-white hover:text-gray-950 transition-colors duration-300 backdrop-blur-sm">
				Get in touch
			</a>
		</div>
	</section>

	<!-- Value Proposition -->
	<section class="bg-white px-6 md:px-12 lg:px-24 py-16 md:py-24">
		<div class="max-w-4xl mx-auto text-center">
			<p class="text-lg md:text-xl text-gray-600 mb-8">
				Starting with Cal Poly startups and scaling through the $40B web services market
			</p>
			<p class="text-base text-gray-500 max-w-2xl mx-auto">
				We help startup founders who need professional websites but lack technical resources or design expertise. From same-day mockups to fully functional products.
			</p>
		</div>
	</section>

    <!-- Services Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24" id="services">
        <div class="mb-16 md:mb-24">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900">What we do</h2>
            <p class="mt-4 text-lg text-gray-600 max-w-2xl">
                From initial concept to final launch, we handle every aspect of bringing your digital product to life.
            </p>
        </div>

        <div class="space-y-24 md:space-y-32">
            <!-- Service 1: Website Design & Development -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Website Design & Development</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Professional websites that make a lasting impression. We create responsive, user-friendly sites that help startups establish credibility and attract customers.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Responsive Design</span>
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Modern Stack</span>
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">SEO Optimized</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-white rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-designer-sketching-website-wireframes-on-1765907064725-2.webp" alt="Website design process" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Service 2: Software Development -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6 lg:order-2">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Software Development</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Custom software solutions built with clean code and solid engineering principles. We transform complex ideas into reliable, scalable digital products.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Full Stack</span>
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Scalable</span>
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Secure</span>
                    </div>
                </div>
                <div class="lg:col-span-8 lg:order-1">
                    <div class="aspect-[16/9] bg-gray-950 rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-developer-coding-on-dual-monitors-with-c-1765907067230-3.webp" alt="Software development" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>

            <!-- Service 3: Rapid Prototyping -->
            <div class="group grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-4 space-y-6">
                    <h3 class="font-serif text-3xl md:text-4xl text-gray-900">Same-Day Mockups</h3>
                    <p class="text-gray-600 text-lg leading-relaxed">
                        Overcome design hesitation with rapid prototyping. We create same-day mockups that help you visualize your product and make confident decisions quickly.
                    </p>
                    <div class="flex flex-wrap gap-2 pt-2">
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Fast Turnaround</span>
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Iterative</span>
                        <span class="px-3 py-1 bg-primary-50 text-primary-700 rounded-full text-xs font-medium">Collaborative</span>
                    </div>
                </div>
                <div class="lg:col-span-8">
                    <div class="aspect-[16/9] bg-white rounded-lg overflow-hidden relative group-hover:scale-[1.02] transition-transform duration-500 ease-out shadow-lg">
                        <img src="/generated/image-startup-team-collaborating-around-laptop-1765907062245-1.webp" alt="Collaborative design process" class="w-full h-full object-cover" />
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Process Section -->
    <section class="bg-white px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl text-gray-900 mb-16 max-w-3xl">How we work</h2>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Discovery -->
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-200 hover:border-primary-300 transition-all duration-300 flex flex-col h-full">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <span class="text-2xl font-bold text-primary-600">1</span>
                </div>
                <h3 class="text-xl font-semibold mb-4 text-gray-900">Discovery</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We start by understanding your vision, target audience, and business goals. Through collaborative discussions, we define the scope and create a clear roadmap for your project.
                </p>
            </div>

            <!-- Design -->
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-200 hover:border-primary-300 transition-all duration-300 flex flex-col h-full">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <span class="text-2xl font-bold text-primary-600">2</span>
                </div>
                <h3 class="text-xl font-semibold mb-4 text-gray-900">Design</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We craft intuitive, beautiful interfaces that align with your brand. With same-day mockups and iterative feedback, you'll see your vision come to life quickly.
                </p>
            </div>

            <!-- Development -->
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-200 hover:border-primary-300 transition-all duration-300 flex flex-col h-full">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <span class="text-2xl font-bold text-primary-600">3</span>
                </div>
                <h3 class="text-xl font-semibold mb-4 text-gray-900">Development</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We build your product with clean, maintainable code using modern technologies. The result is a fast, reliable, and scalable solution ready for real users.
                </p>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="bg-gray-50 px-6 md:px-12 lg:px-24 py-12 md:py-24">
        <div class="mb-12">
            <h2 class="font-serif text-3xl md:text-4xl text-gray-900">Why work with Taylor Labs</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Reason 1 -->
            <div class="bg-white p-8 rounded-lg border border-gray-200">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                    </svg>
                </div>
                <h3 class="text-lg font-semibold text-gray-900 mb-3">Fast Turnaround</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    Same-day mockups and rapid development cycles mean you can launch faster and start validating your idea with real users.
                </p>
            </div>

            <!-- Reason 2 -->
            <div class="bg-white p-8 rounded-lg border border-gray-200">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                </div>
                <h3 class="text-lg font-semibold text-gray-900 mb-3">Technical Expertise</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    Computer science training combined with hands-on development experience ensures reliable, well-architected solutions.
                </p>
            </div>

            <!-- Reason 3 -->
            <div class="bg-white p-8 rounded-lg border border-gray-200">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1" />
                    </svg>
                </div>
                <h3 class="text-lg font-semibold text-gray-900 mb-3">Startup-Focused</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We understand startup constraints and priorities. Our solutions are designed to scale as you grow, without breaking the bank.
                </p>
            </div>

            <!-- Reason 4 -->
            <div class="bg-white p-8 rounded-lg border border-gray-200">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z" />
                    </svg>
                </div>
                <h3 class="text-lg font-semibold text-gray-900 mb-3">Direct Communication</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    Work directly with the founder. No account managers or middlemen—just clear, responsive communication throughout your project.
                </p>
            </div>

            <!-- Reason 5 -->
            <div class="bg-white p-8 rounded-lg border border-gray-200">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
                    </svg>
                </div>
                <h3 class="text-lg font-semibold text-gray-900 mb-3">Modern Tech Stack</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    We use cutting-edge technologies and best practices to build fast, secure, and maintainable applications that stand the test of time.
                </p>
            </div>

            <!-- Reason 6 -->
            <div class="bg-white p-8 rounded-lg border border-gray-200">
                <div class="w-12 h-12 bg-primary-100 rounded-lg flex items-center justify-center mb-6">
                    <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                    </svg>
                </div>
                <h3 class="text-lg font-semibold text-gray-900 mb-3">Founder Mindset</h3>
                <p class="text-gray-600 text-sm leading-relaxed">
                    As a student founder, I understand the challenges you face. We're not just building websites—we're helping you build your business.
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
                <a href="mailto:hello@taylorlabs.co" class="inline-flex items-center justify-center px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors">
                    Email us
                </a>
                <a href="tel:+13602071844" class="inline-flex items-center justify-center px-6 py-3 bg-white border border-primary-300 hover:border-primary-400 text-gray-900 rounded-lg text-sm font-medium transition-colors">
                    Call or text
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="relative bg-gradient-to-b from-gray-900 via-gray-800 to-gray-950 pt-32 pb-48 px-6 md:px-12 lg:px-24 overflow-hidden">
        <div class="max-w-4xl relative z-10">
            <h2 class="font-serif text-4xl md:text-5xl lg:text-6xl text-white leading-tight mb-8">
                Built by a founder, for founders.
            </h2>
            <p class="text-xl md:text-2xl text-gray-300 leading-relaxed">
                Taylor Labs was founded by Evan Taylor, a Computer Science student at Cal Poly with a passion for turning ideas into reality. Starting with Cal Poly startups and expanding through technical credibility and student referrals, we're building the future of digital products—one startup at a time.
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
                <p>Transforming startup ideas into digital products.</p>
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

