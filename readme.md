carinha feliz : .carinha {
  width: 100px; height: 100px;
  background: yellow; border-radius: 50%;
  position: relative; border: 2px solid black;
}
.olhos::before, .olhos::after {
  content: ''; position: absolute;
  width: 10px; height: 10px;
  background: black; border-radius: 50%;
  top: 30px;
}
.olhos::before { left: 25px; }
.olhos::after { right: 25px; }

.boca {
  width: 50px; height: 25px;
  border-bottom: 5px solid black;
  border-radius: 0 0 50px 50px;
  position: absolute; bottom: 15px; left: 25px;
}

