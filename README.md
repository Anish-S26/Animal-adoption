@import url('https://fonts.googleapis.com/css?family=Underdog&display=swap');
@import url('https://fonts.googleapis.com/css?family=Varela+Round&display=swap');
@import url('https://fonts.googleapis.com/css?family=Big+Shoulders+Text:100,300,400,500,600,700,800,900&display=swap');

/*html, body {                            /*FORM STYLESHEET*/
	background-color: #000000;
	font-family: 'Ariel', sans-serif;
}*/

/* header styling */

header {
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	align-items: flex-start;
}

#title {
	color: #c2fcfb;
	font-size: 4.42em;
	padding: 10px 370px;
	  font-family: 'Big Shoulders Text', cursive;
    font-size: 1.8em;
    text-transform: uppercase;

}

/*#top-pic {
	display: block;
	margin-left: auto;
	justify-content: flex-end;
	min-width: 50%;
	max-width: 70%;

}*/

/* main styling */

#survey-form {
	display: flex;
	flex-direction: column;
	justify-content: stretch;
	opacity: 2.0;
	color: #d378fa;
	  font-family: 'Big Shoulders Text', cursive;
    font-size: 1.8em;
	margin: 0px 0px;
	border: 2px solid #e9c7fc;
	border-radius: 5px;
	background-color: #000000;
	box-shadow: 5px 5px 5px #e9c7fc;
}

#description {
	font-size: 1.1em;
	text-align: center;
}

form, #todays-date > select, input, textarea, #dropdown {
	padding: 5px;
	margin-left: 5px;
	font-size: 18px;
}

.main-label {
	display: flex;
	justify-content: stretch;
	font-size: 1.1em;
	font-weight: bold;
	padding: 5px;
}

form > div {

	padding: 3px;
	margin: 1px 5% 15px 5%;
}

ul {
	padding-left: 10px;
}

li{
	padding: 2px 2px 2px 5px;
	display: inline-block;
	list-style: none;
}

input {
	margin: 5px;
}

#email-phone > input, #first-last-name > input, #address > input {
	width: 90%;
}
#gender {
	display: flex;
	justify-content: stretch;
}

#housing {
	display: flex;
	flex-direction: column;
}

#housing > select {
	margin: 15px;
	width: 90%;
}

textarea {
	resize: none;
	width: 100%;
}

#button {
	display: flex;
	justify-content: center;
}

#submit {
	color: #120901;
	background: #d5b8e6;
	border: 2.5px solid #120901;
	border-radius: 15px;
	cursor: pointer;
	margin: 10px;
	font-size: 2.02em;
	font-weight: bold;
	padding: 22px;
}

#submit:hover {
	background: #5bbaac;
	-webkit-transition-duration: 0.4s;
	-moz-transition-duration: 0.4s;
	-o-transition-duration: 0.4s;
	transition-duration: 0.4s;
}
/* above footer styling 

#above-footer {
	display: flex;
	flex-direction: column;
	justify-content: center;
	padding: 50px;
}

#bottom-pic {
	display: block;
	margin-left: auto;
	max-width: 70%;
}*/

/* footer 

#coded-by {
	flex: 1;
	font-size: 1.3em;
	font-weight: bold;
	margin: 1em;
	padding: 5px;
	text-align: center;
}

a {
	color: #fd6907;
	text-decoration: none;
}

a:hover {
	text-decoration: underline;
	color: #ffa366;
	animation-duration: 0.5s;
}*/


