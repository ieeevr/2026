---
layout: ieeevr-default
title: "Panels"
subtitle: "IEEE VR 2026"
title_separator: "|"
---
<style>
  .ks-container { width: 100%; margin-top: 20px; }
  .ks-list-item { display: flex; align-items: center; padding: 20px; border-bottom: 1px solid #eee; gap: 20px; flex-wrap: wrap; }
  .ks-thumb { width: 180px; height: 180px; border-radius: 20%; object-fit: cover; }
  .ks-info { flex: 1; min-width: 250px; }
  .ks-info h2 { margin: 0; font-size: 1.25rem; }
  .ks-info .affiliation { color: #006699; font-size: 1rem; margin: 5px 0; }
  .ks-info .talk-title { font-weight: bold; color: #006699; font-size: 0.9rem; }
  .ks-more-btn { padding: 5px 15px; background: #00589b; color: #fff; border: none; border-radius: 5px; cursor: pointer; transition: 0.3s; font-size: 0.7rem; }
  .ks-more-btn:hover { background: #003d6b; }

  .ks-modal { display: none; position: fixed; z-index: 9999; left: 0; top: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.8); overflow: hidden; }
  .ks-modal-content { position: relative; background: #fff; margin: 3% auto; padding: 0; width: 90%; max-width: 900px; max-height: 85vh; border-radius: 12px; display: flex; flex-direction: column; }
  .ks-modal-header-bar { padding: 15px 25px; border-bottom: 1px solid #eee; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; background: #fff; border-radius: 12px 12px 0 0; z-index: 10; }
  .ks-close { font-size: 32px; font-weight: bold; cursor: pointer; color: #aaa; line-height: 1; }
  .ks-close:hover { color: #000; }
  
  .ks-modal-scroll-area { padding: 30px; overflow-y: auto; flex: 1; }
  .ks-modal-profile { text-align: center; margin-bottom: 30px; }
  .ks-modal-photo { width: 200px; height: 200px; border-radius: 20%; object-fit: cover; margin-bottom: 15px; border: 4px solid #f8f9fa; }
  .ks-modal-name { font-size: 1.8rem; margin: 0; color: #333; }
  .ks-modal-affil { color: #666; font-size: 1.1rem; margin: 8px 0; }
  .ks-modal-talk { font-size: 1.3rem; font-weight: bold; color: #00589b; margin-top: 15px; line-height: 1.3; }

  .ks-section-title { font-size: 1.2rem; font-weight: bold; color: #00589b; border-bottom: 2px solid #00589b; padding-bottom: 5px; margin: 35px 0 15px; text-transform: uppercase; }
  .ks-text-content { font-size: 0.7rem; line-height: 1.3; color: #444; text-align: justify; }
  .page__content h2 { color: #000 !important; }
  .page__content p {
    margin: 0.3em auto 1rem;
    text-align: center;
}
  @media (max-width: 600px) {
    .ks-list-item { flex-direction: column; text-align: center; }
    .ks-info { min-width: 100%; }
    .ks-modal-content { margin: 5% auto; height: 90vh; }
  }
</style>
<p class="big_title">Panels</p>
<div class="ks-container">
  <div class="ks-list-item">
    <div class="ks-info">
      <h2>Future Conference Formats: Balancing Knowledge Dissemination, Socialising and Environmental Impacts</h2>
      <div class="affiliation">Tuesday, March 24 / 15:00-16:30</div>
      <div class="talk-title"></div>
    </div>
    <button class="ks-more-btn" onClick="openKsModal('modal1')">More</button>
  </div>
  <div class="ks-list-item">
    <div class="ks-info">
      <h2>Standardization in XR/VR: Challenges and Priorities Beyond Terminology</h2>
      <div class="affiliation">Wednesday, March 25 / 15:00-16:30</div>
      <div class="talk-title"></div>
    </div>
    <button class="ks-more-btn" onClick="openKsModal('modal2')">More</button>
  </div>
  
  
  
</div>
<div id="modal1" class="ks-modal">
  <div class="ks-modal-content">
    <div class="ks-modal-header-bar"> <span style="font-weight: bold; color: #666;">Detail</span> <span class="ks-close" onClick="closeKsModal('modal1')">&times;</span> </div>
    <div class="ks-modal-scroll-area">
      <div class="ks-modal-profile"> 
        <h2 class="ks-modal-name">Future Conference Formats: Balancing Knowledge Dissemination, Socialising and Environmental Impacts</h2>
        <p class="ks-modal-affil">Tuesday, March 24 /15:00-16:30</p>
        <div class="ks-modal-talk"></div>
      </div>
      <div class="ks-section-title">Presentation</div>
      <div class="ks-text-content">Academic conferences are important means for nurturing fields of research. They allow attendees to present and get feedback on the latest innovations and concepts. They create networking opportunities for people to establish new connections and rekindle existing ones. They enable research pollination that cuts across cultures, geographies and research groups. The predominant model for such annual conferences is a multi-day face-to-face meeting, and in many cases, this model has been used for decades.<br>
<br>

There are, however, many challenges that have arisen over this time. These include increases in travel costs, more international travel restrictions (e.g., visas), pandemics, political unrest, and a growing understanding of the environmental impact of face-to-face conferences with 1000+ attendees. Our community could benefit from a re-examination and re-imagining by considering alternative formats for our annual academic conferences.<br>
<br>

This panel will continue a panel discussion started at IEEE VR 2025 around alternative models for conferences, focusing mainly on our VR/AR/MR/XR community.
</div>
      <div class="ks-section-title">Discussion Topics</div>
      <div class="ks-text-content"> We would like to put out some topics to the audience for discussion, including things like:
      <ol>
<li>Challenges to Running Our Conferences</li>
<li>Single-site In-person (current format) vs Multi-site In-person vs Fully Virtual</li>
<li>Main Goals for Attendees of our ConferencesM.</li>
<li>Expanding Attendee Inclusion/Access</li>
</ol>
</div>

  <div class="ks-section-title">Panelists</div>
      <div class="ks-text-content">
      
      
     <strong> Rob Lindeman, University of Canterbury, NZ</strong><br>

Rob Lindeman is a Professor and Director of the Human Interface Technology Lab NZ (HIT Lab NZ) at the University of Canterbury, New Zealand, and has been doing research in the field of VR since 1993. His work focuses on immersive, multi-sensory feedback systems for VR, AR, gaming, and long-term VR immersion research. He is particularly interested in non-fatiguing, non-sickness-inducing and worry-free experiences. He currently serves on the Steering Committees of both IEEE VR and ACM VRST. He was General Chair of IEEE VR 2010, IEEE 3DUI 2014 and ACM VRST 2023.<br>
<br>

<strong>Ferran Argelaguet, Inria, FR</strong><br>

Ferran Argelaguet is an Inria research scientist and the head of the Seamless Team at Inria Center at Rennes University. He received his PhD in Computer Science from Universitat Politècnica de Catalunya in 2011. His current research activity focuses on the field of 3D User Interfaces (3DUI) which is a multidisciplinary research field involving Human Computer Interaction, Computer Graphics, Human Factors, Ergonomics and Human Perception. He served as co-chair at the previous IEEE VR 2025 conference that was organized in Saint Malo, France, which hosted more than 1200 international attendees, giving him a privileged view of the challenges of organizing IEEE VR.<br>
<br>

<strong>Greg Welch, University of Central Florida, US</strong><br>

Dr. Greg Welch is a Professor at the University of Central Florida. Previously he was a research faculty member at the University of North Carolina at Chapel Hill, and he has worked for NASA and Northrop. He is an IEEE Fellow, an NAI Fellow, and a member of the IEEE VR Academy. His awards include an IEEE VR Technical Achievement Award and a ISMAR Long Lasting Impact Paper Award. He has served as a General Co-Chair for IEEE ISMAR (2012) and IEEE VR (2013 and 2024). He is currently serving as the IEEE VGTC Vice Chair for Conferences.<br>
<br>

<strong>Solène Lambert, Sorbonne Université, FR</strong><br>

Solène Lambert pursued her PhD in human-computer interaction at Sorbonne Université, focusing on surgical telementoring. In 2024, she organized a satellite experience in Paris, France, offering an opportunity for HCI researchers preferring not to travel to Hawai’i for ACM CHI 2024 to remotely "attend" the conference together.<br>
<br>

<strong>Kyle Johnsen, University of Georgia, US</strong><br>

Kyle Johnsen serves as a Professor in the School of Electrical and Computer Engineering at the University of Georgia. He was a General Chair of IEEE Virtual Reality for 2020 and 2021, helping to lead one of the first major academic conferences to explore the myriads of models and collaboration tools required for global remote participation. Since that time, his lab has been creating, using and studying collaborative, immersive virtual and mixed reality environments for research meetings, events, and productivity, with the overarching goal to exploit the potential of ubiquitous VR headsets for engaging in-person, remote, and hybrid social experiences.<br>
<br>


<strong>Anthony Steed, University College London, UK</strong><br>

Anthony Steed is Head of the Virtual Environments and Computer Graphics group in the Department of Computer Science at University College London. He has 30 years of experience in developing effective immersive experiences. While his early work focussed on the engineering of displays and software, more recently it has focussed on user engagement in and content production for collaborative and telepresence scenarios. He received the IEEE VGTC’s 2016 Virtual Reality Technical Achievement Award.  He has been involved in a variety of knowledge transfer activities, including five start-up companies.

      
      
</div>




    </div>
  </div>
</div>
<div id="modal2" class="ks-modal">
  <div class="ks-modal-content">
    <div class="ks-modal-header-bar"> <span style="font-weight: bold; color: #666;">Detail</span> <span class="ks-close" onClick="closeKsModal('modal2')">&times;</span> </div>
    <div class="ks-modal-scroll-area">
      <div class="ks-modal-profile">
        <h2 class="ks-modal-name">Standardization in XR/VR: Challenges and Priorities Beyond Terminology</h2>
        <p class="ks-modal-affil">Wednesday, March 25 / 15:00-16:30</p>
        <div class="ks-modal-talk"></div>
      </div>
      <div class="ks-section-title">Presentation</div>
      <div class="ks-text-content">XR/VR Standardization provides the necessary foundation for reproducibility, interoperability, and widespread adoption, fostering an extensible ecosystem that bridges industry and academia, and streamlines access for novices. Break-through discoveries in Virtual Reality are catalyzed by creative exploration and cutting-edge research, while VR standardization moves at a slower, consensus-driven pace, often remaining an afterthought. As VR technologies mature beyond research prototypes toward consumer and enterprise deployment, the <strong>IEEE VR community must address an important question: Are we standardizing too late, too early, or in ways that fail to match how XR/VR evolve in practice?</strong><br>
<br>

This panel brings together researchers, industry leaders, and standardization experts for a discussion on XR and VR standardization challenges:<br>
<br>

<strong>Core Problem:</strong> VR research develops novel locomotion techniques, interaction paradigms, and perceptual manipulations that push our understanding of the technology and applications forward, yet without standardized evaluation protocols, these innovations remain difficult to compare, reproduce, or adopt industrially. Should the community adopt recommended reporting standards? Incentivize artifact sharing through digital badges? Create dedicated replication tracks? Or go further with mandatory benchmarks for acceptance? Would such requirements stifle innovation or enhance scientific rigor and applicability in the real world? The answer may determine whether VR research translates into deployable, comparable, and reusable knowledge for products and platforms or becomes the foundation for next-generation VR developments.<br>
<br>

<strong>Industry Perspective:</strong> Major players behind VR operating systems and hardware have built proprietary ecosystems that fragment the developer and research communities. OpenXR promised universal compatibility, yet adoption remains incomplete, and some features lack standardization. When does platform competition drive innovation versus create incompatible or costly reinvention that fragments the ecosystem? Should researchers omit adapting to proprietary platforms, or pragmatically work within existing ecosystems? <br>
<br>

<strong>Reproducibility Crisis:</strong> Many of us experienced the frustration of reconstructing VR research implementations from incomplete documentation, spending copious time reverse engineering artifacts (e.g., algorithms, device configurations, or systems from papers and videos). This reflects a field-wide infrastructure gap in methodological documentation and artifact sharing. Is this insufficiently specified methodology simply the cost of rapid innovation, or does it hinder VR's evolution into a mature scientific discipline? Should the community adopt artifact availability statements, incentivize optional repositories, or require minimal reproducibility packages?<br>
<br>

<strong>Why This Matters Now? </strong>Recent initiatives like the ISMAR 2025 Standardization Committee and XRStand workshop 2025 (co-organized by members of this panel) demonstrate growing recognition that VR research and industry must bridge their gap. Complementing those efforts, this panel focuses on identifying the remaining gaps between research innovation and industrial standardization, encouraging an open exchange of ideas on how to move forward.
</div>
      
      
      
      
       <div class="ks-section-title">Panelists</div>
      <div class="ks-text-content">
      
      
<strong>Neil Trevett (NVIDIA, USA)</strong>: is the elected President of the Khronos Group and Vice President of Developer Ecosystems at NVIDIA, where he drives the adoption of open standards and developer technologies for 3D graphics, AI, and immersive media. At Khronos for twenty-five years, Neil has helped initiate and foster many widely adopted open standards including glTF, OpenXR, OpenGL ES, Vulkan, WebGL, and Slang. Most recently, Neil initiated and serves as President of the Metaverse Standards Forum, which has grown to over 2,600 member organizations.<br>
<br>


<strong>Tim Weissker (RWTH Aachen University, Germany)</strong> is a senior scientist with RWTH Aachen University, Germany, where he is permanently appointed for conducting independent research in the broad area of extended reality and 3D user interfaces. Tim’s research interests include a large variety of topics on effective, efficient, and comfortable user interaction in both single- and multi-user environments, all of which leverage the unique potential that extended reality systems offer beyond the mere replication of real-world scenarios. He has recently been involved in research on the reproducibility of VR locomotion techniques as well as the organization of the Reproduction Challenge at ACM VRST.<br>
<br>


<strong>J. Edward Swan II (Mississippi State University, USA)</strong>: is the Interim Associate Dean of Research for the Bagley College of Engineering at Mississippi State University, and the Eiland Professor of Computer Science and Engineering. In 2017 and 2018, he served as Interim Department Head. Before joining Mississippi State University in 2004, he spent seven years as a scientist at the Naval Research Laboratory in Washington, D.C. Dr. Swan’s research has centered on the topics of augmented and virtual reality and applied perception. He is the current chair of the IEEE VR steering committee, and was a general chair of VR 2020 and VR 2021.
<br>
<br>

<strong>Jen-Shuo Liu (Columbia University, USA) - Moderator</strong>: is an AR/VR researcher and engineer focused on visual computing and HCI. He designs perception-based interfaces for teleoperation and maintenance while developing algorithms for HDR and immersive video processing. He holds a Ph.D. from Columbia University, where he focused on AR/VR precueing systems. His research is published in venues including IEEE TVCG, TIP, and ISMAR. An active community contributor, Jen-Shuo serves on the CHI Late-Breaking Work Program Committee, and as both the Publicity & Communications Chair and Pitch-Your-Lab Chair for IEEE ISMAR.
      
</div>








      
    </div>
  </div>
</div>












<script>
  function openKsModal(id) {
    document.getElementById(id).style.display = "block";
    document.body.style.overflow = "hidden";
  }

  function closeKsModal(id) {
    document.getElementById(id).style.display = "none";
    document.body.style.overflow = "auto";
  }

  window.onclick = function(event) {
    if (event.target.className === 'ks-modal') {
      event.target.style.display = "none";
      document.body.style.overflow = "auto";
    }
  }
</script> 
