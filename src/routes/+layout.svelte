<script>
	import '../app.css';
</script>

<div
	class="sticky w-screen h-[10vh] bg-white flex flex-row items-center justify-between z-50 backdrop-filter backdrop-blur-3xl"
>
	<h1 class="text-3xl font-bold px-10">StudySmart</h1>
	<div class="mx-20 text-2xl grid grid-cols-5 gap-10">
		<a href="/">Link</a>
		<a href="/">Link</a>
		<a href="/">Link</a>
		<a href="/">Link</a>
		<a href="/">Link</a>
	</div>
</div>

<div class="w-full h-[90vh] bg-background bg-no-repeat bg-cover -z-50">
	<div class="w-full h-full backdrop-blur-xl backdrop-brightness-95">
		<slot />
	</div>
</div>
