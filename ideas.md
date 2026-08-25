# Roseau Hotel & Spa — Design Directions

## Three candidate approaches

| Theme Name | Very Brief Intro | Probability |
| --- | --- | --- |
| Highland Atelier | A warm, editorial hospitality experience inspired by the sculptural stone, brass, and deep green landscapes around Gondar. It feels quietly exclusive rather than ostentatious. | 0.07 |
| Modern Lalibela | A sunlit, textural contemporary resort interface informed by Ethiopian craft geometry, pale limestone, and natural indigo. It conveys calm cultural confidence. | 0.04 |
| Midnight Conservatory | A dramatic, night-time booking world with lacquered black, botanical shadows, and ceremonial gold details. It frames the reservation as an invitation-only occasion. | 0.09 |

## Chosen approach — Highland Atelier

### Design Movement

**Contemporary Ethiopian hospitality editorialism.** The visual language combines the reserve of a luxury travel journal with tactile architectural cues found in historic Gondar: hand-finished stone, warm parchment, oxidized brass, and controlled botanical accents.

### Core Principles

1. **Quiet ceremony:** Each action feels intentional, from choosing a suite to confirming a payment, using considered labels, calm pacing, and a visible reservation narrative.
2. **Material credibility:** Soft stone surfaces, ink-black type, muted metal lines, and botanical green accents should suggest physical hospitality materials rather than generic software gradients.
3. **Editorial hierarchy:** The experience favors asymmetric compositions, generous margins, serif moments, and numbered sections over stacked dashboard tiles.
4. **Transparent confidence:** Pricing, package inclusions, and booking progress remain legible and itemized without visual clutter.

### Color Philosophy

The base is **parchment ivory** to evoke daylight on local limestone and maintain accessibility. **Ink black** grounds dense practical content; **Roseau green** is the ownable signal of restoration, gardens, and spa calm. **Burnished brass** is reserved for curated luxury cues, selected controls, and confirmation details—never as a dominant fill. A small **terracotta earth** tone provides warmth for secondary labels and sensory contrast.

### Layout Paradigm

The interface behaves like a **reservation folio**: a narrow, sticky reservation ledger occupies one side on desktop while the experience unfolds in a wider editorial column. Booking stages are visually bookmarked by large vertical numerals and ruled dividers. On smaller screens, the ledger becomes an anchored bottom summary so the primary task always remains in view.

### Signature Elements

1. **Folio rules:** Fine brass horizontal and vertical rules with a small circular seal punctuate key transitions.
2. **Numbered chapters:** Large, lightly outlined stage numbers establish the three-step reservation rhythm.
3. **Roseau arch:** A soft, architectural arch motif appears in room imagery framing and brand mark geometry.

### Interaction Philosophy

Controls provide composed physical feedback: selected items acquire a green inset keyline and a brass tick rather than exaggerated fills. Hover states lift only slightly and show considered information. The reservation ledger recalculates immediately, confirming every choice without interrupting the guest.

### Animation

Use 160–240ms snappy ease-out transitions for card selection, buttons, tooltips, and menu changes. The payment dialog enters at 95% scale with opacity transition over 240ms. Reservation stage content fades upward by 12px in a short stagger. The successful voucher uses one restrained, expanding ring around the confirmation mark. All nonessential motion disables under `prefers-reduced-motion`.

### Typography System

**Cormorant Garamond** provides the display voice for brand, room names, key pricing, and confirmation moments; it should be used at deliberate editorial sizes with tight hierarchy. **Manrope** is the operational sans for forms, itemized bills, and controls; use 500–700 weights for clarity. Stage numbers use Manrope with wide tracking and low-opacity outlines. Avoid generic default UI font treatment.

### Brand Essence

**Roseau Hotel & Spa is a discerning Gondar stay for guests who want their rooms, dining, and celebrations arranged with one composed hand.** Personality: **cultured, restorative, exacting**.

### Brand Voice

The voice is assured, hospitable, and precise. Headlines are atmospheric but not vague; calls to action signal a meaningful next step; microcopy reduces uncertainty.

> “Arrange a stay that keeps its own rhythm.”

> “Hold this selection and continue to your payment folio.”

### Wordmark & Logo

The brand mark is a **roseau reed-and-arch seal**: three vertical reed strokes rise inside a simplified arch, with an offset circular sun cut-out. It should appear as a bold, text-free symbol in Roseau green, paired in the UI with a bespoke, letter-spaced wordmark treatment using Cormorant Garamond.

### Signature Brand Color

**Roseau Green — #183F36.** A dark, botanical green used as the unmistakable brand anchor for navigation, selected states, and the confirmed reservation seal.

## Style Decisions

- **Logo rule:** The Roseau mark is always the reed-and-arch seal in Roseau Green `#183F36`; it is never replaced by an abstract filled square or generic icon.
- **Motif rule:** Each major reservation chapter carries a Highland Atelier cue: a brass folio rule, circular seal, outlined stage numeral, or Roseau arch frame.
- **Material rule:** Large neutral surfaces read as warm parchment or soft stone through restrained tactile depth and fine brass/green linework, rather than flat generic UI panels.
