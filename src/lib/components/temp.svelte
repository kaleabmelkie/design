<script lang="ts">
	export let defaultSlotContent = 'slot content'
</script>

<div class="font-bold">Start Temp</div>
<div>
	<slot>{defaultSlotContent}</slot>
</div>
<div class="font-bold">End Temp</div>
