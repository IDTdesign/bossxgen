---
layout: "default"
title: "Form elements"
---

# Form elements

On this page:

<nav>
    <ul>
        <li><a href="#buttons">Buttons</a>
            <ul>
                <li><a href="#button-types">Types</a></li>
                <li><a href="#button-sizes">Sizes</a></li>
            </ul>
        </li>
        <li><a href="#inputs">Inputs</a></li>
        <li><a href="#">other</a></li>
        <li><a href="#">more</a></li>
    </ul>
</nav>

## Buttons

Generic button without theme:

<p>
    <a href="#" class="btn">a.btn</a>
</p>
<p>
    <button>button</button>
    <button type="button">button type='button'</button>
    <button type="submit">button type='submit'</button>
    <button type="reset">button type='reset'</button>
    <button class="btn">button.btn</button>
</p>
<p>
    <input type="button" value="input type='button'">
    <input type="submit" value="input type='submit'">
    <input type="reset" value="input type='reset'">
    <input type="button" class="btn" value="input.btn">
</p>

<div style="margin: 0 -5vw; padding: 1.5em 5vw; background: #333; color: #FFF">
    <p>
        <a href="#" class="btn">a.btn</a>
    </p>
    <p>
        <button>button</button>
        <button type="button">button type='button'</button>
        <button type="submit">button type='submit'</button>
        <button type="reset">button type='reset'</button>
        <button class="btn">button.btn</button>
    </p>
    <p>
        <input type="button" value="input type='button'">
        <input type="submit" value="input type='submit'">
        <input type="reset"  value="input type='reset'">
        <input type="button" value="input.btn" class="btn">
    </p>
</div>

```html
<a href="#" class="btn">a.btn</a>

<button>button</button>
<button type="button">button type='button'</button>
<button type="submit">button type='submit'</button>
<button type="reset">button type='reset'</button>
<button class="btn">button.btn</button>

<input type="button" value="input type='button'">
<input type="submit" value="input type='submit'">
<input type="reset"  value="input type='reset'">
<input type="button" value="input.btn" class="btn">
```

<p>Some words in one line with <button class="btn">some</button> <button class="btn">buttons</button> should be visually aligned by baseline.</p>

### Button types

Types of button and states:


<table>
    <caption>Buttons with style classes</caption>
    <thead>
        <tr>
            <th></th>
            <th><code>.btn-primary</code></th>
            <th><code>.btn-default</code></th>
            <th><code>.btn-link</code></th>
            <th><code>.btn-purchase</code></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th></th>
            <td><button type="button" class="btn btn-primary">Primary</button></td>
            <td><button type="button" class="btn btn-default">Default</button></td>
            <td><button type="button" class="btn btn-link">Lika a Link</button></td>
            <td><button type="button" class="btn btn-purchase">Purchase</button></td>
        </tr>
        <tr>
            <th><code>:hover</code></th>
            <td><button type="button" class="btn hover btn-primary">Primary</button></td>
            <td><button type="button" class="btn hover btn-default">Default</button></td>
            <td><button type="button" class="btn hover btn-link">Lika a Link</button></td>
            <td><button type="button" class="btn hover btn-purchase">Purchase</button></td>
        </tr>
        <tr>
            <th><code>:focus</code></th>
            <td><button type="button" class="btn focus btn-primary">Primary</button></td>
            <td><button type="button" class="btn focus btn-default">Default</button></td>
            <td><button type="button" class="btn focus btn-link">Lika a Link</button></td>
            <td><button type="button" class="btn focus btn-purchase">Purchase</button></td>
        </tr>
        <tr>
            <th><code>:active</code></th>
            <td><button type="button" class="btn active btn-primary">Primary</button></td>
            <td><button type="button" class="btn active btn-default">Default</button></td>
            <td><button type="button" class="btn active btn-link">Lika a Link</button></td>
            <td><button type="button" class="btn active btn-purchase">Purchase</button></td>
        </tr>
        <tr>
            <th><code>[disabled]</code></th>
            <td><button type="button" disabled class="btn btn-primary">Primary</button></td>
            <td><button type="button" disabled class="btn btn-default">Default</button></td>
            <td><button type="button" disabled class="btn btn-link">Lika a Link</button></td>
            <td><button type="button" disabled class="btn btn-purchase">Purchase</button></td>
        </tr>
        <tr>
            <th><code>.btn-inprogress</code></th>
            <td><button type="button" class="btn btn-inprogress btn-primary">Primary</button></td>
            <td><button type="button" class="btn btn-inprogress btn-default">Default</button></td>
            <td><button type="button" class="btn btn-inprogress btn-link">Lika a Link</button></td>
            <td><button type="button" class="btn btn-inprogress btn-purchase">Purchase</button></td>
        </tr>
    </tbody>
</table>


