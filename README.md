# 👑 The Sealed King
Collection on different small procedural assets and other tech art realted projects

## 🎯 Skills & Software
- `Unreal Engine`
- `Niagara`
- `FMod`
- `Materials / Shader`
- `Unreal PCG`
- `Houdini`

## 🗝️ Key Aspects
- Working on game juice / game feel
- Using **Niagara** to create VFX 
- Integrating **FMod** into the project



## 🚩 Personal & Design Goals
In this project I wanted to dive deeper into the visual aspects of tech art and focus more on **Visual Effects**. I had full control over all VFX and was **solely responsible** for the **look, feel and creation** of the effects. I also tried to integrate Houdini into my workflow and looked into Unreals PCG.

<div>
  <h3> 💥 Niagara VFX:</h3>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/321d179e-81a6-4bad-835a-4cdb8d0e40fe"/>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/cf33159e-d8c1-4107-bd58-d0476d814362"/>



  Finding a fitting art style for our effects was a bit of a challenge. It was important to land somewhere between stylized and realistic.. Effects should support our gameplay and not take away from it. I started to play around with different degrees of stylization and intensity. One example is our slash effect. At first, it was just a small trail. Then it became a large slash that covered too much area. Finally, I settled on the medium version that made it into the final game.
  



 I also used Houdini to create several of our effects. The blood decals were created in Houdini using a fluid simulation and then turned into a grayscale texture, which I can sample to achieve a smooth animation that doesn’t rely on the limited frame rate or resolution of a texture sheet. Some of the smoke uses the newer Heterogeneous Volumes in Unreal, which allow the import of volume textures. The smoke simulation was created in Houdini and baked into a volume texture.
  <br clear="all">
  <img align="right" height="250" width="500"
       src="https://github.com/user-attachments/assets/bca1c4c9-7b4b-4f3b-9662-b71ae23b3ed1"/>
   <img align="right" width="250" 
       src="https://github.com/user-attachments/assets/40a91cfc-4ee8-49f0-8fd9-0a64c41972be"/>
  <br clear="all">
</div>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/cdc4276d-1d9c-4106-a22f-d51b635a05e5"/>
<br clear="all">

<div>
   <img align="right"  width="500"
       src="https://github.com/user-attachments/assets/94f27c6d-f0fc-45a6-a1fc-7dbb9a0ab5d2"/>
  <h3> 💣 Chaos - Destruction:</h3>

I was also responsible for implementing Chaos Destruction in our game. Several environmental props such as barrels, tables, chairs, and pillars were made fully destructible.

A major focus was keeping the system performant. I carefully controlled fracture density, collision complexity, and debris lifetime to avoid unnecessary physics calculations. With the Chaos Field I controlled sleep thresholds and stop objects like the pillar from full destruction.

To enhance the impact without adding smaller cluster of geometry, I complemented the destruction with lightweight VFX such as dust bursts and debris particles.
</div>
<br clear="all">
![firegoblet](https://github.com/user-attachments/assets/94f27c6d-f0fc-45a6-a1fc-7dbb9a0ab5d2)


<div>
  <h3> 🛢️ PCG - Barrel Placer:</h3>
  <img align="right" height="500"
       src="https://github.com/user-attachments/assets/0c05af78-3f23-4cd9-a068-ad41d9bc3668"/>

       
As a big PCG fan I also took some time to look into the PCG system from Unreal and created a small tool to place actors quickly inside an area.

  <br clear="all">
</div>
