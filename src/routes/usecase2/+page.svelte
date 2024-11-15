<script>
  import { onMount } from "svelte";

  onMount(async () => {
    await import("htmx.org");
  });
</script>

<h1>HTMX replacing the form with the server response.</h1>

<form hx-post="/api/submit" hx-swap="innerHTML">
  <label>
    Name:
    <input type="text" name="name" required />
  </label>
  <br /><br />
  <label>
    Email:
    <input type="email" name="email" required />
  </label>
  <br /><br />
  <button type="submit">Submit</button>
</form>
