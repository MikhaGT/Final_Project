Getting started:

To start playing the game, you need:
1) To download the entire project
2) To download the Node.js along with the npm and npx
3) To download all of the dependencies using: "npm install three@0.145 @react-three/fiber@8.8.10 @react-three/drei@9.34.4 @react-three/cannon@6.4.0"
4) In the terminal go to the project and run the "npm run start", npm (Node package manager) will build and compile the entire project for you and instantly transfer you to the new broser page where you can enjoy the game.

The main frameworks and tools that has been used in development are React, Cannon.js and Three.js. So the game is itself represent a car on the small track where one can drive and do some cool tricks using the ramp. The game has a basic physics implemented in it using the Cannon.js, this engine works really good with the Three.js and learning and working with cannon.js was much easier then other engines. The ramp is not the only interactable object, again using cannon.js some of the objects are working as colliders (trees for instance) so that player could not go though them, which adds some more realism to the game.

The game controls are displaced in the left lower corner, 'wasd' to move, 'r' to reset the car, 'k' to change the camera (so there are 2 cameras: first is the 3rd person and the second is global, static one), both are really nice as for me and really cool to use together by always switching between them. Also it is a nice tool once a player is getting bored with any of the 2 perspectives, just change them! And last but not the least, 'arrows' which allow a player to flip his car in all 4 direction, that is implemented for a player to be able to make nice flips in the air while jumping from the ramp (because we can control the angular velocity of the car while in the air).
