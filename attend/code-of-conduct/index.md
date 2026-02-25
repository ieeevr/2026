---
layout: ieeevr-default
title: "Code of Conduct"
subtitle: "IEEE VR 2026"
title_separator: "|"
---

<style>
.fa-envelope-square:before {
    content: "" !important;
}
</style>

<style>
    .box_deco_01 {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: space-between;
        padding: 20px;
        border: 1px solid #ddd;
        margin: 0 auto;
    }

    .info_content {
        flex: 1;
        min-width: 300px;
    }

    .info_row {
        display: flex;
        margin-bottom: 10px;
        align-items: baseline;
    }

    .info_label {
       
        color: #333;
        width: 40%;
    }

    .info_value {
        font-weight: bold;
        color: #000;
        text-align: left;
        flex: 1;
    }

    .info_value a {
        text-decoration: none;
        color: inherit;
    }

    .phone_number {
        display: block;
        margin-top: 5px;
        letter-spacing: 1px;
    }

    .qr_section {
        padding-left: 20px;
        border-left: 1px solid #eee;
        margin-left: 20px;
    }

    .qr_section img {
        width: 120px;
        height: 120px;
        display: block;
    }

    @media (max-width: 600px) {
        .box_deco_01 {
            flex-direction: column;
            text-align: center;
        }
        .info_row {
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px;
        }
        .info_label {
            width: 100%;
            margin-bottom: 5px;
        }
        .info_value {
            width: 100%;
            text-align: center;
        }
        .qr_section {
            border-left: none;
            margin-left: 0;
            padding-left: 0;
            margin-top: 20px;
        }
    }
</style>














<script type="text/javascript">
    $(document).ready(function(){
		var email = ""; 
		var domain = "ieeevr.org"; 

		email = "general2026"; 		
		general.innerHTML  = "<span class='text-nowrap'><a href=javascript:location='" + "mail" + "to:" + email + "@" + domain + "'><i class='fas fa-fw fa-envelope-square emailIcon' style=''></i><i class='emailText'>" + email + "@" + domain + "</a></i></span>";

        email = "steering"; 		
		steering.innerHTML  = "<span class='text-nowrap'><a href=javascript:location='" + "mail" + "to:" + email + "@" + domain + "'><i class='fas fa-fw fa-envelope-square emailIcon' style=''></i><i class='emailText'>" + email + "@" + domain + "</a></i></span>";

        email = "eventconduct"; 		
		$(".eventconduct").html("<span class='text-nowrap'><a href=javascript:location='" + "mail" + "to:" + email + "@" + domain + "'><i class='fas fa-fw fa-envelope-square emailIcon' style=''></i><i class='emailText'>" + email + "@" + domain + "</a></i></span>");

        email = "eventconduct"; 		
		$(".eventconductSm").html("<span class='text-nowrap'><a href=javascript:location='" + "mail" + "to:" + email + "@" + domain + "'><i class='fas fa-fw fa-envelope-square emailIconSm' style=''></i><i class='emailTextSm'>" + email + "@" + domain + "</a></i></span>");

        email = "swan"; 
		var domain = "acm.org"; 		
		swan.innerHTML  = "<span class='text-nowrap'><a href=javascript:location='" + "mail" + "to:" + email + "@" + domain + "'><i class='fas fa-fw fa-envelope-square emailIcon' style=''></i><i class='emailText'>" + email + "@" + domain + "</a></i></span>";
	});
</script>


