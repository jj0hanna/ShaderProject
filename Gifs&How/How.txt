I created a few shaders in Unreal using unrels material system and i decided to make a winter world with sparkeling snow, snow on rocks 
and a few shaders that could be used for t.ex powerups. 

- Snow shader: white basecolor with two layers of a sparkle textures and a normalmap. And on top of that a function that makes sure that the sparkels only
shows when the sun is on the material.
- Snow on rock: lerping a texture for the rock, and a white color for the snow. Using a calculation to calculate how much of the snow that sould cover the rock
- Snow with dirt under. Sparkeling snow on top and a brown color under. 
- Iceshader transparant shader and a texture
- HiddenPortal shader. A shader that calculates where the player is and the object. At a certain distance make the object invisable.

- "Powerups shaders" 
Light blue/white powerupball - Powerup inspired of a snowstorm.Three lerping colours and with a moving normalmap texture.
Transparant icy powerupball2 - Icey powerup with a icey chell with a moving texture, and white in the edges
Dark blue powerupball3 - Powerup mixed with insparation from the other two powerups and the sparkeling snow. Using layers that moves differnt and looks like the are inside 
and in fron of the ball. Same for the sparkeling. Added a edge glow and a inner glow to spice upp the powerball and used many differnet colors.