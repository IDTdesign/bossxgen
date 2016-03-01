# Gutter-half, gutter-quarter, gutter-null

Adjust spacing between columns (applies to paddings):

* `gutter-half` — twice smaller,
* `gutter-quarter` — 4 times smaller,
* `gutter-zero` — reset padding to 0.

Based on `@gutter-width` variable.

Each class has two sets of independed modifiers:

1. `-left` and `-right` to adjust only left and right paddings,
2. `-xs`, `-sm`, `-md` and `-lg` to provide mobile-first behaviour: rules applying only on corresponding media queries.

## Usage in HTML

```html
<div class="row">
    <div class="col-sm-4 gutter-half-right-sm">
        ...
    </div>
    <div class="col-sm-4 gutter-half-sm">
        ...
    </div>
    <div class="col-sm-4 gutter-half-left-sm">
        ...
    </div>
</div>
```

## Default values

Component has global mixin with settings named `.gutter-settings();` and global variable `gutter-render` which contains all code.

Default settings:

```less
.gutter-settings() {
    @gutter-width: 30px; // space between grid columns

    // media breakpoints (default: as on bootstrap)
    @breakpoints:
        "min-width: 480px",
        "min-width: 768px",
        "min-width: 992px",
        "min-width: 1200px";

    // names for breakpoint suffixes
    @suffixes: xs, sm, md, lg;

    // classnames
    @gutter: gutter;
    @half: half;
    @quarter: quarter;
    @null: null;

    // classnames modifiers
    @left: left;
    @right: right;

}
```

## Usage in LESS

Running with default parameters:

```less
@import (less) "uicomponents/gutter.less";
```

Redefining gutter-width and breakpoints:

```less
@import (less) "uicomponents/gutter.less";

.gutter-settings() {
    @gutter-width: 60px;

    // media breakpoints
    @breakpoints:
        "min-width: 320px",
        "min-width: 480px",
        "min-width: 768px",
        "min-width: 992px",
        "min-width: 1200px",
        "min-width: 1600px";

    // names for breakpoint suffixes
    @suffixes: xxs, xs, sm, md, lg, xlg;
}
```

Renaming output classnames:

```less
@import (less) "uicomponents/gutter.less";

.gutter-settings() {
    // names for breakpoint suffixes
    @suffixes: phone, tablet, desktop, wide;

    // classnames
    @gutter: gap;
    @half: half;
    @quarter: quarter;
    @null: zero;

    // classnames modifiers
    @left: l;
    @right: r;
}
```
