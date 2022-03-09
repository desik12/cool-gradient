# Cool Gradient

### 🔻 Demo

 [Cool Gradient](https://2537gfwr25.glitch.me/)

<h2 align="center"> 💻 Código </h2>

<h2> HTML </h2>

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <style>
      .background--custom {
        background-color: #FFFFFF;
        width: 100vw;
        height: 100vh;
        position: absolute;
        overflow: hidden;
        z-index: -2;
        top: 0;
        left: 0;
      }
      canvas#canvas {
        z-index: -1;
        position: absolute;
        width: 100%;
        height: 60%;
        transform: rotate(-24deg) scale(2) translateY(-56%);
        --gradient-color-1: #ef008f; 
        --gradient-color-2: #6ec3f4; 
        --gradient-color-3: #7038ff;  
        --gradient-color-4: #ffba27;
        --gradient-speed: 0.000029999999999999997;
      }
    </style>
  </head>
  <body>
    <div class="background--custom">
      <canvas id="canvas" />
    </div>
    <script src="https://cdn.jsdelivr.net/gh/greentfrapp/pocoloco@minigl/minigl.js"></script>
    <script>
    var gradient = new Gradient();
    gradient.initGradient("#canvas");
    </script>
  </body>
</html>
```


<h2> JavaScript </h2>

<div> </div>

```js
    var gradient = new Gradient();
    gradient.initGradient("#canvas");
```

<h2> CSS </h2>
    
```css
      .background--custom {
        background-color: #FFFFFF;
        width: 100vw;
        height: 100vh;
        position: absolute;
        overflow: hidden;
        z-index: -2;
        top: 0;
        left: 0;
      }
      canvas#canvas {
        z-index: -1;
        position: absolute;
        width: 100%;
        height: 60%;
        transform: rotate(-24deg) scale(2) translateY(-56%);
        --gradient-color-1: #ef008f; 
        --gradient-color-2: #6ec3f4; 
        --gradient-color-3: #7038ff;  
        --gradient-color-4: #ffba27;
        --gradient-speed: 0.000029999999999999997;
      }
      
    
  
