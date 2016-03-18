to use alternative (but unsupported) textures for vanilla map

Copy the two atlas files to parent folder (\map\terrain).
->
Go and open "pdxmap.lua" (gfx\fx)

change from

static const float TERRAINTILEFREQ = 128.0f;
static const float NUM_TILES = 4.0f;

to 

static const float TERRAINTILEFREQ = 144.0f;
static const float NUM_TILES = 5.0f;

save