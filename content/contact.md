---
title: "Contact"
date: 2022-11-22T20:47:40+05:30
draft: false
menu: contact 
featured_image: 'who-am-i.jpg'
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
	border: 2px solid black
}

input:focus, #comment {
outline: none ;
}

.text-center{
text-align: center;
}

</style>

<form>
  <div class="form-group">
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
  </div>
  <div class="form-group">
  <!--<label for="comment">Comment:</label> -->
  <textarea class="form-control" rows="5" id="comment" placeholder="Comment..." ></textarea>
 </div>  
<div class="text-center"> 
 <button type="submit" class="btn btn-primary">Submit</button>
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
