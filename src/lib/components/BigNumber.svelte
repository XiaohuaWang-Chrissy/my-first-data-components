<script>
  let { value, label } = $props();
</script>

<div class="bignumber">
  <div class="value">{value}</div>
  <div class="label">{label}</div>
</div>

<style>
  .bignumber {
    text-align: center;
    padding: 1rem 2rem;
    color: #8a78a0;
  }
  .value {
    font-size: 2.5rem;
    font-weight: bold;
  }
  .label {
    font-size: 0.875rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
    color: #8a78a0;
  }
</style>