<table>
    <caption>Links styled as buttons</caption>
    <thead>
        <tr>
            <th></th>
            <th><code>.btn-primary</code></th>
            <th><code>.btn-default</code></th>
            <th><code>.btn-link</code></th>
            <th><code>.btn-purchase</code></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th></th>
            <td><a href="#" class="btn btn-primary">Primary</a></td>
            <td><a href="#" class="btn btn-default">Default</a></td>
            <td><a href="#" class="btn btn-link">Lika a Link</a></td>
            <td><a href="#" class="btn btn-purchase">Purchase</a></td>
        </tr>
        <tr>
            <th><code>:hover</code></th>
            <td><a href="#" class="btn hover btn-primary">Primary</a></td>
            <td><a href="#" class="btn hover btn-default">Default</a></td>
            <td><a href="#" class="btn hover btn-link">Lika a Link</a></td>
            <td><a href="#" class="btn hover btn-purchase">Purchase</a></td>
        </tr>
        <tr>
            <th><code>:focus</code></th>
            <td><a href="#" class="btn focus btn-primary">Primary</a></td>
            <td><a href="#" class="btn focus btn-default">Default</a></td>
            <td><a href="#" class="btn focus btn-link">Lika a Link</a></td>
            <td><a href="#" class="btn focus btn-purchase">Purchase</a></td>
        </tr>
        <tr>
            <th><code>:active</code></th>
            <td><a href="#" class="btn active btn-primary">Primary</a></td>
            <td><a href="#" class="btn active btn-default">Default</a></td>
            <td><a href="#" class="btn active btn-link">Lika a Link</a></td>
            <td><a href="#" class="btn active btn-purchase">Purchase</a></td>
        </tr>
        <tr>
            <th><code>[disabled]</code></th>
            <td><a href="#" disabled class="btn btn-primary">Primary</a></td>
            <td><a href="#" disabled class="btn btn-default">Default</a></td>
            <td><a href="#" disabled class="btn btn-link">Lika a Link</a></td>
            <td><a href="#" disabled class="btn btn-purchase">Purchase</a></td>
        </tr>
        <tr>
            <th><code>.btn-inprogress</code></th>
            <td><a href="#" class="btn btn-inprogress btn-primary">Primary</a></td>
            <td><a href="#" class="btn btn-inprogress btn-default">Default</a></td>
            <td><a href="#" class="btn btn-inprogress btn-link">Lika a Link</a></td>
            <td><a href="#" class="btn btn-inprogress btn-purchase">Purchase</a></td>
        </tr>
    </tbody>
</table>

### Usage

#### `.btn-primary`

<p><input type="submit" class="btn btn-primary" value="Primary Action"></p>

```html
<input type="submit" class="btn btn-primary" value="Primary Action">
```

The main button in the form, it triggers primary action. It is possible to have two or more primary buttons on the *page* when the page has two or more different forms. But should be only one primary button in the *form*.

In HTML this is usually `type="submit"`.

<details>
    <summary>Usage example</summary>
    <figure>
        ![](https://idt.invisionapp.com/static-signed/live-embed/40012101/116144344/11/latest/I8PpULzOAk3SnqcU2icQelL5LiCcHlEPkIFxQEvVaHC1e30TTTcCoNXVpdbDLN92sBYBBT8fj81paT5nr7ctQgQlE/intBillPay-4.png)

        <figcaption>
        This page has general Search form and New transaction form. Both forms have primary button.
        </figcaption>
    </figure>
</details>


#### `.btn-default`

<p><input type="submit" class="btn btn-default" value="Additional Action"></p>

```html
<input type="submit" class="btn btn-default" value="Additional Action">
```

Any additional (not primary) button in the form. For example 'Clear' or 'Print' buttons.

#### `.btn-link`

<p><a href="#" class="btn btn-link">Back</a></p>

```html
<a href="#back" class="btn btn-link">Back</a>
```

Use this type for 'buttons' like 'Cancel' or 'Back' in multiscreen forms. In HTML code `.btn-link` usually is a link tag that has dimensions like a button.

#### `.btn-purchase`

<p><input type="submit" class="btn btn-purchase" value="Purchase"></p>

```html
<input type="submit" class="btn btn-purchase" value="Purchase">
```

Special type of primary button. Green color indicates payments, money charges or adding a service to user's account. Should be used only for purchase action.

<details>
    <summary>Usage example</summary>
    <figure>
        ![](https://idt.invisionapp.com/static-signed/live-embed/40012101/116144346/10/latest/qsGbz46aH8mvFJYJCpu1rmzvgk6SZlEbF6kCSEvAwTrfzuuplEcyYYTqEqSOvchUqWV066NhWJ1s15gzEEkCzUiwlE/intBillPay-confirm.png)

        <figcaption>
        'Submit' button on this screen indicates money charge from user account.
        </figcaption>
    </figure>
</details>

### Button sizes
