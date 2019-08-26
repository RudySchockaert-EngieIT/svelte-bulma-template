<script>
  export let name;
</script>

<style global lang="scss">
  @import "main.scss";
</style>

<h1 class="title is-3">Hello {name}!</h1>

<p class="title">Bulma</p>
<p class="subtitle">
  Modern CSS framework based on
  <a
    href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox">
    Flexbox
  </a>
</p>

<div class="field">
  <div class="control">
    <input class="input" type="text" placeholder="Input" />
  </div>
</div>

<div class="field">
  <p class="control">
    <span class="select">
      <select>
        <option>Select dropdown</option>
      </select>
    </span>
  </p>
</div>

<div class="buttons">
  <a class="button is-primary" href=".">Primary</a>
  <a class="button is-link" href=".">Link</a>
</div>
