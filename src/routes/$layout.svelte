<script>
	import './../styles/reset.css';
  import "./../styles/globals.css";
</script>

<div class="flex-layout">
	<slot />
	<p class="footer">© Acme Corp, 1951</p>
</div>

<style>
	.footer {
		margin: 3rem 0;
		text-align: center;
	}
	.flex-layout {
		min-height: 100vh;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}
</style>
