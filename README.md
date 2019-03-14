<!DOCTYPE html>
<html>
	<head>
	
		<title>Home</title>
		
		<meta charset="UTF-8">
	
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
		
		<!--<link rel="stylesheet" type="text/css" href="CSS/Home.css">-->
		
		<style>
		body
			{ 
				background-image: url("../Images/Geometrie.jpg");
				background-repeat: repeat;
				background-position: center;
				background-attachment: fixed;
			}
			
		#TitluMare 
				  {
					font-size: 120%;
					width: 60%;
					color: #003366;
					background-color: white;
					letter-spacing: 3px; 
					font-family: Arial, Helvetica, sans-serif;
					text-decoration: underline;
				  }

		#wall 
			 {  
				border: 3px ;
				border-style: solid;
				border-color: #003366;
				margin-top: 3%;
				margin-bottom: 5%;
				margin-right: 7%;
				margin-left: 7%;
				background-color: white;
				padding:20px;
			 }
			 
		a {
			  color: #003366;
			  margin-left: 5%;
		  }

		.HomePage
				 { 
					padding:2px;
					text-align:justify;
				 }

				 
		.HomePage p 
				   {
						text-indent: 50px;
						color: #003366;
						font-family: Arial, Helvetica, sans-serif;
						font-size:120%;
				   }	

		.subliniat
				  {
					  text-decoration: underline;
				  }			  
				   
		@media screen and (max-width: 800px) 
		{	
			 #TitluMare 
					   {
							font-size: 60%;
							width: 65%;
							color: white;
							background-color: #003366;
							letter-spacing: 3px; 
							font-family: Comic Sans MS, Helvetica, sans-serif;
					   }
			
			   #wall
					{
						width: 360px;
						border: 3px ;
						border-style: solid;
						border-color: #003366;
						margin-top: 3%;
						margin-bottom: 20%;
						margin-right: 2%;
						margin-left: 8%;
						background-color: white;
						padding:20px;
					} 
					
		.HomePage p 
				   {
						text-indent: 50px;
						color: #003366;
						font-family: Arial, Helvetica, sans-serif;
						font-size:80%;
				   }	
			
		}
		</style>
		
	</head>
	<body>
		<center>
		   <div id="TitluMare">
				<h1> Metode de dezvoltare software </h1>
		   </div>
		</center>
			
		<div id ="wall">
			<div class="HomePage">	
				<center>
					<p class = "subliniat">
						<b>Grupele 351 & 352</b> 
					   </br>							 
					</p>
				</center>			
				<br>
				<h2 style="color: #003366; text-decoration: underline;">Sistemul de notare:</h2>
				<br>
				<p>Curs – 60 % (60 puncte) – prezenta si examen scris</p>
				<p>Laborator – 40% (40 puncte) dintre care:</p>
				<p>Activitate + prezenta - 1p</p>
				<p>Proiect – 3p</p>
				<p>Documentatie – 1p</p>

				<br>
				<h2 style="color: #003366; text-decoration: underline;">Cerinte proiect: </h2>
				<br>
				<p>(1p) Aplicație MVC - folosind Entity Framework (C#) / Hibernate (Java). 
				Trebuie să prezentați tema proiectului, specificațiile acestuia și detaliile de implementare.
				</p>
				<p>(1.5p) Servicii - fiecare membru al echipei trebuie să realizeze un serviciu care să funcționeze independent (folosind orice limbaj de programare). Acesta va rula local, dar și în Cloud. 
				Aplicația MVC trebuie modificată pentru a consuma aceste servicii realizate.
				</p>
				<p>(0.5p) Dificultatea proiectului. Se acordă cele 0.5p în funcție de dificultatea proiectului realizat.</p>

				<br>
				<h2 style="color: #003366; text-decoration: underline;">Deadlines:</h2>
				<br>
				<p>Săptămâna 5-6 - idei + specificații.</p>
				<p>Săptămâna 9-10 - MVC + prezentare.</p>
				<p>Săptămâna 11-12 - 1 serviciu funcțional - deploy Cloud.</p>
				<p>Săptămâna 13/14 - prezentare finală.</p>

				<br>
				<h2 style="color: #003366; text-decoration: underline;">Alte detalii despre proiect:</h2>
				<br>
				<p>Echipa de 5 persoane </p>
				<p>Deployment din VS in Cloud </p>
				<p>Nu trebuie sa fie aplicatie grea, important este sa se vada ca ati inteles</p>
				<p>Tool-uri de gestionare a task-urilor </p>
				<p>Tool-uri de versionare a codului </p>
				<p>La final documentatie </p>

				<br>
				<h2 style="color: #003366; text-decoration: underline;">Echipele pentru proiect:</h2>
				<br>
				<a  href="https://docs.google.com/spreadsheets/d/1bdjM7agH89pbQ2fQrM8uGnIXSv_mgoG5OhRntwJ3iqs/edit?usp=sharing">Link inscriere echipe</a>
				<br>
				<br>

				<h2 style="color: #003366; text-decoration: underline;">Laborator:</h2>
				<br>
				<a href="https://drive.google.com/file/d/1rNdDbqfToKVifmCQ0zmIstF5WbkBAhf9/view">Tutorial MVC 5 si Entity Framework 6</a>

				<br>
				<br>

				<p>Eroare la conexiunea cu baza de date in proiectul de MVC
				In Web config, trebuie modificat String-ul de conexiune: </p> 
				<p style="font-size: 100%">connectionString="Data Source=(LocalDb)\MSSQLLocalDB;Initial Catalog=ContosoUniversity1;Integrated Security=SSPI;"</p> 
				<p>Daca Controllerul a fost creat cu Students, trebuie modificata si ruta:</p> 
				<p>@Html.ActionLink("Students", "Index", "Students")</p>
			</div>
		</div>
	</body>
</html>
