<div align="center">

<img src="assets/glyph-field.gif" width="760" alt="The word Bezel drawn as a field of glyphs that tilt toward the pointer">

<h1>Yash Arya</h1>

<p>Design engineer in New Delhi. Software engineer at Pelocal Fintech, where I design what I build.</p>

<a href="https://www.npmjs.com/package/bezel-ui"><img alt="bezel-ui on npm" src="https://img.shields.io/npm/v/bezel-ui?style=flat-square&label=bezel-ui&color=0a0a0a"></a>
<a href="https://bezel-ui.vercel.app"><img alt="90 components" src="https://img.shields.io/badge/components-90-047857?style=flat-square"></a>
<a href="https://github.com/yasharyas/bezel/blob/main/LICENSE"><img alt="MIT" src="https://img.shields.io/badge/license-MIT-6b6b70?style=flat-square"></a>

</div>

I prototype in the browser rather than in Figma. A hover that reads well in a static frame can be useless on a phone.

## bezel

An open source React component library. Components are copied into your project as source, so you own them from then on.

```bash
npm i bezel-ui
npx bezel-add add scroll-flip-deck
```

<table>
<tr>
<td width="50%" valign="top">

<img src="assets/scroll-flip-deck.gif" width="100%" alt="A deck of cards pinned to the viewport, turning one at a time as the page scrolls">

**ScrollFlipDeck.** Pins to the viewport and turns one card per scroll step. Plain transforms, no scroll library and no 3D library.

</td>
<td width="50%" valign="top">

<img src="assets/particle-qr-code.gif" width="100%" alt="A QR code assembling itself from drifting particles">

**ParticleQrCode.** Falls apart and reassembles every few seconds, and still scans. Every code is decoded from the rendered canvas.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<img src="assets/morph-dialog.gif" width="100%" alt="A dialog growing out of the button that opened it">

**MorphDialog.** Grows out of the button you pressed, keeps keyboard focus inside, and hands it back when it closes.

</td>
<td width="50%" valign="top">

<img src="assets/scratch-foil-reveal.gif" width="100%" alt="Gold foil being scratched away with the pointer to reveal a message">

**ScratchFoilReveal.** Clear 55% of the foil and it dissolves the rest for you. No keyboard path yet, so it is not finished.

</td>
</tr>
</table>

### contrast is a build gate

<img src="assets/contrast-gate.png" width="760" alt="Terminal output listing colour pairs with their measured contrast ratios, each marked pass">

Every colour pair the library can measure gets printed with its ratio. One below WCAG AA fails the build, so the gallery cannot deploy with unreadable text in it.

90 components, after a round of deletions. What went was one shop's checkout screen rather than a library.

[gallery](https://bezel-ui.vercel.app) · [source](https://github.com/yasharyas/bezel)

## paigam

[paigam.co.in](https://paigam.co.in). Wedding invitations that live at a link instead of a PDF.

A PDF cannot change when the venue moves, and it cannot take an RSVP. Designed and built solo, 32 designs, most rooted in a specific tradition rather than a recolour.

## elsewhere

[yash-arya.com](https://yash-arya.com) is the portfolio. The Paigam case study is at [yash-arya.com/design](https://yash-arya.com/design).

[X](https://x.com/yasharyaaa) · [LinkedIn](https://www.linkedin.com/in/yash--arya) · [yasharya2601@gmail.com](mailto:yasharya2601@gmail.com)
