# BlindArtist

Party drawing game built with `Flutter`.

`BlindArtist` is a multiplayer drawing game where players draw without seeing the canvas in the usual way, then reveal the final result, score the round, and build a gallery of chaotic masterpieces. The project combines party-game mechanics with custom transitions, score flow, audio feedback, and gallery support.

## Gameplay Loop

1. Add players.
2. Start a round.
3. One player draws under limited visual feedback.
4. Reveal the drawing.
5. Assign points.
6. Continue until a winner is reached.

## Features

- local multiplayer flow
- drawing-based party gameplay
- reveal and scoring screens
- persistent round gallery during the session
- winner flow with animated overlays
- sound effects and visual transitions
- desktop and web-friendly Flutter setup

## Tech Stack

- Flutter
- Dart
- audioplayers
- image_gallery_saver_plus
- custom painting and animation-heavy UI

## Project Structure

```text
lib/
  app.dart
  screens/              gameplay flow and transitions
  services/             game state and round logic
  models/               player and gallery models
  widgets/              animated UI building blocks
assets/
  images/
  sounds/
  fonts/
```

## Getting Started

```bash
flutter pub get
flutter run
```

## Best Fit

- party game prototype
- local multiplayer experiment
- portfolio project with custom Flutter UI
- interactive concept for casual social gameplay

## Status

Playable game prototype with a full round loop, score progression, and presentation-focused UX.
