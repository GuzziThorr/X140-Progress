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

## 24 Nov 2026

**Milestones**
- Thrust vectoring: the swivelling nozzle is now its own complete sub-assembly in CAD, with one pitch servo and one yaw servo per jet. A sweep through every pitch and yaw combination found no clashes. It is a review copy, waiting on final sign-off.
- Aero covers: the streamlined cover around each nozzle now ends a little further forward, so the nozzle's rim stays clear of it even at full deflection. The aircraft got slightly lighter in the process.
- Website: a new project website with a design showcase page. The aircraft turns slowly on a studio turntable, rebuilt from the latest design and now showing the real nozzle shape.
- Flight software: the hover rig's jet-start sequence now waits in hover-hold mode with the throttle down, so the lift rotors stay at idle while the jets spool up. A fix also makes lowering the stick in hover actually bring the rig down. Both were checked in the simulator.
- In progress: a sim landing flown on the stick touched down gently and level, with the jets dropping back to idle on the ground (a sim result, not a real flight). The design tool also gained a controls panel that swings every surface and nozzle and checks for clashes.

**What's next**
- Run both jets together on the test bench through a hover-style profile.
- Fly the sim with the jets responding the way the real engines' throttle does.
- Sign off the vectoring nozzle and fit it into the main CAD assembly.

**Tweet hooks**
- "Four servos, two nozzles, every pitch and yaw combination swept in CAD: zero clashes."
- "The X140 has a home online: a new design showcase with the aircraft on a slow studio turntable."
- "Small trim, big clearance: we shortened the nozzle covers so the swivelling nozzles never touch them, and saved a little weight too."
- "Gentle touchdown in the sim: stick down, level landing, jets back to idle on the ground."
- "Rotors wait, jets warm up: the hover rig's start sequence keeps the lift rotors at idle until both jets are ready."

---

## 23 Nov 2026

**Milestones**
- Bench day: tidying the wiring and cleaning up the harness that connects the jets to the flight computer, with both jets set up on the test stand.
- The jet bench dashboard gained a control tab: timed engine runs, preflight checks, engine settings and load-cell calibration all from one screen.

**Tweet hooks**
- "Not every day is a breakthrough. Today was wiring: tidying the jet harness so the bench rig is as clean as the plan."
- "Two jets on the stand and a lot of wire to tame. Harness clean-up day on the X140."
- "Our jet bench now has a proper control panel: timed runs, preflight checks and a big red ESTOP."

**Media**
- Photo: Both jets on the bench stand during today's wiring tidy-up (https://raw.githubusercontent.com/GuzziThorr/X140-Progress/main/media/2026-11-23/both-jets-on-the-bench-stand-during-today-s-wiring.jpg)
- Screenshot: Jet bench dashboard, live view: both engines stopped and cold, ready for the next run (https://raw.githubusercontent.com/GuzziThorr/X140-Progress/main/media/2026-11-23/jet-bench-dashboard-live-view-both-engines-stopped.jpg)
- Screenshot: Jet bench dashboard, new control tab: timed runs, preflight checks and engine settings in one place (https://raw.githubusercontent.com/GuzziThorr/X140-Progress/main/media/2026-11-23/jet-bench-dashboard-new-control-tab-timed-runs-pre.jpg)
- Screenshot: Jet bench dashboard, control tab: load cell, engine log and a live activity feed (https://raw.githubusercontent.com/GuzziThorr/X140-Progress/main/media/2026-11-23/jet-bench-dashboard-control-tab-load-cell-engine-l.jpg)

---

## 22 Nov 2026

**Milestones**
- Simulation: the flight computer's own jet-handling routine now runs inside the full flight simulator. On arming it starts the left jet, then the right, talks to simulated engine controllers, and reports when both are ready. If an engine is put out in the sim, the routine picks up the flameout on its own. This is a sim result, not a real engine run.
- The new mode is switched off by default, so the existing sim flights run exactly as before until we turn it on.

**What's next**
- Fly a complete sim flight with the jet routine switched on, with takeoff waiting until both jets report ready.

**Tweet hooks**
- "The flight computer now starts its jets in the sim: left, then right, then a 'jets ready' call, all from the same routine the real hardware will run."
- "Flameout drill, simulated: put an engine out in the sim and the flight computer's jet routine notices by itself."
- "Same software, simulated engines: one more piece of the real flight computer now gets exercised before any fuel is burned."

---

## 19 Nov 2026

**Milestones**
- Simulation: a full flight in the sim using the new thrust schedule. The lift rotors spin up first, then the jets and nozzles take over, and once on the wing the nozzles hold still while the control surfaces do the steering. It finishes with an orderly return and landing. All of these are sim results, not real flights.
- Hover rig: the spine-frame hover rig design is complete in CAD, with the final vectoring nozzles, the fuel system and the wiring all mounted on the spine. Every check passed and every printed part fits on the printer bed.
- Balance: the aircraft's balance point now sits right on the line of jet thrust, with fuel tanks full or empty. We got there by moving the electronics lower in the airframe, not by asking the controller to compensate.
- Jet intake: a simple rectangular ramp intake under the belly, sized to feed both jets and the extra air the exhaust mixers draw in.
- Flight software: simulated engine controllers now let the flight computer's real jet-start routine be tested in the sim, and the flight computer firmware now builds from the same source the sim flies.
- Also in progress: the vectoring nozzle as its own sub-assembly in CAD, and a new project website.

**What's next**
- Tune the approach and landing in the sim, and keep looping the full flight until it's consistently stable.
- Finish the vectoring nozzle sub-assembly and drop it into the main CAD assembly.
- Move from the hover rig design toward printing and building it.

**Tweet hooks**
- "New flight plan in the sim: rotors lift first, jets take over, and once it's on the wing the nozzles hold still and the control surfaces fly it."
- "Balance it in the design, not in the software. The X140's centre of mass now sits right on its thrust line, full tank or empty."
- "The hover rig is designed: one carbon spine carrying the jets, nozzles, fuel and wiring. Every printed part fits on the printer bed."
- "Out with the triangle, in with the rectangle: a simple ramp intake sized to feed both jets and the air their mixers pull in."
- "Before the real jets run, the flight computer gets to start simulated ones. Same routine, no fuel burned."

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
