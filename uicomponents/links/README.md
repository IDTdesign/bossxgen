# Links

Applies colors and custom `:focus` styles for links.

## Usage in HTML

Covers links that have not classnames (`a:not([class])`) and any tags with `.link` classname.
Classname `.link` can be redefines via `.links-settings()` mixin.

```html
<a href="#">regular link</a>
or
<a href="#" class="link any-other-class">link with classname</a>
```

## Default values

Component has global mixin with settings named `.links-settings();` and global variable `links-render` which contains all code.

Default settings:

```less
.links-settings() {
    @class: link; //you can rename that classname
    @text-decoration: underline;
    //colors
    @link:          #0877db;
    @visited:       #9108db;
    @hover:         #2b9aff;
    @visitedhover:  #bc4df8;
    @active:        #bc4df8;
}
```

## Usage in LESS

Running with default parameters:

```less
@import (less) "uicomponents/links.less";
```

Customized styles, colors or classname:

```less
@import (less) "uicomponents/links.less";

.links-settings() {
    @class: lnk; //you can rename that classname
    @text-decoration: none;
    //colors
    @link:          blue;
    @visited:       purple;
    @hover:         red;
    @visitedhover:  red;
    @active:        red;
}
```
