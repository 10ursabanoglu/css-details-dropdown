# css-details-dropdown

**Description**

A simple CSS component that turns HTML `<details>` elements to dropdown menus using only CSS.

**[View the demo on CodePen &rarr;](https://codepen.io/Onursabanoglu/pen/VweMrLv)**


## Dropdown Menu Default

After creating an HTML `<details>` element, add a dropdown class to it. Then create the `<ul>` structure where our menu elements will be listed and place the menu elements in this unordered list.

```html
<details class="dropdown">
  <summary>Dropdown Menu</summary>
  
  <ul class="dropdown-menu">
    <li class="nav-item">
      <a class="nav-link" href="#">Homepage</a>
    </li>
    <li class="nav-item">
      <a class=nav-link href="#">Features</a>
    </li>
    <li class="nav-item">
      <a class=nav-link href="#">Contact</a>
    </li>
  </ul>
</details>
```

The `<summary>` element is the element in which the `<details>` element contains a description title or a summary caption. Clicking the `<summary>` element toggles the state of the `<details>` element.

## Dropdown Menu Right

In the dropdown menu, the menu always opens left justified. If you want to change this location, add the `dropdown-menu-right` helper class.

```html
<details class="dropdown">
  <summary>Dropdown Menu</summary>
  
  <ul class="dropdown-menu">
    <li class="nav-item">
      <a class="nav-link" href="#">Homepage</a>
    </li>
    <li class="nav-item">
      <a class=nav-link href="#">Features</a>
    </li>
    <li class="nav-item">
      <a class=nav-link href="#">Contact</a>
    </li>
  </ul>
</details>
```

And that's it, Works perfectly smoothly!.



#### Please have a look at the resources below:

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/summary