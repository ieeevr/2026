---
layout: ieeevr-default
title: "Program Overview"
subtitle: "IEEE VR 2026"
title_separator: "|"
---

<style>
/* 1. 기본 스타일 및 반응형 설정 */
h3 {
    margin-top: 1.5rem;
    margin-bottom: 0.5rem;
    font-size: 1.3em;
    color: #066569;
    border-bottom: 1px solid #066569;
}
.table-scroll {
    width: 100%;
    overflow-x: auto;
    margin-bottom: 40px;
    -webkit-overflow-scrolling: touch;
}
table {
    border-collapse: collapse;
    width: 100%;
    min-width: 600px;
    table-layout: fixed;
}
th, td {
    border: 1px solid #888;
    padding: 6px;
    text-align: center;
    word-wrap: break-word;
    vertical-align: middle;
    font-size: 0.7rem;
}
.time-col { background-color: #F2F2F2; font-weight: bold; color: #333; font-size:0.55rem; }
.reg-col { background-color: #D9D9D9; font-weight: bold; color: #444; }

/* 세션 타입별 컬러 */
.type-break, .type-lunch { background-color: #f3f3f3; color: #000; }
.type-keynote { background-color: #E4DFEC; color: #5F497A; font-weight: bold; }
.type-social { background-color: #FCE4D6; color: #974806; font-weight: bold; }
.type-workshop { background-color:#e9dfe7; color: #000; }
.type-tuto { background-color: #FFF8EA; color: #000; }
.type-doct { background-color: #E6EEFF; color: #000; }
.type-Future { background-color: #FFE8E8; color: #000; }
.type-Research { background-color: #e5f1e1; color: #000; }
.type-Welcome { background-color: #FFD9DA ; color: #000; }
.type-Parallel { background-color: #E2E2C7; color: #000; font-weight: bold; }

/* 2. View 버튼 스타일 */
.view-btn {
    display: inline-block;
    margin-top: 5px;
    padding: 2px 10px;
    background-color: #066569;
    color: white;
    border: none;
    border-radius: 12px;
    font-size: 0.65rem;
    cursor: pointer;
    font-weight: normal;
    transition: background 0.2s;
}
.view-btn:hover { background-color: #044d50; }

/* 3. 모달 팝업 스타일 */
.modal-overlay {
    display: none;
    position: fixed;
    top: 0; left: 0; width: 100%; height: 100%;
    background: rgba(0, 0, 0, 0.75);
    z-index: 10000;
    justify-content: center;
    align-items: center;
    padding: 15px;
}
.modal-content {
    background: white;
    width: 100%;
    max-width: 850px;
    max-height: 85vh;
    border-radius: 10px;
    overflow-y: auto;
    position: relative;
    padding: 30px;
    box-shadow: 0 12px 40px rgba(0,0,0,0.4);
    text-align: left;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
}
.modal-close {
    position: absolute;
    top: 15px; right: 20px;
    font-size: 32px;
    cursor: pointer;
    color: #999;
    line-height: 1;
}
.modal-close:hover { color: #333; }

/* 모달 내부 텍스트 레이아웃 */
.session-container { margin-bottom: 35px; }
.session-id-tag { font-size: 0.8rem; color: #777; font-weight: normal; }
.session-name-title { font-size: 1.4rem; font-weight: bold; color: #066569; margin: 5px 0; display: block; }
.session-chair-text { font-size: 0.9rem; margin-bottom: 15px; color: #444; }

.paper-block { padding: 12px 0; font-size: 0.95rem; line-height: 1.6; }
.paper-title-text { font-weight: bold; color: #000; }
.author-list-text { font-size: 0.85rem; color: #555; display: block; margin-top: 4px; }

.div-light { border: 0; border-top: 1px solid #eee; margin: 10px 0; }
.div-heavy { border: 0; border-top: 3px solid #066569; margin: 30px 0; }
</style>

<h3>Day 3: Monday, March 23</h3>
<div class="table-scroll">
    <table>
        <colgroup><col style="width: 5%"><col style="width: 5%"><col style="width: 45%"><col style="width: 45%"></colgroup>
        <tbody>
            <tr><td class="time-col">11:30</td><td rowspan="4" class="reg-col">R...</td><td class="type-Parallel">Parallel Sessions 1 <br><button class="view-btn" onclick="openSessModal(1)">view</button></td><td></td></tr>
            <tr><td class="time-col">14:00</td><td class="type-Parallel">Parallel Sessions 2 <br><button class="view-btn" onclick="openSessModal(2)">view</button></td><td></td></tr>
            <tr><td class="time-col">15:00</td><td class="type-Parallel">Parallel Sessions 3 <br><button class="view-btn" onclick="openSessModal(3)">view</button></td><td></td></tr>
            <tr><td class="time-col">16:30</td><td class="type-Parallel">Parallel Sessions 4 <br><button class="view-btn" onclick="openSessModal(4)">view</button></td><td></td></tr>
        </tbody>
    </table>
</div>

<h3>Day 4: Tuesday, March 24</h3>
<div class="table-scroll">
    <table>
        <colgroup><col style="width: 5%"><col style="width: 5%"><col style="width: 23%"><col style="width: 22%"><col style="width: 45%"></colgroup>
        <tbody>
            <tr><td class="time-col">08:30</td><td rowspan="5" class="reg-col">R...</td><td colspan="2" class="type-Parallel">Parallel Sessions 5 <br><button class="view-btn" onclick="openSessModal(5)">view</button></td><td></td></tr>
            <tr><td class="time-col">11:30</td><td colspan="2" class="type-Parallel">Parallel Sessions 6 <br><button class="view-btn" onclick="openSessModal(6)">view</button></td><td></td></tr>
            <tr><td class="time-col">14:00</td><td colspan="2" class="type-Parallel">Parallel Sessions 7 <br><button class="view-btn" onclick="openSessModal(7)">view</button></td><td></td></tr>
            <tr><td class="time-col">15:00</td><td class="type-Parallel">Parallel Sessions 8 <br><button class="view-btn" onclick="openSessModal(8)">view</button></td><td class="type-workshop">Panel Session</td></tr>
            <tr><td class="time-col">16:30</td><td colspan="2" class="type-Parallel">Parallel Sessions 9 <br><button class="view-btn" onclick="openSessModal(9)">view</button></td><td></td></tr>
        </tbody>
    </table>
</div>

<h3>Day 5: Wednesday, March 25</h3>
<div class="table-scroll">
    <table>
        <colgroup><col style="width: 5%"><col style="width: 5%"><col style="width: 23%"><col style="width: 22%"><col style="width: 45%"></colgroup>
        <tbody>
            <tr><td class="time-col">08:30</td><td rowspan="4" class="reg-col">R...</td><td colspan="2" class="type-Parallel">Parallel Sessions 10 <br><button class="view-btn" onclick="openSessModal(10)">view</button></td><td></td></tr>
            <tr><td class="time-col">11:30</td><td colspan="2" class="type-Parallel">Parallel Sessions 11 <br><button class="view-btn" onclick="openSessModal(11)">view</button></td><td></td></tr>
            <tr><td class="time-col">14:00</td><td colspan="2" class="type-Parallel">Parallel Sessions 12 <br><button class="view-btn" onclick="openSessModal(12)">view</button></td><td></td></tr>
            <tr><td class="time-col">15:00</td><td class="type-Parallel">Parallel Sessions 13 <br><button class="view-btn" onclick="openSessModal(13)">view</button></td><td class="type-workshop">Panel Session</td></tr>
        </tbody>
    </table>
</div>

<div class="modal-overlay" id="modalOverlay" onclick="closeModal()">
    <div class="modal-content" onclick="event.stopPropagation()">
        <span class="modal-close" onclick="closeModal()">&times;</span>
        <div id="modalBody"></div>
    </div>
</div>

<script>
/**
 * 엑셀 데이터 통합 객체 (psData)
 * 13개의 Parallel Sessions 내의 모든 세션과 논문 데이터가 포함됨
 */
const psData = {
  "1": [
    { "id": 1, "name": "Projection displays / spatial AR", "chair": "", "papers": [
      { "id": "P1012", "title": "Shadowless Projection Mapping for Tabletop Workspaces with Synthetic Aperture Projector", "authors": "Takahiro Okamoto: The University of Osaka; Masaki Takeuchi: The University of Osaka; Masataka Sawayama: Hokkaido University; Daisuke Iwai: The University of Osaka" },
      { "id": "P1828", "title": "High-Contrast Projection Mapping under Light Field Illumination with LED Display and Aperiodic Lens Array", "authors": "Kotaro Fujimura: The University of Osaka; Hiroki Kusuyama: The University of Osaka; Masaki Takeuchi: The University of Osaka; Daisuke Iwai: The University of Osaka" },
      { "id": "P1060", "title": "DiffPC: Diffusion-Based Projector Photometric Compensation", "authors": "Yuxi Wang: Hangzhou Dianzi University; Haibin Ling: Westlake University; Bingyao Huang: Southwest University" },
      { "id": "P1124", "title": "Setup-Independent Full Projector Compensation", "authors": "Haibo Li: Southwest university; Qingyue Deng: Southwest University; Jijiang Li: Southwest university; Haibin Ling: Westlake University; Bingyao Huang: Southwest University" },
      { "id": "P1036", "title": "ProCap: Projection-Aware Captioning for Spatial Augmented Reality", "authors": "Zimo Cao: Southwest University; Yuchen Deng: Southwest University; Haibin Ling: Westlake University; Bingyao Huang: Southwest University" }
    ]},
    { "id": 2, "name": "Pseudo-haptics and vibration", "chair": "", "papers": [
      { "id": "TVCG-14", "title": "Eliciting Pleasantness with Haptic Feedback: The Role of Physical and Pseudo-Haptic Resistance in Virtual Archery", "authors": "Yusuke Ujitoko: NTT, Inc.; Yuki Ban: The University of Tokyo" },
      { "id": "TVCG-07", "title": "Move or Push? Studying Pseudo-Haptic Perceptions Obtained with Motion or Force Input", "authors": "Yutaro Hirao: Nara Institute of Science and Technology; Takuji Narumi: University of Tokyo; Ferran Argelaguet: Inria / IRISA / CNRS / University of Rennes; Anatole Lécuyer: Inria / IRISA / CNRS / University of Rennes" },
      { "id": "P1740", "title": "AsymDrive: Fingertip-Free Force Illusions Induced by Asymmetric Vibrations on Dorsal-Palmar Tendons", "authors": "Koki Fukuda: The University of Tokyo; Kazuma Aoyama: Virtual Reality Educational Research Center; Hideaki Kuzuoka: The University of Tokyo; Takuji Narumi: the University of Tokyo; Tomohiro Amemiya: The University of Tokyo" },
      { "id": "P1841", "title": "\"Feeling\" the Stretch: Enhancing Embodiment in Virtual Arm Elongation through Spatiotemporal Modulation of Visio-Haptic Feedback", "authors": "Sara Rossi: INSA; Claudio Pacchierotti: CNRS; Maud Marchal: Univ. Rennes, INSA, IRISA, Inria" },
      { "id": "P1191", "title": "Event-Based Referred Vibrotactile Feedback for Bare-Hand XR Interaction", "authors": "Juyoung Lee: Korea Advanced Institute of Science and Technology; Hyunseo Seo: Korea Advanced Institute of Science & Technology (KAIST); Hyunjin Lee: KAIST; Minju Baeck: KAIST; Hui-Shyong Yeo: Huawei; Woontack Woo: KAIST" }
    ]},
    { "id": 3, "name": "Point clouds, cities, and crowds", "chair": "", "papers": [
      { "id": "P1912", "title": "PointShopVR: Immersive Authoring of Large Point Clouds in Virtual Reality", "authors": "Tianfang Lin: TUD Dresden University of Technology; Matthew McGinity: Technische Universität Dresden; Stefan Gumhold: TUD Dresden University of Technology" },
      { "id": "P1680", "title": "ScaleFree: Dynamic KDE for Multiscale Point Cloud Exploration in VR", "authors": "Lixiang Zhao: Xi'an Jiaotong-Liverpool University; Fuqi Xie: Xi'an Jiaotong-Liverpool University; Tobias Isenberg: Université Paris-Saclay, CNRS, Inria, LISN; Hai-Ning Liang: The Hong Kong University of Science and Technology (Guangzhou); Lingyun Yu: Xi'an Jiaotong-Liverpool University" },
      { "id": "TVCG-08", "title": "360CityGML: Realistic and Interactive Urban Visualization System Integrating CityGML Model and 360° Videos", "authors": "Tatsuro Banno: University of Tokyo; Mizuki Takenawa: University of Tokyo; Leslie Wöhler: University of Tokyo; Satoshi Ikehata: National Institute of Informatics; Kiyoharu Aizawa: University of Tokyo" },
      { "id": "P1133", "title": "Follow the Signs or the Crowd? Effects of Environmental Load and Crowd Dynamics in VR Evacuation", "authors": "Zheng Wei: The Hong Kong University of Science and Technology; Jingchen Gao: New York University; Zhe Yan: Hong Kong University of Science and Technology (Guangzhou); Yihan Liu: Renmin University of China; Linjie Qiu: The Hong Kong University of Science and Technology (Guangzhou); Xian Xu: Lingnan university; Yun Huang: University of Illinois at Urbana-Champaign; Huamin Qu: The Hong Kong University of Science and Technology" },
      { "id": "P1388", "title": "Monkey See, Monkey Break? Study of Rule-Breaking Imitation in Virtual Crowds", "authors": "Kexiang Huang: Beijing Institute of Technology; Tairan Yin: Universitat Politecnica de Catalunya; Jose Luis Ponton: Universitat Politècnica de Catalunya; Ruida Tang: Beijing Institute of Technology; Reiya Itatani: Universitat Politecnica de Catalunya; Gangyi Ding: Beijing Institute of Technology; Oscar Argudo: Universitat Politecnica de Catalunya; Nuria Pelechano: Universitat Politècnica de Catalunya" }
    ]},
    { "id": 4, "name": "Cybersickness", "chair": "", "papers": [
      { "id": "P1223", "title": "Predicting Cybersickness Trend and Extent based on FMS labeled Dataset", "authors": "Jun Ryu: Korea University; Gerard Jounghyun Kim: Korea University" },
      { "id": "P2261", "title": "A Statistical Abstraction Framework for Integrating Heterogeneous VR Datasets in Ordinal Cybersickness Prediction", "authors": "Jyotirmay Nag Setu: University of Texas at San Antonio; John Quarles: University of Texas at San Antonio" },
      { "id": "P2328", "title": "Mitigating VR Motion Sickness Through Multi-sensory Simulation of Wind Sensation (MSSWS): A Vestibular-Visual Synchronization Approach", "authors": "Yuan Yue: Tsinghua University; Chao Zhou: Institute of Software Chinese Academy of Sciences; Tangjun Qu: Yanbian University; Yan Hu: Blekinge Institute of Technology; Junhao Wang: Peking University; Juan Liu: School of Mechanical, Electrical & Information Engineering; Tianren Luo: Institute of Software; Xiangxian Li: Shandong University; Yulong Bian: Shandong University" },
      { "id": "P1358", "title": "Kinematic Sickness: Understanding Cybersickness Through Body Kinematics", "authors": "Carlos Alfredo Tirado Cortes: University of Sydney; Yiheng Chi: Adelaide University; Juno Kim: University of New South Wales; Hsiang-Ting Chen: Adelaide University" },
      { "id": "P2188", "title": "Two Phase Multi-Task Learning for Cybersickness Prediction and Adaptive Reduction", "authors": "A E M Ridwan: Kennesaw State University; Purnata Saha: University of Texas at San Antonio; John Quarles: University of Texas at San Antonio; Rifatul Islam: Kennesaw State University" }
    ]}
  ],
  "2": [
    { "id": 5, "name": "Gaussian splatting 1", "chair": "", "papers": [
      { "id": "P1522", "title": "GSReuse: Temporally Adaptive Screen-Space Reuse for Accelerating 3D Gaussian Splatting", "authors": "Chengzhi Tao: Nanjing University; Yiyang Sun: Computer Science and Technology Department, Nanjing University; Jie Guo: Nanjing University; Tao Zhang: NanJing University; Letian Huang: Nanjing University; Junqiu Zhu: Shandong University; daoheng wang: Nanjing University; Yanwen Guo: Nanjing University" },
      { "id": "P1529", "title": "VRGaussianAvatar: Integrating 3D Gaussian Avatars into VR", "authors": "Hail Song: Korea Advanced Institute of Science and Technology; Boram Yoon: KI-ITC ARRC, KAIST; Seokhwan Yang: KAIST; Seoyoung Kang: KAIST; Hyunjeong Kim: Division of Computer Engineerting; Henning Metzmacher: ETH Zurich; Woontack Woo: KAIST" },
      { "id": "P1067", "title": "Taking Language Embedded 3D Gaussian Splatting into the Wild", "authors": "Yuze Wang: Beihang University; Junyi Wang: Shandong University; Yue Qi: Beihang University" },
      { "id": "P1798", "title": "AdaEndoGS: an Adaptive Enlightening Model for Endoscopy Based on 3D Gaussian Splatting", "authors": "Fei Xia: Wuhan University; Yiding Wen: Wuhan University; Yuanfan Liu: Wuhan University; Huanmei Guan: Wuhan University; Fei Luo: Wuhan University" },
      { "id": "P1482", "title": "GSBrief: A Globally Consistent Descriptor with 3D Gaussian Splatting for Visual Localization", "authors": "Junyi Wang: Shandong University; Yuze Wang: Beihang University; Wantong Duan: Beihang University; Meng Wang: Beihang University; Yue Qi: Beihang University" }
    ]},
    { "id": 6, "name": "3DUI 1", "chair": "", "papers": [
      { "id": "TVCG-17", "title": "ForceCtrl: Hand-Raycasting with User-Defined Pinch Force for Control-Display Gain Application", "authors": "Seo Young Oh: Korea Advanced Institute of Science and Technology; Junghoon Seo: Korea Advanced Institute of Science and Technology; Juyoung Lee: Korea Advanced Institute of Science and Technology; Boram Yoon: Korea Advanced Institute of Science and Technology; Sang Ho Yoon: Korea Advanced Institute of Science and Technology; Woontack Woo: Korea Advanced Institute of Science and Technology" },
      { "id": "P1661", "title": "Physics-based Hand-object Interaction via Control Force in Virtual Reality", "authors": "Yue Ma: Beihang University; Yi Wei: Beihang University; Xiaohui Liang: Beihang University" },
      { "id": "P1534", "title": "BlanchTouch: Bringing Fingertip Blanch Detection into Mixed Reality for Touch Input on Flat Surfaces", "authors": "Guanghan Zhao: Tohoku University; Yangyang Cai: Research Institute of Electrical Communication; Kazuyuki Fujita: Tohoku University; Robert W. Lindeman: University of Canterbury; Yoshifumi Kitamura: Tohoku University" },
      { "id": "P1503", "title": "SurfaceXR: Fusing Smartwatch IMUs and Egocentric Hand Pose for Seamless Surface Interactions", "authors": "Vasco Xu: University of Chicago; Brian Chen: Northwestern University; Eric J Gonzalez: Google; Andrea Colaço: Google; Henry Hoffman: University of Chicago; Mar Gonzalez-Franco: Google; Karan Ahuja: Northwestern University" },
      { "id": "P1537", "title": "FanType: Intention-Inferring Fan-shaped Thumb Interface for Text Entry on Small XR Keyboards", "authors": "Guanghan Zhao: Tohoku University; Louis Pierre Adolphe Sylvain Teys: Tohoku University; GYEONGHWAN YANG: Jeonbuk National University; Shengdong Zhao: City University of Hong Kong; Yoshifumi Kitamura: Tohoku University" }
    ]},
    { "id": 7, "name": "Teleportation 1", "chair": "", "papers": [
      { "id": "P1518", "title": "FootEyePorting: Design and Evaluation of Foot–Eye Teleportation Techniques in Virtual Reality", "authors": "Jianwei Yang: Jinan University; Tingjie Wan: Jinan University; BoYu Gao: Jinan University; Huawei Tu: La Trobe University; Henry Been-Lirn Duh: Hong Kong Polytechnic University" },
      { "id": "P2256", "title": "Evaluation of Visual Feedback Techniques for Mid-air Teleportation in an Immersive Environment", "authors": "Nanjia Wang: University of Calgary; Saadman Rahman: University of Calgary; Brody Wells: University of Calgary; Daniel Zielasko: Technical University of Denmark; Frank Maurer: University of Calgary" },
      { "id": "P1761", "title": "NinjaPort: A Multi-Hand Approach for VR Teleportation", "authors": "Bakdauren Narbayev: University of British Columbia; Patricia Lasserre: University of British Columbia (Okanagan Campus); Khalad Hasan: University of British Columbia" },
      { "id": "P1236", "title": "SATOR: Seamless 3D Teleportation to Both Ground and Mid-Air Targets", "authors": "Daniel Rupp: RWTH Aachen University; Matthias Wölwer: University of Trier; Torsten Wolfgang Kuhlen: RWTH Aachen University; Daniel Zielasko: Technical University of Denmark; Tim Weissker: RWTH Aachen University" },
      { "id": "P2231", "title": "Teleportation Destination Previews Support Memory Retention During Virtual Navigation", "authors": "Zubin Datta Choudhary: University of Central Florida; Ferran Argelaguet Sanz: Inria; Gerd Bruder: University of Central Florida; Greg Welch: University of Central Florida" }
    ]},
    { "id": 8, "name": "Avatars 1", "chair": "", "papers": [
      { "id": "P1811", "title": "RSATalker: Realistic Socially-Aware Talking Head Generation for Multi-Turn Conversation", "authors": "Peng Chen: University of Chinese Academy of Sciences; Xiaobao Wei: University of Chinese Academy of Sciences; Yi Yang: Institute of Software, Chinese Academy of Sciences; Naiming Yao: Institute of Software, Chinese Academy of Sciences; Hui Chen: Institute of Software, Chinese Academy of Sciences; Feng Tian: Institute of software, Chinese Academy of Sciences" },
      { "id": "P1995", "title": "What You See Is What You Wear: Crafting Garments for Diverse Avatars with Consistent Wearing Effects", "authors": "Zan Wang: Beijing Institute of Technology; Anqi Li: Beijing Institute of Technology; yixuan li: Beijing Institute of Technology; Wei Liang: Beijing Institute of Technology; Bing Ning: Beijing Institute of Fashion Technology" },
      { "id": "P1913", "title": "HybridSphere: Enhancing Hybrid Meetings with Avatar-Based VR Environments", "authors": "Koji Momota: The University of Osaka; Shizuka Shirai: The University of Osaka; Masato Kobayashi: The University of Osaka; Naoya Chiba: The University of Osaka; Photchara Ratsamee: Osaka Institute of Technology; Kiyoshi Kiyokawa: Nara Institute of Science and Technology; Yuki Uranishi: The University of Osaka" },
      { "id": "P1997", "title": "It's All in the Personality: A Comparative Study of Real, Ideal, and Customized Virtual Instructors for AR Assembly Tasks", "authors": "Abdul Mannan Mohammed: University of Central Florida; Martin McCarthy: University of Central Florida; Carsten Neumann: University of Central Florida; Gerd Bruder: University of Central Florida; Dirk Reiners: University of Central Florida; Carolina Cruz-Neira: University of Central Florida" },
      { "id": "P2104", "title": "Beyond the Self: Avatar Anthropomorphic Fidelity and Calibration Effects on Judging Others' Interpersonal Horizontal Reachability in VR", "authors": "Vyomakesh Shivakumar: Clemson University; Kristopher C. Kohm: NASA Ames Research Center; Andrew Robb: Clemson University; Christopher Pagano: Clemson University; Sabarish V. Babu: Texas A&M University" }
    ]}
  ],
  "3": [
    { "id": 9, "name": "Gaussian splatting 2", "chair": "", "papers": [
      { "id": "P1440", "title": "Shape-Shifting Splats: Realtime Context Translation for Gaussian Splatting in VR", "authors": "Thomas Kernbauer: Graz University of Technology; Simon Fussi: Graz University of Technology; Philipp Fleck: VRVis; Clemens Arth: Graz University of Technology" },
      { "id": "P1080", "title": "LIVE-GS: LLM Powers Interactive VR Experience with Physics-Aware Gaussian Splatting", "authors": "Haotian Mao: Shanghai Jiao Tong University; Hangyu Zhou: Zhejiang University of Science and Technology; Zhuoxiong Xu: Shanghai Jiao Tong University; Siyue Wei: Shanghai Jiao Tong University; Yule Quan: Shanghai Jiao Tong University; Yan Zhang: Shanghai Jiao Tong University; Zixuan Guo: Shanghai Jiao Tong University; Nianchen Deng: Shanghai AI Lab; Xubo Yang: SHANGHAI JIAO TONG UNIVERSITY" },
      { "id": "P1531", "title": "OFERA: Blendshape-driven 3D Gaussian Control for Occluded Facial Expression to Realistic Avatars in VR", "authors": "Seokhwan Yang: Korea Advanced Institute of Science and Technology; Boram Yoon: KI-ITC ARRC, KAIST; Seoyoung Kang: KAIST; Hail Song: Korea Advanced Institute of Science and Technology; Woontack Woo: KAIST" },
      { "id": "P1507", "title": "Motion Hierarchical Gaussian for Dynamic Control in VR", "authors": "Runze Fan: Beihang University; Jian Wu: Beihang University; Qixiang Ma: Beihang University; Zhikai Wen: Beihang University; Lili Wang: Beihang University" },
      { "id": "P2107", "title": "Hybrid Foveated Path Tracing with Peripheral Gaussians for Immersive Anatomy", "authors": "Constantin Kleinbeck: Technical University of Munich; Luisa Theelke: Technical University of Munich; Hannah Schieber: Technical University of Munich (TUM); Ulrich Eck: Technische Universitaet Muenchen; Rüdiger von Eisenhart-Rothe: Klinik für Orthopädie und Sportorthopädie; Daniel Roth: Technical University of Munich" }
    ]},
    { "id": 10, "name": "3DUI 2", "chair": "", "papers": [
      { "id": "P1141", "title": "Direct vs. Score-based Selection: Understanding the Heisenberg Effect in Target Acquisition Across Input Modalities in Virtual Reality", "authors": "Linjie Qiu: The Hong Kong University of Science and Technology (Guangzhou); Duotun Wang: The Hong Kong University of Science and Technology (Guangzhou); Boyu Li: The Hong Kong University of Science and Technology; Jiawei Li: The Hong Kong University of Science and Technology (Guangzhou); Yulin Shen: The Hong Kong University of Science and Technology (Guangzhou); Zeyu Wang: The Hong Kong University of Science and Technology (Guangzhou); Mingming Fan: The Hong Kong University of Science and Technology (Guangzhou)" },
      { "id": "P1795", "title": "Exploring Freehand-Based Selection Techniques of Polyhedron Faces in VR Environments", "authors": "Yifan Qi: Chinese Academy of Science; Xuning Hu: Chinese Academy of Sciences; Xinan Yan: Institute of Software, Chinese Academy of Sciences; Wenxuan Xu: Dartmouth College; Hao Zhang: Institute of software,Chinese Academy of Sciences; Hai-Ning Liang: The Hong Kong University of Science and Technology (Guangzhou); Jin Huang: Chinese Academy of Sciences" },
      { "id": "P1553", "title": "Slightly Stretching Your Arm’s Reach May Improve VR Interaction: The Optimal Interaction Zone in a Memory Task", "authors": "Yuke Pi: Goldsmiths, University of London; Marco Fyfe Pietro Gillies: Goldsmiths, University of London; Dorothy Cowie: Durham University; Xueni Pan: Goldsmiths" },
      { "id": "P2208", "title": "Effect of Interpupillary Distance Mismatch on Distance and Orientation Perception in Action Space Across HMDs", "authors": "Hunter C Finney: University of Utah; Maggie K McCracken: University of Utah; Eric Zhuo: University of Utah; Sarah Creem-Regehr: University of Utah; Jeanine Stefanucci: University of Utah" },
      { "id": "P1477", "title": "Use Case Matters: Comparing the User Experience and Task Performance Across Tasks for Embodied Interaction in VR", "authors": "Jonathan Tschanter: University of Würzburg; Christian Merz: University of Würzburg; Marie Luisa Fiedler: University of Würzburg; Carolin Wienrich: University of Würzburg; Marc Erich Latoschik: University of Würzburg" }
    ]},
    { "id": 11, "name": "Teleportation 2", "chair": "", "papers": [
      { "id": "P1181", "title": "Perceptually-Guided Adjusted Teleporting: Perceptual Thresholds for Teleport Displacements in Virtual Environments", "authors": "Rose Connolly: Trinity College Dublin; Victor Zordan: Roblox Corporation; Rachel McDonnell: Trinity College Dublin" },
      { "id": "TVCG-10", "title": "How Far is Too Far? The Trade-Off between Selection Distance and Accuracy during Teleportation in Immersive Virtual Reality", "authors": "Daniel Rupp: RWTH Aachen University; Tim Weissker: University of Trier; Matthias Wölwer: RWTH Aachen University; Torsten W. Kuhlen: RWTH Aachen University; Daniel Zielasko: Technical University of Denmark" },
      { "id": "P1735", "title": "Reorienting with the Bare Hand: Gesture-Based Techniques for Orientation-Enabled Teleportation in Virtual Reality", "authors": "Yushi Wei: The Hong Kong University of Science and Technology (Guangzhou); Xinru Cheng: The Hong Kong University of Science and Technology (Guangzhou); Rongkai Shi: The Hong Kong University of Science and Technology (Guangzhou); Hai-Ning Liang: The Hong Kong University of Science and Technology (Guangzhou)" },
      { "id": "P1886", "title": "Portals in Impossible VR Spaces: A Taxonomy and Effects on Spatial Memory", "authors": "Ana Rita Rebelo: NOVA LINCS, NOVA School of Science and Technology; Khrystyna Vasylevska: TU Wien; Rui Nóbrega: NOVA Schools of Science and Technology; Hannes Kaufmann: Vienna University of Technology" },
      { "id": "P1105", "title": "Balancing the Virtual Path: Influence of Amplitude, Frequency, and Input Method on VR Locomotion", "authors": "Michael Nelson: Purdue; Christos Mousas: Purdue University" }
    ]},
    { "id": 12, "name": "Avatars 2", "chair": "", "papers": [
      { "id": "P2159", "title": "Reallocation of Body Ownership Between Avatar and Omniscient Entity in Third-Person Perspective VR", "authors": "Jiayi Hu: The University of Tokyo; Kai Guo: Graduate School of Frontier Sciences; Zhongrui Kang: The University of Tokyo; Yuki Ban: The University of Tokyo; Shinichi Warisawa: The University of Tokyo" },
      { "id": "P1079", "title": "A Large-Scale Quantitative Analysis of Avatars in VR and AR", "authors": "Natalie Hube: University of Stuttgart; Alexander Achberger: University of Stuttgart; Michael Sedlmair: University of Stuttgart" },
      { "id": "P1198", "title": "Avatar-Driven Interaction: Constructing Immersive Education in Virtual Classrooms", "authors": "Yue Wu: Sichuan Normal University; Wu He: Sichuan Normal University" },
      { "id": "P1478", "title": "Am I Still Me? Visual Congruence Across Reality–Virtuality and Avatar Appearance in Shaping Self-Perception and Behavior", "authors": "Marie Luisa Fiedler: University of Würzburg; Christian Merz: University of Würzburg; Lukas Schach: University of Würzburg; Jonathan Tschanter: University of Würzburg; Mario Botsch: TU Dortmund University; Carolin Wienrich: University of Würzburg; Marc Erich Latoschik: University of Würzburg" },
      { "id": "P1668", "title": "Streamlined Facial Data Collection based on Utterance and Emotional Data for Human-to-Avatar Reconstruction", "authors": "Seoyoung Kang: KAIST; Seokhwan Yang: Korea Advanced Institute of Science and Technology; Hail Song: Korea Advanced Institute of Science and Technology; Boram Yoon: KI-ITC ARRC, KAIST; Jinwook Kim: KAIST; Kangsoo Kim: University of Calgary; Woontack Woo: KAIST" }
    ]}
  ],
  "4": [
    { "id": 13, "name": "Rendering and animation", "chair": "", "papers": [
      { "id": "P1224", "title": "Gloss Perception in VR at Long Viewing Distances: Effects of Binocular Highlight Intensity Asymmetry", "authors": "Kai Guo: Graduate School of Frontier Sciences; Juro Hosoi: The University of Tokyo; Yuki Shimomura: The University of Tokyo; Yuki Ban: The University of Tokyo; Shinichi Warisawa: The University of Tokyo" },
      { "id": "P1238", "title": "Evaluating Cutout Rendering Techniques for Pass-Through Embodiment Using a Real-Mirror Metaphor", "authors": "Kristoffer Waldow: TH Köln; Arnulph Fuhrmann: TH Köln; Daniel Roth: Technical University of Munich" },
      { "id": "P1715", "title": "AniXDim: Integrating Cross-Dimensional Interaction into Desktop Character Animation Workflows", "authors": "Haihan Lin: Shanghai Jiao Tong University; Ye Pan: Shanghai Jiaotong University ; Nianlong Li: Institute of Software, Chinese Academy of Sciences; wanjun lv: Lenovo; Teng Han: Institute of Software, Chinese Academy of Sciences; Feng Tian: Institute of software, Chinese Academy of Sciences" },
      { "id": "P1731", "title": "Local Surface Approximation Contours for Virtual Reality Stylisation", "authors": "Amir Zaidi: Delft, University of Technology; Ricardo Marroquim: TU Delft; Michael Weinmann: Delft University of Technology ; Elmar Eisemann: Delft University of Technology" }
    ]},
    { "id": 14, "name": "3DUI 3", "chair": "", "papers": [
      { "id": "P1698", "title": "RayFlex: Inducing Weight Perception through Raycast Pseudo-Haptics in Virtual Reality", "authors": "Yushi Wei: The Hong Kong University of Science and Technology (Guangzhou); Sen Zhang: Xi'an Jiaotong-Liverpool University; Rongkai Shi: The Hong Kong University of Science and Technology (Guangzhou); Simon Fong: University of Macau; Pan Hui: The Hong Kong University of Science and Technology (Guangzhou); Hai-Ning Liang: The Hong Kong University of Science and Technology (Guangzhou)" },
      { "id": "P2086", "title": "Multi-WIM Paradigm: Comparing Urban Planning Variants with Worlds-in-Miniature", "authors": "Karoline Brehm: Bauhaus Universität Weimar; Ephraim Schott: Bauhaus-Universität Weimar; Manuel Hartmann: Bauhaus-Universität Weimar; Bernd Froehlich: Bauhaus-Universität Weimar" },
      { "id": "P2214", "title": "Scaled Mouse: An Efficient and Accurate Interaction Technique for 3D Docking in Seated VR", "authors": "Xinpeng Liu: Simon Fraser University ; Di Zhao: Simon Fraser University; Wolfgang Stuerzlinger: Simon Fraser University" },
      { "id": "P1202", "title": "Re-evaluating Virtual Reality Manipulation Techniques for Precise Alignment of Complex 3D Objects", "authors": "Cherelle Connor: Virginia Tech; Alexander Giovannelli: Virginia Tech; Leonardo Pavanatto: Virginia Tech; Francielly Rodrigues: Virginia Tech; Haichao Miao: Lawrence Livermore National Laboratory; Vuthea Chheang: San Jose State University ; Brian Giera: Lawrence Livermore National Laboratory; Peer-Timo Bremer: Lawrence Livermore National Laboratory; Doug Bowman: Virginia Tech" },
      { "id": "P2216", "title": "Interaction Under Whole-Body User Rotations in VR Space", "authors": "Filip Škola: CYENS Centre of Excellence; Fotis Liarokapis: CYENS Centre of Excellence" }
    ]},
    { "id": 15, "name": "Locomotion techniques", "chair": "", "papers": [
      { "id": "P1052", "title": "Looming-Based Transition: Reducing Sickness during Discrete Travel in Virtual Reality", "authors": "Gunnar Geyer: Bauhaus-Universität Weimar; Ephraim Schott: Bauhaus-Universität Weimar; Bernd Froehlich: Bauhaus-Universität Weimar" },
      { "id": "P1519", "title": "L-Eye: Using Gaze Information to Mitigate Cybersickness during Artificial Locomotion", "authors": "Xubo Yang: Shanghai Jiao Tong University; Yuqing Sun: Shanghai Jiao Tong University; Yikai Jiang: Shanghai Jiao Tong University; Yan Zhang: Shanghai Jiao Tong University; Chenxi Huang: Shanghai Jiao Tong University; Nianchen Deng: Shanghai AI Lab; Xubo Yang: SHANGHAI JIAO TONG UNIVERSITY" },
      { "id": "P2219", "title": "LocoMotif: User-Friendly Motion Generation for Virtual Reality Locomotion", "authors": "Filip Škola: CYENS Centre of Excellence; Andreas Aristidou: University of Cyprus; Fotis Liarokapis: CYENS Centre of Excellence" },
      { "id": "P2013", "title": "Effect of Walking Speed and Ground Texture on Distance Perception in Seated VR Locomotion", "authors": "Xinpeng Liu: Simon Fraser University ; Wolfgang Stuerzlinger: Simon Fraser University" },
      { "id": "P2223", "title": "Influence of Avatars on Distance Perception during VR Locomotion", "authors": "Nanjia Wang: University of Calgary; Frank Maurer: University of Calgary" }
    ]}
  ],
  "5": [
    { "id": 18, "name": "Projection & Displays", "chair": "", "papers": [
      { "id": "P1122", "title": "Projection Mapping on Moving Deformable Surfaces using Multi-Projector Systems", "authors": "..." }
    ]},
    { "id": 19, "name": "Interaction 1", "chair": "", "papers": [
      { "id": "P1031", "title": "Exploring Interactive Scaffolding for 3D Sketching in Mixed Reality", "authors": "..." }
    ]}
  ],
  "6": [
    { "id": 22, "name": "Sickness & Comfort", "chair": "", "papers": [
      { "id": "P1402", "title": "Investigation of Viewport Smoothing for Reducing Cybersickness", "authors": "..." }
    ]}
  ],
  "7": [
    { "id": 26, "name": "Avatars & Social", "chair": "", "papers": [
      { "id": "P1775", "title": "The Impact of Avatar Realism on Social Presence", "authors": "..." }
    ]}
  ],
  "8": [
    { "id": 30, "name": "Vision & Graphics", "chair": "", "papers": [
      { "id": "P2015", "title": "Optimized Rendering for Wide Field-of-View HMDs", "authors": "..." }
    ]}
  ],
  "9": [
    { "id": 33, "name": "Tracking & Input", "chair": "", "papers": [
      { "id": "P1099", "title": "IMU-Based Hand Tracking for Mobile VR", "authors": "..." }
    ]}
  ],
  "10": [
    { "id": 37, "name": "Learning & Training", "chair": "", "papers": [
      { "id": "P1442", "title": "VR Training for Emergency Response", "authors": "..." }
    ]}
  ],
  "11": [
    { "id": 41, "name": "Collaboration", "chair": "", "papers": [
      { "id": "P1663", "title": "Collaborative Virtual Environments for Remote Design", "authors": "..." }
    ]}
  ],
  "12": [
    { "id": 45, "name": "User Experience", "chair": "", "papers": [
      { "id": "P1883", "title": "Measuring UX in Mixed Reality", "authors": "..." }
    ]}
  ],
  "13": [
    { "id": 49, "name": "Mixed Reality Applications", "chair": "", "papers": [
      { "id": "P1212", "title": "MR for Heritage Visualization", "authors": "..." },
      { "id": "P1738", "title": "SceneHub4D: A Dataset and Evaluation Framework for 6-DoF 4D VR Scenes", "authors": "..." }
    ]},
    { "id": 50, "name": "User Input", "chair": "", "papers": [
      { "id": "TVCG-05", "title": "Integrating User Input in Automated Object Placement for Augmented Reality", "authors": "..." },
      { "id": "P1038", "title": "Evaluating the Viability of Additive Models to Predict Task Completion Time for 3D Interactions in Augmented Reality", "authors": "..." }
    ]}
  ]
};

// 모달 제어 함수
function openSessModal(psNum) {
    const sessions = psData[psNum];
    if (!sessions) return;

    let content = "";
    sessions.forEach((sess, index) => {
        content += `
            <div class="session-container">
                <span class="session-id-tag">Session ID: ${sess.id}</span>
                <span class="session-name-title">${sess.name}</span>
                <div class="session-chair-text">Session Chair: ${sess.chair || "TBA"}</div>
                <hr class="div-light">
        `;

        sess.papers.forEach((paper, pIdx) => {
            content += `
                <div class="paper-block">
                    · Paper ID: ${paper.id}<br>
                    · Paper Title: <span class="paper-title-text">${paper.title}</span><br>
                    <span class="author-list-text">· Author List: ${paper.authors}</span>
                </div>
            `;
            if (pIdx < sess.papers.length - 1) {
                content += `<hr class="div-light">`;
            }
        });

        content += `</div>`;
        
        // 같은 Parallel Session 내 다른 Session ID가 있을 경우 진한 구분선 추가
        if (index < sessions.length - 1) {
            content += `<hr class="div-heavy">`;
        }
    });

    document.getElementById("modalBody").innerHTML = content;
    document.getElementById("modalOverlay").style.display = "flex";
    document.body.style.overflow = "hidden"; // 배경 스크롤 차단
}

function closeModal() {
    document.getElementById("modalOverlay").style.display = "none";
    document.body.style.overflow = "auto";
}
</script>
