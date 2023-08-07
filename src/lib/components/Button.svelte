<script lang="ts">
  export let type: 'primary' | 'secondary' | 'warning' = 'primary'
  export let primary = false;
  export let secondary = false;
  export let warning = false;
  export let disabled = false;
</script>


<button {disabled} class="px-4 py-2 font-bold transition rounded-lg  
  {primary ? 'bg-purple-600 text-white hover:bg-purple-700' : ''} 
  {secondary ? 'bg-transparent text-slate-800 border-slate-300 border hover:bg-slate-200' : ''}
  {warning ? 'bg-red-700 text-white hover:bg-red-800' : ''}
  {disabled ? 'cursor-not-allowed saturate-[0.75]' : 'active:scale-90'}">Hello</button>
