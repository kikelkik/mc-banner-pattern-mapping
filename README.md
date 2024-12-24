# mc-banner-pattern-mapping
Mapping for Banner Patterns before and after Minecraft 1.21.2

Since Version 1.21.2, banner pattern names and its data format has been changed.

For example, a `/give @p white_banner{BlockEntityTag:{Patterns:[{Pattern:"cr",Color:3}]}}` doesn't work anymore and should be `/give @p white_banner[banner_patterns=[{"pattern":"creeper","color":"lime"}]]` instead.

## Pattern Mapping

| **Old pattern name** | **New Pattern Name** |
-- | --
bl | square_bottom_left
bo | border
br | square_bottom_right
bri | bricks
bs | stripe_bottom
bt | triangle_bottom
bts | triangles_bottom
cbo | curly_border
cr | cross
cre | creeper
cs | stripe_center
dls | stripe_downleft
drs | stripe_downright
flo | flower
gra | gradient
hh | half_horizontal
ld | diagonal_left
ls | stripe_left
mc | cirlce
moj | mojang
mr | rhombus
ms | stripe_middle
rud | diagonal_up_right
rs | stripe_right
sc | straight_cross
sku | skull
ss | small_stripes
tl | square_top_left
tr | square_top_right
ts | stripe_top
tt | triangle_top
tts | triangles_top
vh | half_vertical
gru | gradient_up
vhr | half_vertical_right
hhb | half_horizontal_bottom
lud | diagonal_up_left
rd | diagonal_right
glb | globe
pig | piglin

## Color Mapping

| **Old Color Value** | **New Color Name**       |
|-----------|-----------------|
| 0         | white           |
| 1         | orange          |
| 2         | magenta         |
| 3         | light_blue      |
| 4         | yellow          |
| 5         | lime            |
| 6         | pink            |
| 7         | gray            |
| 8         | light_gray      |
| 9         | cyan            |
| 10        | purple          |
| 11        | blue            |
| 12        | brown           |
| 13        | green           |
| 14        | red             |
| 15        | black           | 

