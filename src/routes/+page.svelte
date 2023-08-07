<script lang="ts">
  import Button from "$lib/components/Button.svelte"
  import Input from "$lib/components/Input.svelte"
  import Flex from "$lib/components/Flex.svelte"
  let number = 0
</script>

<Flex row gap='md'>
<Button primary disabled>Hello</Button>
<Input placeholder="Enter text here" />
</Flex>