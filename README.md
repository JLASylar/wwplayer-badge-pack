# WWPlayer white studio logos

Badge packs for WWPlayer. They replace the studio logos WWPlayer shows on detail pages with white versions. There are two packs. Add the one you prefer in WWPlayer → Settings → Appearance → Badge packs. You can add both and switch between them.

## Dark logos only (27 logos)

Recolours only the black or very dark logos, which are hard to see on dark backgrounds, such as Constantin Film, Lionsgate, DreamWorks and NEON. Colourful logos like Marvel, Universal and Gaumont keep their original colours.

```
https://raw.githubusercontent.com/JLASylar/wwplayer-badge-pack/main/pack.json
```

## All white (63 logos)

Turns every studio logo in WWPlayer's catalog white, so the row looks uniform. Logos that are a filled shape with text inside (Marvel, Bad Robot, DC, StudioCanal and others) become a white shape with the text cut out.

```
https://raw.githubusercontent.com/JLASylar/wwplayer-badge-pack/main/pack-all-white.json
```

## Notes

- Each entry uses the regex `(?!)`, which matches nothing, so neither pack changes resolution, HDR or codec labels. WWPlayer matches studios by name only.
- Streaming platform logos (Netflix, Disney+, Prime Video and others) are not covered. WWPlayer only applies badge packs to production-company logos.
- The images are the logos bundled with WWPlayer 1.3.15, recoloured to white. All trademarks belong to their owners.
