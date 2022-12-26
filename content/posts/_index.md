---
title: "$ ls blogs"

---


{{< rawhtml2 >}}

<style>

.resp-sharing-button__link{
	
	opacity: 0;	
	color: white;
}



.relative.w-100.w-30-l.mb4.bg-white{

	pointer-events: auto;
    transform: scale(1);
    opacity: 1;
    transition: all 80ms ease-in;
	display: flex;
    flex-direction: column;
	border-radius: 3%;

}
.relative.w-100.w-30-l.mb4.bg-white:hover{

  	transform: scale(1.05);
  	box-shadow: 0 0 10px rgba(0,0,0,0.5);
  	z-index: 10;
	    	
}


.relative.w-100.w-30-l.mb4.bg-white:hover .black{
	
	font-size: 1.2em;
	width: 100%;
	transform-origin: bottom ;
	transition: transform 0.25s ease-out;


}

.relative.w-100.w-30-l.mb4.bg-white:hover hr{
		
  	font-size: 1.4em;
  	-webkit-filter: drop-shadow(hsla(0, 0%, 0%, 0.10) 1px 2px 2px);
	width: 100%;
	transform-origin: bottom center;
	transform: scaleX(0.5);
	transition: transform 0.70s ease;
	align: center;
	height: 1.5px;
	bottom: 0;
	left: 0;
	background-color: black;
}

.relative.w-100.w-30-l.mb4.bg-white:hover hr{
		
	border: 1px inset black;
	position: relative;
}

  
.relative.w-100.w-30-l.mb4.bg-white:hover hr:after{
	
	 transform: scaleX(1);
     transform-origin: bottom left;

}


.relative.w-100.w-30-l.mb4.bg-white::before hr:after{
	
	transform-origin: right;
  transform: scaleX(0);
  transition: transform .3s ease-in-out;

}

	
.relative.w-100.w-30-l.mb4.bg-white:hover::before hr:after{

	transform-origin: left;
  transform: scaleX(1);

}

aside:hover > .relative.w-100.w-30-l.mb4.bg-white:not(:hover){

 filter: blur(2.5px);
  -webkit-filter: blur(2.5px);
  

}
	

.dim:focus, .dim:hover {
  opacity: 1;
}

.cards:hover > .card:not(:hover) {
}





</style>

{{< /rawhtml2 >}}
