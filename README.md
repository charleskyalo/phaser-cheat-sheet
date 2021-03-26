

<img align="right"  width="100" height="100" src="https://user-images.githubusercontent.com/40355510/112586621-2d42be80-8e0d-11eb-912c-8af3443114d4.png" alt="phaser js logo">


## [phaser js](https://phaser.io)
###  *What is it phaser js?* *What problem does it solve* ?



# Phaser is a fun, free and fast 2D game framework for making HTML5 games for desktop and mobile web browsers, supporting Canvas and WebGL rendering.

[docs](https://photonstorm.github.io/phaser3-docs/index.html)

[Phaser homepage](https://phaser.io/)


### phaser game Boiler plate  

```js
// the  preload function exists in the scene object  loads in assets like images and sounds

function preload (){
// load assets from external paths either local or external sources
}



// the create function in the scene object creates the game sprite  images and colliders groups and som  

function create(){
  // contains code to render game objects;
}

// the update function  in the scene object that executes every  animation frame it can be used to check for keyboard input or manipulating game objects among other things.
 function update(){
// excecute code every animation frame
}

// the config object contains the game meta information such as height  and width of the game screen background color the scene functions  

const config = {
  // contain game properties with meta information
type:Phaser.AUTO,
width:480,
height:640,
physics:{
  default:'arcade'
}
scene:[scene1,scene2,scene3]
// the config.type property will render the game using canvas or webgl

}

//  create and start phase game
const game = new Phaser.game(config);


```
