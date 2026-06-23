# C0ll3n-DBD-Nodes

## Content
### Dedicated Shader

*It's a dedicated shader with a toggle to choose between Legacy-style or IDGAD-style hair; the inputs change depending on the selection.*

- C0ll3n DBD Hair

<img width="288" height="163" alt="v2 3 5" src="https://github.com/user-attachments/assets/df5d08d5-3e6f-4f01-8650-409ec7d9566c" />

<img width="303" height="788" alt="v2 3 5SS2" src="https://github.com/user-attachments/assets/cdb49a17-9fea-40be-8ad8-7c7d30c1b204" /><img width="303" height="606" alt="v2 3 5SS3" src="https://github.com/user-attachments/assets/7d2625d7-3ed4-4510-b330-795d3a9518be" />

### Hair Composite Nodes

*These are nodes that attempt to convert certain parameters from the dedicated shaders to the Bubba or Lance Quen shaders*

- C0ll3n Hair composite
- C0ll3n HC Simple [IDGAD]

<img width="626" height="446" alt="v2 3 5SS10" src="https://github.com/user-attachments/assets/5d175c61-408d-44f2-bca9-e2bdd38d43c1" />

### Custom Hairs (Swapping/Remapping)

*The IDGAD Hairs node group must be connected to one of the shaders that accept IDGAD texture inputs; it can be used with any shader that processes these textures. Hair Styles is a standalone shader that offers more features because it uses more textures than IDGAD can provide on its own, even with the Flow map*
*Requires to remap the UV's using a Hair Guide texture (Included in the blend file) in UV Editor*

- C0ll3n IDGAD Hairs
- C0ll3n Hair Styles

<img width="527" height="434" alt="v2 3 Info4" src="https://github.com/user-attachments/assets/497d693c-1ee1-4d67-9741-af7ba5fc09f2" />

### Parallax/Offset

*These are groups of nodes designed to create the effect of adding more hair, which is useful for models with very little hair. The effect varies depending on the viewing angle, but it requires support from a shader; it can be either IDGAD or Legacy*
*You need to create 3 more copies of the original texture, depending on which one you're working on (IDGAD or Legacy), no apply for Simple version*

- C0ll3n Parallax/Offset [Inputs]
- C0ll3n Parallax/Offset [Outputs]
- C0ll3n Simple Parallax

<img width="915" height="225" alt="v2 3 5SS11" src="https://github.com/user-attachments/assets/60b63c19-ca6f-4903-8bb5-6116f93338df" />

### Extra node groups

*These are groups of nodes that function as additional add-ons: “Sun Damage” adds a gradient to “DBD Face Sun Damage” within Bubba's nodes, leaving a visible mark along the edges; “Texture Color Influence” is only for editing colors, saturations, etc., of a color texture (BC); “Custom Tip/Root Color” is only useful on hair whose UVs' have been changed—such as Legacy wigs—to use IDGAD shaders or the dedicated Hair Styles shader, and "DBD JD IDGAD" is a node group made by JD that only work for Bubba shaders that expect those inputs (Specular, Roughness, and Scatter)*

- Sun Damage Gradient
- Texture Color Influence
- Custom Tip/Root Color
- DBD JD IDGAD

<img width="782" height="329" alt="v2 3 Info5" src="https://github.com/user-attachments/assets/20ddca96-6133-41c4-94ca-af36cf00f9fc" />

### Hair Guides

*These are alpha textures for use it as a guide designed for wwork with custom hairs node and/or shader and remap UV's of your hair model, this process can be done in UV Editing in Blender; for being append, you have to go in 'Image' folder; HairGuide_IRS it's a texture for IRS texture made by Bubba, but it needs to be imported maually (IRS.png inside 'Image' folder) using a 'Texture Image' node and connect it in any IDGAD shader*

- HairGuide_Curly
- HairGuide_Dreadlocks
- HairGuide_IRS
- HairGuide_Straight
- HairGuide_Unkempt

<img width="132" height="242" alt="v2 3 SS3" src="https://github.com/user-attachments/assets/744508a9-e7c3-4845-9a03-2fb18e32b5e9" /> <img width="167" height="99" alt="v2 3 SS4" src="https://github.com/user-attachments/assets/eeddfb1c-14b3-4e14-aeb3-a08387706cae" />

*Within 'NodeTree' you'll find more nodes with parentheses '(Don't Import)' and more textures in 'Image'. You can completely ignore these, as each one is imported internally into the same Shaders or Node Group being used*
