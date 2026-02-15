body {
  margin: 0;
  padding: 0;
  background: linear-gradient(to bottom, #ff758c, #ff7eb3);
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: Arial, sans-serif;
  text-align: center;
  overflow: hidden;
  color: white;
}

.container {
  position: relative;
}

button {
  padding: 15px 30px;
  font-size: 18px;
  border: none;
  border-radius: 30px;
  background: #ff2e63;
  color: white;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  transform: scale(1.1);
  background: #ff004f;
}

.hidden {
  display: none;
}

/* Flower */
.flower {
  position: relative;
  width: 200px;
  height: 200px;
  margin: 30px auto;
}

.petal {
  width: 100px;
  height: 100px;
  background: #ff2e63;
  border-radius: 50%;
  position: absolute;
  top: 50px;
  left: 50px;
  transform: scale(0);
  transition: transform 0.8s ease;
}

.p1 { transform: rotate(0deg) translateY(-60px) scale(0); }
.p2 { transform: rotate(90deg) translateY(-60px) scale(0); }
.p3 { transform: rotate(180deg) translateY(-60px) scale(0); }
.p4 { transform: rotate(270deg) translateY(-60px) scale(0); }

.center {
  width: 70px;
  height: 70px;
  background: yellow;
  border-radius: 50%;
  position: absolute;
  top: 65px;
  left: 65px;
  transform: scale(0);
  transition: transform 0.8s ease 0.5s;
}

.stem {
  width: 12px;
  height: 120px;
  background: green;
  position: absolute;
  top: 140px;
  left: 94px;
  transform: scaleY(0);
  transform-origin: top;
  transition: transform 0.8s ease 0.3s;
}

.message {
  opacity: 0;
  transition: opacity 1s ease 1s;
}

/* Active state */
.show .petal {
  transform: scale(1);
}

.show .center {
  transform: scale(1);
}

.show .stem {
  transform: scaleY(1);
}

.show .message {
  opacity: 1;
}
