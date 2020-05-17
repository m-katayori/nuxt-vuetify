<template>
	<div>
		<!-- <Logo />
		<VuetifyLogo /> -->
		<h1>植物管理アプリ</h1>
		<v-btn to="/plants">つかってみる</v-btn>
	</div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
	components: {
		Logo,
		VuetifyLogo
	}
}
</script>
