<script lang="ts">
	import Menu from './_layout.svelte';
</script>

<head>
	<meta
		name="description"
		content="Main page of the site with portfolio. Frontend developer: Palkina Sofia Sergeevna"
	/>
	<title>Palkina Sofia</title>
</head>

<body>
	<div class="header">
		<h1 class="header-title">Palkina Sofia</h1>
		<p class="header-subtitle">frontend developer</p>
	</div>
</body>
<Menu />

<style>
	body {
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-size: cover;
		background-position: center;
		font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
	}
	.header {
		width: 100%;
		height: 100vh;
		background-color: #7ac6c2;
		background-image: url(../img/fon.jfif);
		background-size: cover;
		background-position: center;

		/* выравнивание */
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.header-title {
		margin: 0;

		font-weight: bold;
		font-size: 70px;
		line-height: 130%;

		text-align: center;

		color: #ffffff;
	}
	.header-subtitle {
		margin: 0;

		font-weight: bold;
		font-size: 25px;
		line-height: 150%;

		text-align: center;
		letter-spacing: 0.2cm;
		text-transform: uppercase;

		color: #ffffff;
	}
</style>
