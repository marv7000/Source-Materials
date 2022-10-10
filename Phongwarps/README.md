# Phongwarps

Phongwarps are a way to "bend" the phong lighting using a texture. This usually results in a more controlled phong reflection on non-diffuse materials.

[![image](https://developer.valvesoftware.com/w/images/d/d0/Phongwarp_example.png)]()

Use the warps in your .vmt with

    $phongwarptexture <filename>

Depending on the material you might want to use either ``phongwarp_iron`` or ``phongwarp_steel`` for generic materials.
You may compress these with DXT5.

## Important 
Do not use Phongwarps for organic materials, as they will likely look off. Instead, check out [Lightwarps](https://developer.valvesoftware.com/wiki/$lightwarptexture).

| Name | Use Case |
| --- | --- |
| phongwarp_chrome | Very shiny/polished metals
| phongwarp_iron | Most basic metals
| phongwarp_steel | Steel, Weapons
| phongwarp_wood | WIP, doesn't look too great
