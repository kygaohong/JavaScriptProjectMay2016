This project is built with HTML, CSS, and full stack JavaScript (front-end framework Angular, Express, Node.js and MongoDB) to fufill the requirement of CodeLouisville training for Full Stack JavaScript. Media Queries were used to make this website responsive for different device sizes.  

Cities to test the app (We can use any city all over the world)
	Prudhoe bay, AL
	Louisville, KY
	Manaus, Brazil
	Punta Arenas, Chile
	Puerto Montt, Chile
	

History of this project
(1) jQuery plugin simpleweatherjs working locally
	estabolish a html/css/JS website using jquery plugin "simpleWeather"
		version 3.1.0, website: http://simpleweatherjs.com/
(2) fix font problem
	download all font files used in style.css and save them in the folder ../font/
	change the links in the css file to pointing to the new location of the font files
(3) add a form with a submit button to change the input city
	html, form: example from http://www.w3schools.com/html/html_forms.asp
	JS/jQuery.submit()example from https://api.jquery.com/submit/
(4) add cloth
	cloth image from website: https://www.thenorthface.com/
(5) switch to Angular and put on 3 pages structure
	remove cloth
	angular submition of a form, and Enables binding angular expressions to onsubmit events
		example from: https://docs.angularjs.org/api/ng/directive/ngSubmit
		'use strict' does not work for controller
(6) Show cloth with if selection based on highest temp 
		using JavaScript if ... else statement
(7) finish 3 page structure
(8) using Angular service 
	change ng-app in index.html index2.html "submitCity" to "weatherCloth", and move to body tag
	change controller name from ExampleController to mainCtrl
	test angular service using example at http://www.w3schools.com/angular/angular_services.asp
	using angular service to determine today/tomorrow based on current url
(9) fix the alignment problem at about.html
(10) add angular directives for about.html
(11) add node.js and express (static part)
(12) add mock data
(13) tried move scripts to app directory, but failed
(14) Added Change the cloth function 
(15) Setting Up MongoDB
(16) Fixed screen width problem
		
