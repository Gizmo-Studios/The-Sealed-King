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

<div>
  <h3> 🔫 PCG - Magazine:</h3>

  <img align="right" height="500"
       src="https://github.com/user-attachments/assets/3d2f5b2a-0016-4220-b525-3c071b24872c"/>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/d6ee8bee-d9a4-4b13-a037-41ea51970b74"/>
  I wanted to create a tool for fast and easy editing of an asset with multiple variations. Because I really enjoy shooters, the first idea that came to my mind was a magazine generator that creates magazines with different sizes and shapes.

The tool handles the entire pipeline, including high-poly to low-poly baking and UV unwrapping. Combined with procedural materials in Substance Designer, it is possible to create a wide range of interesting variations.

The finished assets are best suited for third-person games that require a large amount of variation. Since the assets are generated procedurally, they can lack a bit of uniqueness compared to fully hand-crafted models.
  <img align="left" width="300"
       src="https://github.com/user-attachments/assets/c79f7dce-8564-4e0c-9dc2-4a329833f4f3"/>


  <br clear="all">
</div>
