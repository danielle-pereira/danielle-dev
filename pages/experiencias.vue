<template>
	<div>

		<Projeto />
		<HeaderInt titulo="EXPERIÊNCIAS" color_title="exp-color" />

		<div class="pages experiencias">
			<div class="content shadow-sm experiencias" v-for="(exp, index) in experiencias" :key="index">
				<div class="title"><b>{{ exp.empresa }}</b></div>
				<div class="outros">
					<div>Cargo: <b>{{ exp.cargo }}</b></div>
					<div>Período: <b>{{ exp.periodo }}</b></div>
					<div><b>Resumo:</b> <span v-html="exp.resumo"></span></div>
				</div>
				<div class="outros" style="margin-top: 15px;">
					
					<div class="icons-float">
						<div class="box-icon" v-for="(tec, i) in exp.tecnologias" :key="i">
							<i :class="`${tec.icone} colored icon-size`"></i>
							<div :style="{color: tec.cor}">{{ tec.nome }}</div>
						</div>

					</div>
					<div class="clear-fix"></div>
				</div>
			</div>
						
			<nuxt-link class="back" to="/">Voltar</nuxt-link>
		</div>

	</div>
</template>

<script>
import exp_data from '../json/exp_data.json'
export default {
    name: "Header",
    transition: "slide-bottom",
	data(){
		return{
			experiencias: exp_data
		}
	}
}
</script>
