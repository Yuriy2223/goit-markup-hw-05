# goit-markup-hw-05

.current {
  position: relative;
  color: #404bbf;
}

.current::after {
  transform: translate(0, -3px);
  left: 0;
  top: 100%;
  display: block;
  content: "";
  position: absolute;
  width: 100%;
  height: 4px;
  background: #404bbf;
  border-radius: 2px;
}