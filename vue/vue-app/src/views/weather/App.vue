<template>
	<HeaderDisplay></HeaderDisplay>
	<WeatherContent></WeatherContent>
</template>

<script>
import HeaderDisplay from '@/components/weather/HeaderDisplay.vue';
import WeatherContent from '@/components/weather/WeatherContent.vue';

export default {
	name: 'WeatherIndex',
	components: {
		HeaderDisplay: HeaderDisplay,
		WeatherContent: WeatherContent,
	},
};
</script>

<style></style>
