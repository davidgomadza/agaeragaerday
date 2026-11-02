# agaeragaerday
What is your day of death
Photo Oracle Mechanics & Visual Feedback
The page walks you through a two-step reading with clear on-screen cues.

Upload & prep: Drag and drop, paste, or click “Upload photo” to load an image. The canvas scales it to fit, and the two question buttons become active.

Scan paths: Clicking “What is their day of birth?” animates a glowing trail along the bottom-left → top-right → top-left route. The second question traces the top-right → bottom-left → bottom-right path. Keyboard shortcuts 1 and 2 trigger the same actions.

Voice & transcript: Each answer appears as a typed bubble and can be spoken aloud (toggle Voice). The transcript keeps a running log of both questions and their simulated dates.

Optional AGT8000 mode: Enabling the checkbox changes the death reading to a “death removed” message, extending the year by 7,777,777.

Optimization Tip: You can tweak the scan animation speed by changing duration = 2300 (milliseconds) inside runScan, or adjust the AGT year extension in deathText where 7777777 appears. The simulated birth years and lifespan ranges are defined in makeReadings if you want different ranges.
