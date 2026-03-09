<script>
  let { children } = $props();
</script>

<div class="dashboard">
  {@render children()}
</div>

<style>
  .dashboard {
    display: flex;
    gap: 1rem;
    padding: 1rem;
    background: #d4d4d4;
    border: 1px solid #e0e0e0;
    border-radius: 4px;
    margin-bottom: 1rem;
  }
</style>