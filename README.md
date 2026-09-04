# VoidCrew

Browser social-deduction game prototype built with vanilla HTML/CSS/JS and WebRTC DataChannels.

## Features
- Static frontend
- WebRTC host/join prototype
- Manual Offer/Answer signaling
- Lobby and player roster
- WASD / arrow movement
- Tasks and progress
- Emergency meeting UI
- Responsive sci-fi interface

## Run
Deploy the repository as a static site on Vercel or GitHub Pages.

## Multiplayer
1. Host chooses Create Host and Start Host.
2. Host sends the Offer Code to the joining player.
3. Joining player pastes the offer and creates an Answer.
4. Joining player sends the Answer Code back.
5. Host pastes the Answer and connects.
6. Launch the mission.

For production, replace manual signaling with a small signaling service and add TURN fallback, reconnection, authoritative state validation, and stronger synchronization.
