<script>
import { import_meta_env_ } from 'ctx-core/env'
export let GTM_ID = import_meta_env_().GTM_ID
</script>

<slot></slot>

<noscript>
	<iframe
		src="https://www.googletagmanager.com/ns.html?id={GTM_ID}"
		height="0"
		width="0"
		style="display:none;visibility:hidden;"
		title=""
	></iframe>
</noscript>
