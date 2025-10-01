[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/d-DorLAf)
# minigame-1
## Devlog
Write your Devlog here.
To explain the relationship between Components, GameObjects, and Scenes, I like to think of my platforming game itself. Components are like the parts that give each object its abilities—such as making coins spin, spikes damage the player, or the player able to jump. GameObjects are the individual elements in the game—each platform, coin, spike, and the player capsule—assembled from these components. The Scene is the entire level where all the GameObjects interact to create the gameplay experience. Without Components, GameObjects wouldn’t work; without GameObjects, the Scene would be empty; and without the Scene, the game wouldn’t exist.
In this level, I arranged the platforms in a new layout and placed at least five coins and five spikes throughout the Main Scene. I added a SpikeDamage component to the spikes, ensuring that whenever the player touches a spike, they die and the game stops, increasing the challenge. I also adjusted the player’s movement speed in the FirstPersonController Component to make jumping and navigating the platforms feel smoother. This process helped me understand how Components give functionality to GameObjects, and how the arrangement of GameObjects shapes the experience of the entire Scene.

## Open-Source Assets
- Starter first-person assets: https://assetstore.unity.com/packages/essentials/starter-assets-firstperson-updates-in-new-charactercontroller-pa-196525
- Low poly platformer kit: https://assetstore.unity.com/packages/3d/environments/lowpoly-platformer-kit-free-modular-stylized-blocks-319018 
