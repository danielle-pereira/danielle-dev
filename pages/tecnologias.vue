<template>
	<div>

		<Projeto />
		<HeaderInt titulo="TECNOLOGIAS" color_title="tecs-color" />

		<div class="pages">
			<div class="content shadow-sm bio">
				<div class="title-tec tecs-color">FRONTEND</div>

				<div class="icons-float">
					<div class="box-icon">
						<i class="devicon-html5-plain colored icon-size"></i>
						<div style="color: #e54d26;">HTML</div>
					</div>

					<div class="box-icon">
						<i class="devicon-css3-plain colored icon-size"></i>
						<div style="color: #3d8fc6;">CSS</div>
					</div>

					<div class="box-icon">
						<i class="devicon-bootstrap-plain colored icon-size"></i>
						<div style="color: #59407f;">BOOTSTRAP</div>
					</div>

					<div class="box-icon">
						<i class="devicon-bulma-plain colored icon-size"></i>
						<div style="color: #00d1b2;">BULMA</div>
					</div>
					
					<div class="box-icon">
						<i class="devicon-vuejs-plain colored icon-size"></i>
						<div style="color: #41b883;">Vue.js</div>
					</div>
					<div class="box-icon">
						<i class="devicon-nuxtjs-plain colored icon-size"></i>
						<div style="color: #00c48d;">nuxtJS</div>
					</div>

					<div class="box-icon">
						<i class="devicon-javascript-plain icon-size" style="color: #c7b20a;"></i>
						<div style="color: #c7b20a;">javascript</div>
					</div>
					
			
					<div class="box-icon">
						<i class="devicon-typescript-plain colored icon-size"></i>
						<div style="color: #3074C0;">Typescript</div>
					</div>

				</div>
				<div class="clear-fix"></div>
			</div>

			<div class="content shadow-sm bio" style="margin-top: 30px;">
				<div class="title-tec tecs-color">BACKEND</div>

				<div class="icons-float">

					<div class="box-icon">
						<i class="devicon-nodejs-plain colored icon-size"></i>
						<div style="color: #83cd29;">Node.js</div>
					</div>

					<div class="box-icon">
						<i style="color: #999;" class="devicon-express-original colored icon-size"></i>
						<div style="color: #999;">Express</div>
					</div>

					<div class="box-icon">
						<i class="devicon-nestjs-plain colored icon-size"></i>
						<div style="color: #E0454F;">NestJS</div>
					</div>

					<div class="box-icon">
						<i class="devicon-typescript-plain colored icon-size"></i>
						<div style="color: #3074C0;">Typescript</div>
					</div>

				</div>
				<div class="clear-fix"></div>
			</div>

			<div class="content shadow-sm bio" style="margin-top: 30px;">
				<div class="title-tec tecs-color">MOBILE</div>

				<div class="icons-float">
					<div class="box-icon">
						<i class="devicon-react-plain colored icon-size"></i>
						<div style="color: #61DAFA;">React Native</div>
					</div>

					<div class="box-icon">
						<i class="devicon-typescript-plain colored icon-size"></i>
						<div style="color: #3074C0;">Typescript</div>
					</div>

				</div>
				<div class="clear-fix"></div>
			</div>

			<div class="content shadow-sm bio" style="margin-top: 30px;">
				<div class="title-tec tecs-color">BANCO DE DADOS</div>

				<div class="icons-float">
					<div class="box-icon">
						<i class="devicon-mongodb-plain colored icon-size"></i>
						<div style="color: #4faa41;">MongoDB</div>
					</div>
				</div>

				<div class="clear-fix"></div>
			</div>

			<div class="content shadow-sm bio" style="margin-top: 30px;">
				<div class="title-tec tecs-color">DEVELOPMENT, DEVOPS, DEPLOY, CODE VERSION...</div>

				<div class="icons-float">
			
					<div class="box-icon">
						<i class="devicon-vscode-plain colored icon-size"></i>
						<div style="color: #3c99d4;">vscode</div>
					</div>
		
					<div class="box-icon">
						<i class="devicon-digitalocean-plain colored icon-size"></i>
						<div style="color: #0080ff;">digitalocean</div>
					</div>
					
					<div class="box-icon">
						<i class="devicon-git-plain colored icon-size"></i>
						<div style="color: #f34f29;">git</div>
					</div>
					
					<div class="box-icon">
						<i style="color: #999;" class="devicon-github-plain colored icon-size"></i>
						<div style="color: #999;">github</div>
					</div>
					
					<div class="box-icon">
						<i class="devicon-gitlab-plain colored icon-size"></i>
						<div style="color: #e24329;">gitlab</div>
					</div>

					<div class="box-icon">
						<i class="devicon-npm-original-wordmark colored  icon-size"></i>
						<div style="color: #cb3837;">npm</div>
					</div>

					<div class="box-icon">
						<i class="devicon-yarn-plain colored icon-size"></i>
						<div style="color: #2c8ebb;">yarn</div>
					</div>

					<div class="box-icon">
						<i style="color: #999;" class="devicon-composer-plain colored icon-size"></i>
						<div style="color: #999;">composer</div>
					</div>

				</div>
				<div class="clear-fix"></div>
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
