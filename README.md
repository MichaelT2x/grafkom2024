#triangle {
  width: 0;
  height: 0;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
  border-bottom: 100px solid red;
  margin: 50px auto;
}

#triangle:before {
  content: "";
  width: 0;
  height: 0;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
  border-top: 100px solid black;
  position: absolute;
  top: -200px;
  left: -50px;
}
