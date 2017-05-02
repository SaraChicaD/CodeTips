top: 50%;
left: 50%;
transform: translate(-50%, -50%);
***
left: 50%;
transform: translateX(-50%);
***
margin: auto; 
margin: 0 auto;
***
container {
  text-align: center;
}
item {
  display: inline-block;
}
***
item (400px wide) {
  position: absolute;
  left: 50%;
  top: 50%;
  margin-left: -200px;
  margin-top: -200px;
}
****
container {
  position: relative
}
item {
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
}
