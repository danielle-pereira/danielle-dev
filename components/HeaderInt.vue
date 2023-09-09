<template>
	<div class="header-int">
		<div class="flex-mobile">
			<nuxt-img src="/assets/img/me.jpg" class="shadow-lg" />
			<b :class="`${color_title}`">{{ titulo }}</b>
			<div class="clear-fix"></div>
		</div>

		<div class="flex">
			<div class="text-center image">
				<nuxt-img src="/assets/img/me.jpg" class="shadow-lg" />
				<div class="title"><b :class="`${color_title}`">{{ titulo }}</b></div>
			</div>


			<div class="menu-int">
				<MenuItens :reverse="true" />
			</div>
		</div>

	</div>
</template>

<script>

export default {
	name: "Header",
	transition: "slide-bottom",
	props: ['titulo', 'color_title']
}
</script>
