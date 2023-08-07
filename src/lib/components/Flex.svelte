<script lang="ts">
    export let row = true;
    export let column = false;
    export let gap: 'sm' | 'md' | 'lg' = 'sm';
</script>

<div class:flex-row={row} class:flex-col={column} class:gap-2={gap=='sm'} class:gap-4={gap=='md'} class="flex">
<slot />
</div>