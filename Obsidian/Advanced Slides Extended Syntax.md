---
bg: '#1e1e2e'
---

# Horizontal and Vertical Slides

Use --- for horizontal and -- for vertical.

---

Here's a vertical one.

--

# Element Annotations

text with border <!-- element class="with-border" -->

text with background <!-- element style="background:blue" -->

text with attribute <!-- element data-toggle="modal" -->

---

# Slide Annotations

<!-- .slide: style="background-color: coral;" -->

---

# Block Comments

::: block

## Hello

Contents

:::

::: block <!-- element style="background:coral;" -->

Hello

:::

---

# Fragments

Fade in <!-- element class="fragment" -->

Fade out <!-- element class="fragment fade-out" -->

Highlight red <!-- element class="fragment highlight-red" -->

Fade in, then out <!-- element class="fragment fade-in-then-out" -->

Slide up while fading in <!-- element class="fragment fade-up" -->

---

- Permanent item
- Appear Fourth <!-- element class="fragment" data-fragment-index="4" -->
- Appear Third <!-- element class="fragment" data-fragment-index="3" -->
- Appear Second <!-- element class="fragment" data-fragment-index="2" -->
- Appear First <!-- element class="fragment" data-fragment-index="1" -->

---

<style>
	.with-border{
		background: #1e1e2e;
		border: 10px solid #b4befe;
	}
</style>

styled text <!-- element class="with-border" -->
