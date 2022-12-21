---
title: "Home"
menu: home
featured_image: '/linux-7.png'
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


 @media screen and (min-width: 60em)
.pv6-l {
  padding-top: 0rem;
  padding-bottom: 0rem;
}
.pv4 {
  padding-top: 0rem;
  padding-bottom: 2rem;
}

/*.pv4{

	padding-top: 0rem;
}
.pv6-l{

	padding-bottom: 8rem;

}*/

.container h1:nth-child(1) {
  color: #355c7d;
  font-family: 'Fira Code', monospace;
  font-weight: 800;
  font-size: 20px;
  margin: 0 0 0 0;
  text-align: center;
  white-space: nowrap;
  overflow: hidden;
  width: 350px;
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
  width: 329px;
  text-align: center;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  overflow: hidden;
	overflow-x: hidden;
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
    border-right: 2px solid orange;
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


.resume{
	
	font-size: 2rem;
	color: #355c7d;
}

.resb{
	
	padding: 7px;
	background-color: white;
 	font-size: 1.2rem;
	border: 2px solid black;	
	border-radius: 4px;
}

.resb:hover{
	
	color: white;
	background-color: black;

}

.resl {
  background-image: linear-gradient(
    to right,
    #355c7d,
    #355c7d 50%,
    #000 50%
  );
  background-size: 200% 100%;
  background-position: -100%;
  display: inline-block;
  padding: 5px 0;
  position: relative;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  transition: all 0.3s ease-in-out;
}

.resl:before{
  content: '';
  background: #355c7d;
  display: block;
  position: absolute;
  bottom: -3px;
  left: 0;
  width: 0;
  height: 3px;
  transition: all 0.3s ease-in-out;
}

.resl:hover {
 background-position: 0;
}

.resl:hover::before{
  width: 100%;
}



</style>

<body>

<div class = "container">
  <h1>Hi, I'm</h1>
  <h1>Sumit</h1>
</div>
<br><br>
<div class="resume" >
	<a class="resl" href="/sumit-p.pdf" target="_blank" >
	Resume
	</a>
</div>
</body>

{{< /rawhtml3 >}}
