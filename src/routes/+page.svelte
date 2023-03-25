<svelte>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte>

<section>
	<h2>Send form!</h2>

	<div class="form-input">
		<label for="" class="form-item">Image</label>
		<input type="text" class="form-item" />
		<label for="" class="form-item">Name</label>
		<input type="text" class="form-item" />
		<label for="" class="form-item">Surname</label>
		<input type="text" class="form-item" />
		<label for="" class="form-item">Numbers</label>
		<input type="text" class="form-item" />
	</div>
	<button class="form-item">Submit</button>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
	h2 {
		font-weight: bold;
		font-size: x-large;
	}
	.form-input {
		display: flex;
		flex-direction: column;
	}
	.form-item {
		margin-top: 0.35rem;
		margin-bottom: 0.35rem;
	}
</style>
