<script lang="ts">
  export let type: 'primary' | 'secondary' | 'warning' = 'primary'
</script>


<button class="px-4 py-2 font-bold transition rounded-lg active:scale-95 
  {type == 'primary' ? 
    'bg-purple-500 text-white hover:bg-purple-700' : 
    type == 'secondary' ?
      'bg-transparent text-slate-800 border-slate-300 border hover:bg-slate-200' :
      'bg-red-700 text-white hover:bg-red-800'} ">Hello</button>
