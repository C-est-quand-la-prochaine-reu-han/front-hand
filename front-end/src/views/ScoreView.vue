<template>
	<div class="score-container">
		<div class="score-item">
			<h1>3</h1>
		</div>
		<div class="score-item vertical-bar">
			<h1>6</h1>
		</div>
	</div>
</template>

<style scoped>
	.score-container {
		display: flex;
		flex-direction: row;
		justify-content: center;
		height: 50px;
	}

	.score-item {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
	}

	.score-item h1 {
		text-align: center;
		margin: auto;
		font-size: 1.8em;
	}

	.vertical-bar {
		border-left: 1px;
		border-style: solid;
		border-top: none;
		border-right: none;
		border-bottom: none;
		border-color: var(--vt-c-divider-dark-1);
	}

	body.light-mode .vertical-bar {
		border-color: var(--vt-c-divider-light-1);
	}
</style>
