<template>
	<div>
		<h1>회원가입 페이지</h1>
		<SignupForm></SignupForm>
	</div>
</template>

<script>
import SignupForm from '@/components/til/SignupForm.vue';

export default {
	components: {
		SignupForm,
	},
};
</script>

<style lang="scss" scoped></style>
