<template>
	<div>
	<v-dialog
		v-model="dialog"
		width="500"
	>
		<template v-slot:activator="{ on }">
		<v-btn
			v-on="on"
		>
			植物登録
		</v-btn>
		</template>

		<v-card>
		<v-card-title
		>
			植物登録
		</v-card-title>

		<v-card-text>
			<v-text-field
				label="植物名"
			></v-text-field>
		</v-card-text>

		<v-card-actions>
			<v-spacer></v-spacer>
			<v-btn
				@click="dialog = false"
				color="error"
				text
			>
				閉じる
			</v-btn>
			<v-btn
				@click="dialog = false"
				color="primary"
				text
			>
				登録する
			</v-btn>
		</v-card-actions>
		</v-card>
	</v-dialog>
	</div>
</template>

<script>
	export default {
	data () {
		return {
		dialog: false,
		}
	},
	}
</script>