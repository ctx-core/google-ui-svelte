<script>
import { onMount } from 'svelte'
import { dataLayer__init } from '@ctx-core/google'
onMount(()=>dataLayer__init())
</script>

<slot></slot>
