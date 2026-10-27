# Garden Dice

A small, cozy garden game prototype. **Play it here: https://richardbolland.github.io/garden-dice/**

You throw a real 3D die onto a patch of garden. Wherever it lands, and whichever face ends up on top, that's what happens to that square: a seed gets planted, the soil gets watered, a rock appears, or a little creature moves in.

You get five throws a day. Then night falls, everything you watered grows, and fully grown plants earn you a few coins. Spend them on new die faces, new seeds, more land and decorations. Nothing ever dies and there's no way to lose.

## How it's built

- A single `index.html`: no build step.
- [Three.js](https://threejs.org/) for rendering and [cannon-es](https://github.com/pmndrs/cannon-es) for the dice physics, both loaded from jsDelivr.
- All art is drawn in code on canvas.
- Progress is saved in your browser's `localStorage`.

Early prototype, so expect rough edges.
