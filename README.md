# Rinkside Air Hockey

A 1v1 air hockey game that runs in the browser. Play on one phone or tablet laid flat between you, or online with each player on their own device.

**Play it:** https://jnstacy98.github.io/Air-Hockey/

## Online play (two devices)

1. Both players open the game and tap **Online**.
2. One player taps **Host a game** and reads out the 4-letter code.
3. The other taps **Join a game**, types the code, and taps **Join**.
4. The host picks a score and taps **Face off**.

Each screen shows that player's own paddle at the bottom. The devices connect directly to each other over WebRTC, using the free [PeerJS](https://peerjs.com) service to find each other. A copy of the PeerJS library is included as `peerjs.min.js`.

## How to play

- **Touch:** drag the paddle on your end of the table.
- **Keyboard:** orange uses the arrow keys (or the mouse), blue uses W A S D.
- Choose first to 5, 7 or 10 goals. Each player's score is printed facing them.
- **vs Computer** mode lets one person play alone.
- Press the pause button in the corner, or P / Esc on a keyboard, to pause.

## Run it locally

There's no build step. Open `index.html` in any browser. Online play needs an internet connection.
