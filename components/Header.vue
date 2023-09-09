<template>
	<div class="header">
		<div class="grid-content text-center">
			<nuxt-img src="/assets/img/me.jpg" class="shadow-lg" />
			<div class="title">DANIELLE <b>PEREIRA</b></div>
		</div>

		<div class="typer-style">
			<vue-typer :text='["Frontend Developer", "Servidores Linux", "Backend Developer"]' :repeat='Infinity'
				:shuffle='false' initial-action='typing' :pre-type-delay='70' :type-delay='70' :pre-erase-delay='2000'
				:erase-delay='250' erase-style='clear' :erase-on-complete='false' caret-animation='phase'>
			</vue-typer>
		</div>

		<div class="address">
			<div>Maringá-PR / Indianópolis-PR</div>
			<div class="email">daniellecristine22@gmail.com</div>
			<div> <i class="el-icon-mobile-phone"></i> <b>44 9 9154-7559</b></div>
		</div>

		<div class="menu">
			<MenuItens />
		</div>

	</div>
</template>

<script>

export default {
	name: "Header",
	transition: "slide-bottom",
}
</script>
