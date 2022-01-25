# BiomeGd
## The perfect Noise Layer for immaculate biome mapping.
### By Harroo

## About

BiomeGd is made with one purpose in mind, easy Biomes.

It has 2 modes, Fleck and Blot. Choose the one that works best for you.

It will return a `float` value between `0.0f` and `1.0f`;

## Samples

### Fleck Mode
![scrot1](https://raw.githubusercontent.com/harroo/BiomeGd/main/Samples/fleck-sample.png)
### Blot Mode
![scrot1](https://raw.githubusercontent.com/harroo/BiomeGd/main/Samples/blot-sample.png)

## How to get setup with BiomeGd?

Simply Copy the [BiomeGd/](https://github.com/harroo/BiomeGd/tree/main/BiomeGd) folder into your Project.

To use BiomeGd, try the following!

```cs
/* Using-tag. */
using BiomeGd;

/* To get Noise-Values. */
float v = BiomeFleck.Get(x, y, scale); // Fleck Mode..
// Or ..
float v = BiomeBlot.Get(x * scale, y * scale); // Blot Mode..

/* Example usage. */
int biomeId = (int)(v * 4);

switch (biomeId) {

    case 0: return Biome.Desert;

    case 1: return Biome.Snow;

    case 2: return Biome.Forest;

    case 3: return Biome.Hills;
}
```


## Other stuffs

If you'd like to chat, or ask me anything, feel free to come along and say hello on Discord!
[https://discord.gg/MeAFfR4eUD](https://discord.gg/MeAFfR4eUD)

---

Spelling and Orthography correction: [Kieralia](https://github.com/kieralia)
