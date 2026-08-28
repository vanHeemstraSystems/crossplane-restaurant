# Recording

Recording system audio (the sound from a Dia tab) with BlackHole works by routing that audio into a virtual device that a recorder can capture. Here’s the full setup.

1. Install BlackHole

- Download BlackHole 2ch (the free version) from Existential Audio’s site (existential.audio) or via Homebrew if you use it.

- Run the installer and restart if prompted.

2. Create a Multi-Output Device (so you can still hear the audio)

BlackHole alone captures sound but sends it away from your speakers, so you’d hear nothing while recording. A Multi-Output Device sends audio to both your speakers and BlackHole.

1. Open Audio MIDI Setup (in Applications → Utilities, or spotlight-search it).

2. Click the + button (bottom-left) → Create Multi-Output Device.

3. In the right panel, check both:

 - Your speakers/headphones (e.g. “MacBook Pro Speakers”)

 - BlackHole 2ch

4. Optional: right-click the new device → Use This Device For Sound Output, or rename it something clear.

3. Route your Mac’s output to BlackHole

- Go to System Settings → Sound → Output and select your Multi-Output Device (or just BlackHole if you don’t need to hear it).

- Now audio playing in Dia flows into BlackHole.

4. Record it

Pick whichever recorder you prefer and set its input to BlackHole 2ch:

Option A — QuickTime Player (free, built-in)

1. Open QuickTime → File → New Audio Recording.

2. Click the small ⌄ arrow next to the record button.

3. Choose BlackHole 2ch as the microphone.

4. Hit record, play the Dia tab, then stop and save.

Option B — ⌘⇧5 Screen Recording

- In the ⌘⇧5 bar, click Options and set the microphone to BlackHole 2ch. This captures the tab audio (note: it records BlackHole as the “mic,” so you won’t also get your own voice unless you set up an Aggregate Device — see below).

5. When you’re done

Switch System Settings → Sound → Output back to your normal speakers/headphones, or you may wonder why other apps seem silent.

Two common gotchas:

- You hear nothing while recording → you skipped the Multi-Output Device (step 2). BlackHole by itself is silent to your ears.

- Want your voice + tab audio together (e.g. narrating a call) → create an Aggregate Device combining your microphone and BlackHole, and use that as the recorder’s input.

Want me to walk through the Aggregate Device setup for capturing your mic and tab audio at the same time?
