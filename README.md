# loopz
Game loop with fps limit option using request animation frame

    yarn install loopz --save

### Usage

    import Loop from 'loopz;

    // How many times update function shall be called per second
    const fps = 60;

    new Loop(dt => {
      // dt is passed time in milliseconds eg: ~16
      console.log(dt);
    }, fps).start();
