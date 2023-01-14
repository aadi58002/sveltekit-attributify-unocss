<script lang="ts">
  import 'uno.css';
</script>

<div h-screen px-5>
  <slot />
</div>

<style>
  :global(body) {
    --at-apply: 'text-black';
  }
  :global(body.dark) {
    --at-apply: 'bg-[#181A1B] text-white';
  }
</style>
