---
layout: ieeevr-default
title: "Students Volunteers"
subtitle: "IEEE VR 2025"
title_separator: "|"
---
<script type="text/javascript">
	$(document).ready(function(){
		var email = ""; 
		var domain = "ieeevr.org"; 

		
		email = "studentvolunteers2025"; 
		studentvolunteers.innerHTML  = "<span class='text-nowrap'><a href=javascript:location='" + "mail" + "to:" + email + "@" + domain + "'><i class='fas fa-fw fa-envelope-square emailIconSm' style=''></i><i class='emailTextSm'>" + email + "@" + domain + "</a></i></span>";
		
			

	});
</script>
<p style="width:100%; margin: 30px auto; padding: 20px 0; text-align:center; font-size:1rem; border-radius: 30px; background-color: #f3f3f3">This content is currently being updated.</p>
<div style="display:none">
<h1>Student Volunteers <span id="studentvolunteers"></span> </h1>
<div>	
	<ul>
		{% for sv in site.data.sv %}
			<li><span class="bold">{{ sv.prenom }} {{ sv.nom }} </span> &#x2012; <i> {{ sv.affiliation }}</i></li>
		{% endfor %}
	</ul>
</div>
</div>

