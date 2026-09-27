# BlotX card art

Card faces of the "Classic" and "Large" decks in the BlotX app: the 32 Belote cards (7 to Ace in
four suits), one SVG per card.

## Original work

Based on **Vector Playing Cards 2.0** by Chris Aguilar. Copyright 2015 Chris Aguilar.

- Source: https://sourceforge.net/projects/vector-cards/
- Also on Wikimedia Commons: [File:Color_52_Faces_v.2.0.svg](https://commons.wikimedia.org/wiki/File:Color_52_Faces_v.2.0.svg)
- License: GNU Lesser General Public License, version 3, as stated by the author in the original file

## What we changed

Modified by Blot X LLC in September 2026.

Both decks:

- Kept only the 32 Belote cards; removed the 2 to 6 of each suit and the jokers.
- Removed the card border stroke and made the corners square (the app rounds them when drawing).
- Moved a few misplaced pips and corner indexes onto a consistent grid.
- Enlarged the center pip of the four Aces.
- Ace of Spades: replaced the center pip with an ornamented spade filled with Armenian manuscript
  bird-script (t'rchnagir) motifs, embedded as an image.
- Renamed the layers (`bg`, `index`, `suit`, `pip`, `art`) and exported each card as its own SVG.

Large deck only (`vector-large/`):

- Redrew the corner indexes larger in Barlow Condensed Medium (SIL Open Font License 1.1),
  converted to outlines, with larger corner suit pips.
- Scaled the face pips to 88% and the court art to 86% about the card center.

## Files

- `vector-classic/`: the "Classic" deck, 32 SVG files
- `vector-large/`: the "Large" deck, 32 SVG files

Files are named after the card: suit `S`, `H`, `D`, `C` (spades, hearts, diamonds, clubs) and rank
`SEVEN`, `EIGHT`, `NINE`, `TEN`, `JACK`, `QUEEN`, `KING`, `ACE`, for example `H_QUEEN.svg`. Every
card is 237.047 x 331.535 units.

## License

These modified files are distributed under the same license as the original: the GNU Lesser
General Public License, version 3. `LICENSE` holds the LGPL text and `COPYING` holds the GNU
General Public License version 3, which the LGPL builds on.
