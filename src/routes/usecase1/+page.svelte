<script>
  import {
    MobiusButton,
    MobiusButtonVariants,
  } from "@vikram-components/mobius-component";

  import { onMount } from "svelte";

  onMount(async () => {
    await import("htmx.org");
  });
</script>

<h1>
  HTMX loading the server response in the specified target element inside a
  <b>div</b>
</h1>

<form
  method="POST"
  hx-post="/api/submit"
  hx-target="#response"
  hx-swap="innerHTML"
>
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

<div id="response"></div>
