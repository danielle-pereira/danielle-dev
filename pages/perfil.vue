<template>
	<div>

		<Projeto />
		<HeaderInt titulo="PERFIL" color_title="perf-color" />

		<div class="pages">
			<div class="content shadow-sm bio">
				 <b>Conheça Danielle.</b>

				<br /> 
				Uma mulher com alma de menina de 33 anos que embarcou em uma emocionante jornada de transição de carreira para o mundo da tecnologia. 
				Ela é casada com um talentoso desenvolvedor Fullstack e tem um coração repleto de amor para dar a um garoto de 9 anos, além de cuidar carinhosamente de uma doguinha idosa.

				<br />
				Danielle é uma verdadeira entusiasta da natureza, e seu amor pela vida ao ar livre é evidente em sua paixão por explorar os encantos da mãe natureza. <br>
				Além disso, ela é uma ávida jogadora, sempre pronta para embarcar em aventuras virtuais e desafios emocionantes. <br>
				Se você quiser ganhar um lugar especial no coração dela, basta acompanhá-la em uma xícara de café bem feito, pois ela é uma amante declarada dessa bebida que aquece a alma.
				<br />
				<br />
				Recentemente, Danielle mergulhou de cabeça no universo Tech, cursando o segundo semestre de Engenharia de Software. 
				Ela está em busca constante de crescimento e evolução, ávida por aprender novas técnicas e dominar novas linguagens de programação. <br>
				Seu foco principal é sempre alcançar a máxima agilidade e performance no desenvolvimento de software, e ela está determinada a se destacar nesse campo em constante evolução.
				<br />
				Junte-se a Danielle em sua emocionante jornada pelo mundo da tecnologia, onde sua paixão, determinação e desejo de aprendizado são os ingredientes perfeitos para uma trajetória de sucesso.
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
