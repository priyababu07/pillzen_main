<template>
    <section class="team">
		<div class="center">
			<h1>Our Team</h1>
		</div>

		<div class="team-content">
			<div class="box1">
				
				<h3>Abhishek Biju</h3>
				</div>

			<div class="box2">
				<h3>Abel Abraham Philip</h3>
				
			</div>

			<div class="box3">
				
				<h3>Yathukrishnan T.U</h3>
				
			</div>

			<div class="box4">
				
				<h3>Neha Sara Biju</h3>
				
			</div>

            <div class="box5">
				
				<h3>Milna Therese Shally</h3>
				
			</div>
            <div class="box6">
				
				<h3>Anoop Kumar A</h3>
				
			</div>

		</div>
	</section>
  </template>
  
  <script>
  
  </script>
  
  <style>
  *{
	padding: 0;
	margin: 0;
	box-sizing: border-box;
	font-family: 'Space Grotesk', sans-serif;
	text-decoration: none;
}
.team{
	position: relative;
	width: 100%;
	height: 100vh;
	background-image: url("/assets/istockphoto-1214712621-612x612.jpg");
	display: flex;
	align-items: center;
	justify-content: center;
	flex-direction: column;
}
.team-content{
	width:80%;
	max-width: 1100px;
	margin: 0 auto;
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(150px, auto));
	align-items: center;
	gap: 4rem;
	text-align: center;
	margin-top: 4rem;
}
.team-content img{
	width: 40%;
	height:200px;
	border-radius: 15px;
	margin-bottom: 15px;
}
.center h1{
	color: #1c1b1b;
	font-size: 4rem;
	text-align: center;
}
.box1{
	padding: 16px;
  background-image:url("/assets/Group 240.png");
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 50%; /* Set border-radius to 50% for rounded card */
  transition: all .38s ease;
  width: 150px; /* Set the width and height of the card as needed */
  height: 160px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-right: 70px;
    
}
.box1 h3{
    margin-top: 230px;
	font-size: 15px;
	font-weight: 200;
	color: #181717;
	margin-bottom: 8px;
}
.box2{
	padding: 16px;
  background-image:url("/assets/Group 241.png");
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 50%; /* Set border-radius to 50% for rounded card */
  transition: all .38s ease;
  width: 150px; /* Set the width and height of the card as needed */
  height: 160px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-right: 70px;
    
}

.box2 h3{
    margin-top: 230px;
	font-size: 15px;
	font-weight: 200;
	color: #181717;
	margin-bottom: 8px;
}
.box3{
	padding: 16px;
  background-image:url("/assets/Group 245.png");
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 50%; /* Set border-radius to 50% for rounded card */
  transition: all .38s ease;
  width: 150px; /* Set the width and height of the card as needed */
  height: 160px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-right: 70px;
    
}

.box3 h3{
    margin-top: 230px;
	font-size: 15px;
	font-weight: 200;
	color: #181717;
	margin-bottom: 8px;
}
.box4{
	padding: 16px;
  background-image:url("/assets/Group 246.png");
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 50%; /* Set border-radius to 50% for rounded card */
  transition: all .38s ease;
  width: 150px; /* Set the width and height of the card as needed */
  height: 160px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-right: 70px;
    
}

.box4 h3{
    margin-top: 230px;
	font-size: 15px;
	font-weight: 200;
	color: #181717;
	margin-bottom: 8px;
}
.box5{
	padding: 16px;
  background-image:url("/assets/Group 247.png");
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 50%; /* Set border-radius to 50% for rounded card */
  transition: all .38s ease;
  width: 150px; /* Set the width and height of the card as needed */
  height: 160px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-right: 70px;
    
}

.box5 h3{
    margin-top: 230px;
	font-size: 15px;
	font-weight: 200;
	color: #181717;
	margin-bottom: 8px;
}
.box6{
	padding: 16px;
  background-image:url("/assets/Group 248.png");
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  border-radius: 50%; /* Set border-radius to 50% for rounded card */
  transition: all .38s ease;
  width: 150px; /* Set the width and height of the card as needed */
  height: 160px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  
    
}

.box6 h3{
    margin-top: 230px;
	font-size: 15px;
	font-weight: 200;
	color: #181717;
	margin-bottom: 8px;
}
.box h5{
	font-size: 15px;
	font-weight: 600;
	color: #b7b4bb;
	margin-bottom: 15px;
	letter-spacing: 2px;
}


.box1:hover{
	transform: translateY(-10px);
	cursor: pointer;
}
.box2:hover{
	transform: translateY(-10px);
	cursor: pointer;
}
.box3:hover{
	transform: translateY(-10px);
	cursor: pointer;
}
.box4:hover{
	transform: translateY(-10px);
	cursor: pointer;
}
.box5:hover{
	transform: translateY(-10px);
	cursor: pointer;
}

.box6:hover{
	transform: translateY(-10px);
	cursor: pointer;
}


@media(max-width: 1240px){
	.team{
		width: 100%;
		height: auto;
		padding: 90px 2%;
	}
	.center h1{
		font-size: 3.2rem;
	}
	.team-content{
	  justify-content: center;
	}
}
 
  </style>
  