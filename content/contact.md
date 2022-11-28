---
title: "$ ln -s you me _"
date: 2022-11-22T20:47:40+05:30
draft: false
menu: contact 
#featured_image: '/who-am-i.jpg'
---

{{< rawhtml >}}

<style>
.form-control {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  border-radius: 10px;
  border: 2px solid grey;
}

.form-group {
  border-radius: 5px;
  padding: 20px;
}

button {
  background-color: white; /* Green */
  border: 3px solid black;
  color: black;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
	border-radius: 10px;
}

button:hover {
	
	background-color: black;
	color: white;
	transition: ease 5;
}

input:hover, textarea:hover {
	border: 2px solid black;
	
}

input:focus, #comment {
outline: none ;
}

.text-center{
text-align: center;
}

.form-border{
	
	padding: 30px;
	border: 2px solid grey;
	border-radius: 10px;
}

.social{
	margin: 20px;
	padding: 30px;
}

i{
padding: 30px;
}



svg:hover {
transform: scale(1.2);
}

hr{
	color: black;
}


</style>
<script src="https://kit.fontawesome.com/21e7e643ab.js" crossorigin="anonymous"></script>
<script>
function ClearFields() {

     document.getElementById("InputEmail").value = "";
     document.getElementById("comment").value = "";
}
</script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/emailjs-com@2.4.0/dist/email.min.js">
</script>
<script type="text/javascript">
  function send(){
    emailjs.init("ZTRDqv6HWKvOzvwAG"); //please encrypted user id for malicious attacks
  
  var templateParams = {
    to_name: 'sumitpatel24389@gmail.com',
    from_name: document.getElementById("InputEmail"),
    message_html: document.getElementById("comment")
  };

  emailjs.send('service_tunohqr', 'template_2smg9rm', templateParams, 'ZTRDqv6HWKvOzvwAG')
    .then(function(response) {
      console.log('SUCCESS!', response.status, response.text);
    }, function(error) {
      console.log('FAILED...', error);
    });
}
</script>


<div class="container">
<h1 align="center"> Connect with me on </h1>
<hr>
</div>
<div class="social" align="center">
	<a href="https://github.com/Dark-Kernel"><i class="icon-3x "><svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-4.466 19.59c-.405.078-.534-.171-.534-.384v-2.195c0-.747-.262-1.233-.55-1.481 1.782-.198 3.654-.875 3.654-3.947 0-.874-.312-1.588-.823-2.147.082-.202.356-1.016-.079-2.117 0 0-.671-.215-2.198.82-.64-.18-1.324-.267-2.004-.271-.68.003-1.364.091-2.003.269-1.528-1.035-2.2-.82-2.2-.82-.434 1.102-.16 1.915-.077 2.118-.512.56-.824 1.273-.824 2.147 0 3.064 1.867 3.751 3.645 3.954-.229.2-.436.552-.508 1.07-.457.204-1.614.557-2.328-.666 0 0-.423-.768-1.227-.825 0 0-.78-.01-.055.487 0 0 .525.246.889 1.17 0 0 .463 1.428 2.688.944v1.489c0 .211-.129.459-.528.385-3.18-1.057-5.472-4.056-5.472-7.59 0-4.419 3.582-8 8-8s8 3.581 8 8c0 3.533-2.289 6.531-5.466 7.59z"/></svg></i></a>


<a href="https://www.linkedin.com/in/sumit-patel-aa6264240/"><i><svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg></i></a>

<br>
<br>
<br>
<!--</div>
<h1 align="center">message me on</h1>
<div class="social" align="center">
-->
<a href="mailto:sumitpatel24389@gmail.com"><i><svg width="50" height="50" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" clip-rule="evenodd"><path d="M19 24h-14c-2.761 0-5-2.239-5-5v-14c0-2.761 2.239-5 5-5h14c2.762 0 5 2.239 5 5v14c0 2.761-2.238 5-5 5zm-.141-6.333c.63 0 1.141-.512 1.141-1.142v-9.05c0-.63-.511-1.142-1.141-1.142h-13.718c-.63 0-1.141.512-1.141 1.142v9.05c0 .63.511 1.142 1.141 1.142h13.718zm-6.859-4.058l-6.228-4.321-.014 7.712h12.457v-7.712l-6.215 4.321zm5.913-6.609c-1.745 1.215-5.913 4.153-5.913 4.153l-5.947-4.153h11.86z"/></svg></i></a>

<a href="https://t.me/sumit0patel"><i><svg width="50px" height="50px" viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xml:space="preserve" xmlns:serif="http://www.serif.com/" style="fill-rule:evenodd;clip-rule:evenodd;stroke-linejoin:round;stroke-miterlimit:1.41421;"><path id="telegram-3" d="M19,24l-14,0c-2.761,0 -5,-2.239 -5,-5l0,-14c0,-2.761 2.239,-5 5,-5l14,0c2.762,0 5,2.239 5,5l0,14c0,2.761 -2.238,5 -5,5Zm-2.744,-5.148c0.215,0.153 0.491,0.191 0.738,0.097c0.246,-0.093 0.428,-0.304 0.483,-0.56c0.579,-2.722 1.985,-9.614 2.512,-12.09c0.039,-0.187 -0.027,-0.381 -0.173,-0.506c-0.147,-0.124 -0.351,-0.16 -0.532,-0.093c-2.795,1.034 -11.404,4.264 -14.923,5.567c-0.223,0.082 -0.368,0.297 -0.361,0.533c0.008,0.235 0.167,0.44 0.395,0.509c1.578,0.471 3.65,1.128 3.65,1.128c0,0 0.967,2.924 1.472,4.41c0.063,0.187 0.21,0.334 0.402,0.384c0.193,0.05 0.397,-0.002 0.541,-0.138c0.811,-0.765 2.064,-1.948 2.064,-1.948c0,0 2.381,1.746 3.732,2.707Zm-7.34,-5.784l1.119,3.692l0.249,-2.338c0,0 4.324,-3.9 6.79,-6.124c0.072,-0.065 0.082,-0.174 0.022,-0.251c-0.06,-0.077 -0.169,-0.095 -0.251,-0.043c-2.857,1.825 -7.929,5.064 -7.929,5.064Z"/></svg></i></a>

</div>
&nbsp;
<br>
<br>
<form action="https://formsubmit.co/d37f54b1d10858705ecacfa503ff5646" id="contact-form" method="POST">
<!-- <form  action="send();" id="contact-form"> -->
<h1 align="center">Suggestions ?</h1>
<hr>
&nbsp;
<br>
<br>
<div>

</div>

  <div class="form-border">
	<div class="form-group">
    <input type="email" name="email" class="form-control" id="InputEmail" aria-describedby="emailHelp" placeholder="Enter email" />
  </div>
  <div class="form-group">
  <!--<label for="comment">Comment:</label> -->
  <textarea class="form-control" name="message" rows="5" id="comment" placeholder="Message..." ></textarea>
 </div>  
<div class="text-center"> 
 <button type="submit" class="btn btn-primary" onClick="ClearFields();" >Submit</button>
</div>
</div>
</form>


<!--
<form action={FORM_ENDPOINT} method="POST" target="_blank">

  <div class="mb-3 pt-0">

    <input type="text" placeholder="Your name" name="name" required />

  </div>

  <div class="mb-3 pt-0">

    <input type="email" placeholder="Email" name="email" required />

  </div>

  <div class="mb-3 pt-0">

    <textarea placeholder="Your message" name="message" required></textarea>

  </div>

  <div class="mb-3 pt-0">

    <button type="submit">Send a message</button>

  </div>

</form>
-->
{{< /rawhtml >}}
