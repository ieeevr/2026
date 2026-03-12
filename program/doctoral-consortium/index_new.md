---
layout: ieeevr-default
title: "Doctoral Consortium"
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
    font-size: 1.1rem;
}

td {
    font-size: 0.8rem;
    border-bottom: 1px solid #eee !important;
    padding: 15px 25px;
    text-align: center;
    word-wrap: break-word;
    vertical-align: middle;
}   

.time-col {
    background-color: #F2F2F2;
    font-weight: bold;
    color: #333;
    font-size: 0.7rem;
    line-height: 1.4;
}

.type-Parallel {
    transition: background 0.2s;
    text-align: left;
}

.type-Parallel:hover {
    background-color: #f3f3f3;
}

.session-link {
    text-decoration: none;
    color: inherit;
    display: block;
    width: 100%;
    height: 100%;
    font-weight: bold;
}

.session-link:hover {
    text-decoration: underline;
}

#session-details {
    margin-top: 50px;
}

.session-container {
    margin-bottom: 25px;
    padding-top: 20px;
}

.session-title-wrapper {
    margin: 5px 0;
}

.session-id-tag {
    font-size: 1.4rem;
    color: #262188;
    font-weight: bold;
}

.session-name-title {
    font-size: 1.4rem;
    font-weight: bold;
    color: #262188;
}

.session-chair-text {
    font-size: 0.8rem;
    color: #444;
}

.session-chair-text.last {
    margin-bottom: 15px; 
}

.paper-block {
    padding: 12px 0;
    font-size: 0.8rem;
    line-height: 1.6;
}

.paper-item {
    padding-left: 14px;  
    margin-bottom: 4px;
}

.paper-id-text {
    display: none;
}

.paper-title-text {
    font-weight: bold;
    color: #000;
}

.toggle-btn {
    cursor: pointer;
    color: #262188;
    font-weight: bold;
    user-select: none;
    display: inline-block;
    margin-top: 5px;
    text-indent: 0;
}

.toggle-btn:hover {
    text-decoration: underline;
}

.toggle-content {
    display: none;
    margin-top: 5px;
    padding-left: 10px;
    color: #444;
    text-indent: 0;
    line-height: 1.5;
    font-size: 0.7rem
}

