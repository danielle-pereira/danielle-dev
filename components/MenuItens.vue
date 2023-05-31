<template>
	<ul>
		<li v-for="(item, index) in reverse ? itens.slice().reverse() : itens" :key="index"><nuxt-link :to="`/${item.rota}`">{{ item.nome }}</nuxt-link></li>
	</ul>
</template>

<script>
export default {
	props: ['reverse'],
	data(){
		return{
			itens: [
				{
					nome: 'PERFIL',
					rota: 'perfil'
				},
				{
					nome: 'TECNOLOGIAS',
					rota: 'tecnologias'
				},
				{
					nome: 'EXPERIÊNCIAS',
					rota: 'experiencias'
				},
			],
			getItens : []
		}
	},
	mounted(){
		// return this.getItens = this.reverse ? this.itens.slice().reverse() : this.itens
	}
}
</script>
