# Mole Calculations Lab

Chemistry calculations practice for Year 11 students heading into Year 12: moles and molar mass, concentration, stoichiometry, limiting reactant and titration, then a mixed challenge.

Each section opens with a worked example that appears one step at a time, has one interactive, and then gives endless practice questions with fresh numbers at three levels: Core, Apply and Year 12 ready. Calculations take typed answers (accepted within 1%; very large or small numbers go in two boxes, the number and the power of ten); a recognisable slip, such as an upside-down division or a missed bracket, gets its own feedback. Concept questions are multiple choice, with an explanation for every option.

## Sections

| Section | Status | Interactive |
|---|---|---|
| 1 Moles and molar mass | done | Molar mass builder: click atoms in; each atom is a block as wide as its mass |
| 2 Concentration | done | Beaker lab: beaker A fixed, beaker B on sliders (moles, volume); dots are 0.01 mol, colour deepens with concentration; challenges |
| 3 Stoichiometry | done | Equation balancer: numbers in front on steppers, each molecule drawn as a cluster of atoms, a left/right count per element; reactions are listed in `RXNS`; once balanced, a panel sets the mole ratio against the masses of the same amounts |
| 4 Limiting reactant | done | Reaction mixer: four gas reactions drawn as molecules; set the amounts, predict which runs out, then see the products and the excess. Amounts move in steps of the number in front, so a reaction always happens. The sandwich rule appears only in the key ideas. |
| 5 Titration | done | Burette lab, starting with a guided run (a practice acid, a pink end-point mark on the burette, step-by-step coaching, the tap closing itself just before the mark and locked near it), then on your own: an unknown HCl against 0.100 mol L⁻¹ NaOH. Read the meniscus in a magnified view (checked to 0.05 mL), run the tap or add drops, watch pink flash and then stay, record trials, tick the concordant titres, average, and calculate; the real concentration is revealed at the end. |
| Challenge | done | The mole map (two hubs joined by the mole ratio); a route planner where students order the steps for ten problems before calculating; practice as Mixed (questions from every section), Multi-step (crossing sections) and Year 12 ready |

Once the atomic-mass strip scrolls off screen, an "Atomic masses" button in the corner opens a small floating copy.

Link straight to a section with its address: `index.html#moles`, `#concentration`, `#stoichiometry`, `#limiting`, `#titration`, `#challenge`.

## Privacy

Nothing is collected. The page makes no network requests at all: no analytics, no fonts or scripts from other sites, no cookies, no browser storage. A student's answers and score exist only while the page is open.

## Files

- `index.html`: the whole resource. Styles, then the page, then the script: data (atomic masses, compound names), helpers, the shared engine (stepper, practice, tally), then one block per section. Each practice question is a small generator function.
- `FONT-LICENSE.txt`: the licence for the embedded font, a subset of IBM Plex Sans (SIL Open Font License 1.1), renamed "Lab Sans" inside the page as the licence asks of modified copies.

Atomic masses are the one-decimal values used on the class worksheets.
