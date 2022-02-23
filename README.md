# MaxHollyProject

@import url(https://fonts.googleapis.com/css?family=Lato);

body {background-color: white;
font-family: 'Lato', serif;
    font-size: 1.2rem;}

/*  nav bar code begin*/

header {position: -webkit-sticky;
	position: sticky;
	top: 0;
  margin-bottom: 0;}

ul {
  list-style-type: none;
  margin: 0;
  margin-bottom: 0;
  padding: 0;
  overflow: hidden;
  background-color: white;
}

li {
  float: right;
}

li a {
  display: block;
  color: grey;
  text-align: center;
  padding: 14px;
  text-decoration: none;
  font-size: 70%;
  padding-bottom: 10px;
  letter-spacing: 0.4rem;
}

li a:hover {
  background-color: orange;
  color: black;
}
/* nav bar end */

.parallax {
  background-image: url("https://images.unsplash.com/photo-1609620348316-a006a93e5e6f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8YmxhY2slMjBhbmQlMjB3aGl0ZSUyMGFuaW1hbHxlbnwwfHwwfHw%3D&w=1000&q=80");
  min-height: 400px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  margin-bottomm: 0;
  margin-top: -4%;
  
}


/* writing in banner */
.banner-content {
    color: orange;
    font-family: "Lato", serif;
    text-align: right;
    text-transform: uppercase;
    letter-spacing: 0.4rem;
}
.banner-content h1 {
    font-size: 200%;
    font-weight: bold;
}
.banner-content h3 {
    font-size: 3rem;
    color: white;
    font-weight: bold;
  padding-bottom: 8%;
  padding-top: 4%;
}
/* writing inside banner ends here */



/* where to edit for each page  */


figure img { border-radius: 50%;
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  width: 300px; 
  height: auto;}
  
h5 {text-align: center;
    color: orange;
    font-family: "Lato", serif;
    text-transform: uppercase;
    letter-spacing: 0.4rem;}

p {
    text-align: center;
  margin: 5%;
  margin-top: 1%;
  line-height: 2;
}


/* footerparallax */
.footer {
  background-image: url("https://c.pxhere.com/photos/5a/ca/Black_Cc0_Eating_High_Resolution_Mammal_Stock_Photo_White_Wild-1617263.jpg!d");
  min-height: 300px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

h4 {font-family: "Lato", serif;
    text-align: right;
    text-transform: uppercase;
    letter-spacing: 0.4rem;
    color: orange;
    padding-right: 10%;
    padding-top: 5%;}

.button {
  display: flex;
  justify-content: right;
  text-align: right;
  padding-right: 10%;
  margin-top: -5%;
}

.btn {
    background: white;
    padding: 15px 20px;
    color: black;
    text-transform: uppercase;
    margin-top: 7%;
    margin-right: 22px;  
}
 .btn:hover {
    background: #ffb424;
    color: #fff;
}


