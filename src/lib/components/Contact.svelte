<script lang="ts">
	import SocialLink from '$lib/components/SocialLink.svelte';
</script>

<div class="relative isolate py-32 bg-black/30 md:bg-transparent section pointer-events-none" id="contact">
	<div class="mx-auto max-w-5xl px-6 lg:px-8">
		<div class="grid grid-cols-1 gap-x-8 gap-y-10 md:grid-cols-3">
			<div>
				<h2 class="text-3xl font-bold tracking-tight text-zinc-900 dark:text-zinc-100 pointer-events-auto">
					Liên Hệ
				</h2>
				<p class="mt-4 leading-7 text-zinc-600 dark:text-zinc-300 pointer-events-auto">
					Tôi rất vui khi nhận được sự góp ý, <br/> nhận xét và liên hệ giải đáp thắc mắc
				</p>

				<ul role="list" class="mt-8 pointer-events-auto">
					<SocialLink href="https://github.com/hvtienprotv84" class="mt-4">
						<svelte:fragment slot="icon">
							<svg fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"
							class="w-6 h-6">
								<path
									fill-rule="evenodd"
									d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
									clip-rule="evenodd"
								/>
							</svg>
						</svelte:fragment>
						Github</SocialLink
					>
					<SocialLink href="/" class="mt-4">
						<svelte:fragment slot="icon">
							<svg fill="currentColor" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="100" height="100" viewBox="0 0 50 50">
								<path d="M25,3C12.85,3,3,12.85,3,25c0,11.03,8.125,20.137,18.712,21.728V30.831h-5.443v-5.783h5.443v-3.848 c0-6.371,3.104-9.168,8.399-9.168c2.536,0,3.877,0.188,4.512,0.274v5.048h-3.612c-2.248,0-3.033,2.131-3.033,4.533v3.161h6.588 l-0.894,5.783h-5.694v15.944C38.716,45.318,47,36.137,47,25C47,12.85,37.15,3,25,3z"></path>
							</svg>
						</svelte:fragment>
						Facebook
					</SocialLink>
					<SocialLink href="/" class="mt-4">
						<svelte:fragment slot="icon">
							<svg fill="currentColor" xmlns="http://www.w3.org/2000/svg" class="w-14 h-14" x="0px" y="0px" viewBox="0,0,300,150">
								<g fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><g transform="scale(5.12,5.12)"><path d="M9,4c-2.74952,0 -5,2.25048 -5,5v32c0,2.74952 2.25048,5 5,5h32c2.74952,0 5,-2.25048 5,-5v-32c0,-2.74952 -2.25048,-5 -5,-5zM9,6h6.58008c-3.57109,3.71569 -5.58008,8.51808 -5.58008,13.5c0,5.16 2.11016,10.09984 5.91016,13.83984c0.12,0.21 0.21977,1.23969 -0.24023,2.42969c-0.29,0.75 -0.87023,1.72961 -1.99023,2.09961c-0.43,0.14 -0.70969,0.56172 -0.67969,1.01172c0.03,0.45 0.36078,0.82992 0.80078,0.91992c2.87,0.57 4.72852,-0.2907 6.22852,-0.9707c1.35,-0.62 2.24133,-1.04047 3.61133,-0.48047c2.8,1.09 5.77938,1.65039 8.85938,1.65039c4.09369,0 8.03146,-0.99927 11.5,-2.88672v3.88672c0,1.66848 -1.33152,3 -3,3h-32c-1.66848,0 -3,-1.33152 -3,-3v-32c0,-1.66848 1.33152,-3 3,-3zM33,15c0.55,0 1,0.45 1,1v9c0,0.55 -0.45,1 -1,1c-0.55,0 -1,-0.45 -1,-1v-9c0,-0.55 0.45,-1 1,-1zM18,16h5c0.36,0 0.70086,0.19953 0.88086,0.51953c0.17,0.31 0.15875,0.69977 -0.03125,1.00977l-4.04883,6.4707h3.19922c0.55,0 1,0.45 1,1c0,0.55 -0.45,1 -1,1h-5c-0.36,0 -0.70086,-0.19953 -0.88086,-0.51953c-0.17,-0.31 -0.15875,-0.69977 0.03125,-1.00977l4.04883,-6.4707h-3.19922c-0.55,0 -1,-0.45 -1,-1c0,-0.55 0.45,-1 1,-1zM27.5,19c0.61,0 1.17945,0.16922 1.68945,0.44922c0.18,-0.26 0.46055,-0.44922 0.81055,-0.44922c0.55,0 1,0.45 1,1v5c0,0.55 -0.45,1 -1,1c-0.35,0 -0.63055,-0.18922 -0.81055,-0.44922c-0.51,0.28 -1.07945,0.44922 -1.68945,0.44922c-1.93,0 -3.5,-1.57 -3.5,-3.5c0,-1.93 1.57,-3.5 3.5,-3.5zM38.5,19c1.93,0 3.5,1.57 3.5,3.5c0,1.93 -1.57,3.5 -3.5,3.5c-1.93,0 -3.5,-1.57 -3.5,-3.5c0,-1.93 1.57,-3.5 3.5,-3.5zM27.5,21c-0.10375,0 -0.20498,0.01131 -0.30273,0.03125c-0.19551,0.03988 -0.37754,0.11691 -0.53711,0.22461c-0.15957,0.1077 -0.2966,0.24473 -0.4043,0.4043c-0.10769,0.15957 -0.18473,0.3416 -0.22461,0.53711c-0.01994,0.09775 -0.03125,0.19898 -0.03125,0.30273c0,0.10375 0.01131,0.20498 0.03125,0.30273c0.01994,0.09775 0.04805,0.19149 0.08594,0.28125c0.03789,0.08977 0.08482,0.17607 0.13867,0.25586c0.05385,0.07979 0.11578,0.15289 0.18359,0.2207c0.06781,0.06781 0.14092,0.12975 0.2207,0.18359c0.15957,0.10769 0.3416,0.18473 0.53711,0.22461c0.09775,0.01994 0.19898,0.03125 0.30273,0.03125c0.10375,0 0.20498,-0.01131 0.30273,-0.03125c0.68428,-0.13959 1.19727,-0.7425 1.19727,-1.46875c0,-0.83 -0.67,-1.5 -1.5,-1.5zM38.5,21c-0.10375,0 -0.20498,0.01131 -0.30273,0.03125c-0.09775,0.01994 -0.19149,0.04805 -0.28125,0.08594c-0.08977,0.03789 -0.17607,0.08482 -0.25586,0.13867c-0.07979,0.05385 -0.15289,0.11578 -0.2207,0.18359c-0.13562,0.13563 -0.24648,0.29703 -0.32227,0.47656c-0.03789,0.08976 -0.066,0.1835 -0.08594,0.28125c-0.01994,0.09775 -0.03125,0.19898 -0.03125,0.30273c0,0.10375 0.01131,0.20498 0.03125,0.30273c0.01994,0.09775 0.04805,0.19149 0.08594,0.28125c0.03789,0.08977 0.08482,0.17607 0.13867,0.25586c0.05385,0.07979 0.11578,0.15289 0.18359,0.2207c0.06781,0.06781 0.14092,0.12975 0.2207,0.18359c0.07979,0.05385 0.16609,0.10078 0.25586,0.13867c0.08976,0.03789 0.1835,0.066 0.28125,0.08594c0.09775,0.01994 0.19898,0.03125 0.30273,0.03125c0.10375,0 0.20498,-0.01131 0.30273,-0.03125c0.68428,-0.13959 1.19727,-0.7425 1.19727,-1.46875c0,-0.83 -0.67,-1.5 -1.5,-1.5z"></path></g></g>
								</svg>
						</svelte:fragment>
						Zalo
					</SocialLink>
					<SocialLink href="/" class="mt-4">
						<svelte:fragment slot="icon">
							<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-5 h-5"
								><path
									d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"
								/></svg
							>
						</svelte:fragment>
						Linkedin
					</SocialLink>
					<SocialLink href="/" class="mt-4">
						<svelte:fragment slot="icon">
							<svg fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"
							class="w-6 h-6">
								<path
									fill-rule="evenodd"
									d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
									clip-rule="evenodd"
								/>
							</svg>
						</svelte:fragment>
						Instagram
					</SocialLink>
					<!-- <SocialLink href="https://youtube.com/@flobit" class="mt-4">
						<svelte:fragment slot="icon">
							<svg fill="currentColor" viewBox="0 0 24 24" aria-hidden="true" 
							class="w-6 h-6">
								<path
									fill-rule="evenodd"
									d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.746 22 12 22 12s0 3.255-.418 4.814a2.504 2.504 0 0 1-1.768 1.768c-1.56.419-7.814.419-7.814.419s-6.255 0-7.814-.419a2.505 2.505 0 0 1-1.768-1.768C2 15.255 2 12 2 12s0-3.255.417-4.814a2.507 2.507 0 0 1 1.768-1.768C5.744 5 11.998 5 11.998 5s6.255 0 7.814.418ZM15.194 12 10 15V9l5.194 3Z"
									clip-rule="evenodd"
								/>
							</svg>
						</svelte:fragment>
						youtube
					</SocialLink> -->
					<!-- <SocialLink href="https://flobit.substack.com/" class="mt-4">
						<svelte:fragment slot="icon">
							<svg
								xmlns="http://www.w3.org/2000/svg"
								shape-rendering="geometricPrecision"
								text-rendering="geometricPrecision"
								image-rendering="optimizeQuality"
								fill-rule="evenodd"
								clip-rule="evenodd"
								viewBox="0 0 448 511.471"
								fill="currentColor"
								class="w-4 h-4"
								><path
									d="M0 0h448v62.804H0V0zm0 229.083h448v282.388L223.954 385.808 0 511.471V229.083zm0-114.542h448v62.804H0v-62.804z"
								/></svg
							>
						</svelte:fragment>
						substack
					</SocialLink> -->

					<SocialLink href="mailto:huynhvinhtien.84@gmail.com" class="mt-8">
						<svelte:fragment slot="icon">
							<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
							class="w-6 h-6">
								<path
									d="M1.5 8.67v8.58a3 3 0 003 3h15a3 3 0 003-3V8.67l-8.928 5.493a3 3 0 01-3.144 0L1.5 8.67z"
								/>
								<path
									d="M22.5 6.908V6.75a3 3 0 00-3-3h-15a3 3 0 00-3 3v.158l9.714 5.978a1.5 1.5 0 001.572 0L22.5 6.908z"
								/>
							</svg>
						</svelte:fragment>
						huynhvinhtien.84@gmail.com
					</SocialLink>
				</ul>
			</div>
		</div>
	</div>
</div>