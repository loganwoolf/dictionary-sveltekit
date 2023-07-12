<div class="app">
	<h1 class="title">definite-ly</h1>

	<div class="search flex flex-column align-center">
		<label class="search--label" for="word">
			<input
				class="search--input"
				id="word"
				name="word"
				placeholder="enlighten yourself"
				type="text"
			/>
		</label>
		<button class="search--clear">clear</button>
	</div>
</div>

<style>
	.app {
		border: var(--border-base);
		box-shadow: var(--drop-shadow);
		padding: 1rem 2rem;
	}

	.title {
		margin-bottom: 1rem;
	}

	.search {
		align-items: center;
		display: flex;
		flex-direction: column;
		gap: 0.75rem;
	}

	.search * {
		display: block;
		width: 100%;
	}

	.search--input,
	.search--clear {
		text-align: center;
		padding: 0.33rem 2rem;
	}

	.search--input:hover:not(:focus) {
		box-shadow: var(--drop-shadow-semi);
	}

	.search--clear:hover {
		box-shadow: var(--drop-shadow);
		cursor: pointer;
	}

	.search--clear:active {
		box-shadow: unset;
		translate: 4px 4px;
	}
</style>
