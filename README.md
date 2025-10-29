# Tool Decals
A new way to customize your tools! Apply, Remove and even add your very own decals to the game!

Ever wanted to customize your tools? Well heres the perfect solution, introducing: Tool Decals

Tool Decals is a Pack that mainly serves 2 purposes, #1 Giving the Player the ability to customize their tools using items they need to find throughout their world and #2 Making it as easy as possible for other Datapacks to add their own Skins using Tool Decals as the base


### Applying Decals:
To apply decals players will first need to craft the Decal Bench, a new block crafted out with copper once placed the player can right click the Decal Bench with any compatible Tool and Weapon to put it on the Decal Bench and then either right click with a brush to remove the current decal or right click with a decal item, this will consume the item and apply the decal to the tool after which it can be picked up again by right clicking with an empty hand


### Compatability:
Due to Tool Decals being meant to be used in combination with other datapacks compatability was very important to me. Every item (should a decal be applied) will save their original `item_model` and revert back to it should the decal be removed by the player 


### FAQ:
Q: How do decals affect my tools?
A: Decals purely affect the visuals of the tools, all other data is kept the same.

Q: How do i get started?
A: Theres advancements in the datapack that guide you trough getting decals and the decal bench

Q: Where can i find custom items?
A: All custom items can be obtained using the command /function decals:give/<item_name>

Q: Why are all custom items black and purple blocks?
A: You dont have the required Resourcepack installed and/or enabled you can find it under the downloads section of the datapack


### How to add Custom Decals:

Adding Custom Decals is entirely handled via the `custom_data` component

#1 Registering a Custom Item as a Decal
The Datapack determins what and what isnt a Decal using `decal:1b` that means any item can be turned into a decal

#2 Linking a Skin to the Decal Item
By adding `decals.decal:"<item_model>"` to the `custom_data` component on your custom item the item model specified inside of the `"<item_model>"` field will later be added to the item on the Decal Bench or (should an item model already exsist on the item) replaced with the specified item model 

**[!Note! the item model must be registered under the namespace decals otherwise it will break the pack we recommand you give your model names a custom prefix to avoid possible issues with other addons]**

### Current Support Languages:
- `En` Translation by Jan
- `De` Translation by Jan
- `It` Translation by LordOfBruh

### Credits:
- Jan: Textures, Coding, Ideas
- LordOfBruh: Major Help with Coding, Moral Support, Cutie Patootie
