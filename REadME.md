# Pizza Legends !
16 x 9 aspect ratio 
## Code
````
(function(){

})();
````
Function That Execute Is Self 

this.element = config.element;
to pass any element to Overworld Class 

## Code
````md
init(){
    const hero = new Image();
    hero.onload = () => {
      this.ctx.drawImage(
        hero,
        0, //   Left Cut
        0, //   Top Cut
        32, //  Width Of Cut
        32, //  Height Of Cut
        x * 16 - 8, // Position Vertical
        y * 16 - 18, // Position Horizontal
        32, // Size Of Sprite In Width
        32 // Size Of Sprite In Height
      );
    };
    hero.src = "/WebGame/images/characters/people/hero.png";
    }
````



init() : is initializing the function to its class .

const hero : is a container for the image to call .

hero.scr : is need to know where the image source will be taken.

hero.onload : will download the image that taken on the source.

this.ctx.drawImage([image]/[cuts,cuts]/[width cut , height cut]/[pos x , pos y]/[width , height]);

 - will put the image in the game-container and draw it on the canvas.
 - image : is the image that been called
 - x,y : is the coordinates of the image in game-container


