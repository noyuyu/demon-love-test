# Demon Love Test

A first-person meta romance web game about a yandere demon, presented through a fake chat interface and mobile system UI.

## About

Demon Love Test is a first-person yandere demon romance told through a fake chat interface and familiar pieces of mobile system UI.

Through a personality test, private conversations, profile pages, system pop-ups, and final choices, you watch a demon made specifically for you come into existence—then move closer, become possessive, try to hold itself back, and slowly lose control.

The game leans toward an otome-inspired experience, mixing yandere romance, demons, meta-fiction, fourth-wall breaks, and interactions disguised as ordinary phone behavior.

## Recommended Experience

Play on a phone in portrait orientation for the intended experience.

Some fake system UI may look slightly different depending on the device and operating system, especially between iOS and Android.

## This Is Not a Simple Multiple-Choice Quiz

Do not limit yourself to the main choices at the bottom of the screen. Parts of the interface that look purely decorative may be interactive.

The game responds not only to deliberate choices, but also to waiting, touching, copying, leaving the page, returning, staying inactive, and other browser or device actions.

## Features

- A fake chat interface that gradually stops feeling entirely fake
- Fake mobile system UI and browser notifications
- Fourth-wall breaks and meta interactions
- Multiple formal endings, hidden endings, and easter eggs
- Interactive elements concealed inside apparently decorative UI
- Persistent second-playthrough dialogue changes based on previous endings
- Browser-based local game state
- Mobile-specific touch and device interactions
- Idle and inactivity-triggered events
- Page visibility and leaving-and-returning interactions
- A hidden clipboard-related interaction
- Long-press and touch interactions

## Hidden Interactions

The game rewards curiosity, hesitation, and doing things that a normal quiz would ignore. Without giving everything away:

- Try long-pressing on mobile.
- Try copying text and pasting it into places that look empty.
- Leave the page and come back.
- Stay inactive on certain screens.
- Some endings require waiting instead of immediately choosing.

## Endings

The game contains multiple formal endings, hidden scenes, hidden endings, and second-playthrough dialogue variations. What the demon says on a later run can change depending on which endings you have already triggered.

## Project Reach

Public release stats:

- 12,000+ views
- 712 likes
- 305 saves
- 85 comments

## Tech / Privacy

The project is a static front-end web game built with:

- HTML
- CSS
- Vanilla JavaScript

There is no backend or server-side account system. Game state is stored locally in the browser, primarily through `localStorage`.

The source does not include API keys, access tokens, passwords, or login credentials, and no server-side personal-data upload logic was found during review. The game does use browser-provided features for notifications, page visibility, device orientation and connection changes, clipboard events, and touch interactions as part of its meta mechanics.

Everything is contained in a single `index.html` file with no build step or external dependencies.

## Running Locally

Clone or download the repository, then open `index.html` in a modern browser.

For behavior closer to the deployed version, start a local static server from the project directory:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Live Demo

[Play Demon Love Test on Netlify](https://peaceful-gumption-764d67.netlify.app/?v=14)
