```html
<div style="
  position: relative;
  width: 100%;
  display: grid;
">

  <!-- Fondo -->
  <img
    src="assets/xpfondo-opaco.png"
    alt="Fondo"
    style="
      grid-area: 1 / 1;
      width: 100%;
      display: block;
    "
  />

  <!-- GIFs por encima del fondo -->
  <div style="
    grid-area: 1 / 1;
    position: relative;
    z-index: 2;
    display: flex;
    align-items: flex-start;
    gap: 10px;
  ">
    <img
      src="https://media.tenor.com/FpQNiik_1v8AAAAi/clippy-karl-klammer.gif"
      alt="Clippy"
      width="100"
      style="height: auto;"
    />

    <img
      src="https://i.postimg.cc/15B8MGDz/windows-C-AOL-red.gif"
      alt="GIF animado"
      width="400"
      style="height: auto;"
    />
  </div>

</div>
```
