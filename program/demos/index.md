---
layout: ieeevr-default
title: "Research Demos"
subtitle: "IEEE VR 2026"
title_separator: "|"
---
<style>
html {
    scroll-behavior: smooth;
}

h3 {
    margin-top: 1.5rem;
    margin-bottom: 0.8rem;
    font-size: 1em;
    border-bottom: 2px solid #262188;
    padding-bottom: 5px;
    padding-bottom: 1rem;
}

.table-scroll {
    width: 100%;
    overflow-x: auto;
    margin-bottom: 40px;
    -webkit-overflow-scrolling: touch;
    border-radius: 20px;
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);
}
    
table {
    border-collapse: collapse;
    width: 100%;
    min-width: 600px;
    table-layout: fixed;
    margin-bottom: 0;
}

thead {
    background-color: #262188 !important;
    color: #fff;
    border-bottom: none;
}   

th {
    font-size: 0.8rem;
    line-height: 1.2;
    text-align: center;
    padding: 15px 25px;
}

td {
    font-size: 0.8rem;
    border-bottom: 1px solid #eee !important;
    padding: 15px 25px;
    text-align: center;
    word-wrap: break-word;
    vertical-align: middle;
    line-height: 1.4;
}   

.time-col {
    background-color: #F2F2F2;
    font-weight: bold;
    color: #333;
}

.session-id-tag {
    margin-top: 1rem;
    font-size: 1.3em;
    color: #262188;
    border-bottom: 1px solid #262188;
}

.div-light {
    border: 0;
    border-top: 1px solid #eee;
    margin: 10px 0;
}

.div-heavy {
    border: 0;
    border-top: 3px solid #262188;
    margin: 5px 0;
}

/* --- 추가 및 수정된 스타일 영역 --- */

.paper-section {
    margin-bottom: 40px;
    padding-bottom: 20px;
    border-bottom: 1px solid #ddd;
}

.paper-section:last-child {
    border-bottom: none;
}

.meta-info {
    font-size: 0.7rem;
    margin-bottom: 8px;
    line-height: 1.4;
}

.meta-info strong {
    font-weight: bold;  
    font-size:0.8rem
}

.abstract-wrapper {
    margin-top: 15px;
}

.abstract-toggle {
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    font-size: 0.8rem;
    margin-bottom: 5px;
    user-select: none;
    transition: color 0.2s;
}

.abstract-toggle strong{
    color: #262188;
}


.abstract-toggle .arrow {
    font-size: 0.8em;
    margin-left: 8px;
    transition: transform 0.3s ease;
}

.abstract-toggle.open .arrow {
    transform: rotate(-180deg);
}

.abstract-content {
    display: none;
    margin-top: 10px;
    color: #333;
    line-height: 1.6;
    font-size: 0.9rem;
}

.page__content p, .page__content li, .page__content dl {
    font-size: 0.8rem;
}

/* 반응형 유튜브 임베드 컨테이너 */
.video-container {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 비율 */
    height: 0;
    overflow: hidden;
    margin-top: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    background-color: #000; /* 로딩 전 배경색 */
}

/* --- 유튜브 썸네일 클릭 최적화를 위한 CSS 추가 --- */
.youtube-player {
    position: absolute;
    top: 0; 
    left: 0; 
    width: 100%; 
    height: 100%;
    background-position: center;
    background-size: cover;
    cursor: pointer;
}

.youtube-player::after {
    content: "▶";
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 60px;
    color: rgba(255,255,255,0.8);
    text-shadow: 0 0 15px rgba(0,0,0,0.6);
    transition: color 0.2s;
}

.youtube-player:hover::after {
    color: #cc181e; /* 유튜브 시그니처 레드 */
}

.big_title {
    font-size: 1.8rem !important;
    font-weight: bold;
    padding-bottom: 0 !important;
    margin-bottom: 0 !important;
    text-align: left !important;
}
.page__content p {
    font-size: 0.7rem;
    line-height:1.2
}
</style>

