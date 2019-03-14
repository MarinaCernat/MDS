<center><h1>Metode de dezvoltare software</h1></center>
<br>
<h2>Sistemul de notare:</h2>
<p>Curs – 60 % (60 puncte) – prezenta si examen scris</p>
<p>Laborator – 40% (40 puncte) dintre care:</p>
<p>Activitate + prezenta - 1p</p>
<p>Proiect – 3p</p>
<p>Documentatie – 1p</p>
<br>

<h2>Cerinte proiect: </h2>
<p>(1p) Aplicație MVC - folosind Entity Framework (C#) / Hibernate (Java). 
Trebuie să prezentați tema proiectului, specificațiile acestuia și detaliile de implementare.
</p>
<p>(1.5p) Servicii - fiecare membru al echipei trebuie să realizeze un serviciu care să funcționeze independent (folosind orice limbaj de programare). Acesta va rula local, dar și în Cloud. 
Aplicația MVC trebuie modificată pentru a consuma aceste servicii realizate.
</p>
<p>(0.5p) Dificultatea proiectului. Se acordă cele 0.5p în funcție de dificultatea proiectului realizat.</p>
<br>

<h2>Deadlines:</h2>
<p>Săptămâna 5-6 - idei + specificații.</p>
<p>Săptămâna 9-10 - MVC + prezentare.</p>
<p>Săptămâna 11-12 - 1 serviciu funcțional - deploy Cloud.</p>
<p>Săptămâna 13/14 - prezentare finală.</p>
<br>

<h2>Alte detalii despre proiect:</h2>
<p>Echipa de 5 persoane </p>
<p>Deployment din VS in Cloud </p>
<p>Nu trebuie sa fie aplicatie grea, important este sa se vada ca ati inteles</p>
<p>Tool-uri de gestionare a task-urilor </p>
<p>Tool-uri de versionare a codului </p>
<p>La final documentatie </p>
<br>
			
<h2>Echipele pentru proiect:</h2>
<a  href="https://docs.google.com/spreadsheets/d/1bdjM7agH89pbQ2fQrM8uGnIXSv_mgoG5OhRntwJ3iqs/edit?usp=sharing">Link inscriere echipe</a>
<br>				

<h2>Laborator:</h2>
<a href="https://drive.google.com/file/d/1rNdDbqfToKVifmCQ0zmIstF5WbkBAhf9/view">Tutorial MVC 5 si Entity Framework 6</a>
<br>

<p>Eroare la conexiunea cu baza de date in proiectul de MVC:</p>
<br>
<p>In Web config, trebuie modificat String-ul de conexiune: </p> 
<p style="font-size: 100%">connectionString="Data Source=(LocalDb)\MSSQLLocalDB;Initial Catalog=ContosoUniversity1;Integrated Security=SSPI;"</p> 
<p>Daca Controllerul a fost creat cu Students, trebuie modificata si ruta:</p> 
<p>@Html.ActionLink("Students", "Index", "Students")</p>
