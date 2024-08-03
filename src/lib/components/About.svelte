<script lang="ts">
	import Depth3D from '$lib/3D/Depth3D/Depth3D.svelte';

	// @ts-ignore
	import imageMe from '$lib/images/1.png?w=1024&format=webp';
	// @ts-ignore
	import depthMe from '$lib/images/avatar-depth.png?w=1024&format=webp';

	import Resume from './Resume.svelte';
</script>

<div class="relative isolate overflow-hidden bg-black">
	<div class="mx-auto max-w-5xl px-6 lg:px-8">
		<div id="about" class="py-16 md:py-32 section">
			<div class="grid grid-cols-1 gap-y-16 lg:grid-cols-2 lg:grid-rows-[auto_1fr] lg:gap-y-12">
				<div class="lg:pl-20">
					<div class="max-w-sm px-2.5 lg:max-w-none">
						<!-- <img
							src={imageMe}
							alt="this is me"
							loading="lazy"
							sizes="(min-width: 1024px) 32rem, 20rem"
							class="aspect-square rotate-3 rounded-2xl bg-zinc-100 object-cover dark:bg-zinc-800"
						/> -->

						<div class="aspect-square rotate-3 -m-10 lg:-m-10">
							<Depth3D
								image={{
									image: imageMe,
									depth: depthMe
								}}
							/>
							<div class="sr-only">this is me</div>
						</div>
					</div>
				</div>
				<div class="lg:order-first lg:row-span-2">
					<h1
						class="text-4xl font-bold tracking-tight text-zinc-800 dark:text-zinc-100 sm:text-5xl"
					>
						Xin Chào, Tôi là Huỳnh Vĩnh Tiến.
					</h1>
					<div class="mt-6 space-y-7 text-base text-zinc-600 dark:text-zinc-400">
						<p>
							Lorem ipsum odor amet, consectetuer adipiscing elit. Platea suspendisse nostra quis sem; turpis vulputate ad. Imperdiet varius donec gravida; nostra laoreet nunc posuere turpis. Cursus placerat nibh non purus, proin mollis. Diam scelerisque metus sed sapien.
						</p>
						<p>
							Augue vel habitant bibendum aliquam habitant velit pretium dolor. Tempus luctus primis massa tellus dui. Massa dictum metus enim viverra lectus eu.
						</p>
						<p>
							At sit nostra tortor nascetur; himenaeos mattis purus. Dignissim congue tortor nisi amet laoreet aenean natoque. Consectetur aptent neque maecenas dolor; per nisl bibendum. Torquent velit faucibus fermentum tristique arcu malesuada morbi etiam.
						</p>
						<p>
							Inceptos felis dis eleifend erat; conubia iaculis ac faucibus nec! Mi euismod pellentesque in lobortis felis magna nec. Vel diam maximus maximus fermentum scelerisque lobortis praesent et. Montes consequat vehicula quam metus mi in porttitor. 
						</p>
						<p>
							Dolor urna vel varius penatibus mollis odio ac rhoncus mus. Tortor duis malesuada auctor metus phasellus dolor iaculis. Adipiscing mattis diam parturient commodo semper maximus.  <a
								href="#contact"
								class="text-cyan-400 hover:text-cyan-300 font-semibold"
							>
								Liên hệ
							</a>
						</p>
					</div>
				</div>

				<div class="lg:pl-20">
					<Resume />
				</div>
			</div>
		</div>
	</div>
</div>