<div >
    <h1>Code of Conduct<div class="floatRight"><span class="eventconductSm"></span></div></h1>
    <p>
        IEEE Virtual Reality 2026 is dedicated to providing a harassment-free conference experience for everyone, regardless of gender, sexual orientation, disability, physical appearance, body size, race, or religion. We do not tolerate harassment of conference participants in any form.
    </p>
    <p>
        As a conference that aims to share ideas and freedom of thought and expression, it is essential that the conference takes place in an environment that recognizes the inherent worth of every person by being respectful of all. All communication should be appropriate for a professional audience including people of many different backgrounds. Attendees violating these rules may be asked to leave the conference without a refund at the sole discretion of the conference organizers. In addition, attendees are subject to the <i class="far fa-file-pdf"></i> <a href="{{"/assets/attend/ieee_code_of_conduct.pdf" | relative_url }}" target="_blank">IEEE Code of Ethics</a>.
    </p>
 <h2>Reporting a Breach of the Code of Conduct</h2>
   
	<p>
        If you wish to report a breach of the code of conduct this can be done via email to:
        <ul>
            <li> 
                The General Co-Chairs: <span id="general"></span>
            </li>
            <li> 
                The Steering Committee: <span id="steering"></span>
            </li>
            <li> 
                The Chair, Ed Swan: <span id="swan"></span>
            </li>
        </ul>
        <p>All reports will only be sent to the authorized people and will be treated confidentially.</p>
        <p>You can also report conduct issues directly the IEEE CS Committee to Assist in Reporting Ethics & Conduct Violations (CS Assist) or the IEEE Ethics Reporting Line.</p>



		<p class="box_deco_01">
    <span class="info_content">
        <span class="info_row">
            <span class="info_label">CS Assist committee:</span>
            <span class="info_value"><a href="mailto:assist@computer.org">assist@computer.org</a></span>
        </span>
        <span class="info_row">
            <span class="info_label">IEEE Ethics Reporting Line:</span>
            <span class="info_value">
                <a href="https://www.ieee-ethics-reporting.org" target="_blank">www.ieee-ethics-reporting.org</a>
                <span class="phone_number">+1.888.359.6323</span>
            </span>
        </span>
    </span>
    <span class="qr_section">
        <img src="/2026/assets/images/codeof_QR.gif" alt="QR Code">
    </span>
</p>


		
    </p>

    <h2>IEEE Computer Society Open Conference Statement</h2>

    <p>
        Equity, Diversity, and Inclusion are central to the goals of the IEEE Computer Society and all of its conferences. Equity at its heart is about removing barriers, 
        biases, and obstacles that impede equal access and opportunity to succeed. Diversity is fundamentally about valuing human differences and recognizing diverse talents. 
        Inclusion is the active engagement of Diversity and Equity.
    </p>
    <p>
        A goal of the IEEE Computer Society is to foster an environment in which all individuals are entitled to participate in any IEEE Computer Society activity free 
        of discrimination. For this reason, the IEEE Computer Society is firmly committed to team compositions in all sponsored activities, including but not limited to, 
        technical committees, steering committees, conference organizations, standards committees, and ad hoc committees that display Equity, Diversity, and Inclusion.
    </p>

    <p>
        IEEE Computer Society meetings, conferences and workshops must provide a welcoming, open and safe environment, that embraces the value of every person, 
        regardless of race, color, sex, sexual orientation, gender identity or expression, age, marital status, religion, national origin, ancestry, or disability.
        All individuals are entitled to participate in any IEEE Computer Society activity free of discrimination, including harassment based on any of the above factors.
    </p>

    <h2>IEEE Event Conduct and Safety Statement</h2>

    <p>
        IEEE believes that science, technology, and engineering are fundamental human activities, for which openness, international collaboration, and the free flow 
        of talent and ideas are essential. Its meetings, conferences, and other events seek to enable engaging, thought provoking conversations that support IEEE’s 
        core mission of advancing technology for humanity. Accordingly, IEEE is committed to providing a safe, productive, and welcoming environment to all participants, 
        including staff and vendors, at IEEE-related events.
    </p>

    <p>
        IEEE has no tolerance for discrimination, harassment, or bullying in any form at IEEE-related events. All participants have the right to pursue shared 
        interests without harassment or discrimination in an environment that supports diversity and inclusion. Participants are expected to adhere to these 
        principles and respect the rights of others.
    </p>

    <p>
        IEEE seeks to provide a secure environment at its events. Participants should report any behavior inconsistent with the principles outlined here, to 
        on site staff, security or venue personnel, or to <span class="eventconduct"></span>. 
    </p>
</div>
