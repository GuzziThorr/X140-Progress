# Darner Core X140: running progress log

The X140 is a jet-powered VTOL aircraft: two small turbojets with steerable nozzles plus folding electric lift rotors, so it can take off and land vertically and then fly fast on its wing. Alongside it we are building a hover test rig that flies the same flight computer and the same jets before the full aircraft does.

This file is updated once a day. Newest day first. Everything in it is safe to quote in public posts.

## For the posting bot
- Pick ONE story from the newest day for the daily post. Prefer a line under "Tweet hooks".
- If the newest day is quiet, pick something from "Story so far" that hasn't been posted yet.
- Don't repeat a hook that has already been posted (see "Hooks used").
- Don't invent numbers, dates or claims that aren't written here. Sim results are sim results, not flights.
- If a day has a **Media** list, attach that photo or video to the post about it (download the linked file). Media is optional: a text-only post is fine.

---

## 18 Nov 2026

**Milestones**
- Simulation: the aircraft flew its first full circuit on the wing, rotors folded away, with transitions from hover to wing flight and back. A sim bug that was making transitions fail was found and fixed.
- Thrust vectoring: the swivelling nozzle design settled on four servos, one for pitch and one for yaw on each jet, mounted well forward of the hot section with long pushrods.
- Aero covers: each nozzle now has its own streamlined elliptical cover with a flared exit.
- Preflight: a controls sweep moves every surface and nozzle one at a time, before the jets can start. It runs from a single button on the ground-station dashboard and is proven in the simulator.
- Ground station: the laptop dashboard ran against the real flight-control software for the first time and five faults were found and fixed.
- Structure: the full concept C airframe structure is being built stage by stage in CAD.
- Exhaust mixer: a lobed mixer that replaces the stock jet exhaust cone is going to a test print to check the fit.

**Design review: what we learned**
- We put the X140 airframe through an honest review, comparing our early sizing estimates against CFD and full simulated flights. They didn't agree, and the CFD and sim results came out well short of the early promises.
- Three lessons: the airframe can't cruise efficiently enough, the jets are sized for hovering rather than for cruise, and our different models never agreed with each other.
- The conclusion is to move on from this airframe, and to take the best of it with us: the CFD pipeline, the flight simulator setup, the jet bench testing, our library of purchased parts, and the 3D-printed build process.

**What's next**
- Get the hover rig hovering and moving steadily, then add the wings, then transition to wing flight and back.
- Finish the mixer fit check and the nozzle assembly in CAD.

**Tweet hooks**
- "First full circuit on the wing in the sim, rotors folded. Hover, transition, cruise, and back to hover."
- "Four servos, two jets, one job: point the thrust exactly where we need it."
- "Before the jets ever light, every surface and nozzle gets a full sweep. One button."
- "First run of our ground station against the real flight software: five bugs found, five fixed. That's what first runs are for."
- "Printing a lobed exhaust mixer to check the fit before we commit to the real thing."
- "We ran the numbers properly, and the airframe didn't make the cut. That's what reviews are for. Keeping the tools, the test data and the build process."
- "Early estimates are optimists. CFD and simulated flights are realists. Lesson learned on the X140."
- "X140 exploring air entrainment: a printed lobed mixer in place of the stock exhaust cone. Fit check first, then the thrust stand."

**Media**
- Photo: X140 exploring air entrainment into its design. The printed lobed mixer fitted to the jet, with the stock exhaust cone it replaces beside it. (https://raw.githubusercontent.com/GuzziThorr/X140-Progress/main/media/2026-11-18/x140-exploring-air-entrainment-into-its-design-pri.jpg)

---

## Story so far (9 to 17 Nov 2026)

**17 Nov: the flight computer learns to run the jets**
- The flight computer now starts both jets itself in stages, and detects a flameout from the engine telemetry.
- A laptop ground-station dashboard came together, talking to the aircraft over long-range telemetry radios, with live battery status for both flight packs and a link-loss stop.
- Engine-out handling was refined: the rig levels its rotors once down and shuts everything off when disarmed.
- Hook: "No RC transmitter yet. The X140 hover rig is flown from a laptop dashboard over a telemetry radio."

**16 Nov: the hover rig gets its backbone**
- After comparing a many-tube truss with a simple spine, we chose the spine: one carbon backbone, a printed hub, one arm per side, and legs down to a wide stance on gas-strut feet.
- Braces were redrawn by hand in CAD from the leg clamps to the tank clamp, and the motors moved onto printed cone stand-offs.
- The frame is sized for a 200 mm drop, using as few tubes as possible, none longer than 1 m.
- Engine-out rule: lose a jet and the hover rig lands where it is. The full aircraft flies home first, burns fuel if it's heavy, then lands.
- Hook: "We had a 41-tube truss. We chose a single spine. Fewer parts, less to break."

**15 Nov: one-jet survival in the sim**
- The simulator flew hover on a single jet, and landed on one jet in hot-day and low-fuel cases.
- The swinging bell nozzle design arrived: one piece, pivoting, with the mixing inside the nozzle.
- The first hover-rig frame was sized from hover and landing loads.
- Hook: "What happens if a jet quits in the hover? We keep breaking the sim until the answer is boring."

**14 Nov: concept C**
- Concept C became the design we're building: a tube-and-node skeleton with 3D-printed joints, stressed outer wing modules, and design rules fed back from the first CAD build.
- The vectoring nozzle mechanism was approved and weighed part by part.
- The sim held position in hover and hovered on one jet.
- Hook: "Concept C: carbon tubes, printed nodes, and every lesson from the first CAD build folded back into the design tool."

**13 Nov: first full CAD build and first sim hover**
- The pusher design was built in CAD for the first time, section by section: body and tank, wing and control surfaces, tail and nozzles, rotor pods, legs, nose and wiring harness.
- The aircraft hovered in the simulator on jet vectoring alone, passed all its step tests, and survived losing a servo power rail.
- Hook: "First CAD build of the whole aircraft, and first simulated hover on jet vectoring, on the same day."

**12 Nov: concepts A and B**
- Several layouts were explored: concept A (centre load), an angular variant, a pusher variant, and concept B, the best of a 10-concept search.
- Hidden nozzles, primary structure sizing (spars, frames, hardpoints), and a lobed exhaust mixer were worked through.
- Hook: "Ten concepts in, one design out. Here's how we're narrowing down the X140."

**10 to 11 Nov: the shape of the aircraft**
- A blended wing body with twin jets, nose fuel, battery pods and folding rotors took shape in our in-house design tool.
- Independent two-axis nozzle vectoring, jet intakes, folding blades, splayed landing legs and wing sections were all added and iterated live in the tool.
- Tractor and pusher variants were both kept and compared.
- Hook: "Day one of the X140 design: a blended wing body, two jets, and rotors that fold away for cruise."

**9 Nov: kickoff**
- The X140 project started on our existing aircraft design platform, carrying over the tools, the bench-test data and the lessons from our earlier aircraft.

---

## Hooks used
(The bot or the user adds hooks here once posted, so they aren't repeated.)
