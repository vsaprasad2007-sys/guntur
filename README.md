<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Guntur City Information Portal</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#f5f5f5;
}
header{
    background:#00695c;
    color:white;
    text-align:center;
    padding:25px;
}
nav{
    background:#004d40;
    padding:12px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-weight:bold;
}
section{
    padding:30px;
}
.card{
    background:white;
    margin:15px 0;
    padding:20px;
    border-radius:10px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}
.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
}
.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:8px;
}
table{
    width:100%;
    border-collapse:collapse;
}
table,th,td{
    border:1px solid #ccc;
}
th{
    background:#00695c;
    color:white;
}
th,td{
    padding:10px;
}
footer{
    background:#004d40;
    color:white;
    text-align:center;
    padding:15px;
}
</style>
</head>
<body>

<header>
    <h1>Guntur City Information Portal</h1>
    <p>The Mirchi Capital of India</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#population">Population</a>
    <a href="#wards">Wards</a>
    <a href="#tourism">Tourism</a>
    <a href="#education">Education</a>
    <a href="#health">Healthcare</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
<div class="card">
<h2>About Guntur</h2>
<p>
Guntur is one of the major cities of Andhra Pradesh.
It is famous for its chilli market, agriculture,
education institutions, healthcare facilities and
its proximity to Amaravati.
</p>
</div>
</section>

<section id="population">
<div class="card">
<h2>Population Statistics</h2>

<table>
<tr>
<th>Parameter</th>
<th>Value</th>
</tr>

<tr>
<td>Population</td>
<td>906,344</td>
</tr>

<tr>
<td>Area</td>
<td>159.46 km²</td>
</tr>

<tr>
<td>Total Wards</td>
<td>57</td>
</tr>

<tr>
<td>Sex Ratio</td>
<td>999 Females per 1000 Males</td>
</tr>

</table>
<a href="documents/guntur word document.docx" download>
📄 Download Guntur Report (Word Document)
</a>

</div>
</section>

<section id="wards">
<div class="card">
<h2>Administrative Wards</h2>

<p>
Guntur Municipal Corporation consists of 57 wards.
Each ward contains several localities and colonies.
Ward details can be updated dynamically from GMC records.
</p>

<ul>
<li>Ward 1 – Auto Nagar, Vasavi Nagar, Gandhi Nagar</li>
<li>Ward 2 – Seetha Nagar, RTC Colony</li>
<li>Ward 3 – Balaji Nagar, Teachers Colony</li>
<li>...</li>
<li>Ward 57 – Additional Localities</li>
</ul>

</div>
</section>

<section id="tourism">
<div class="card">
<h2>Tourist Attractions</h2>

<div class="gallery">

<img src="guntur1.jpg" alt="Amaravati">

<img src="guntur2.jpg" alt="Kondaveedu Fort">

<img src="guntur3.jpg" alt="Undavalli Caves">

<img src="guntur4.jpg" alt="Bird Sanctuary">

</div>

</div>
</section>

<section id="education">
<div class="card">
<h2>Education</h2>

<ul>
<li>Acharya Nagarjuna University</li>
<li>Guntur Medical College</li>
<li>Andhra Christian College</li>
<li>RVR & JC College of Engineering</li>
<li>KL University (nearby region)</li>
</ul>

</div>
</section>

<section id="health">
<div class="card">
<h2>Healthcare Facilities</h2>

<ul>
<li>Government General Hospital</li>
<li>Guntur Medical College Hospital</li>
<li>Private Multi-Speciality Hospitals</li>
<li>Primary Health Centres</li>
</ul>

</div>
</section>

<section id="contact">
<div class="card">
<h2>Contact Information</h2>

<p><strong>Guntur Municipal Corporation</strong></p>
<p>Grand Trunk Road, Guntur</p>
<p>Phone: 0863-2345103</p>
<p>Email: info@gmcguntur.ap.gov.in</p>

</div>
</section>

<footer>
<p>© 2026 Guntur City Information Portal</p>
</footer>

</body>
</html>

