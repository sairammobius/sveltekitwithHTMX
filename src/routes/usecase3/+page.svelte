<script>
  import { onMount } from "svelte";

  onMount(async () => {
    await import("htmx.org");
  });
</script>

<h1>Fetching Server Response using "hx-get" on div</h1>

<div hx-get="/api/submit" hx-trigger="click[ctrlKey]" style="cursor:pointer;">
  <b>Control Click Me</b>
</div>
