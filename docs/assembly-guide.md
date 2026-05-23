# APD Assembly Guide — C1 Embodiment (Extension Spring)

This guide covers building the APD using Embodiment C1 (extension spring / elastomeric cord),
the simplest and most accessible build. Read the full specification in `docs/APD_Specification_v1.0.pdf`
before starting. All dimensions in millimetres unless stated.

---

## Tools Required

- Angle grinder or hacksaw
- Drill with M6, M8, M10 bits
- Welding equipment (or access to a local welder for 2–3 joints)
- Spanners and Allen keys (M6, M8, M10)
- Measuring tape and square
- Sandpaper and primer for steel finishing

---

## Phase 1: Base Frame Chassis (Subsystem A)

### 1.1 Frame Fabrication

Take your specification drawings (Fig. 9) to a local metal fabrication shop.
Give them the following dimensions:

- Outer frame: 2120 mm (L) × 600 mm (W) × 85 mm (H)
- Material: 40 × 40 × 3 mm mild steel box section for the perimeter
- Internal cross-braces at 500 mm intervals along the length
- Two longitudinal slots along the top inner surface to accept the channel rails (17)
- Ask the fabricator to leave both long sides open (no top plate) so the sliding platform can travel
- Weld four M10 nut inserts at each corner of the underside for the levelling feet (23)
- Pre-drill 6 anchor pin holes (262) at 100 mm intervals along the centreline of the base, 
  starting 300 mm from the rear end

**Cost: approx. ₹3,000–5,000 depending on your city. Bring the Fig. 4 exploded drawing.**

### 1.2 Kneeling Pad Zone

The rear 460 mm of the frame top is the fixed kneeling zone.

- Cut EVA foam to 460 × 600 × 40 mm
- Cover with PU leatherette, staple or glue to a thin plywood backing
- Bolt the backing to the rear of the frame through countersunk holes

### 1.3 Levelling Feet

Thread M10 rubber-tipped levelling feet (23) into the corner inserts.
Adjust to level the device on your floor. The adjustable range gives 10–25 mm.

---

## Phase 2: Channel Rails and Sliding Platform (Subsystem B)

### 2.1 Channel Rails (17)

- Cut two aluminium U-channel sections to 1400 mm length
- The channel inner width must match your castor wheel outer diameter (40 mm typical)
- Bolt the channels to the inner top surface of the base frame, parallel,
  spaced to match the castor positions on the platform (approximately 450 mm apart centre-to-centre)
- Ensure the channels are perfectly parallel and level — use a long straight edge

### 2.2 Sliding Platform Deck (13)

- Cut 700 × 500 × 18 mm plywood or aluminium composite panel
- Mark castor positions: two pairs of two, 200 mm from each end, 450 mm apart
- Drill castor mounting holes and bolt six sealed ball-bearing castors (16) to the underside
- Castors must align with the channel rails — do a dry fit before fixing

### 2.3 Contact Surfaces

Attach to the top of the sliding platform:
- **Forearm pads (14):** Two 250 × 120 × 40 mm EVA foam blocks, centred on each side,
  approximately 200 mm from the rear edge of the platform
- **Hand contact pad (15):** One 260 × 600 × 40 mm EVA foam block at the forward end

Cover all pads with anti-slip PU leatherette. Secure with countersunk bolts through the platform.
All pads should be removable for cleaning — use Velcro backing as an alternative to fixed bolts.

### 2.4 Travel Stops

- **Rear stop (21):** A bolt or rubber block fixed to the rear inner wall of the base frame,
  positioned so the platform sits 5 mm clear of the kneeling pad when fully rearward
- **Front bumper (22):** A 50 × 50 × 30 mm natural rubber block bonded to the forward inner wall.
  The platform should contact this softly at full extension — adjust position after testing stroke length.

### 2.5 Test the Slide

Place the platform in the rails and slide it by hand. It should travel smoothly with minimal
side-play. If it wobbles laterally, shim the channel rails inward slightly. If it binds,
check that the rails are truly parallel.

---

## Phase 3: Kinetic Restoration Subsystem — C1 (Extension Spring)

### 3.1 Anchor Bracket on Platform (263)

Weld or bolt a steel eye-bolt bracket to the underside centreline of the sliding platform,
centred front-to-back. This is the moving anchor point for the spring.

### 3.2 Anchor Pin in Base Frame (262)

The base frame has 6 pre-drilled holes along the centreline (from Phase 1).
Insert an M10 eye-bolt through hole position 3 (middle) as your starting point.
This is your adjustable anchor — you will experiment with positions later.

### 3.3 Install the Springs

- Route two extension springs (or one heavy bungee cord) through the central channel
  between the platform underside and the floor of the base frame
- Hook one end to the platform bracket (263)
- Hook the other end to the anchor pin (262) in the base frame
- The spring should be under moderate tension when the platform is in the rearward (home) position

**Calibration:** Sit or kneel on the device and slide forward. The spring resistance should
be noticeable but not requiring excessive effort. On release, the platform should return
about 60–70% of the way back under spring power alone. You provide the rest.
Move the anchor pin forward (toward the front of the device) for more assist.
Move it rearward (toward the kneeling pad) for less.

