# mapbox-gl-draw-circle-mode


## Usage

### Installation

```
npm install mapbox-gl-draw-circle-mode
```

```js
import DrawCircle from 'mapbox-gl-draw-circle-mode';
const modes = MapboxDraw.modes;
modes.draw_rectangle = DrawRectangle;

const draw = new MapboxDraw({
  modes: modes
});

draw.changeMode('draw_rectangle');
```

### License

MIT