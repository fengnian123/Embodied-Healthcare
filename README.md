<table>
  <tr>
    <td width="104" align="center">
      <img src="assets/embodied-healthcare-icon-256.png" alt="Embodied Healthcare icon" width="92">
    </td>
    <td>
      <h1>Awesome Embodied Healthcare</h1>
      <p>A strict bibliography for healthcare systems where intelligence is grounded in bodies, actions, robots, or embodied interaction.</p>
      <p>
        <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
        <img src="https://img.shields.io/badge/updated-2026--06--09-blue" alt="Last Updated">
      </p>
    </td>
  </tr>
</table>

## Overview

This repository curates papers and resources at the intersection of **embodied intelligence** and **healthcare**. The main list focuses on work where healthcare is connected to a robot body, physical interaction, simulated embodiment, clinical action loop, or human-robot interaction.

This is a strict re-screened list. Pure medical LLMs, EHR agents, static medical VLMs, screen-only clinical decision systems, and generic healthcare informatics papers are intentionally excluded from the main sections.

The list is intentionally biased toward recent work. Older papers are kept when they are field landmarks, high-citation surveys, clinical evidence papers, or widely reused datasets and benchmarks.

> This repository is a research bibliography, not medical advice or clinical deployment guidance. Publication labels are compact metadata for navigation; please verify final venue and citation details before formal use.

## Contents

