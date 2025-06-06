# task-2-assignment-06-2025

# Task 2

### HTML:

```tsx
<!-- index.html -->

<nav class="nav">

<button class="hamburger" id="menuBtn">Menu</button>

<ul class="menu" id="menu">

<li>Home</li><li>About</li><li>Contact</li>

</ul>

</nav>
```

### CSS:

```tsx

/* styles.css */

.nav {display:flex;justify-content:space-between;align-items:center;}

.menu {display:flex;gap:2rem;}

@media (max-width:768px){

.menu{flex-direction:column;position:absolute;top:64px;left:0;width:100%;

background:#fff;transform:translateY(-150%);transition:.3s ease;}

.menu.open{transform:translateY(0);}

}
```

## Goal

At exactly 768 px the menu “ghosts” in and out.

1. Use ChatGPT/ Cursor to identify the root cause of the slide-down glitch.
2. Produce a patched styles.css (CSS fence, nothing extra) that fixes it.

**Experiment and try ChatGPT as well as Cursor.**
