<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="background-section">
  <a href="/chugga">chugga</a>
</section>

<h2>
	This Trolley Ain't For Riding
</h2>

<style>
	.background-section {
		display: flex;
		justify-content: center;
		align-items: center;
		position: relative;
		width: 100%;
		height: 100vh; 
		background: url('https://custom-skills-public.s3.amazonaws.com/trollilopolis/images/trolleyIntro.png') no-repeat center/cover;
	}

	.clickable-cow {
		position: absolute;
		top: 50%;
		left: 50%;
		width: 100px;
		height: 100px;
		background: transparent;
	}
</style>


