<script></script>

<ol>
  <li>
    <a href="/usecase1"
      >HTMX loading the server response in the specified target element inside a <b
        >div</b
      ></a
    >
  </li>
  <li>
    <a href="/usecase2">HTMX replacing the form with the server response.</a>
  </li>
  <li>
    <a href="/usecase3">Fetching Server Response using "hx-get" on div</a>
  </li>
</ol>

<!-- <h1>HTMX loading the server response in the specified target element inside a <b>div</b></h1>
  
<form
hx-post="/api/submit"
hx-target="#response"
hx-swap="innerHTML"
>
<label>
  Name:
  <input type="text" name="name" required />
</label>
<br />
<label>
  Email:
  <input type="email" name="email" required />
</label>
<br />
<button type="submit">Submit</button>
</form>

<div id="response">
 
</div>

<br>
<br>
<br>
<br>

<h1>HTMX replacing the form with the server response.</h1>
  
<form
hx-post="/api/submit"
hx-swap="innerHTML"
>
<label>
  Name:
  <input type="text" name="name" required />
</label>
<br />
<label>
  Email:
  <input type="email" name="email" required />
</label>
<br />
<button type="submit">Submit</button>
</form>

<br>
<br>
<br>
<br>

<h1>Fetching Server Response using "hx-get" on div</h1>

<div hx-get="/api/submit" hx-trigger="click[ctrlKey]" style="cursor:pointer;">
    <b>Control Click Me</b>
</div> -->
