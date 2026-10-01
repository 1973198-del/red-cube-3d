:root {
  --bg-top: #090f1b;
  --bg-bottom: #060911;
  --panel: rgba(11, 17, 29, 0.8);
  --panel-edge: rgba(123, 175, 255, 0.25);
  --wall: #293a54;
  --wall-deep: #171f2e;
  --track: #101a2d;
  --track-light: #1d2d44;
  --red-1: #ff3d3d;
  --red-2: #cb1d1d;
  --red-3: #ff8d8d;
  --accent: #74f3ff;
  --accent-soft: rgba(116, 243, 255, 0.34);
  --ink: #edf7ff;
  --shadow: rgba(0, 0, 0, 0.4);
}

* {
  box-sizing: border-box;
}

html, body {
  margin: 0;
  min-height: 100%;
  font-family: Arial, Helvetica, sans-serif;
  background: linear-gradient(180deg, var(--bg-top), var(--bg-bottom));
  color: var(--ink);
}

body {
  min-height: 100vh;
  display: grid;
  place-items: center;
}

input[type="radio"] {
  position: absolute;
  opacity: 0;
  pointer-events: none;
}

.page {
  position: relative;
  width: min(95vw, 980px);
  padding: 2rem 1.1rem 2.5rem;
}

.hud {
  text-align: center;
}

.tag {
  display: inline-block;
  margin: 0 0 0.8rem;
  padding: 0.45rem 0.8rem;
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.04);
  letter-spacing: 0.18rem;
  font-size: 0.7rem;
  text-transform: uppercase;
  opacity: 0.88;
}

.hud h1 {
  margin: 0;
  font-size: clamp(2.3rem, 6vw, 4.25rem);
  letter-spacing: 0.08rem;
  text-transform: uppercase;
}

.subtitle {
  margin: 0.55rem 0 0;
  letter-spacing: 0.18rem;
  font-size: 0.78rem;
  text-transform: uppercase;
  opacity: 0.75;
}

.controls {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 0.8rem;
  margin: 1.5rem auto 1rem;
}

.controls label {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 110px;
  padding: 0.75rem 1.1rem;
  border: 1px solid var(--panel-edge);
  border-radius: 14px;
  background: linear-gradient(180deg, rgba(22, 31, 49, 0.95), rgba(8, 12, 21, 0.9));
  box-shadow: inset 0 0 12px rgba(116, 243, 255, 0.06);
  font-size: 0.82rem;
  font-weight: 700;
  letter-spacing: 0.12rem;
  text-transform: uppercase;
  cursor: pointer;
  transition: transform 0.2s ease, border-color 0.2s ease, box-shadow 0.2s ease;
}

.controls label:hover {
  transform: translateY(-1px);
  border-color: rgba(116, 243, 255, 0.65);
  box-shadow: 0 0 18px rgba(116, 243, 255, 0.15);
}

.status {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 0.8rem;
  margin: 0 auto 1.2rem;
  padding: 0.75rem 1rem;
  width: min(100%, 520px);
  border: 1px solid rgba(116, 243, 255, 0.16);
  border-radius: 12px;
  background: rgba(10, 15, 23, 0.72);
  font-size: 0.82rem;
  text-transform: uppercase;
  letter-spacing: 0.14rem;
}

.label {
  opacity: 0.7;
}

.value::before {
  content: "Reach the exit gate";
}

.level-panel {
  display: flex;
  justify-content: center;
  align-items: center;
}

.maze {
  position: relative;
  width: min(92vw, 760px);
  height: 440px;
  background:
    linear-gradient(180deg, rgba(18, 26, 39, 0.94), rgba(7, 12, 19, 0.98)),
    repeating-linear-gradient(
      to right,
      rgba(255, 255, 255, 0.03),
      rgba(255, 255, 255, 0.03) 1px,
      transparent 1px,
      transparent 18px
    );
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 24px;
  overflow: hidden;
  box-shadow:
    inset 0 0 55px rgba(112, 155, 255, 0.1),
    0 26px 60px rgba(0, 0, 0, 0.38);
}

.maze::before {
  content: "";
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at 50% 10%, rgba(130, 164, 255, 0.17), transparent 30%);
}

.wall {
  position: absolute;
  background: linear-gradient(180deg, var(--wall), var(--wall-deep));
  border: 1px solid rgba(255, 255, 255, 0.06);
  box-shadow: inset 0 0 12px rgba(255, 255, 255, 0.05), 0 0 16px rgba(0, 0, 0, 0.25);
}

.wall-a {
  left: 110px;
  top: 55px;
  width: 160px;
  height: 18px;
}

.wall-b {
  left: 250px;
  top: 225px;
  width: 18px;
  height: 150px;
}

.wall-c {
  left: 340px;
  top: 55px;
  width: 18px;
  height: 160px;
}

.wall-d {
  left: 450px;
  top: 180px;
  width: 150px;
  height: 18px;
}

.wall-e {
  left: 550px;
  top: 80px;
  width: 18px;
  height: 210px;
}

.wall-f {
  left: 120px;
  top: 315px;
  width: 470px;
  height: 18px;
}

.exit-door {
  position: absolute;
  right: 42px;
  top: 110px;
  width: 34px;
  height: 120px;
  border: 2px solid rgba(116, 243, 255, 0.7);
  border-radius: 12px;
  background: linear-gradient(180deg, rgba(116, 243, 255, 0.2), rgba(116, 243, 255, 0.05));
  box-shadow: 0 0 22px rgba(116, 243, 255, 0.55);
  animation: pulse 1.2s ease-in-out infinite alternate;
}