.toggle-content.show {
    display: block;
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

.key-info-box {
    background: #f9f9f9;
    border-left: 4px solid #262188;
    padding: 15px 20px;
    margin-bottom: 30px;
    font-size: 0.9rem;
    line-height: 1.6;
}
</style>

<p class="big_title">Doctoral Consortium</p>

<div class="key-info-box">
    <strong>Key Information</strong><br>
    The Doctoral Consortium will be held on 21 March 2026 (Saturday) in “ 325D ” room. All times below are given in local time of Korea (UTC+9).<br><br>
    Here are the key information for the presenters and mentors:
    <ul>
        <li>Each presentation includes a 10-minute talk + 5-minute Q&A.</li>
        <li>All presenters and mentors need to be present at the scheduled session and are encouraged to attend as much of the doctoral consortium as possible.</li>
        <li>After each session, the mentors and students can use the ” 327 ” room to further breakout discussions and mentoring during Break/Lunch time.</li>
        <li>Because some mentors cannot attend the conference in person, we recommend that the students take the initiative to reach out to allocated mentors and arrange a separate online meeting for mentoring.</li>
        <li>The venue for the DC track is: “ 325D ” room.</li>
        <li>The presentation and mentoring at the DC mark the start of collaborations and we strongly recommend that the presenters and mentors hold periodical meetings to deepen the collaborations.</li>
    </ul>
    In the following schedule, the student is mentioned first followed by the associated mentors.
</div>

<div id="schedule-tables"></div>
<div id="session-details"></div>

<script>
const psData = {
  "1": [
    { 
      "id": 1, 
      "name": "DC Session 1", 
      "chair": "", 
      "papers": [ 
        { "id": "1062", "title": "[DC] VR Ecology: Relational Haptic Co-Creation for Kinaesthetic Creativity in XR", "authors": "<b>Mentee:</b> Vollmer, S.C. (Department of Computational Arts, York University, Toronto, Canada)<br><b>Mentor:</b> Jen-Shuo Liu (Columbia University)" }, 
        { "id": "1224", "title": "[DC] Investigating Eye-Body Coupling and Gaze Adaptation in Virtual Reality", "authors": "<b>Mentee:</b> Anvari, Taravat (Institute for Psychology, University of Muenster, Muenster, Germany)<br><b>Mentor:</b> Jean Botev (VR/AR Lab, University of Luxembourg)" }, 
        { "id": "1238", "title": "[DC]Toward Adaptive and Accessible XR Through User and Context Modeling", "authors": "<b>Mentee:</b> Wu, Zhiqing (Computational Media and Arts Thrust, The Hong Kong University of Science and Technology (Guangzhou), Guangzhou, Guangdong, China)<br><b>Mentor:</b> Alejandro Martin Gomez (University of Arkansas)" }, 
        { "id": "1240", "title": "[DC]From Being There to Acting There: A Motor Learning Perspective on Reconceptualizing VR Interaction", "authors": "<b>Mentee:</b> Xiao, Cleo (Department of Computer Science, University of Copenhagen, Copenhagen, Denmark)<br><b>Mentor:</b> Regis Kopper (Iowa State University)" }, 
        { "id": "1246", "title": "[DC] Improving XR Training and Collaboration Through Shared, Self, and Mediated Awareness", "authors": "<b>Mentee:</b> Catarina Gonçalves Fidalgo (Human-Computer Interaction Institute, Carnegie Mellon University, Pittsburgh, Pennsylvania, United States & Instituto Superior Técnico, University of Lisbon, Lisbon, Portugal)<br><b>Mentor:</b> Rashid Ali (Department of Engineering Science, University West, Sweden)" } 
      ] 
    }
  ],
  "2": [
    { 
      "id": 2, 
      "name": "DC Session 2", 
      "chair": "", 
      "papers": [ 
        { "id": "1249", "title": "[DC] Beyond Visual Dominance: Haptics as Social Cues for Enhanced Multi-User Experiences in VR", "authors": "<b>Mentee:</b> Jang, Hyuckjin (Graduate School of Culture Technology, KAIST, Daejeon, Korea, Republic of)<br><b>Mentor:</b> Yan Hu (Blekinge Institute of Technology, Sweden)" }, 
        { "id": "1258", "title": "[DC] Adaptive Visual Complexity in VR Training: An Eye-Tracking Approach to Detecting and Regulating Embodied Cognitive Load", "authors": "<b>Mentee:</b> Nasri, Mahsa (Northeastern University, Boston, Massachusetts, United States)<br><b>Mentor:</b> Tim Dwyer (Monash University, Australia)" }, 
        { "id": "1260", "title": "[DC] Enhancing Accessibility and User Experience of Virtual Reality Locomotion for Older Adults", "authors": "<b>Mentee:</b> Chong, Kit-Ying Angela (Systems Design Engineering/TAG lab, University of Waterloo, Waterloo, Ontario, Canada)<br><b>Mentor:</b> Daniel A. Muñoz (Hong Kong Baptist University)" }, 
        { "id": "1263", "title": "[DC] Immersive disorientation - Visualizing Dolly Zoom through Counter-Invariant Perception in Cinematic Virtual Reality", "authors": "<b>Mentee:</b> Fong, Andrew (School of Creative Media, City University of Hong Kong, Hong Kong)<br><b>Mentor:</b> Shohei Mori (University of Stuttgart)" }, 
        { "id": "1265", "title": "[DC] Virtual Reality for Mental Health: Toward Bioadaptive Narrative and Sensory Feedback Systems", "authors": "<b>Mentee:</b> Olofsson, Max (Gothenburg University, Institute of Neuroscience and Physiology, Gothenburg, Sweden)<br><b>Mentor:</b> Majed Elwardy (Blekinge Institute of Technology)" } 
      ] 
    }
  ],
  "3": [
    { 
      "id": 3, 
      "name": "DC Session 3", 
      "chair": "", 
      "papers": [ 
        { "id": "1267", "title": "[DC] Towards Universal Access: Building a Cross-Device Mixed Reality Ecosystem", "authors": "<b>Mentee:</b> Becerril Palma, Paulina (Department of Information Science and Media Studies, University of Bergen, Bergen, Norway)<br><b>Mentor:</b> Richard (Rick) Skarbez (La Trobe University)" }, 
        { "id": "1268", "title": "[DC] Visual Perception Enhancement via Transient Visual Cue in Immersive Virtual Reality", "authors": "<b>Mentee:</b> Kim, DongHoon (Computer Science, Utah State University, Logan, Utah, United States)<br><b>Mentor:</b> Tim Weissker (RWTH Aachen University)" }, 
        { "id": "1274", "title": "[DC] Augmented Co-Embodiment for Motor Skill Learning with Held Tools in Virtual Reality", "authors": "<b>Mentee:</b> Morell, Jean (CAOR, Mines Paris, Paris, France)<br><b>Mentor:</b> Steve Feiner (Columbia University)" }, 
        { "id": "1276", "title": "[DC] Virtual Reality and Beyond: Exploring the Design and User Experience of Augmented Social Touch in VR", "authors": "<b>Mentee:</b> Tietenberg, Julius (Faculty of Computer Science / Department of Human-centered Computing and Cognitive Science (HCCS) / Entertainment Computing Group, University of Duisburg-Essen, Duisburg, Germany)<br><b>Mentor:</b> Sasha Alexdottir (Department of NCCA, Faculty of Media, Science and Technology, Bournemouth University, UK)" }, 
        { "id": "1278", "title": "[DC] Personality and Affective States in Virtual Reality: A Multi-Study Program on Awe, Acute Stress, and Trust", "authors": "<b>Mentee:</b> Steininger, Melissa (Department of Epileptology, University Hospital Bonn, Bonn, Germany)<br><b>Mentor:</b> Manuela Chessa (University of Genoa, Italy)" } 
      ] 
    }
  ],
  "4": [
    { 
      "id": 4, 
      "name": "DC Session 4", 
      "chair": "", 
      "papers": [ 
        { "id": "1279", "title": "[DC] Mixed Reality for Psychological Resilience: A Conceptual Framework for Rescue Training in combination with ACT", "authors": "<b>Mentee:</b> Kastner, Kevin (CeMOS – Research and Transfer Center, Technical University of Applied Sciences Mannheim, Mannheim, Germany)<br><b>Mentor:</b> Ali Haskins (University of Central Florida)" }, 
        { "id": "1287", "title": "[DC] Self Adaptive 3D User Interfaces", "authors": "<b>Mentee:</b> Argo, Erin (Augusta University, Augusta, Georgia, United States)<br><b>Mentor:</b> Jinghui Hu (Lancaster University)" }, 
        { "id": "1291", "title": "[DC] Agency-Preserving AI Mediation (APAM) Supporting Self-Directed Learning in Augmented Reality", "authors": "<b>Mentee:</b> Schwertfeger, Sharmen (School of Computer & Cyber Sciences, Augusta University, Augusta, Georgia, United States)<br><b>Mentor:</b> Ye Pan (Shanghai Jiao Tong University)" }, 
        { "id": "1298", "title": "[DC] Road-map to Efficient Attention Guided Augmented Reality User Interfaces: From Controlled Environments to the Wild", "authors": "<b>Mentee:</b> Ahmed, Tanim (Computer Science/IRLab, Iowa State University, Ames, Iowa, United States)<br><b>Mentor:</b> Jeanine Stefanucci (University of Utah)" } 
      ] 
    }
  ]
};

const scheduleMeta = [
  { day: "Saturday, March 21, 2026", times: [
      { time: "08:45am - 10:00am", ps: "1" },
      { time: "10:30am - 11:45am", ps: "2" },
      { time: "1:15pm - 2:30pm", ps: "3" },
      { time: "3:00pm - 4:15pm", ps: "4" }
  ]}
];

const paperAbstracts = {
    "1062": "VR Ecology investigates relational presence in XR co-creation: how an AI partner can stay legible and negotiable within embodied making. Instead of prompts or speech, the AI uses a small ProTactile-inspired set of haptic micro-signals (orientation, offer/handoff, slow/confirm). An end-to-end WebXR prototype streams hand and gesture data, drives haptic output, and records trace-memory logs with human/AI/system provenance for replay and annotation. Planned within-subject studies compare visual-only, haptic-only, and combined cues, measuring coordination timing (turn-taking, interruption, response latency), task/process outcomes, and validated self-report of flow and agency; capability-staging contingency matrices keep evaluations comparable as the system evolves.",
    "1224": "Gaze plays a central role in guiding human movement, yet most VR locomotion systems still treat gaze and motion as separate signals. Our research examines how these modalities interact during natural and redirected walking, and how this coupling changes under altered visual–motor contingencies. We first showed that integrating binocular gaze with sparse VR tracking enhances fullbody pose estimation. Building on this foundation, we now analyze high-frequency gaze behaviour during both short- and longterm exposure to redirected walking (RDW) to investigate whether gaze strategies adapt over time. The overall goal of our research is to characterize how gaze–locomotion coupling reorganizes under RDW and to determine whether gaze remains informative for understanding walking direction throughout adaptation. This paper summarizes our completed and ongoing work and outlines key questions for discussion during the Doctoral Consortium.",
    "1238": "As XR technologies become increasingly integrated into everyday applications, designing interfaces that dynamically adapt to diverse users, tasks, and environments is critical. Traditional XR systems often assume static layouts and uniform user capabilities, but in real-world use, users move between contexts, switch tasks, and face varying physical and cognitive demands, which can disrupt usability. My research investigates adaptive interaction in XR, focusing on dynamically adjusting spatial layouts, input strategies, feedback mechanisms, and interaction logic to respond to users’ physical, cognitive, and environmental conditions. My PhD research examines age-related differences, develop hand redirection techniques to optimize interaction in supine postures in VR, and explore adaptive mixed-reality learning environments that tune task complexity and visual feedback based on cognitive load.",
    "1240": "Virtual Reality promises embodied superpowers that defy physical laws, creating a sensorimotor gap between fixed biological limits and unbounded virtual capabilities. While the field employs various evaluation methods, my systematic review critiques the application of subjective concepts like presence, revealing that its usage is often theoretically underspecified for validating interaction quality. Addressing this, I shift focus from the subjective feeling of being there to the computational mechanisms of acting there. I conceptualize VR interaction as a sensorimotor mapping and propose a design space grounded in motor learning theory, distinguishing between motor adaptation (recalibrating internal models) and de novo learning (constructing novel policies). Finally, I employ Bayesian computational modeling to decode the learning dynamics of mappings in the design space. By simulating users as Bayesian agents, this work aims to explain the acquisition of virtual capabilities, contributing to a transition from heuristic trial-and-error to predictive computational modeling.",
    "1246": "Extended Reality (XR) creates new possibilities for training and collaboration by merging digital information with the physical space. However, sustaining awareness - the ongoing understanding of what others (or oneself) are doing, seeing, and needing - remains challenging. My PhD explores how awareness emerges in XR training spaces, and how it can be maintained between people, within oneself, and in interaction with intelligent agents.",
    "1249": "This research investigates the potential of haptic patterns serving as a social cue that supports users’ social cognition in visually demanding virtual reality (VR) environments. While prior work in social VR has primarily focused on visual and auditory information, this research aims to examine how vibrotactile patterns can represent relational or group-relevant information and influence users’ social understanding. Building on multisensory social cognition theories, the research aims to establish design principles for haptic-based social signals and explore how they complement visual cues in social VR contexts.",
    "1258": "Virtual Reality (VR) provides an effective medium for training complex spatiotemporal procedures. However, current systems rarely account for individual differences in cognitive load during embodied interactions. This doctoral research investigates how integrated eye-tracking in VR headsets can be used both to detect and to regulate learners’ embodied cognitive states. First, I will develop an instrument that combines low-level ocular metrics (e.g., pupil dilation, fixation) with higher-level gaze behaviors (e.g., gaze entropy, scanpath organization) to model embodied cognitive load in spatiotemporal VR tasks. Using these models, I will design and evaluate a visually adaptive VR training environment that adjusts visual complexity, saliency, and scene structure in real time based on inferred user state. Two planned user studies will (1) validate the embodied cognition instrument and train real-time classifiers, and (2) test whether state-contingent visual adaptation improves learning and user experience. This work aims to contribute eye-tracking-based models and design guidelines for adaptive VR training.",
    "1260": "There is an increase in Virtual Reality (VR) applications geared towards Older Adults (OAs) in both medical and leisure usages. However, OAs are repeatedly excluded in technological designs, despite the significant growth of the aging population globally. This results in technological designs that are not age-friendly contributing to frustrations when trying to use VR that eventually led to non-adoption. VR locomotion is one of the many aspects that may represent barriers for the adoption of VR by OAs. VR locomotion are ways an individual may navigate within a virtual environment and is fundamental to any VR experiences. In VR research, most VR systems are designed with younger users in mind. When it comes to older users, these designs are either transferred directly or at best minimally adapted. This further suggests VR as an inaccessible platform for OAs. This PhD work aims to improve accessibility of VR experiences for OAs by addressing VR locomotion. Mixed and participatory methods will be used to focus on 1) unique OA needs in VR locomotion, 2) mental model of VR interactive mechanisms, and 3) the suitability criteria for evaluating VR locomotion techniques.",
    "1263": "Cinematic virtual reality (CVR) is a relatively new academic discipline within the field of VR studies. Many areas remain unexplored, notably cinematography for CVR. My doctoral research focuses on the camera movement in CVR, i.e., the dolly zoom. While the well-established technique creates visual distortion through camera movement in traditional cinema, it cannot be applied directly in CVR due to the optical limitations. Thus, the research explores the possibility of representing the perceptual distortion of the dolly zoom supported by rigorous scientific principles. This paper consists of three parts. First, it introduces the background and research questions of the proposed research. Second, it discusses theories and the methodology outlining the project. Third, it recapitulates the work done and proposes further work to complete the research. The key focus of the research is simulating the dolly zoom effects by manipulating the 3DoF project parameters and creating an inverted scaling shader for 6DoF experiences. It will contribute to the development of CVR by introducing a new research direction in cinematography, a field that is currently understudied in scholarly research.",
    "1265": "This research investigates how virtual reality, physiological biofeedback, and conversational AI can be integrated to create adaptive mental health interventions. Traditional care faces significant scalability challenges, prompting a need for digital alternatives. The proposed system operates through two primary modes: a sensory mode and a narrative mode. To stabilize arousal and provide grounding, the sensory component utilizes experiences such as naturalistic environments, cyberdelic visuals, spatial audio, and haptic feedback. Conversely, the narrative component employs a generative AI agent to offer guided reflection and supportive dialogue. Transitions between these modes are driven by real-time physiological data, including heart rate variability, EEG, and EDA activity. When the system detects markers of high stress or increased cognitive load, it prioritizes sensory grounding. Once indicators suggest the user is stable or receptive, it shifts toward narrative exploration. By integrating these modalities, the project seeks to establish design principles for scalable, consumer-oriented digital tools that respond dynamically to individual needs in real-time.",
    "1267": "While mixed reality (MR) has seen significant recent advancements, it remains a technology with entry barriers. Recent studies on universal access in MR, including my previous Ph.D. research, have shown an increasing interest in the use of non-dedicated devices to broaden access and improve user experience for users that, for various reasons, prefer alternatives to head-mounted displays (HMDs). Non-dedicated MR describe multi-purpose devices that can also be used to deliver MR experiences, such as smartphones, tablets, or projectors. This position paper covers theoretical work on universal access to MR with a focus on access and user experience using non-dedicated devices. I describe my two previous projects: a systematic review and a co-creation workshop with older adults. In addition, I describe my ongoing research on seamless cross-device interactions through universal input methods. Last, I describe the current progress and planned next steps, alongside questions to discuss at the Doctoral Consortium at IEEE VR 2026.",
    "1268": "Virtual Reality (VR) offers users a realistic sense of presence by simulating environments rich in visual stimuli. To provide a practical and effective experience, it is essential to guide a user's behavior and perception within the VR environment as intended by the creator. Highlighting is a widely used method to increase perception of a specific object by making an object stand out from its surroundings, but it can disrupt the context or the immersive quality of the VR environment. This consortium paper presents research questions to address the issue and experimental plans to investigate a perception-enhancing method that preserves immersion.",
    "1274": "Virtual reality (VR) is an interesting tool for developing new pedagogical methods for motor skill learning, enabling to give more varied visual concurrent feedback. Co-embodiment allows to share the control of an avatar between two persons. This technique has become popular in virtual reality for studying the relationship between the sense of agency and embodiment of the co-controlled avatar. Recently, some studies have begun to propose motor skill learning methods based on virtual co-embodiment. I propose to improve and extend these methods on three main topics. (Q1) Investigate whether additionnal concurrent feedbacks alongside virtual co-embodiment could improve learning performances. (Q2) Extend the results of embodiment and co-embodiment to an external held object, such as a crafting tool. (Q3) Propose more efficient co-embodiment methods for motor skill learning, without mobilising a human instructor. Our objective is to improve motor skill learning performance in craftsmanship, especially when using held tools, paying particular attention to the conscious and unconscious learning processes.",
    "1276": "This paper highlights the potential of exploring mediated social touch in virtual reality beyond the recreation of face-to-face interactions, motivating my proposed research structure to identify key design parameters of augmented social touch and to investigate the resulting immersive, social, and emotional user experience.",
    "1278": "This doctoral research investigates how personality traits shape affective experiences and physiological responses in Virtual Reality (VR). While VR is widely used to elicit emotions, induce stress, and support social interaction, individual differences are often treated as noise rather than a central focus. Building on the Big Five model, this cumulative thesis examines personality-affect relationships across three complementary studies that share a common methodological core: immersive VR or interactive 3D environments, brief personality assessment, and biosensors. The first, already completed, study explores awe in VR across diverse scenes and cultures, revealing strong effects of scene type and presence but a more complex pattern for personality and physiology than expected. The second study examines acute stress in a VR nursing training scenario, asking how personality moderates stress responses, performance, and acceptance of VR compared to traditional skills lab training. The third study focuses on avatar-mediated trust in collaborative VR, investigating how personality traits influence trust in virtual partners and associated physiological responses. Together, these studies uncover personality-specific affective and physiological patterns in VR and derive design implications for awe experiences, training systems, and avatar design.",
    "1279": "The digital transformation offers novel training opportunities for emergency and rescue teams. Traditional simulations in volunteer services face limitations, often lacking either visual realism or essential physical feedback. This PhD project addresses this gap by proposing a Mixed Reality training model. By combining physical training dummies with responsive virtual patients, the system allows for the simultaneous practice of procedural skills and mental resilience under realistic psychological stress. The goal is to integrate technical proficiency with enhanced mental well-being using Acceptance and Commitment Therapy principles.",
    "1287": "3D User Interfaces for Augmented and Virtual Reality operate in highly dynamic, embodied, and context-dependent environments, where fixed interaction rules and static layouts are insufficient. While many XR systems incorporate runtime adaptation or heuristic optimization, these approaches differ fundamentally from true closed-loop adaptation as defined in Adaptive Software research. This work lays foundational ground for defining Adaptive 3D User Interfaces by grounding interface adaptation in established self-adaptive systems principles. We identify core interface properties—form, content, placement, and interaction—as primary candidates for adaptation. We present a controlled, ontology-driven adaptive interface framework that enables reproducible evaluation of adaptive behavior. Finally, we outline an experimental protocol for assessing user performance, preference, and trust under adaptive interface conditions.",
    "1291": "AI-mediated assistance is increasingly embedded in learning contexts, yet many systems prioritize efficiency and responsiveness in ways that displace learner control. While prior work on adaptive learning, explainable AI, and intelligent tutoring has examined transparency and personalization, learner agency is typically treated as a secondary design constraint rather than a primary interactional objective. This research investigates how AI-mediated assistance can be designed to preserve learner agency during self-directed learning. It proposes Agency-Preserving AI Mediation (APAM), a design framework that emphasizes negotiable control over when and how assistance is enacted. Using augmented reality (AR) as an interactional medium, the work examines how agency can be made observable through learner action rather than inferred cognitive state. Context-Enhanced Learning (CEL) supports coherent, context-sensitive assistance without asserting learner ability or performance. This work contributes an interaction-centered perspective on agency preservation in immersive AI-mediated learning systems.",
    "1298": "This doctoral consortium paper discusses my roadmap towards efficient attention-guided Augmented Reality interfaces for public safety. My main goal is to evaluate the effect of AR interface placement and interaction design on performance, workload, and situational awareness under a dual-task configuration. Currently, I am working on how different AR display placements under dual-task configuration contribute to trade-offs between performance and workload. I aim to evaluate core AR UI modules, such as information display, path guidance, annotations, and alerts, using a dual-task evaluation toolkit, and work with first responders to validate the findings from the lab in a real-life scenario. The goal of this roadmap is to recommend practical design considerations and empirically validated AR interfaces to assist first responders in maintaining performance during dynamic scenarios."
};

document.addEventListener("DOMContentLoaded", function() {
    const tableContainer = document.getElementById("schedule-tables");
    const detailsContainer = document.getElementById("session-details");

    let tablesHTML = "";
    let detailsHTML = "";

    scheduleMeta.forEach(dayInfo => {
        tablesHTML += `<div class="table-scroll"><table>`;
        tablesHTML += `<colgroup><col style="width: 25%;"><col style="width: 75%;"></colgroup>`;
        tablesHTML += `<thead><tr><th colspan="2" style="text-align: left; padding-left: 20px;">${dayInfo.day}</th></tr></thead><tbody>`;

        dayInfo.times.forEach(slot => {
            const sessions = psData[slot.ps];
            
            if (sessions && sessions.length > 0) {
                sessions.forEach((sess, index) => {
                    tablesHTML += `<tr>`;
                    
                    if (index === 0) {
                        tablesHTML += `<td rowspan="${sessions.length}">${slot.time} (UTC+9)</td>`;
                    }
                    
                    tablesHTML += `<td class="type-Parallel"><a href="#session-${sess.id}" class="session-link">${sess.name} </a></td>`;
                    tablesHTML += `</tr>`;

                   const fullDateTime = `${dayInfo.day}, ${slot.time}`;

                    detailsHTML += `
                        <div id="session-${sess.id}" class="session-container">
                            <div class="session-title-wrapper">
                                <span class="session-id-tag">Session ${sess.id}: </span>
                                <span class="session-name-title">${sess.name}</span>
                            </div>
                            <div class="session-chair-text">·  Date & Time: ${fullDateTime}</div>
                            <div class="session-chair-text">· Room: 325D</div>
                            <div class="session-chair-text last">· Session Chair: ${sess.chair || "TBA"}</div>
                            <hr class="div-light">
                    `;

                    sess.papers.forEach((paper, pIdx) => {
                        // Using Paper ID to fetch the abstract text to avoid title string matching issues
                        const abstractText = paperAbstracts[paper.id] || "Abstract details not available.";

                        detailsHTML += `
                            <div class="paper-block paper-item">
                                <span class="paper-id-text">· Paper ID: ${paper.id}<br></span>
                                <span class="paper-title-text">${paper.title}</span><br>
                                
                              <div>
                                <span style="font-weight: bold; color: #262188; margin-top: 5px; font-size:0.8rem; display: block">· Author & Mentor List</span>
                                <div style="margin-top: 5px; padding-left: 10px; color: #444; line-height: 1.5; font-size: 0.7rem;">${paper.authors}</div>
                              </div>
                                
                                <div>
                                    <span class="toggle-btn" onclick="this.nextElementSibling.classList.toggle('show')">· Abstract ▼</span>
                                    <div class="toggle-content">${abstractText}</div>
                                </div>
                            </div>
                        `;
                        if (pIdx < sess.papers.length - 1) {
                            detailsHTML += `<hr class="div-light">`;
                        }
                    });

                    detailsHTML += `</div>`;
                    
                    if (index < sessions.length - 1) {
                        detailsHTML += `<hr class="div-heavy">`;
                    }
                });
                
                detailsHTML += `<hr class="div-heavy">`;
            }
        });
        tablesHTML += `</tbody></table></div>`;
    });

    tableContainer.innerHTML = tablesHTML;
    detailsContainer.innerHTML = detailsHTML;
});
    
</script>