<p class="big_title">RESEARCH DEMOS</p>
<div class="table-responsive table-scroll">
  <table>
      <colgroup>
          <col style="width:20%">        
          <col style="width:30%">
          <col style="width:20%"> 
          <col style="width:30%">
      </colgroup>
    <thead>
      <tr>
        <th></th>
        <th>Date</th>
        <th>Time</th>
        <th>Venue</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="3" >Research Demo Booths open</td>
        <td >Monday, March 23</td>
        <td>11:00-11:30<br/>
        13:15-14:00<br/>16:00-16:30</td>
        <td>Grand Ballroom B, 3F</td>
      </tr>
      <tr>
        <td >Tuesday, March 24</td>
        <td>09:30-10:00<br/>
        13:15-14:00<br/>16:00-16:30</td>
        <td>Grand Ballroom B, 3F</td>
      </tr>
      <tr>
        <td >Wednesday, March 25</td>
        <td>09:30-10:00<br/>
        13:15-14:00<br/>16:00-16:30</td>
        <td>Grand Ballroom B, 3F</td>
      </tr>
    </tbody>
  </table>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Dart Throwing in Virtual Reality with Aim Assistance</h3>
  <p class="meta-info"><strong>Booth ID: 1</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Ren Boz</strong>, <i>College of Information Science, University of Arizona, Tucson, Arizona, United States</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Throwing tasks in virtual reality (VR) are often challenging due to limitations in depth perception, force control, and the absence of familiar physical feedback. Aim assistance can mitigate these challenges, allowing users to perform throwing actions more accurately and consistently. This demo presents an interactive showcase derived from our conditionally accepted IEEE VR 2026 Conference and TVCG paper, which examines how aim assistance influences both task performance and user experience in a VR dartthrowing task. The demonstrated system incorporates a subtle, trajectorybased aim assistance method that operates at the moment of release. Rather than visibly guiding the trajectory, our technique gently adjusts the dart’s initial flight direction to partially compensate for throwing errors. During the demo, attendees can directly experience and compare dart throwing with and without aim assistance, allowing them to observe the differences in accuracy, control, and the overall interaction firsthand.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="8N-zOR_JQWI"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">VR Games Based on Circumplex Model of Group Tasks for QoE Measurements and Beyond</h3>
  <p class="meta-info"><strong>Booth ID: 2</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Norbert Barczyk</strong>, <i>AGH University of Krakow, Cracow, Poland</i>; <strong>Kamil Koniuch</strong> <i>AGH University of Krakow, Cracow, Poland</i>; <strong>Mateusz Olszewski</strong> <i>AGH University of Krakow, Cracow, Poland</i>; <strong>Lucjan Janowski</strong> <i>AGH University of Krakow, Krakow, Poland</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This research demo presents a system for studying collaboration in Virtual Reality. The system was developed in Unity and provides a multi-user VR simulator with a set of collaborative tasks categorized according to McGrath’s circumplex model of group tasks. The platform is fully configurable, allowing researchers to adapt tasks and parameters to their own studies on VR cooperation. The system integrates in-VR subjective assessment, enabling users to rate Quality of Experience without removing the headset. In addition, it automatically collects performance data to support quantitative analysis. In this demo, participants collaborate in dyads and experience a novel approach to studying subjective QoE in networked VR cooperation.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="a1q7rDVux9Q"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Presentation of Impact Sensations by a Floor-Mounted Turntable</h3>
  <p class="meta-info"><strong>Booth ID: 3</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Mutsuki Shimada</strong>, <i>Graduate School of Informatics and Engineering, Department of Informatics, The University of Electro-Communications</i>; <strong>Izumi Mizoguchi</strong>, <i>Graduate School of Informatics and Engineering, The University of Electro-Communications</i>; <strong>Prof. Hiroyuki Kajimoto</strong> <i>The University of Electro-Communications</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Previous studies on impact sensation presentation have primarily focused on delivering impulses to the hands using wearable or handheld devices. On the other hand, impact reaction forces propagate through the entire body, ultimately acting between the feet and the ground. Leveraging this physical property, we hypothesize that presenting reaction forces through the feet can enhance impact sensation. This study investigates a method that uses a floor-mounted turntable. As the user stands on the device, it rotates impulsively during a striking motion to present reaction forces, thereby enhancing the realism of the impact experience.To evaluate the effectiveness of the proposed method, we conducted a user study. Participants wore a head-mounted display and stood on the turntable while performing a virtual ball-striking task in a VR environment using a handheld controller. Reaction force feedback was delivered through the feet by actuating the turntable in synchrony with their striking motions. The experimental factors included the rotation direction, the presence or absence of rotation, and a combined condition that used both the proposed method and conventional controller vibration. Participants performed multiple strikes under each condition, after which they provided subjective ratings on a 7-point Likert scale regarding impact sensation, sense of presence, sense of agency, and enjoyment.The results showed that the condition in which counterclockwise rotation was presented first led to significant improvements in impact sensation, sense of presence, sense of agency, and enjoyment compared to the no-rotation condition. In addition, the condition combining the proposed method with controller vibration resulted in significantly higher impact sensation and sense of presence than the vibration-only condition. These findings suggest that presenting reaction force feedback through the feet is effective in enhancing impact sensation on its own, and that combining this approach with existing hand-based vibration feedback further enhances both impact sensation and sense of presence.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="nMVWQWlP5iM"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">GazeDrift: A Balloon-Popping Serious Game for Eye Tracking Troubleshooting in VR</h3>
  <p class="meta-info"><strong>Booth ID: 4</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>László Kopácsi</strong> <i>Interactive Machine Learning, German Research Center for Artificial Intelligence (DFKI)</i>; <strong>Abdulrahman Mohamed Selim</strong> <i>Interactive Machine Learning Department (IML), German Research Center for Artificial Intelligence (DFKI)</i>; <strong>Arham Ahmed</strong>, <i>Interactive Machine Learning, German Research Center for Artificial Intelligence (DFKI)</i>; <strong>Michael Barz</strong> <i>Interactive Machine Learning, German Research Center for Artificial Intelligence (DFKI)</i>; <strong>Daniel Sonntag</strong>, <i>German Research Center for Artificial Intelligence (DFKI Applied Artificial Intelligence, University of Oldenburg</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Eye tracking is integral to the user experience in modern extended reality (XR) headsets; however, practical deployment is frequently hindered by calibration drift, signal jitter, and the Midas touch problem. Non-expert users often lack the mental models required to distinguish between system inaccuracies and behavioural errors, complicating the troubleshooting process. To address this, we present GazeDrift, a virtual reality (VR) serious game designed to educate users about the inherent limitations of eye tracking. Through a gamified balloon-popping task, the system isolates and simulates three specific error conditions: jitter, systematic shift, and reduced peripheral accuracy. By combining interactive tutorials, feedback-driven gameplay, and conceptual quizzes, GazeDrift provides a structured environment for users to develop an intuitive understanding of gaze interaction artefacts.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="phl6AvO8F4E"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">User-Centric Active Learning through Immersive Visualization</h3>
  <p class="meta-info"><strong>Booth ID: 4</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Rida Saghir</strong> , <i>Carl von Ossietzky Universität Oldenburg, Oldenburg, Germany German Research Institute for Artificial Intelligence (DFKI), Interactive Machine Learning</i>; <strong>Saleem Ahmad</strong> , <i>Interactive Machine Learning, German Research Institute for Artificial Intelligence</i>; <strong>László Kopácsi</strong> , <i>Interactive Machine Learning, German Reserach Center for Artificial Intelligence (DFKI)</i>; <strong>Thiago S. Gouvêa</strong> , <i>Interactive Machine Learning, German Research Center for Artificial Intelligence (DFKI)</i>; <strong>Daniel Sonntag</strong> , <i>German Research Center for Artificial Intelligence (DFKI), Saarbrücken, Germany Applied Artificial Intelligence, Carl von Ossietzky Universität Oldenburg</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Understanding data structure is critical for effective human involvement in machine learning, particularly in user-centric active learning where annotation decisions by humans shape model behaviour. Learned embedding spaces capture this structure, but are typically explored through 2D interfaces. Virtual Reality (VR) offers an opportunity to present these embeddings immersively, supporting richer perception and interaction. We present an interactive VR interface for human-in-the-loop active learning, enabling users to explore and annotate samples directly within an immersive embedding space. The system visualizes a continuously updating 3D embedding space derived from an audio classifier and augments it with common active learning cues, including uncertainty, density, diversity, and class coverage through visual encoding. User annotations trigger iterative retraining, allowing the model and visualization to co-evolve in response to human input.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="QEreFVQ7zBo"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">GTK: An Open-Source Toolkit for Gaze-based Interaction in XR</h3>
  <p class="meta-info"><strong>Booth ID: 4</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>László Kopácsi</strong> , <i>Interactive Machine Learning, German Research Center for Artificial Intelligence (DFKI)</i>; <strong>Michael Barz</strong> , <i>Interactive Machine Learning, German Research Center for Artificial Intelligence (DFKI), Saarbrücken</i>; <strong>Daniel Sonntag</strong> , <i>German Research Center for Artificial Intelligence (DFKI), Saarbrücken, Germany Applied Artificial Intelligence, University of Oldenburg</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Gaze interaction is becoming increasingly prevalent in Extended Reality (XR) due to the widespread integration of eye-tracking sensors in modern head-mounted displays. However, implementing robust gaze-based interfaces requires substantial development effort, often leading to reimplementation of established interaction patterns. We present the Gaze Interaction Toolkit (GTK), an open-source Unity package designed to facilitate the integration of active and passive gaze-based interaction in XR environments. GTK provides modular components including gaze-aware interactables, gaze-contingent information displays, and spatial context menus, as well as tools for onboarding, visual attention monitoring, and eye-tracking accuracy assessment. We demonstrate these features through an industrial sorting task scenario that systematically introduces users to multimodal gaze-assisted interaction techniques, illustrating the toolkit's capabilities for developing gaze-responsive user interfaces in XR training applications.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="zc5DSeV4Xog"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">A No-Code Versatile XR Framework with Shared Experiences</h3>
  <p class="meta-info"><strong>Booth ID: 5</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Dr Jean-Philippe Farrugia</strong> , <i>LIRIS - IUT, Université Lyon 1</i>; <strong>Jonathan Ollivier</strong>, <i>Computer Science department, Lyon 1 University</i>; <strong>Ing. Dr. Fabrice Jaillet</strong> <i>LIRIS , CNRS</i>; <strong>Bruno Tellez</strong>, <i>LIRIS, Lyon 1 University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This paper introduces the new version of HERA, a no-code versatile open-source XR Authoring framework with shared user experiences. HERA allows to easily create XR applications without any technical knowledge. It is entirely web-based and therefore does not need any installation. It uses well known technologies and is compatible with any WebXR device. The new version presented in this paper allows multi-user XR experience sharing: it proposes a companion application used to remotely control and present a project to several people at the same time. To illustrate this feature, we present two multi-user XR demos: a virtual historical model AR showcase, and a VR environment exploration.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="6dRI_3YliBo"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Intuitive Gesture-Based Interaction with 4D Objects in Virtual Reality</h3>
  <p class="meta-info"><strong>Booth ID: 6</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Akihiro Matsuura</strong>, <i>Graduate School of Science and Engineering, Tokyo Denki University</i>; <strong>Yifei Wang</strong>, <i>Graduate School of Science and Engineering, Tokyo Denki University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>We present a gesture-based VR system for manipulating four-dimensional objects and points with a three-dimensional perspective view in the virtual space. We defined intuitive gestures for basic operations to manipulate and deform objects and points in the four-dimensional space, such as translation, scaling, and two types of rotations, one of which is specific to the four-dimensional space with invisible axis in the perspective view. Users can immerse in the virtual space and can easily manipulate the four-dimensional objects using the proposed hand gestures.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="S-YjX1FDzHc"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Beyond Frame: A Remediation Authoring Tool for Transforming 2D Artworks into VR Experiences</h3>
  <p class="meta-info"><strong>Booth ID: 7</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Sieun Park</strong>, <i>Sogang University</i>; <strong>Jusub Kim</strong>, <i>Art&Technology/Sogang University,</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>The rapid advancement of generative AI has expanded the possibilities for VR content creation, yet the "remediation" of 2D paintings into immersive 3D experiences remains a fragmented and technically demanding process. Creators often struggle with disjointed AI tools that produce randomized, uncontrollable results. This paper introduces a unified "2D-to-VR" authoring framework designed to lower technical barriers while creating a "Human-in-the-loop" workflow. We present a prototype system that automates the analysis and spatialization of 2D art into 2D, 2.5D, and 3D VR modes, and we demonstrate its efficacy through a pilot implementation using Claude Monet’s Water Lilies.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="VByFzBZ7Wko"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Continuous and Interpretable Empathic Behaviors for Embodied Intelligent Virtual Agents</h3>
  <p class="meta-info"><strong>Booth ID: 8</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Yongho Lee</strong> , <i>Electronics and Telecommunications Research Institute</i>; <strong>Heesook Shin</strong> , <i>Electronics and Telecommunications Research Institute</i>; <strong>Gun A. Lee</strong> , <i>IVE STEM, University of South Australia</i>; <strong>Youn-Hee Gil</strong> , <i>Electronics and Telecommunications Research Institute</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>We present a research demo of an embodied intelligent virtual agent (IVA) for empathic human-agent communication in immersive extended reality (XR). The agent supports low-latency streaming conversation using a commercial artificial intelligence (AI) service and synchronizes speech with viseme-driven lip sync and facial dynamics. During communication, the agent's empathy state and nonverbal behaviors are computed from user interaction data, including gaze, facial expressions, gestures, and vocal features. The empathy state integrates understanding-oriented and affect-oriented components, enabling the agent to express empathic behavior through eye contact, nodding, mimicry, body proximity, and facial expression in a continuous and interpretable manner. Our demo highlights the potential of grounding empathic IVA behavior in empirical observations of externally expressed empathy in dyadic XR commuications.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="NlTil7qQnjc"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">GenAssist: Interactive Prompt-Driven XR Program Generation</h3>
  <p class="meta-info"><strong>Booth ID: 9</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Sruti S Srinidhi</strong> , <i>Carnegie Mellon University</i>; <strong>Akul Singh</strong> , <i>Carnegie Mellon University</i>; <strong>Edward Lu</strong> , <i>Carnegie Mellon University</i>; <strong>Anthony Rowe</strong> , <i>Carnegie Mellon University Bosch Research</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This work demonstrates GenAssist, a system for generating interactive Extended Reality (XR) programs from natural language prompts. Given plain-text descriptions, our system utilizes Retrieval-Augmented Generation (RAG) to fetch relevant documentation and example code, enabling Large Language Models (LLMs) to synthesize and execute XR programs in real time. To ensure outputs align with user specifications, GenAssist incorporates a closed-loop feedback mechanism that uses virtual cameras to inspect the scene and iteratively refine the code, mimicking the manual development cycle of compiling and testing. Beyond static object placement, the system generates functional scripts that animate objects and enable complex user interactions. Our demo showcases the live generation of interactive XR content, allowing users to use voice or text prompts to iteratively build, view, and interact with 3D programs through a headset.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="R1G8fc9G1nI"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">HMD-only Controllable 3D Gaussian Avatars in VR: Face and Full-body Demonstration</h3>
  <p class="meta-info"><strong>Booth ID: 10</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Seokhwan Yang</strong> , <i>KAIST</i>; <strong>Hail Song</strong> , <i>GSCT UVRLab, Korea Advanced Institute of Science and Technology</i>; <strong>Woontack Woo</strong> , <i>KI-ITC ARRC, KAIST</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>We present a VR research demo for practical telepresence with photorealistic 3D Gaussian Splatting (3DGS) avatars under HMD-only sensing. The demo provides two complementary experiences in a single session: a face experience, where headset-provided blendshape signals drive an expressive 3DGS head avatar rendered stereoscopically on the client, and a full-body experience, where a user-specific 3DGS full-body avatar is created from a single image and driven using headset signals. During the demo, participants first capture a single image for full-body avatar creation, experience facial control using a pre-built third-person head avatar while the full-body avatar is generated, and then control their personalized full-body avatar in VR. By enabling both facial and full-body controllability and contrasting two rendering-responsibility designs---client-side direct 3D rendering and server-side stereoscopic image rendering/streaming---the demo offers practical insights for designing responsive, realistic VR telepresence systems with neural primitive avatars.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="2xcV-SPTBg4"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Situately : Embodied Conversational Agent With LLM-Powered Nonverbal Behavior and Object Interaction</h3>
  <p class="meta-info"><strong>Booth ID: 11</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Hyunchul Kim</strong> , <i>KAIST</i>; <strong>Kwang Bin Lee</strong> , <i>Lifelike Avatar and Agent Lab, Graduate School of Culture Technology, Korea Advanced Institute of Science and Technology</i>; <strong>Jungsoo Lee</strong>, <i>Korea Advanced Institute of Science and Technology</i>; <strong>Sihyun Jeong</strong> , <i>Graduate School of Culture Technology, KAIST</i>; <strong>Sung-Hee Lee</strong> , <i>Graduate School of Culture and Technology, Korea Advanced Institute of Science and Technology</i>; <strong>Dr. Jeongmi Lee</strong> , <i>Graduate School of Culture Technology, KAIST</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Embodied conversational agents possess virtual bodies in virtual environments, yet often lack socially and spatially plausible bodily behavior during interaction, leading to reduced social presence. We present a real-time, concurrent framework for embodied conversational agents that controls and coordinates nonverbal behavior and spatially grounded actions beyond verbal interaction alone. Built on large language models and ongoing conversational context, our system enables multimodal control by generating structured outputs for avatar-level nonverbal expression and object interaction. These structured outputs are directly mapped to real-time avatar animations, allowing users to perceive the agent’s nonverbal expressions and object interactions in a shared space. We demonstrate our approach through an interactive virtual environment demo, showing how concurrent multimodal control enhances users’ sense of social presence and the feeling that the agent is "here together."</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="fwZtH-t1kCA"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Experiencing Weight Illusion in AR Extended Displays: A Portable Community Demo</h3>
  <p class="meta-info"><strong>Booth ID: 12</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Hayato Tanabe</strong> , <i>Ritsumeikan University</i>; <strong>Satoshi Hashiguchi</strong> , <i>Ritsumeikan University</i>; <strong>Yuta Kataoka</strong> , <i>Ritsumeikan University</i>; <strong>Prof. Asako Kimura</strong> , <i>Ritsumeikan Univ.,</i>; <strong>Shohei Mori</strong> <i>VISUS , University of Stuttgart</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Augmented reality (AR) design parameters, such as spatial layout and visual delay, are typically optimized for system performance, yet they can also influence human perception. Prior research has shown that visual manipulation alone can alter perceived weight through pseudo-haptic effects, even in the absence of physical feedback. In particular, the perceived weight of AR extended displays (AREDs) has been reported to vary depending on their spatial arrangement relative to a handheld device and the visual delay applied to them. In this demonstration, we present an interactive AR system that enables participants to directly experience how these design parameters affect perceived weight. By transforming a laboratory-level experimental setup into a demonstration-oriented system, participants can freely adjust the layout and visual delay of AREDs in real time and experience corresponding changes in weight perception. This demonstration highlights how subtle system-level design choices in AREDs can shape perceptual experiences and provides an accessible platform for exploring pseudo-weight illusions beyond controlled experimental settings.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="4X-7aQ4rEUU"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">LOCOMO-Play: Gamification of Sustainable Artificial Intelligence Use in Augmented Reality</h3>
  <p class="meta-info"><strong>Booth ID: 13</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Somang Nam</strong> , <i>Faculty of Computer Science and Technology, Algoma University</i>; <strong>Hyunggu Jung</strong> , <i>Seoul National University, Seoul, Korea, Republic of Seoul National University Hospital</i>; <strong>Mr. Yunseo Moon</strong> , <i>Department of Computer Science and Engineering, University of Seoul</i>; <strong>Dr Seilin S Uhm</strong> , <i>Faculty of Environmental and Life Sciences, University of Southampton</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>The growing use of large language models (LLMs) in Extended Reality has brought attention to the significant energy demand and carbon output produced during inference, yet most people who use these systems are unaware of these environmental impacts. To address this, we introduce LOCOMO (LOwer COnsumption, More Optimization)-Play, a gamified augmented reality application which encourages more sustainable AI interactions by turn- ing prompt compression into a playful task. The tool combines real-time computer vision with LLM-based reasoning and lets users collect Sustainability Points and unlock rewards for writing shorter, energy-efficient prompts. By showing easy to understand carbon comparisons and offering instant responses, LOCOMO-Play helps users learn how to reduce their carbon footprint.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="3H0BLDD6FcA"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">NutriFilter: VLM-Driven Dietary Augmentation in XR Passthrough Environments</h3>
  <p class="meta-info"><strong>Booth ID: 14</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Taegeun Yoon</strong> , <i>Taejon Christian International School,</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Managing strict medical dietary restrictions imposes a severe cognitive load, which often leads to decision fatigue. We present NutriFilter, a novel mediated reality framework that modulates the visual saliency of restricted foods within a mixed reality environment. Our research explored the visual saliency options, like chromatic alteration, Gaussian blurring, and total occlusion. We developed a proof-of-concept prototype to demonstrate the feasibility of utilizing a vision-language model to enhance the food scene. By dynamically filtering visual stimuli to visually mask items, NutriFilter demonstrates the efficacy of context-aware Extended Reality interfaces in mitigating cognitive burden and supporting adherence to complex dietary protocols.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="gEIaCbBCpRs"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Enabling natural interactions with virtual humans in XR via real-time human action recognition</h3>
  <p class="meta-info"><strong>Booth ID: 15</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Hannes Fassold</strong>, <i>JOANNEUM RESEARCH, DIGITAL,</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>As Extended Reality (XR) applications evolve from passive viewing experiences to interactive simulations, the behavior of virtual humans becomes a critical factor for immersion. Users expect them to react naturally to their movements, yet implementing robust action recognition and its integration into a VR application remains a challenging task. This paper introduces a modular toolkit designed to bridge this gap. By decoupling the rendering loop from the inference process, our system allows for a sophisticated deep learning-based detection of user actions (such as hand waving or crossing hands) without compromising the frame rate of the XR experience. We present the system architecture and its integration into the Unity engine, and describe the demo applications we developed.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="i12LjsBs420"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">TwinHaus: Digital Twin Design Tool for Sustainable Building Construction</h3>
  <p class="meta-info"><strong>Booth ID: 16</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Somang Nam</strong> , <i>Algoma University</i>; <strong>Joel Saji Varghese</strong>, <i> Algoma University</i>; <strong>Aanya Goel</strong>, <i>Algoma University</i>; <strong>Hyunggu Jung</strong>, <i>Seoul National University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>As the construction industry increasingly prioritizes sustainability, the need for immersive tools that can visualize and analyze complex building performance factors has become essential. Many existing design solutions rely on static reports or 2D simulations, which fail to convey the spatial and dynamic nature of airflow, water consumption, and heat transfer within architectural spaces. We present TwinHaus, a unified digital twin framework that operates across Augmented and Virtual Reality to make these invisible environmental phenomena perceptible in real time. The system integrates heuristic particle-based airflow simulation, fixture-linked water consumption visualization, and raycasting-driven thermodynamic modelling to reflect user interactions within a sustainable housing unit dynamically. A comprehensive environmental dashboard further connects these simulations to quantifiable metrics, allowing data-informed decisions to be made during the design process. The system demonstrates how immersive extended-reality tools can support architects and engineers in optimizing sustainable building performance early in the development cycle.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="UdONtatZ5QY"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">ResXR: An Open-Source Toolkit for Standardized XR Behavioral Research</h3>
  <p class="meta-info"><strong>Booth ID: 17</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Mr. Yehuda Bergstein</strong> , <i>School of Neurobiology, Biochemistry and Biophysics, Tel Aviv University</i>; <strong>Noa Barel</strong>, <i>School of Neurobiology, Biochemistry and Biophysics, Tel Aviv University, Tel Aviv, Israel</i>; <strong>Mr. Omri Bromberg</strong> , <i>School of Neurobiology, Biochemistry and Biophysics, Tel Aviv University, Tel Aviv, Israel</i>; <strong>Ms. Galia Shai Basson</strong> , <i>School of Neurobiology, Biochemistry and Biophysics, Tel Aviv University, Tel Aviv, Israel</i>; <strong>Tom Schonberg</strong> <i>Sagol , School of Neuroscience, Tel Aviv University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Extended Reality (XR) offers unique opportunities for behavioral and psychological research by combining experimental control with ecological validity. However, widespread adoption for research is hindered by high technical barriers and the absence of standardized data formats. To address this gap, we present ResXR, an end-to-end open source software project for conducting behavioral XR experiments. ResXR provides a Unity-based experiment template for multimodal data capture (head, hand, eye, and face tracking from Meta’s Quest Pro head mounted display) alongside a Python processing pipeline that automates the creation of a standardized data structure, validation, preprocessing, and quality reporting, inspired by established neuroimaging data formats and tools like fMRIPrep. By lowering entry barriers and promoting reproducibility, ResXR positions standalone headsets as accessible "human research mobile laboratories" for rigorous XR research.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="tK_l0BTGtuY"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">ChromaXR: Enhancing Color Perception for Users with Color Vision Deficiency</h3>
  <p class="meta-info"><strong>Booth ID: 18</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Rafael Alves Goiás</strong> , <i>Advanced Knowledge Center in Immersive Technologies (AKCIT), Goiânia, Goiás, Brazil Federal University of Goiás</i>; <strong>Lucas Lima Neves</strong> , <i>Advanced Knowledge Center in Immersive Technologies (AKCIT), Goiânia, Goiás, Brazil Federal University of Goiás</i>; <strong>Paulo Vitor Santana da Silva</strong> , <i>Advanced Knowledge Center in Immersive Technologies (AKCIT), Goiânia, Federal University of Goiás, Goiânia</i>; <strong>Gustavo Webster</strong> , <i>Advanced Knowledge Center in Immersive Technology</i>; <strong>Davi Duarte de Freitas</strong> , <i>Advanced Knowledge Center in Immersive Technologies (AKCIT), Goiânia, UFRN, Natal</i>; <strong>Dr. Rafael Teixeira Sousa</strong> , <i>Advanced Knowledge Center in Immersive Technologies (AKCIT), Goiânia, Brazil Federal University of Mato Grosso</i>; <strong>ARLINDO GALVÃO</strong> , <i>Advanced Knowledge Center in Immersive Technologies (AKCIT), Goiânia, Goiás, Brazil Federal University of Goias, Goiânia</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This demo introduces an extended reality (XR) system designed to enhance environmental perception for individuals with Color Vision Deficiency (CVD). The system leverages a hybrid workflow: first, users perform a digital implementation of the Farnsworth D-15 Arrangement Test within a fully immersive Virtual Reality (VR) environment to ensure controlled lighting and diagnostic precision. Based on this assessment, the system generates a personalized visual profile, which is then applied as a tailored, static compensation filter in an Augmented Reality (AR) setting. This overlay optimizes color contrast and discrimination in the user’s real-world field of view. At the demonstration venue, participants can experience the full XR pipeline, transitioning from VR-based calibration to AR-assisted vision, showcasing the potential of cross-reality tools as scientifically-grounded assistive technologies.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="m1wlzWSjIOs"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">A Tangible Mixed Reality System for 3D Modeling</h3>
  <p class="meta-info"><strong>Booth ID: 19</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Mohd Zubair</strong> , <i>Creative Interfaces Lab, Indraprastha Institute of Information Technology Delhi</i>; <strong>Vishal Bharti</strong>, <i>Creative Interfaces Lab, Indraprastha Institute of Information Technology Delhi</i>; <strong>Anmol Srivastava</strong>, <i>Creative Interfaces Lab, Indraprastha Institute of Information Technology Delhi</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>3D modeling using traditional computer-aided design (CAD) tools often poses challenges, particularly to novice users. Several prior works have explored virtual reality-based CAD systems. However, most face major problems such as loss of accuracy. To address these challenges, we present BoxCraft a tangible mixed-reality (MR) system for intuitive 3D modeling with two modalities. BoxCraft allows users to create and edit 3D models in an MR space by using physical tokens enhanced with visual overlays for immediate spatial feedback. We have conducted a participatory design workshop (n = 6) and an early user study (n = 7) to explore interaction design options and user experience. Preliminary results show that, although tangible token-based interaction requires a longer initial learning phase, participants, especially beginners, preferred it over controller-based interaction and traditional CAD tools for reductions in cognitive load. This research demo presents the BoxCraft system, its interaction techniques, and initial user feedback, pointing out the potential of tangible MR interfaces in making 3D modeling more accessible.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="3ENmTwRC7kk"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Fast Digitization in XR of Reality-Linked Gaussian-Splatted Proxies</h3>
  <p class="meta-info"><strong>Booth ID: 20</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Benjamin Yang</strong> , <i>Department of Computer Science, Columbia University</i>; <strong>Shanying Liu</strong> , <i>Department of Computer Science, Columbia University</i>; <strong>Kirthana Natarajan</strong> , <i>Department of Computer Science, Columbia University</i>; <strong>Steven Feiner</strong> , <i>Department of Computer Science, Columbia University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Capturing real objects as interactive 3D assets in XR typically requires offline photogrammetry. We present Gaussian-Splatted Proxies, a system for fast object digitization in XR using feed-forward 3D Gaussian splatting. With a Quest 3 headset, users select objects detected by the system through the passthrough cameras, then capture images that an edge server reconstructs as interactive Gausasian splats. Our system extracts individual objects from scene reconstructions without any per-scene training by projecting detection bounding boxes into 3D space. The resulting assets can be grabbed, inspected, rotated, and used to select the corresponding objects in the physical world.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="orx3gFPBNpA"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">With Lily: Design and Implementation of Verbal and Nonverbal Interaction with a Virtual Humanoid in Mixed Reality for Affective Communication</h3>
  <p class="meta-info"><strong>Booth ID: 21</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Taehyun Kim</strong> , <i>Sogang University, Art & Technology</i>; <strong>Yongsoon Choi</strong> , <i>Art &Technology, Sogang Univ</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This demo presents a virtual humanoid in a mixed reality (MR) environment designed to support emotional communication through integrated verbal and nonverbal interactions. The goal of this work is to enable users to engage in comfortable and enjoyable conversations with a virtual entity, free from the social pressures of real-world relationships, thereby promoting psychological ease and emotional stability. To this end, the demo introduces a comprehensive design and implementation of verbal and nonverbal interaction techniques that allow the virtual humanoid to express emotions and intentions in a natural manner. In addition, we present an integrated approach that encompasses environmental design, conversational strategies, and the construction of a virtual personality, all aimed at fostering user motivation for communication and deep emotional immersion.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="pGuwNVslvRE"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">SentiSing: A Real-Time Affective Feedback System for Immersive Karaoke in Virtual Reality</h3>
  <p class="meta-info"><strong>Booth ID: 22</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Qingzhu Zhang</strong> , <i>University of California, Berkeley</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This paper presents a VR karaoke system that treats voice as a continuous affective input for immersive environmental feedback. Vocal and musical affect are analyzed as joint control signals, mapped to generative visual dynamics in a virtual forest. Arousal and valence function as expressive parameters governing growth, color, and atmospheric change. Users perceive how variations in vocal expression and musical emotion shape evolving environmental responses in real time. This work explores the design space of affect-driven VR music interaction, showing how coupled vocal and musical affect can support expressive engagement in immersive singing.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="QkYn7hEvvmU"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Voice-Based Access Control in Virtual Reality Using Natural Conversational Speaker Verification</h3>
  <p class="meta-info"><strong>Booth ID: 23</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Andressa Araújo</strong> , <i>Bastos Advanced Knowledge Center in Immersive Technology - AKCIT, Goiânia</i>; <strong>Alexandre Costa Ferro Filho</strong> , <i>Advanced Knowledge Center for Immersive Technologies, Goiânia, Brazil Federal University of Goias</i>; <strong>Dr. Rafael Teixeira Sousa</strong> , <i>Federal University of Mato Grosso</i>; <strong>ARLINDO GALVÃO</strong> , <i>Federal University of Goias, Goiânia</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Voice-based biometric authentication offers a natural and hands-free alternative for access control in immersive Virtual Reality (VR) environments. We present a VR-based access control demo in which a non-player character (NPC) acts as a virtual gatekeeper, authenticating users through conversational speaker verification. Instead of explicit enrollment procedures or predefined passphrases, the system leverages a short, natural greeting exchange to perform speaker verification and, when necessary, seamless enrollment. The demo illustrates how voice biometrics can be integrated into VR in a user-friendly manner, preserving immersion while enabling secure and personalized access control.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="n017pkLqMz4"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Pulling Illusion Induced by Asymmetric Vibration with Visual Motion Cues</h3>
  <p class="meta-info"><strong>Booth ID: 24</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Keigo Hattori</strong> , <i>Ritsumeikan University</i>; <strong>Satoshi Hashiguchi</strong> , <i>Ritsumeikan University</i>; <strong>Takeshi Tanabe</strong> , <i>National Institute of Advanced Industrial Science and Technology (AIST)</i>; <strong>Tomohiro Amemiya</strong> , <i>The University of Tokyo</i>; <strong>Fumihisa Shibata</strong> , <i>College of Information Science and Engineering, Ritsumeikan University</i>; <strong>Prof. Asako Kimura</strong> , <i>Ritsumeikan Univ</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>In this demo paper, we present a VR system that combines vibrotactile feedback with visual motion cues to demonstrate the illusory pulling sensation induced by asymmetric vibration. The demo allows users to experience illusory pulling sensation without applyingphysical external forces, using a lightweight and ungrounded setup. The system features a simplified visual scene in which object motion provides an interpretable causal context for vibrotactile stimulation. By synchronizing asymmetric or symmetric vibration with object movement, users can directly experience how visual context relates to the perception of pulling sensations. Our demo illustrates possibilities for designing illusory pulling sensations supported by visually interpretable motion cues, and suggests how visual causality can influence the interpretation of vibrotactile feedback in VR experiences.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="ut6Kv4ZLSVE"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">MirroringWay: Designing an Inter-World Transition Method with Materialized Mirror Imagery</h3>
  <p class="meta-info"><strong>Booth ID: 25</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Niko Igarash i</strong>, <i>Nakanishi lab, Keio University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This study explores a novel transition method for enabling experiences that traverse multiple types of worlds, including real, virtual reality (VR), and augmented reality (AR). As one such approach, we designed MirroringWay, a transition method that employs a mirror as the mediating element. MirroringWay reproduces within VR mirror-generated imagery resembling an endlessly extending space produced by a facing-mirror configuration and materializes it as a traversable transition space. As a fundamental evaluation of this method, we conducted a user study focusing on transitions from a real environment to a VR environment, examining whether mirror-based movement can function as a valid transition experience.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="0siRHU_NVWE"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">BossPlz: An Accessible, Multi-Sensory Interactive Virtual Reality (VR) Experience for Extreme Natural Environments</h3>
  <p class="meta-info"><strong>Booth ID: 26</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Jiayi Wu</strong> , <i>University of the Arts, London, London, United Kingdom The Hong Kong University of Science and Technology (Guangzhou)</i>; <strong>Sheng Mai</strong> , <i>University College London</i>; <strong>Mr Wang Shangyang</strong> , <i>Sun Yat-sen University</i>; <strong>Shanshan zhang</strong> , <i>University of the arts London</i>; <strong>Dr. Yuyang Wang</strong> , <i>The Hong Kong University of Science and Technology (Guangzhou),</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Virtual Reality (VR) simulators often lack physical interference, limiting their use for training in challenging natural or extreme environments. We present a multi-sensory VR system using integrated aero-haptic (wind) and thermal (heat) feedback. Unlike traditional systems focused on passive immersion, our system models environmental forces as an active physical antagonist. The user must perform a fine-motor task (e.g., shielding a flame from wind) while managing this dynamic interference. This work contributes a low-cost, accessible hardware setup and a new interaction paradigm focused on active physical, rather than cognitive, interference management.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="1aaXkyJdNug"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">VR Zen Garden: Designing Virtual Environment for Stress Relief</h3>
  <p class="meta-info"><strong>Booth ID: 27</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Hail Song</strong>, <i>GSCT UVRLab, Korea Advanced Institute of Science and Technology</i>; <strong>Jinseok Hong</strong> , <i>UVR Lab, KAIST</i>; <strong>Seonji Kim</strong> , <i>UVR Lab, KAIST</i>; <strong>Kyung Taek Oh</strong> , <i>GSCT, KAIST</i>; <strong>Woontack Woo</strong> , <i>KI-ITC ARRC, KAIST, Daejeon, Korea, Republic of UVR Lab., KAIST</i>; <strong>Sungyoung Kim</strong> , <i>Applied and Innovative Research for Immersive Sound Lab, Graduate School of Culture Technology, Korea Advanced Institute of Science and Technology, Department of Electrical and Computer Engineering Technology, College of Engineering Technology, Rochester Institute of Technology</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>We propose VR Zen Garden, a virtual reality (VR) application designed to support stress relief and meditation through interactive spatial soundscapes. The system enables users to create personalized auditory environments by combining two key interactions: Object Placement, which spatializes sound-emitting objects, and Sand Pattern Raking, which modulates sound properties through visual patterns. These inputs are processed by the Sound Spatializer and the Metaphoric Sound Mixer, allowing users to intuitively shape immersive 3D soundscapes in real time. VR Zen Garden offers an engaging and embodied approach to mindfulness, highlighting the potential of sound-driven design in immersive wellness applications.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="n2F5Gs9k41k"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">ChronoShore: Exploring Short- and Long-Term Environmental Time in a Virtual Coastal Ecosystem</h3>
  <p class="meta-info"><strong>Booth ID: 28</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Lucca Troll</strong> , <i>University of Trier</i>; <strong>Yuen C. Law</strong> , <i>Costa Rica Institute of Technology</i>; <strong>Daniel Zielasko</strong> , <i>Technical University of Denmark</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>We present an extended version of ChronoShore, an immersive virtual reality (VR) environment for interacting with environmental time at multiple temporal scales. The system is situated in a high-fidelity simulation of a coastal region in Costa Rica, reconstructed from geological and topographical data using a multi-level-of-detail approach. Unlike conventional timeline-based controls, ChronoShore enables users to explore and manipulate time through diegetic environmental cues, or zeitgebers, embedded directly in the virtual world. In addition to short-term time control via celestial bodies such as the sun and moon, the new version introduces long-term temporal interaction through vegetation, particularly trees, allowing users to traverse years or decades within the simulation. The environment features an enhanced weather model with realistic seasonal dynamics, including rain patterns and cloud morphologies that evolve over the course of the day in response to atmospheric conditions. ChronoShore serves as a research and application platform for studying time perception in VR, immersive storytelling of geological and environmental processes, and relaxation-oriented experiences. The platform is available to other researchers upon request.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="5dZuX5zkEvs"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Demonstrating Controller-Free Mixed Reality X-Ray Machine Training</h3>
  <p class="meta-info"><strong>Booth ID: 29</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Youngseo Kim</strong> , <i>Graduate School of Virtual Convergence, Sogang University</i>; <strong>Hongik Jeon</strong> , <i>Graduate School of Virtual Convergence, Sogang University</i>; <strong>Seunggwan Choi</strong> , <i>Graduate School of Virtual Convergence, Sogang University</i>; <strong>Prof. Sanghun Park</strong> , <i>Graduate School of Virtual Convergence, Sogang University</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>We demonstrate a controller-free, Mixed Reality training system that enables hands-on X-ray machine operation through natural hand interaction. The system addresses key limitations of conventional medical device training, including restricted physical access, high equipment costs, and radiation exposure risks. By leveragingoptical hand tracking on a standalone head-mounted display, users can interact with a virtual X-ray machine using gestures that closely resemble real-world operation. A central component of the demo is a Virtual Tablet interface, which provides video-based operational guidance and allows users to seamlessly select and execute trainingscenarios for different patient postures. All interactions—including device manipulation and user interface navigation—are performed entirely through hand tracking, enabling immediate, walk-up use without controllers or calibration overhead. The system is designed specifically for live demo settings, allowing first-time users to experience realistic medical device operation within minutes. Informal user feedback from nursing students and clinical professionals indicates high engagement, strong perceived realism, and clear potential for scalable deployment in medical education and clinical training environments.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="ucrnKScKxaA"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Demonstration of Visuo-Haptic Redirection in Above-surface Drawing with an Extendable Pen</h3>
  <p class="meta-info"><strong>Booth ID: 30</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Fumihiko Nakamura</strong> , <i>College of Information Science and Engineering, Ritsumeikan University</i>; <strong>Hinata Miyauchi</strong> , <i>Ritsumeikan University</i>; <strong>Yuta Kataoka</strong> , <i>Ritsumeikan University</i>; <strong>Fumihisa Shibata</strong> , <i>College of Information Science and Engineering, Ritsumeikan University</i>; <strong>Prof. Asako Kimura</strong> , <i>Ritsumeikan, Univ</i>; <strong>Shohei Mori</strong> , <i>VISUS, University of Stuttgart</i>;</p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Virtual reality (VR) enables drawing with fewer constraints than conventional media. However, the absence of physical drawing surfaces results in a lack of haptic feedback and physical support, which are essential for drawing. To address this limitation, we present an above-surface drawing technique that integrates visuo-haptic redirection with an encountered haptic feedback via an extendable pen. Our approach physically renders contact by extending the pen tip to a physical desk surface while visually redirecting the virtual pen position, thereby shifting the perceived contact point along the height direction. By leveraging visuo-haptic illusion, this technique expands the drawable interaction space beyond the mechanical limits of the device while preserving the sensation of physical contact. We demonstrate our system through a VR drawing scenario involving both linearly and non-linearly varying surface geometries, allowing users to experience above-surface drawing with encountered haptics under different redirection conditions.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="p8iShhpPRJQ"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Seeing the Real Me: Experiencing Real-Body Pass-Through Embodiment and Interaction</h3>
  <p class="meta-info"><strong>Booth ID: 31</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>Kristoffer Waldow</strong> , <i>Computer Graphics Group, TH Köln, Köln, Germany School of Medicine and Health, Technical University of Munich</i>; <strong>Arnulph Fuhrmann</strong> , <i>Computer Graphics Group, TH Köln</i>; <strong>Prof. Dr. Daniel Roth</strong> , <i>Human-Centered Computing and Extended Reality Lab, Technical University of Munich</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>Embodiment is fundamental to immersive VR, yet traditional avatars often suffer from perceptual mismatches. Pass-Through Embodiment (PTE) addresses this by integrating a stereoscopic live video feed of the user’s body into the virtual environment. By combining depth-based segmentation with video-see-through streams, PTE provides a high-fidelity, photon-captured representation. We present the first public PTE demonstration, allowing users to perceive themselves while interacting with diverse virtual scenes. Participants can evaluate how their body, different edge rendering, and environmental contexts affect visual coherence in real-time. This demonstrates how PTE facilitates a naturally anchored sense of embodiment, bridging physical and virtual worlds through natural interaction.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="PGQpbg4mNK4"></div>
  </div>
</div>

<div class="paper-section">
  <h3 class="session-id-tag">Hands-on Fragility: A Multi-Modal Pseudo-Haptic System for Delicate Interaction in VR</h3>
  <p class="meta-info"><strong>Booth ID: 32</strong></p>
  <p class="meta-info"><strong>Author</strong><br/><strong>João Anisio J.A Marinho Nobrega Da</strong>, <i>AKCIT - Game Lab, Federal University of Rio Grande do Norte</i>; <strong>Davi Duarte de Freitas</strong> , <i>UFRN, Natal</i>; <strong>Marcos Arthur da Silva Melo</strong>, <i>IMD, UFRN - Universidade Federal do Rio Grande do Norte, Natal</i>; <strong>Gabriel Lucena</strong>, <i>UFRN, Natal, Rio Grande do Norte</i> ; <strong>Alyson Souza</strong>, <i>AKCIT-IMD, Digital Metropolis Institute, Federal University of Rio Grande do Norte</i></p>
  
  <div class="abstract-wrapper">
    <div class="abstract-toggle" onClick="toggleAbstract(this)"><strong>Abstract</strong> <span class="arrow">▼</span></div>
    <div class="abstract-content">
      <p>This research demo presents a multi-modal pseudo-haptic system designed to simulate object fragility in Virtual Reality (VR) using bare-hand interaction. While consumer VR lacks granular haptic feedback, our system employs a procedural cracking shader, stress-dependent audio, and a diegetic UI to elicit a sense of "care" in users. A user study (N=31) confirms that these software-driven cues allow users to distinguish between fragility levels and significantly alter their motor behavior. This demonstration allows participants to experience this psychological tension firsthand through a series of pick-and-place tasks, providing a novel framework for handling delicate virtual artifacts without specialized hardware.</p>
    </div>
  </div>

  <div class="video-container">
    <div class="youtube-player" data-id="pEs84eRFmz0"></div>
  </div>
</div>

<script>
// 초록 내용 토글 함수
function toggleAbstract(element) {
    element.classList.toggle("open");
    var content = element.nextElementSibling;
    if (content.style.display === "block") {
        content.style.display = "none";
    } else {
        content.style.display = "block";
    }
}

// 유튜브 썸네일 선로딩(Facade 패턴) 및 클릭 시 iframe 렌더링 스크립트
document.addEventListener("DOMContentLoaded", function() {
    var players = document.querySelectorAll(".youtube-player");
    
    players.forEach(function(player) {
        // 1. data-id 값을 가져와 유튜브 고화질 썸네일 이미지 설정
        var videoId = player.getAttribute("data-id");
        player.style.backgroundImage = "url('https://i.ytimg.com/vi/" + videoId + "/hqdefault.jpg')";
        
        // 2. 사용자가 썸네일을 클릭하면 실제 iframe을 생성해서 대체
        player.addEventListener("click", function() {
            var iframe = document.createElement("iframe");
            iframe.setAttribute("src", "https://www.youtube.com/embed/" + videoId + "?autoplay=1");
            iframe.setAttribute("frameborder", "0");
            iframe.setAttribute("allowfullscreen", "1");
            iframe.setAttribute("allow", "accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture");
            
            // CSS 클래스 유지하면서 요소 교체
            iframe.style.position = "absolute";
            iframe.style.top = "0";
            iframe.style.left = "0";
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "0";
            
            this.parentNode.replaceChild(iframe, this);
        });
    });
});
</script>