.exit-door::before {
  content: "EXIT";
  position: absolute;
  left: 50%;
  bottom: -28px;
  transform: translateX(-50%);
  font-size: 0.7rem;
  letter-spacing: 0.17rem;
  text-transform: uppercase;
}

.player {
  --x: -170px;
  --y: 120px;
  --angle: 0deg;
  --arrow-rot: 0deg;
  position: absolute;
  left: 50%;
  top: 50%;
  width: 90px;
  height: 90px;
  transform: translate(calc(-50% + var(--x)), calc(-50% + var(--y))) rotateY(var(--angle));
  transform-style: preserve-3d;
  transition: transform 0.45s ease;
}

.player::before {
  content: "";
  position: absolute;
  left: 50%;
  top: -18px;
  width: 16px;
  height: 16px;
  background: linear-gradient(180deg, #fff, #9ceaf4);
  clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
  transform: translateX(-50%) rotate(var(--arrow-rot));
  filter: drop-shadow(0 0 10px rgba(116, 243, 255, 0.7));
}

.cube {
  position: relative;
  width: 80px;
  height: 80px;
  transform-style: preserve-3d;
  animation: spin 2s linear infinite;
}

.face {
  position: absolute;
  inset: 0;
  border: 2px solid rgba(255, 255, 255, 0.15);
  background: linear-gradient(135deg, var(--red-3), var(--red-1) 42%, var(--red-2));
  box-shadow:
    inset -10px -10px 14px rgba(94, 0, 0, 0.35),
    inset 10px 10px 14px rgba(255, 210, 210, 0.26),
    0 0 18px rgba(255, 72, 72, 0.34);
}

.front { transform: translateZ(40px); }
.back { transform: rotateY(180deg) translateZ(40px); }
.left { transform: rotateY(-90deg) translateZ(40px); }
.right { transform: rotateY(90deg) translateZ(40px); }
.top { transform: rotateX(90deg) translateZ(40px); }
.bottom { transform: rotateX(-90deg) translateZ(40px); }

#move-left:checked ~ .page .player {
  --x: -180px;
  --y: 120px;
  --angle: -90deg;
  --arrow-rot: -90deg;
}

#move-right:checked ~ .page .player {
  --x: 170px;
  --y: 52px;
  --angle: 90deg;
  --arrow-rot: 90deg;
}

#move-forward:checked ~ .page .player {
  --x: 50px;
  --y: -80px;
  --angle: 0deg;
  --arrow-rot: 0deg;
}

#move-backward:checked ~ .page .player {
  --x: -40px;
  --y: 170px;
  --angle: 180deg;
  --arrow-rot: 180deg;
}

#move-escape:checked ~ .page .player {
  --x: 230px;
  --y: -25px;
  --angle: 0deg;
  --arrow-rot: 0deg;
}

#move-left:checked ~ .page .value::before {
  content: "Turn left through the wall gap";
}

#move-right:checked ~ .page .value::before {
  content: "Move right and find the lane";
}

#move-forward:checked ~ .page .value::before {
  content: "Advance deeper into the corridor";
}

#move-backward:checked ~ .page .value::before {
  content: "Backtrack and re-evaluate";
}

#move-escape:checked ~ .page .value::before {
  content: "The cube escapes the maze";
}

#move-escape:checked ~ .page .exit-door {
  box-shadow: 0 0 30px rgba(116, 243, 255, 0.9), 0 0 52px rgba(116, 243, 255, 0.5);
  border-color: rgba(214, 251, 255, 0.95);
}

.credit {
  position: absolute;
  right: 18px;
  bottom: 12px;
  font-size: 0.72rem;
  letter-spacing: 0.16rem;
  text-transform: uppercase;
  opacity: 0.8;
}

@keyframes spin {
  0% { transform: rotateX(-18deg) rotateY(0deg) rotateZ(0deg); }
  25% { transform: rotateX(-18deg) rotateY(90deg) rotateZ(10deg); }
  50% { transform: rotateX(-18deg) rotateY(180deg) rotateZ(0deg); }
  75% { transform: rotateX(-18deg) rotateY(270deg) rotateZ(-10deg); }
  100% { transform: rotateX(-18deg) rotateY(360deg) rotateZ(0deg); }
}

@keyframes pulse {
  0% {
    transform: scale(0.96);
    box-shadow: 0 0 18px rgba(116, 243, 255, 0.4);
  }
  100% {
    transform: scale(1.08);
    box-shadow: 0 0 32px rgba(116, 243, 255, 0.82);
  }
}

@media (max-width: 640px) {
  .controls {
    gap: 0.5rem;
  }

  .controls label {
    min-width: 90px;
    padding: 0.65rem 0.75rem;
    letter-spacing: 0.08rem;
  }

  .status {
    gap: 0.45rem;
    padding: 0.7rem 0.8rem;
    font-size: 0.68rem;
    letter-spacing: 0.08rem;
  }

  .maze {
    height: 360px;
  }

  .wall-a {
    left: 65px;
    width: 130px;
  }

  .wall-b {
    left: 165px;
    height: 100px;
  }

  .wall-c {
    left: 255px;
    height: 110px;
  }

  .wall-d {
    left: 330px;
    width: 110px;
  }

  .wall-e {
    left: 430px;
    height: 160px;
  }

  .wall-f {
    left: 60px;
    width: 360px;
  }

  .exit-door {
    right: 20px;
    width: 24px;
    height: 90px;
  }

  .credit {
    right: 10px;
    bottom: 10px;
    font-size: 0.62rem;
    letter-spacing: 0.1rem;
  }
}