Target return force: approximately 25–40% of your upper body mass.
For a 70 kg person (upper body ~35 kg), aim for 9–14 kg of pull at mid-stroke.

---

## Phase 4: Support Rail Assembly (Subsystem D)

### 4.1 Rail Posts (11)

- Cut two aluminium 6061-T6 round tube sections (25 mm OD, 2 mm wall) to 750 mm length
- Drill pairs of M8 holes at 50 mm intervals along the lower 200 mm of each tube —
  these are the height adjustment holes for the pin-locking matrix (32)

### 4.2 Base Brackets (30)

- Fabricate or purchase two L-bracket assemblies that accept 25 mm tube
- Bolt to the rearward corners of the base frame
- Ensure rails are vertical and parallel when installed

### 4.3 Crossbar (31)

- Cut one 600 mm length of 25 mm aluminium tube
- Weld or use compression clamps to join the tops of the two rails
- The crossbar should sit level at the top of the rails

### 4.4 Rail Grips (19)

- Slide standard bicycle handlebar grips (25 mm ID, thermoplastic rubber) onto the rail tubes
- Position at the height where you would naturally grip when kneeling
- Secure with grip glue or end plugs

### 4.5 Height Adjustment

Insert M8 bolts or spring pins through the holes in the base bracket that correspond
to your preferred rail height. Typical starting position: 650 mm grip height.

---

## Phase 5: Optional Electronic Counter (Subsystem E)

### 5.1 Components

- Arduino Nano
- FSR 402 force-sensitive resistor (circular, 55 mm)
- 4-digit 7-segment LED display module
- 3.7V 2000 mAh Li-Po battery with USB charging module
- ABS project box (approximately 80 × 50 × 30 mm)

### 5.2 FSR Installation

- Cut a 60 mm circular hole in the kneeling pad plywood backing
- Insert the FSR face-up, with the sensing area pointing upward into the foam
- Route the cable through the base frame to the electronics enclosure

### 5.3 Firmware Logic (FSM)

Upload the following logic to the Arduino Nano:

```
State 0 (baseline): pad pressure HIGH (> P_high threshold)
  → if pressure drops below P_low: go to State 1

State 1 (extended): pad pressure LOW (< P_low)
  → if pressure recovers above P_high: go to State 2

State 2 (returned): validate complete cycle
  → increment count, display on LED, return to State 0

Any non-sequential pressure event: discard, stay in current state
```

Calibrate P_low and P_high thresholds with your body weight on the pad.
Typical P_high: 70% of your body weight reading. P_low: 10% (nearly unloaded).

### 5.4 Enclosure Mounting

Mount the project box on the rear support rail (11) at eye level when kneeling.
Route a small hole for the FSR cable. The display should be clearly readable
from the kneeling position without requiring head movement.

---

## Phase 6: Finish and Safety Check

### 6.1 Steel Finishing

- Sand all steel edges with 120 grit — no sharp edges anywhere
- Prime with rust-inhibiting primer
- Finish with matte black spray paint or send the frame for powder coating

### 6.2 Safety Checklist

Before first use, verify:

- [ ] All bolts are tight (Loctite threadlocker on structural bolts)
- [ ] Spring is fully captured at both ends — cannot slip off under load
- [ ] Front bumper stops the platform before it exits the rails
- [ ] Rear stop prevents platform from contacting the kneeling pad
- [ ] Rails do not rock or flex under full body weight
- [ ] Levelling feet are firm on the floor — device does not slide during use
- [ ] All foam pad edges are finished — no exposed staples or sharp corners

### 6.3 First Use

Start with 10 slow practice prostrations, checking for:
- Any unusual noise (binding, scraping)
- Lateral movement of the platform
- Spring return force — adjust anchor pin as needed
- Rail height comfort — adjust if gripping feels awkward

Gradually increase to full practice pace over several sessions.

---

## Variations and Improvements

**Upgrading from C1 to C2 (gas struts):**
Replace the extension springs and anchor pin with two gas compression struts
mounted at 20–30 degrees from horizontal inside the base frame.
The oblong mounting pivot matrix (266) allows angle adjustment.
See Fig. 5 in the specification for positioning detail.

**Adding a prostration board surface:**
Traditional Tibetan practice uses a smooth wooden board.
You can add a 3 mm hardboard sheet over the main deck surface (13)
with a very light wax or silicone finish for the most traditional sliding feel.

**Folding mechanism:**
A piano hinge along the 1060 mm midpoint of the base frame allows the device
to fold in half for storage. Requires a locking catch to prevent unintended folding during use.

---

## Sharing Your Build

If you build an APD, please:
1. Open an Issue on the GitHub repository with photos
2. Note any modifications you made and why
3. Share your BOM with local sourcing details for your country or region

Every build report helps the next person. The design improves through community use.

---

*CERN OHL-S v2 — Free to build, modify, and share. Modified versions must be released under the same licence.*
