# 🚀 Rocket SCSS

**⚠️ This project is still in progress. A complete component library coming soon.**

_Rocket SCSS_ is a component library built on [🧑‍🚀 Launchpad SCSS](https://github.com/alexerlandsson/launchpad-scss). Containing minimal styled basic components useful in any project.

## Methodology

The design of the components is based on the _CSS_ mothodology **BEM**.

The following is an example of how a component could be structured.

```html
<div class="foo foo--alternative">
  <div class="foo__bar">
    <!-- HTML -->
  </div>
</div>
```

In the example above, `.foo` is the name of the component (_block_). `.foo__bar` is a child _element_. `.foo--alternative` is a _modifier_. To convert this into _scss_ it could look like this:

```scss
.foo {
  color: #000;

  &--altenative {
    color: #757575;
  }

  &__bar {
    margin-bottom: 8px;
  }
}
```

## SCSS Base

This component library is based on [🧑‍🚀 Launchpad SCSS](https://github.com/alexerlandsson/launchpad-scss). See the _Launchpad SCSS_ documentation for more information about the scss base structure and helpers.