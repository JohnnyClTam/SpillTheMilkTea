---
layout: misc
title: Contact
---

<div class="background" style="background-color:black;">
	<div class="table-row">
		<div class="table-cell split-height" style="background-color: #e6d2b5;">
			<div class="table-column mobile-margins">
			  	<div class="table-cell">
					<h1 style="font-size:2em;padding-left:5vw; padding-right:5vw;">Got a question or idea to share?<br>Contact us below!</h1>
					<p style="text-align:center; font-size:1em; padding-left:5vw; padding-right:5vw;">Interested in learning more about me, my work or how we can collaborate on an upcoming project? Feel free to reach out anytime, I would be more than happy to chat.</p>
					<form id="contactform" action="https://formspree.io/xlepkqbn" method="POST">
						<div class="table-row" style="padding-left:5vw; padding-right:5vw;">
						    <div class="table-cell">
						    	<input type="text" name="name" placeholder=" Name">
						    </div>
						   	<div class="table-cell">
						   		<input type="email" name="_replyto" placeholder=" Email">
						   	</div>
					   </div>
					   <div class="table-row" style="padding-left:5vw; padding-right:5vw;">
						    <div class="table-cell">
						    	<input type="hidden" name="_subject" value="Spill The Milk Tea Feedback" />
						    </div>
						</div>
						<div class="table-row" style="align-content:center;padding-left:5vw; padding-right:5vw;">
						    <div class="table-cell">
						    	<textarea name="message" placeholder=" Your feedback, pitch, suggestion or unanswered questions..."></textarea>
						    </div>
						    <input type="text" name="_gotcha" style="display:none" />
						</div>
						<div class="table-row" style="padding-left:5vw; padding-right:5vw;">
							<div class="table-cell mobile-margins">
						    	<input type="submit" value="Send" style="background-color:black; color: white; min-height:50px;">
							</div>
						</div>
					</form>
					<script>
					    var contactform =  document.getElementById('contactform');
					    contactform.setAttribute('action', '//formspree.io/' + 'your' + '@' + 'email' + '.' + 'com');
					</script>
			 	</div>
			 </div>
		</div>
		<div class="table-cell split-height">
		 	<img class="center" src="{{site.baseurl}}/assets/img/boba.jpg" style="min-width:100%; min-height:100%; object-fit: cover; margin-top:0; height: 100%; width: 100%;   object-position: 20% 50%;">
		</div>
	</div>
</div>