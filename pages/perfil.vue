<template>
	<div>

		<Projeto />
		<HeaderInt titulo="PERFIL" color_title="perf-color" />

		<div class="pages">
			<div class="content shadow-sm bio">
				Danielle, 33 anos, casada com um desenvolvedor Fullstack.
				<br /> Mãe de coração de um garoto de 9 anos, e uma doguinha idosa.

				<br />
				Apaixonada pela natuzera, jogos e café
				<br />
				<br />
				Recém chegada no mundo Tech, em transição de carreira, cursando  segundo semestre de Engenharia de Software.
				<br />
				Busco sempre evoluir, aprender novas técnicas e novas linguagens, focando sempre em agilidade e performance no desenvolvimento.
			</div>
			<nuxt-link class="back" to="/">Voltar</nuxt-link>
		</div>

	</div>
</template>

<script>
export default {
    name: "Header",
    transition: "slide-bottom",
}
</script>
