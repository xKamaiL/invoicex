<script lang="ts">
	//

	let title = ``;
</script>

<slot />

<svelte:head>
	<title>
		InvoiceX - {title}
	</title>
	<meta name="description" content="InvoiceX share your invoice to " />
	<meta name="keywords" content="invoice, invoiceX, share invoice" />
	<meta name="author" content="InvoiceX" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<meta name="theme-color" content="#000000" />
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:site" content="@invoicex" />
	<meta name="twitter:creator" content="@invoicex" />
	<meta property="og:url" content="https://invoicex.pages.dev/" />
	<meta property="og:title" content="InvoiceX" />
	<!-- TODO: implement dynamic og image -->
	<meta property="og:description" content="InvoiceX share your invoice to your friends" />
	<meta property="og:image" content="https://invoicex.pages.dev/og.png" />
	<meta property="og:image:width" content="1200" />
	<meta property="og:image:height" content="630" />
</svelte:head>
