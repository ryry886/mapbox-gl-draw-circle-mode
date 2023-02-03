# mapbox-gl-draw-circle-mode


## Usage

### Installation

```
npm install mapbox-gl-draw-circle-mode
```

```js
import DrawCircle from 'mapbox-gl-draw-circle-mode';
const modes = MapboxDraw.modes;
modes.draw_circle = DrawCircle;

const draw = new MapboxDraw({
  modes: modes
});

draw.changeMode('draw_circle');
```

or

```js
import DrawCircle from 'mapbox-gl-draw-circle-mode';
const draw = new MapboxDraw({

    modes: {
      //...MapboxDraw.modes,
      draw_circle:DrawCircle
    }
});

draw.changeMode('draw_circle');
```


### License

MIT
