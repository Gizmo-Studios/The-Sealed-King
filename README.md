# 👑 The Sealed King
Collection on different small procedural assets and other tech art realted projects

## 🎯 Skills & Software
- `Unreal Engine`
- `Niagara`
- `FMod`
- `Materials / Shader`
- `Unreal PCG`

## 🗝️ Key Aspects
- Working on game juice / game feel
- Using **Niagara** to create VFX 
- Integrating **FMod** into the project



## 🚩 Personal & Design Goals
Scince I saw a GDC Talk from Sea of Thieves a few years back I am really interested in **Tech Art** and **Procedural Content Generation**. Planning and writing tools gives me a certain kind of pleasure, like solving a puzzle. All pieces falling into the right place and with one button press I can create awsome assets or change something on the fly.

<div>
  <h3> 🧱 Hotspot Texturing:</h3>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/321d179e-81a6-4bad-835a-4cdb8d0e40fe"/>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/cf33159e-d8c1-4107-bd58-d0476d814362"/>

  <br clear="all">
  <img align="right" width="250"
       src="https://github.com/user-attachments/assets/28af9585-0118-4421-9c26-44555badf97a"/>
   <img align="right" width="250"
       src="https://github.com/user-attachments/assets/40a91cfc-4ee8-49f0-8fd9-0a64c41972be"/>


 
  Inspired by Martin Donald’s Hotspot Texturing example, I wanted to try the approach myself. I created a small Houdini asset that takes a mesh as input and either unwraps it automatically based on surface angles or allows the use of a handmade unwrap.

  The asset provides options to define the UV and mesh size and calculates a score based on size and aspect ratio, with adjustable weighting to control which factor is more important. The trim texture is supplied by the user along with a cut plane. The sections of the texture plane are also scored, and the tool then finds the best match between the UV score and the mesh score.

  The UVs are placed into the corresponding trim area and scaled to fit either uniformly or along a single axis. Afterwards, the unwrapped mesh can be used directly in-engine together with the texture.

  This tool allows a large number of objects to be unwrapped and textured in very little time and works especially well in sci-fi settings due to its focus on hard-surface modeling.

  <br clear="all">
</div>

<div>
  <h3> 🔫 PCG - Magazine:</h3>

  <img align="right" width="500"
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