- [Curation Scope](#curation-scope)
- [Surveys and Scope](#surveys-and-scope)
- [Surgical Embodied Intelligence](#surgical-embodied-intelligence)
- [Rehabilitation and Physical Assistance](#rehabilitation-and-physical-assistance)
- [Caregiving, Elderly Care, and Social Robots](#caregiving-elderly-care-and-social-robots)
- [Hospital Service and Nursing Robots](#hospital-service-and-nursing-robots)
- [Healthcare LLM / VLA Robot Prototypes](#healthcare-llm--vla-robot-prototypes)
- [Datasets, Simulators, and Benchmarks](#datasets-simulators-and-benchmarks)
- [Embodied Intelligence Foundations](#embodied-intelligence-foundations)
- [Excluded From This Strict Version](#excluded-from-this-strict-version)
- [Feedback](#feedback)

## Curation Scope

| Included | Excluded from main sections | Selection rule |
| --- | --- | --- |
| Healthcare robotics, surgical autonomy, rehabilitation robots, assistive manipulation, social robots in care, hospital logistics robots, telepresence robots, embodied medical training systems, and healthcare-oriented robot learning datasets or simulators. | Screen-only medical foundation models, EHR/chat agents, medical image-only VLMs, clinical decision benchmarks without embodiment, and general hospital IT systems without a robot body or action loop. | Older papers are retained only when they are landmarks, high-citation surveys, clinical evidence papers, or widely used datasets/benchmarks. Recent papers are prioritized when they involve real robots, strong institutions, top venues, open datasets/code, or direct healthcare embodiment. |

**Cross-listing policy:** a small number of resources appear in more than one section when they are both a task paper and a dataset, simulator, survey, or robot prototype.

## Surveys and Scope

- **[Robotics-Healthcare] Robotics in Healthcare: A Survey**<br>
  `SN Computer Science 2024` | [[doi]](https://doi.org/10.1007/s42979-023-02551-0)<br>
  Recent broad survey with high readership and citation signal; useful for clinical robotics scope and deployment challenges.

- **[Screens2Scenes] From screens to scenes: A survey of embodied AI in healthcare**<br>
  `Information Fusion 2025` | [[pdf]](https://arxiv.org/pdf/2501.07468) | [[doi]](https://doi.org/10.1016/j.inffus.2025.103033)<br>
  Defines healthcare EAI as perception-action systems rather than screen-only medical AI.

- **[LLM-HCR] The Future of Intelligent Healthcare: A Systematic Analysis and Discussion on the Integration and Impact of Robots Using Large Language Models for Healthcare**<br>
  `Robotics 2024` | [[pdf]](https://www.mdpi.com/2218-6581/13/8/112/pdf) | [[doi]](https://doi.org/10.3390/robotics13080112)<br>
  Identifies multimodal communication, semantic reasoning, and task planning as core LLM-healthcare-robot requirements.

- **[Healthcare-EAI-SR] Embodied Artificial Intelligence in Healthcare: A Systematic Review of Robotic Perception, Decision-Making, and Clinical Impact**<br>
  `Healthcare 2026` | [[pdf]](https://www.mdpi.com/2227-9032/14/5/572/pdf) | [[doi]](https://doi.org/10.3390/healthcare14050572)<br>
  Systematic review of healthcare EAI across surgical assistance, rehabilitation, hospital logistics, and telepresence.

- **[Foundation-Service-Robots] Embodied AI with Foundation Models for Mobile Service Robots: A Systematic Review**<br>
  `arXiv 2025` | [[pdf]](https://arxiv.org/pdf/2505.20503) | [[abs]](https://arxiv.org/abs/2505.20503)<br>
  Covers foundation-model service robots and explicitly discusses healthcare-facing deployment opportunities.

- **[SASR-Health] A Narrative Review of Systematic Reviews on the Applications of Social and Assistive Support Robots in the Health Domain**<br>
  `Applied Sciences 2025` | [[doi]](https://doi.org/10.3390/app15073793)<br>
  Summarizes recent systematic-review evidence for social and assistive robots in healthcare, therapy, dementia, and elder care.

- **[Pediatric-EAI] A Survey on Embodied AI for Pediatrics**<br>
  `CVPRW 2026` | [[pdf]](https://openaccess.thecvf.com/content/CVPR2026W/CV4CHL/papers/Shen_A_Survey_on_Embodied_AI_for_Pediatrics_CVPRW_2026_paper.pdf)<br>
  Recent healthcare-specific survey focused on pediatric embodied AI, closed-loop medical workflows, and autonomy levels.

- **[Robotic-Caregiving] Feeding, grooming, dressing, and body repositioning: categorizing four pillars of learning-based manipulation for robotic caregiving**<br>
  `Artificial Intelligence Review 2026` | [[doi]](https://doi.org/10.1007/s10462-026-11524-7)<br>
  Organizes physical caregiving manipulation around daily living tasks.

## Surgical Embodied Intelligence

- **[STAR] Supervised autonomous robotic soft tissue surgery**<br>
  `Science Translational Medicine 2016` | [[doi]](https://doi.org/10.1126/scitranslmed.aad9398)<br>
  Landmark supervised-autonomous soft-tissue surgery with perception, planning, and control.

- **[EndoNet] EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos**<br>
  `IEEE TMI 2016` | [[pdf]](https://hal.science/hal-03511473v1/document) | [[doi]](https://doi.org/10.1109/TMI.2016.2593957)<br>
  High-impact surgical phase and tool recognition paper; retained as a foundational surgical perception baseline.

- **[GestureBench] A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery**<br>
  `IEEE TBME 2017` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5559351/) | [[doi]](https://doi.org/10.1109/TBME.2016.2647680)<br>
  Standardizes gesture segmentation and recognition for robot-assisted surgery.

- **[AI-SurgRob] Artificial Intelligence and the Future of Surgical Robotics**<br>
  `Annals of Surgery 2019` | [[doi]](https://doi.org/10.1097/SLA.0000000000003262)<br>
  Influential clinical perspective on surgical robots evolving from teleoperation to autonomy.

- **[STAR-Lap] Autonomous robotic laparoscopic surgery for intestinal anastomosis**<br>
  `Science Robotics 2022` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8992572/) | [[doi]](https://doi.org/10.1126/scirobotics.abj2908)<br>
  Major STAR extension to laparoscopic intestinal anastomosis with tissue tracking and adaptive control.

- **[SuFIA] Language-Guided Augmented Dexterity for Robotic Surgical Assistants**<br>
  `IROS 2024` | [[project]](https://orbit-surgical.github.io/sufia)<br>
  Uses LLM-driven task planning and perception for surgical assistant sub-tasks such as tool handover.

- **[SRT] Surgical Robot Transformer (SRT): Imitation Learning for Surgical Tasks**<br>
  `CoRL 2024` | [[pdf]](https://arxiv.org/pdf/2407.12998) | [[project]](https://surgical-robot-transformer.github.io/)<br>
  Learns da Vinci surgical tasks from imitation data using a relative-action formulation.

- **[SurgIRL] SurgIRL: Towards Life-Long Learning for Surgical Automation by Incremental Reinforcement Learning**<br>
  `arXiv 2024 / ICRA 2025 workshop` | [[project]](https://ucsdarclab.com/autopublication/surgirl-towards-life-long-learning-for-surgical-automation-by-incremental-reinforcement-learning/)<br>
  Recent surgical automation work emphasizing incremental reinforcement learning and sim-to-real dVRK evaluation.

- **[SRT-H] SRT-H: A Hierarchical Framework for Autonomous Surgery via Language Conditioned Imitation Learning**<br>
  `Science Robotics 2025` | [[pdf]](https://arxiv.org/pdf/2505.10251) | [[doi]](https://doi.org/10.1126/scirobotics.adt5254) | [[data]](https://doi.org/10.5281/zenodo.15637074)<br>
  Language-conditioned hierarchy for long-horizon autonomous surgical steps; strong recent milestone in surgical autonomy.

- **[Surgical-EI] Surgical embodied intelligence for generalized task autonomy in laparoscopic robot-assisted surgery**<br>
  `Science Robotics 2025` | [[doi]](https://doi.org/10.1126/scirobotics.adt3093) | [[code]](https://github.com/med-air/SurRoL)<br>
  VPPV pipeline and simulator for generalized laparoscopic task autonomy.

- **[RoboNurse-VLA] RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model**<br>
  `IROS 2025` | [[pdf]](https://arxiv.org/pdf/2409.19590) | [[project]](https://robonurse-vla.github.io/) | [[doi]](https://doi.org/10.1109/IROS60139.2025.11246030)<br>
  VLA-based surgical instrument grasping and handover using vision, language, and robot action.

- **[SutureBot] SutureBot: A Precision Framework and Benchmark For Autonomous End-to-End Suturing**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2510.20965) | [[data]](https://huggingface.co/datasets/jchen396/suturebot)<br>
  New dVRK suturing benchmark and dataset evaluating long-horizon autonomous suturing and modern VLA policies.

## Rehabilitation and Physical Assistance

- **[UpperLimb-Rehab] A survey on robotic devices for upper limb rehabilitation**<br>
  `JNER 2014` | [[pdf]](https://jneuroengrehab.biomedcentral.com/counter/pdf/10.1186/1743-0003-11-3) | [[doi]](https://doi.org/10.1186/1743-0003-11-3)<br>
  Older but high-impact map of upper-limb rehabilitation robot mechanisms and clinical needs.

- **[Shared-pHRI] A Review of Intent Detection, Arbitration, and Communication Aspects of Shared Control for Physical Human-Robot Interaction**<br>
  `Applied Mechanics Reviews 2018` | [[pdf]](https://asmedigitalcollection.asme.org/appliedmechanicsreviews/article-pdf/70/1/010804/5964415/amr_070_01_010804.pdf) | [[doi]](https://doi.org/10.1115/1.4039145)<br>
  Foundational shared-control review for rehabilitation, prosthetics, and assistive robots.

- **[AssistiveGym] Assistive Gym: A Physics Simulation Framework for Assistive Robotics**<br>
  `ICRA 2020` | [[pdf]](https://arxiv.org/pdf/1910.04700) | [[code]](https://github.com/Healthcare-Robotics/assistive-gym)<br>
  Widely used simulation tasks for feeding, dressing, bathing, and physical assistance.

- **[RATULS] Robot-assisted training compared with enhanced upper limb therapy and usual care after stroke: the RATULS three-group RCT**<br>
  `Health Technology Assessment 2020` | [[pdf]](https://njl-admin.nihr.ac.uk/document/download/2034515) | [[doi]](https://doi.org/10.3310/hta24540)<br>
  Multicenter clinical trial evidence for upper-limb rehabilitation robots.

- **[UL-Rehab-2024] Assistive Robotics for Upper Limb Physical Rehabilitation: A Systematic Review and Future Prospects**<br>
  `Chinese Journal of Mechanical Engineering 2024` | [[doi]](https://doi.org/10.1186/s10033-024-01056-y)<br>
  Recent rehabilitation robotics review with bibliometric analysis and forward-looking technical challenges.

- **[SoftRehab] Soft Robotics in Upper Limb Neurorehabilitation and Assistance: Current Clinical Evidence and Recommendations**<br>
  `Soft Robotics 2025` | [[doi]](https://doi.org/10.1089/soro.2024.0034)<br>
  Recent clinical-evidence perspective on soft wearable robots for neurorehabilitation and assistance.

- **[Robotic-Caregiving] Feeding, grooming, dressing, and body repositioning: categorizing four pillars of learning-based manipulation for robotic caregiving**<br>
  `Artificial Intelligence Review 2026` | [[doi]](https://doi.org/10.1007/s10462-026-11524-7)<br>
  Links embodied intelligence with ADL-centered robotic caregiving.

- **[HMR-1] HMR-1: Hierarchical Massage Robot with Vision-Language-Model for Embodied Healthcare**<br>
  `arXiv 2026` | [[abs]](https://arxiv.org/abs/2603.08817) | [[code]](https://github.com/Xiaofeng-Han-Res/HMR-1)<br>
  Recent embodied healthcare prototype with acupoint grounding, massage control, physical experiments, and MedMassage-12K.

## Caregiving, Elderly Care, and Social Robots

- **[SAR-Elderly] Socially Assistive Robots in Elderly Care: A Systematic Review into Effects and Effectiveness**<br>
  `JAMDA 2010` | [[doi]](https://doi.org/10.1016/j.jamda.2010.10.002)<br>
  Older but highly cited evidence map for social robot interventions in elderly care.

- **[Robot-Therapist] Your Robot Therapist Will See You Now: Ethical Implications of Embodied Artificial Intelligence in Psychiatry, Psychology, and Psychotherapy**<br>
  `JMIR 2019` | [[pdf]](https://www.jmir.org/2019/5/e13216/PDF) | [[doi]](https://doi.org/10.2196/13216)<br>
  Important ethics paper for embodied AI in mental health care.

- **[SAR-Implementation] Enablers and barriers to the implementation of socially assistive humanoid robots in health and social care: a systematic review**<br>
  `BMJ Open 2020` | [[pdf]](https://bmjopen.bmj.com/content/bmjopen/10/1/e033096.full.pdf) | [[doi]](https://doi.org/10.1136/bmjopen-2019-033096)<br>
  Explains why healthcare robots fail or succeed in real care organizations.

- **[SAR-Dementia] Socially assistive robots for people with dementia: Systematic review and meta-analysis**<br>
  `Ageing Research Reviews 2022` | [[doi]](https://doi.org/10.1016/j.arr.2022.101633)<br>
  Strong evidence review of feasibility, acceptability, and clinical effects of dementia-care robots.

- **[VP-Robot-LLM] Creating Virtual Patients using Robots and Large Language Models: A Preliminary Study with Medical Students**<br>
  `ACM HRI Companion 2024` | [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3610978.3640592) | [[doi]](https://doi.org/10.1145/3610978.3640592)<br>
  Social robot embodiment for interactive medical education.

- **[VP-Robot-JMIR] Virtual Patient Simulations Using Social Robotics Combined With Large Language Models for Clinical Reasoning Training in Medical Education**<br>
  `JMIR 2025` | [[doi]](https://doi.org/10.2196/63312)<br>
  Journal version of embodied virtual-patient training with LLM-driven interaction.

- **[CareRobots-OlderAdults] The impact of care robots on older adults: A systematic review**<br>
  `Geriatric Nursing 2025` | [[pubmed]](https://pubmed.ncbi.nlm.nih.gov/40669132/) | [[doi]](https://doi.org/10.1016/j.gerinurse.2025.103507)<br>
  Recent systematic review of care robots' effects on older adults' well-being, quality of life, and health outcomes.

- **[LLM-SAR-Geriatric] Integrating a Large Language Model Into a Socially Assistive Robot in a Hospital Geriatric Unit**<br>
  `JMIR Human Factors 2025` | [[paper]](https://humanfactors.jmir.org/2025/1/e81936)<br>
  Recent hospital study of an LLM-enabled socially assistive robot with user engagement and perception evaluation.

- **[Dementia-Speech-Robot] Developing Conversational Speech Systems for Robots to Detect Speech Biomarkers of Cognition in People Living with Dementia**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2502.10896)<br>
  Recent robot conversation system using LLM-backed dialogue for dementia-related speech biomarker collection.

- **[OpenRoboCare] OpenRoboCare: A Multimodal Multi-Task Expert Demonstration Dataset for Robot Caregiving**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2511.13707)<br>
  Expert occupational-therapist demonstrations for ADL caregiving with RGB-D, pose, gaze, annotation, and tactile signals.

## Hospital Service and Nursing Robots

- **[RoNA] An advanced medical robotic system augmenting healthcare capabilities: robotic nursing assistant**<br>
  `ICRA 2011` | [[doi]](https://doi.org/10.1109/ICRA.2011.5980213)<br>
  Older but retained as an early mobile nursing assistant reference for patient handling and hospital support.

- **[ARNA] Acceptability of Using a Robotic Nursing Assistant in Health Care Environments: Experimental Pilot Study**<br>
  `JMIR 2020` | [[pdf]](https://www.jmir.org/2020/11/e17509/PDF) | [[doi]](https://doi.org/10.2196/17509)<br>
  Pilot evidence on nurse acceptance of an adaptive robotic nursing assistant.

- **[Inpatient-RNA] An Assessment of an Inpatient Robotic Nurse Assistant: A Mixed-Method Study**<br>
  `Journal of Medical Systems 2024` | [[pdf]](https://link.springer.com/content/pdf/10.1007/s10916-024-02117-4.pdf) | [[doi]](https://doi.org/10.1007/s10916-024-02117-4)<br>
  Ward-level assessment of robotic assistance for vital signs, medicine delivery, and reminders.

- **[Hospital-Risk] Boosting the hospital by integrating mobile robotic assistance systems: a comprehensive classification of the risks to be addressed**<br>
  `Autonomous Robots 2024` | [[pdf]](https://link.springer.com/content/pdf/10.1007/s10514-023-10154-0.pdf) | [[doi]](https://doi.org/10.1007/s10514-023-10154-0)<br>
  Risk taxonomy for translating mobile robot systems into hospitals.

- **[Humanoids-Hospitals] Humanoids in Hospitals: A Technical Study of Humanoid Surrogates for Dexterous Medical Interventions**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2503.12725)<br>
  Explores humanoid teleoperation for medical interventions and exposes current limits of dexterous hospital robots.

- **[ORB] ORB: Operating Room Bot, Automating Operating Room Logistics through Mobile Manipulation**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2509.15600)<br>
  Recent operating-room logistics framework for mobile manipulation in hospital environments.

- **[Nursing-Control] Developing a Cross-Device Platform for Robotic Systems in Nursing Care: Mixed Methods Feasibility Study**<br>
  `JMIR Nursing 2026` | [[pdf]](https://nursing.jmir.org/2026/1/e84118/PDF)<br>
  Recent nursing-care feasibility study on interfaces for controlling robotic systems in care facilities.

- **[Hospital-Logistics] Application management and effectiveness analysis of intelligent logistics robots in hospital drug and specimen delivery scenarios**<br>
  `Scientific Reports 2026` | [[doi]](https://doi.org/10.1038/s41598-026-49800-9)<br>
  Recent hospital deployment evidence for drug and specimen logistics robots.

## Healthcare LLM / VLA Robot Prototypes

- **[RHA-LLM] Framework for Integrating Large Language Models with a Robotic Health Attendant for Adaptive Task Execution in Patient Care**<br>
  `Applied Sciences 2024` | [[pdf]](https://www.mdpi.com/2076-3417/14/21/9922/pdf) | [[doi]](https://doi.org/10.3390/app14219922)<br>
  LLM-mediated task execution framework for a robotic health attendant.

- **[RoboNurse-VLA] RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model**<br>
  `IROS 2025` | [[pdf]](https://arxiv.org/pdf/2409.19590) | [[project]](https://robonurse-vla.github.io/) | [[doi]](https://doi.org/10.1109/IROS60139.2025.11246030)<br>
  Direct healthcare VLA prototype for surgical tool handover.

- **[Home-HCR-LLM] Task Decomposition and Self-Evaluation Mechanisms for Home Healthcare Robots Using Large Language Models**<br>
  `IEEE Access 2025` | [[doi]](https://doi.org/10.1109/access.2025.3559076)<br>
  LLM task decomposition and self-evaluation for home healthcare robot manipulation.

- **[AoECR] AoECR: AI-ization of Elderly Care Robot**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2502.19706)<br>
  Elderly-care robot project using a nursing-bed setting, patient-nurse interaction data, and an LLM for nursing manipulation.

- **[HMR-1] HMR-1: Hierarchical Massage Robot with Vision-Language-Model for Embodied Healthcare**<br>
  `arXiv 2026` | [[abs]](https://arxiv.org/abs/2603.08817) | [[code]](https://github.com/Xiaofeng-Han-Res/HMR-1)<br>
  Healthcare-specific VLM robot prototype for acupoint grounding and massage trajectory execution.

- **[GR00T-Surgical] GR00T N1.5 for SO-ARM Starter: Surgical Assistance Model Card**<br>
  `NVIDIA / Hugging Face 2026` | [[model]](https://huggingface.co/nvidia/SO_ARM_Starter_Gr00t)<br>
  Healthcare-facing VLA model card for autonomous surgical instrument management in Isaac for Healthcare.

## Datasets, Simulators, and Benchmarks

- **[JIGSAWS] JHU-ISI Gesture and Skill Assessment Working Set (JIGSAWS): A Surgical Activity Dataset for Human Motion Modeling**<br>
  `M2CAI MICCAI Workshop 2014` | [[pdf]](https://cirl.lcsr.jhu.edu/wp-content/uploads/2015/11/JIGSAWS.pdf) | [[data]](https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/)<br>
  Older but still important video, kinematics, and skill-label dataset for robot-assisted surgical training tasks.

- **[GestureBench] A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery**<br>
  `IEEE TBME 2017` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5559351/) | [[doi]](https://doi.org/10.1109/TBME.2016.2647680)<br>
  Benchmark protocol for robotic surgery gesture analysis.

- **[AssistiveGym] Assistive Gym: A Physics Simulation Framework for Assistive Robotics**<br>
  `ICRA 2020` | [[pdf]](https://arxiv.org/pdf/1910.04700) | [[code]](https://github.com/Healthcare-Robotics/assistive-gym)<br>
  Embodied simulation for physical assistance tasks.

- **[SurRoL] SurRoL: An Open-source Reinforcement Learning Centered and dVRK Compatible Platform for Surgical Robot Learning**<br>
  `IROS 2021` | [[doi]](https://doi.org/10.1109/IROS51168.2021.9635867) | [[code]](https://github.com/med-air/SurRoL)<br>
  Surgical robot learning simulator aligned with dVRK.

- **[Open-X] Open X-Embodiment: Robotic Learning Datasets and RT-X Models**<br>
  `ICRA 2024` | [[pdf]](https://arxiv.org/pdf/2310.08864) | [[project]](https://robotics-transformer-x.github.io/)<br>
  Cross-embodiment robot data model, useful as a reference for future medical robot datasets.

- **[SRT-H-Data] SRT-H supplementary data**<br>
  `Science Robotics 2025` | [[data]](https://doi.org/10.5281/zenodo.15637074)<br>
  Public artifact for language-conditioned surgical imitation learning.

- **[OpenRoboCare] OpenRoboCare: A Multimodal Multi-Task Expert Demonstration Dataset for Robot Caregiving**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2511.13707)<br>
  Multimodal ADL caregiving demonstrations from occupational therapists.

- **[SutureBot] SutureBot: A Precision Framework and Benchmark For Autonomous End-to-End Suturing**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2510.20965) | [[data]](https://huggingface.co/datasets/jchen396/suturebot)<br>
  dVRK suturing dataset and benchmark for precision-focused, long-horizon surgical manipulation.

- **[MedMassage-12K] MedMassage-12K / HMR-1 Benchmark**<br>
  `arXiv 2026` | [[abs]](https://arxiv.org/abs/2603.08817) | [[code]](https://github.com/Xiaofeng-Han-Res/HMR-1)<br>
  Multimodal acupoint massage dataset and benchmark for embodied healthcare VLMs.

## Embodied Intelligence Foundations

These papers are not healthcare papers. They are kept as compact conceptual and technical background because embodied healthcare builds on embodied intelligence. Older foundation papers are retained only when they remain major references for current robot learning or VLA work.

- **[SayCan] Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**<br>
  `CoRL 2022` | [[pdf]](https://arxiv.org/pdf/2204.01691) | [[project]](https://say-can.github.io/)<br>
  Landmark method combining language priors with robot affordances.

- **[PaLM-E] PaLM-E: An Embodied Multimodal Language Model**<br>
  `ICML 2023` | [[pdf]](https://arxiv.org/pdf/2303.03378) | [[project]](https://palm-e.github.io/)<br>
  Injects visual and robot-state tokens into language models.

- **[RT-1] RT-1: Robotics Transformer for Real-World Control at Scale**<br>
  `RSS 2023` | [[doi]](https://doi.org/10.15607/RSS.2023.XIX.025) | [[project]](https://robotics-transformer1.github.io/)<br>
  Large-scale real-world robot policy learning.

- **[RT-2] RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**<br>
  `CoRL 2023` | [[pdf]](https://proceedings.mlr.press/v229/zitkovich23a/zitkovich23a.pdf) | [[project]](https://robotics-transformer2.github.io/)<br>
  Transfers web-scale VLM knowledge into robot actions.

- **[DiffusionPolicy] Diffusion Policy: Visuomotor Policy Learning via Action Diffusion**<br>
  `RSS 2023` | [[doi]](https://doi.org/10.15607/RSS.2023.XIX.026) | [[code]](https://github.com/real-stanford/diffusion_policy)<br>
  Diffusion-based action generation for dexterous manipulation.

- **[VoxPoser] VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**<br>
  `CoRL 2023` | [[pdf]](https://arxiv.org/pdf/2307.05973) | [[project]](https://voxposer.github.io/)<br>
  Language-conditioned 3D value maps for manipulation.

- **[Open-X] Open X-Embodiment: Robotic Learning Datasets and RT-X Models**<br>
  `ICRA 2024` | [[pdf]](https://arxiv.org/pdf/2310.08864) | [[project]](https://robotics-transformer-x.github.io/)<br>
  Dataset consolidation for multi-robot generalization.

- **[AutoRT] AutoRT: Embodied Foundation Models for Large Scale Orchestration of Robotic Agents**<br>
  `arXiv 2024` | [[abs]](https://arxiv.org/abs/2401.12963)<br>
  Uses foundation models to orchestrate robot fleets and scale real-world robot data collection.

- **[ELLMER] Embodied large language models enable robots to complete complex tasks in unpredictable environments**<br>
  `Nature Machine Intelligence 2025` | [[pdf]](https://www.nature.com/articles/s42256-025-01005-x.pdf) | [[doi]](https://doi.org/10.1038/s42256-025-01005-x)<br>
  RAG plus LLM-enabled embodied robot execution in unpredictable environments.

- **[RoboNeuron] RoboNeuron: A Middle-Layer Infrastructure for Agent-Driven Orchestration in Embodied AI**<br>
  `arXiv 2025` | [[abs]](https://arxiv.org/abs/2512.10394)<br>
  Recent middleware layer connecting MCP-style LLM agents with robot middleware such as ROS2.

## Excluded From This Strict Version

- Screen-only medical foundation models: Med-PaLM, GMAI, LLaVA-Med, Med-Flamingo, and generalist biomedical VLMs.
- Screen-only medical agents and benchmarks: EHRAgent, MedAgents, MedAgentsBench, AgentClinic, and clinical decision agent benchmarks.
- Generic healthcare AI, IoT, digital twin, and hospital informatics papers without a robot body, simulated embodiment, or action loop.

## Feedback

Suggested additions should be directly embodied, healthcare-relevant, and preferably supported by top venue acceptance, strong citations, real deployment evidence, open robot data or code, or clear community adoption.

If you find this project useful, a star is appreciated.
