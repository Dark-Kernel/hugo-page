---
title: "Home"
menu: home
featured_image: '2-linux-og3.jpg'
---


{{< rawhtml3 >}}


<style>

body{
  background: #FBD4C5;
}

.container{
  width: 100%;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
  margin-top: 100px;
}

.container h1:nth-child(1) {
  color: #355c7d;
  font-family: 'Fira Code', monospace;
  font-weight: 800;
  font-size: 20px;
  margin: 0 0 0 35%;
  text-align: left;
  white-space: nowrap;
  overflow: hidden;
  width: 170px;
  animation: type 1.5s steps(30,end) forwards;
}

.container h1:nth-child(2) {
  opacity: 0;
  font-family: "Work Sans", sans-serif;
  margin: 0 auto auto auto;
  /*background: linear-gradient(to right, #f8b195, #f67280, #c06c84);*/
  background: linear-gradient(to right, #000000, #434343 );/
  font-weight: 800;
  font-size: 100px;  
  width: 430px;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  overflow: hidden;
  animation: shring-animation 2.1s steps(30,end) 1.5s forwards, blink .5s step-end infinite alternate;
}

@keyframes shring-animation {
  0% {
    background-position: 0 0;
    opacity: 0;
    width: 0;
  }
  1% {
    background-position: 0 0;
    opacity: 1;
    border-right: 1px solid orange;
  }
  50% {
    background-position: 150px 0;
    opacity: 1;
    border-right: 1px solid orange;
  }
  100% {
    background-position: 400px 0;
    opacity: 1;
    border-right: 1px solid orange;
  }
}

@keyframes type {
  0% {
    width: 0;
  }
  1%, 99%{
    border-right: 1px solid orange;
  }
  100%{
    border-right: none;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}


</style>

<body>

<div class = "container">
  <h1>Hi, I'm</h1>
  <h1>Sumit.</h1>
</div>

</body>

{{< /rawhtml3 >}}
