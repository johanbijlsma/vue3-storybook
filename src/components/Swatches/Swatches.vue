/* eslint-disable vue/valid-template-root */
<template>
<div>
<h1>Semantic use of new Color swatches</h1>
<div class="container semantic">
  <section>
    <h2>Colors</h2>
    <div class="swatch-container semantic">
      <div class="swatch text-default ">
        <div>Text Default</div>
      </div>
      <div class="swatch text-subtle">
        <div>Text Subtle</div>
      </div>
      <div class="swatch link-default">
        <div>Link Default</div>
      </div>
      <div class="swatch link-active">
        <div>Link Active</div>
      </div>

    </div>
  </section>
  <section>
    <h2>Background</h2>
    <div class="swatch-container semantic">
      <div class="swatch surface-1 ">
        <div>Surface Level 1</div>
      </div>
      <div class="swatch surface-2 ">
        <div>Surface Level 2</div>
      </div>
      <div class="swatch surface-3">
        <div>Surface Level 3</div>
      </div>
      <div class="swatch surface-4 ">
        <div>Surface Level 4</div>
      </div>
      </div>

  </section>
  <section>
    <h2>Border</h2>
    <div class="swatch-container semantic">
      <div class="swatch divider-subtle ">
        <div>Divider Subtle</div>
      </div>
      <div class="swatch form-default ">
        <div>Form Default</div>
      </div>
</div>
  </section>
  <section>
    <h2>Usage</h2>
    <pre><code>
.text-default {
  background-color: var(--gray-950);
}
.text-subtle {
  background-color: var(--gray-600);
}
.link-default {
  background-color: var(--violet-700);
}
.link-active {
  background-color: var(--violet-800);
}
.surface-1 {
  background-color: var(--gray-100);
}
.surface-2 {
  background-color: var(--white);
}
.surface-3 {
  background-color: var(--gray-50);
}
.surface-4 {
  background-color: var(--white);
}
.divider-subtle {
  background-color: var(--gray-200);
}
.form-default {
  background-color: var(--gray-500);
}
      </code></pre>
  </section>
</div>
</div>
</template>

<script>
export default {
  name: 'Swatches'

}

</script>

<style lang="scss" >
@import "swatches.scss"
</style>
