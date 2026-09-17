# The Reading Ladder

A tablet-first phonics tutor prototype for children ages 3-5, based on the product design blueprint.

## What is in this first build

- A closed, audio-led daily lesson: arrive, retrieve, model, practice, read, leave
- Touch-first phonics interactions for `/m/`, `/a/`, `/t/`, CVC blending, and connected text
- Calm, deterministic feedback with modeled recovery instead of penalties
- Age 3 / Age 5 session modes
- Local progress and a compact grown-up dashboard
- A required offline mission and a first physical-book bridge
- No feed, streak, points, autoplay, ads, or child-facing commerce

This build deliberately covers the **content kernel**, **tutor MVP**, a thin slice of **adaptation**, and the first **book bridge**. It does not add the proposed delight layer because the blueprint says to prove learning and healthy stopping first.

## Run locally

No build step or dependencies are required.

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080. Speech uses the browser's built-in Web Speech API. Progress is saved only in browser `localStorage`.

## Product notes

This is a product prototype, not a validated literacy intervention. Grapheme order and instructional language should be reviewed with a reading scientist and speech-language expert before testing with children.
