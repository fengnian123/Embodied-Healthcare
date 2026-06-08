<div align="center">

# Awesome Embodied Healthcare

A strict bibliography for healthcare systems where intelligence is grounded in bodies, actions, robots, or embodied interaction.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Last Updated](https://img.shields.io/badge/updated-2026--06--09-blue)](#)

</div>

## Overview

This repository curates papers and resources at the intersection of **embodied intelligence** and **healthcare**. The main list focuses on work where healthcare is connected to a robot body, physical interaction, simulated embodiment, clinical action loop, or human-robot interaction.

This is a strict re-screened list. Pure medical LLMs, EHR agents, static medical VLMs, screen-only clinical decision systems, and generic healthcare informatics papers are intentionally excluded from the main sections.

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

| Included | Excluded from main sections | Cross-listing |
| --- | --- | --- |
| Healthcare robotics, surgical autonomy, rehabilitation robots, assistive manipulation, social robots in care, hospital logistics robots, telepresence robots, embodied medical training systems, and healthcare-oriented robot learning datasets or simulators. | Screen-only medical foundation models, EHR/chat agents, medical image-only VLMs, clinical decision benchmarks without embodiment, and general hospital IT systems without a robot body or action loop. | A small number of resources appear in more than one section when they are both a task paper and a dataset, simulator, survey, or robot prototype. |

## Surveys and Scope

- **[Screens2Scenes] From screens to scenes: A survey of embodied AI in healthcare**<br>
  `Information Fusion 2025` | [[pdf]](https://arxiv.org/pdf/2501.07468) | [[doi]](https://doi.org/10.1016/j.inffus.2025.103033)<br>
  Defines healthcare EAI as perception-action systems rather than screen-only medical AI.

- **[LLM-HCR] The Future of Intelligent Healthcare: A Systematic Analysis and Discussion on the Integration and Impact of Robots Using Large Language Models for Healthcare**<br>
  `Robotics 2024` | [[pdf]](https://www.mdpi.com/2218-6581/13/8/112/pdf) | [[doi]](https://doi.org/10.3390/robotics13080112)<br>
  Identifies multimodal communication, semantic reasoning, and task planning as core LLM-healthcare-robot requirements.

- **[Healthcare-EAI-SR] Embodied Artificial Intelligence in Healthcare: A Systematic Review of Robotic Perception, Decision-Making, and Clinical Impact**<br>
  `Healthcare 2026` | [[pdf]](https://www.mdpi.com/2227-9032/14/5/572/pdf) | [[doi]](https://doi.org/10.3390/healthcare14050572)<br>
  Maps EAI evidence across surgery, rehabilitation, logistics, and telepresence.

- **[Robotic-Caregiving] Feeding, grooming, dressing, and body repositioning: categorizing four pillars of learning-based manipulation for robotic caregiving**<br>
  `Artificial Intelligence Review 2026` | [[doi]](https://doi.org/10.1007/s10462-026-11524-7)<br>
  Organizes physical caregiving manipulation around daily living tasks.

## Surgical Embodied Intelligence

- **[STAR] Supervised autonomous robotic soft tissue surgery**<br>
  `Science Translational Medicine 2016` | [[doi]](https://doi.org/10.1126/scitranslmed.aad9398)<br>
  Landmark supervised-autonomous soft-tissue surgery with perception, planning, and control.

- **[EndoNet] EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos**<br>
  `IEEE TMI 2016` | [[pdf]](https://hal.science/hal-03511473v1/document) | [[doi]](https://doi.org/10.1109/TMI.2016.2593957)<br>
  Surgical phase and tool recognition for embodied surgical perception.

- **[GestureBench] A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery**<br>
  `IEEE TBME 2017` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5559351/) | [[doi]](https://doi.org/10.1109/TBME.2016.2647680)<br>
  Standardizes gesture segmentation and recognition for robot-assisted surgery.

- **[STAR-Shared] A Confidence-Based Shared Control Strategy for the Smart Tissue Autonomous Robot (STAR)**<br>
  `IROS 2018` | [[doi]](https://doi.org/10.1109/IROS.2018.8594290)<br>
  Assigns autonomy based on robot confidence for safer human-robot surgical collaboration.

- **[Lap-Suturing] Autonomous Laparoscopic Robotic Suturing with a Novel Actuated Suturing Tool and 3D Endoscope**<br>
  `ICRA 2019` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7901147/) | [[doi]](https://doi.org/10.1109/ICRA.2019.8794306)<br>
  Extends autonomous suturing toward constrained laparoscopic settings.

- **[Auto-Electrosurgery] Supervised Autonomous Electrosurgery via Biocompatible Near-Infrared Tissue Tracking Techniques**<br>
  `IEEE TMRB 2019` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7810241/) | [[doi]](https://doi.org/10.1109/TMRB.2019.2949870)<br>
  Uses NIR tissue tracking for supervised autonomous surgical path execution.

- **[AI-SurgRob] Artificial Intelligence and the Future of Surgical Robotics**<br>
  `Annals of Surgery 2019` | [[doi]](https://doi.org/10.1097/SLA.0000000000003262)<br>
  Early clinical perspective on surgical robots evolving from teleoperation to autonomy.

- **[SurRoL] SurRoL: An Open-source Reinforcement Learning Centered and dVRK Compatible Platform for Surgical Robot Learning**<br>
  `IROS 2021` | [[doi]](https://doi.org/10.1109/IROS51168.2021.9635867) | [[code]](https://github.com/med-air/SurRoL)<br>
  dVRK-compatible simulator for surgical robot learning.

- **[STAR-Lap] Autonomous robotic laparoscopic surgery for intestinal anastomosis**<br>
  `Science Robotics 2022` | [[pmc]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8992572/) | [[doi]](https://doi.org/10.1126/scirobotics.abj2908)<br>
  Advances STAR to laparoscopic intestinal anastomosis with tissue tracking and adaptive control.

- **[SRT] Surgical Robot Transformer (SRT): Imitation Learning for Surgical Tasks**<br>
  `CoRL 2024` | [[pdf]](https://arxiv.org/pdf/2407.12998) | [[project]](https://surgical-robot-transformer.github.io/)<br>
  Adapts imitation learning to da Vinci data via relative actions.

- **[SRT-H] SRT-H: A Hierarchical Framework for Autonomous Surgery via Language Conditioned Imitation Learning**<br>
  `Science Robotics 2025` | [[pdf]](https://arxiv.org/pdf/2505.10251) | [[doi]](https://doi.org/10.1126/scirobotics.adt5254) | [[data]](https://doi.org/10.5281/zenodo.15637074)<br>
  Language-conditioned hierarchy for long-horizon autonomous surgical steps.

- **[Surgical-EI] Surgical embodied intelligence for generalized task autonomy in laparoscopic robot-assisted surgery**<br>
  `Science Robotics 2025` | [[doi]](https://doi.org/10.1126/scirobotics.adt3093) | [[code]](https://github.com/med-air/SurRoL)<br>
  VPPV pipeline and simulator for generalized laparoscopic task autonomy.

- **[RoboNurse-VLA] RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model**<br>
  `IROS 2025` | [[pdf]](https://arxiv.org/pdf/2409.19590) | [[project]](https://robonurse-vla.github.io/) | [[doi]](https://doi.org/10.1109/IROS60139.2025.11246030)<br>
  VLA-based surgical instrument grasping and handover.

## Rehabilitation and Physical Assistance

- **[UpperLimb-Rehab] A survey on robotic devices for upper limb rehabilitation**<br>
  `JNER 2014` | [[pdf]](https://jneuroengrehab.biomedcentral.com/counter/pdf/10.1186/1743-0003-11-3) | [[doi]](https://doi.org/10.1186/1743-0003-11-3)<br>
  Classic map of upper-limb rehabilitation robot mechanisms and clinical needs.

- **[Shared-pHRI] A Review of Intent Detection, Arbitration, and Communication Aspects of Shared Control for Physical Human-Robot Interaction**<br>
  `Applied Mechanics Reviews 2018` | [[pdf]](https://asmedigitalcollection.asme.org/appliedmechanicsreviews/article-pdf/70/1/010804/5964415/amr_070_01_010804.pdf) | [[doi]](https://doi.org/10.1115/1.4039145)<br>
  Foundation for shared control in rehabilitation, prosthetics, and assistive robots.

- **[AssistiveGym] Assistive Gym: A Physics Simulation Framework for Assistive Robotics**<br>
  `ICRA 2020` | [[pdf]](https://arxiv.org/pdf/1910.04700) | [[code]](https://github.com/Healthcare-Robotics/assistive-gym)<br>
  Simulation tasks for feeding, dressing, bathing, and physical assistance.

- **[RATULS] Robot-assisted training compared with enhanced upper limb therapy and usual care after stroke: the RATULS three-group RCT**<br>
  `Health Technology Assessment 2020` | [[pdf]](https://njl-admin.nihr.ac.uk/document/download/2034515) | [[doi]](https://doi.org/10.3310/hta24540)<br>
  Multicenter clinical trial evidence for upper-limb rehabilitation robots.

- **[Robotic-Caregiving] Feeding, grooming, dressing, and body repositioning: categorizing four pillars of learning-based manipulation for robotic caregiving**<br>
  `Artificial Intelligence Review 2026` | [[doi]](https://doi.org/10.1007/s10462-026-11524-7)<br>
  Links embodied intelligence with ADL-centered robotic caregiving.

## Caregiving, Elderly Care, and Social Robots

- **[SAR-Elderly] Socially Assistive Robots in Elderly Care: A Systematic Review into Effects and Effectiveness**<br>
  `JAMDA 2010` | [[doi]](https://doi.org/10.1016/j.jamda.2010.10.002)<br>
  Early evidence map for social robot interventions in elderly care.

- **[Robot-Therapist] Your Robot Therapist Will See You Now: Ethical Implications of Embodied Artificial Intelligence in Psychiatry, Psychology, and Psychotherapy**<br>
  `JMIR 2019` | [[pdf]](https://www.jmir.org/2019/5/e13216/PDF) | [[doi]](https://doi.org/10.2196/13216)<br>
  Ethical analysis of embodied AI in mental health care.

- **[SAR-Implementation] Enablers and barriers to the implementation of socially assistive humanoid robots in health and social care: a systematic review**<br>
  `BMJ Open 2020` | [[pdf]](https://bmjopen.bmj.com/content/bmjopen/10/1/e033096.full.pdf) | [[doi]](https://doi.org/10.1136/bmjopen-2019-033096)<br>
  Explains why healthcare robots fail or succeed in real care organizations.

- **[Social-Health] Assistive Robots for the Social Management of Health: A Framework for Robot Design and Human-Robot Interaction Research**<br>
  `International Journal of Social Robotics 2020` | [[pdf]](https://link.springer.com/content/pdf/10.1007/s12369-020-00634-z.pdf) | [[doi]](https://doi.org/10.1007/s12369-020-00634-z)<br>
  Frames health support as socially mediated robot interaction.

- **[Affective-SAR] Conversational Affective Social Robots for Ageing and Dementia Support**<br>
  `IEEE TCDS 2021` | [[doi]](https://doi.org/10.1109/TCDS.2021.3115228)<br>
  Emphasizes affective conversation, trust, and long-term dementia support.

- **[SAR-Dementia] Socially assistive robots for people with dementia: Systematic review and meta-analysis**<br>
  `Ageing Research Reviews 2022` | [[doi]](https://doi.org/10.1016/j.arr.2022.101633)<br>
  Evaluates feasibility, acceptability, and clinical effects of dementia-care robots.

- **[VP-Robot-LLM] Creating Virtual Patients using Robots and Large Language Models: A Preliminary Study with Medical Students**<br>
  `ACM HRI Companion 2024` | [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3610978.3640592) | [[doi]](https://doi.org/10.1145/3610978.3640592)<br>
  Social robot embodiment for interactive medical education.

- **[VP-Robot-JMIR] Virtual Patient Simulations Using Social Robotics Combined With Large Language Models for Clinical Reasoning Training in Medical Education**<br>
  `JMIR 2025` | [[doi]](https://doi.org/10.2196/63312)<br>
  Journal version of embodied virtual-patient training with LLM-driven interaction.

## Hospital Service and Nursing Robots

- **[RoNA] An advanced medical robotic system augmenting healthcare capabilities: robotic nursing assistant**<br>
  `ICRA 2011` | [[doi]](https://doi.org/10.1109/ICRA.2011.5980213)<br>
  Early mobile nursing assistant for patient handling and hospital support.

- **[ARNA] Acceptability of Using a Robotic Nursing Assistant in Health Care Environments: Experimental Pilot Study**<br>
  `JMIR 2020` | [[pdf]](https://www.jmir.org/2020/11/e17509/PDF) | [[doi]](https://doi.org/10.2196/17509)<br>
  Pilot evidence on nurse acceptance of an adaptive robotic nursing assistant.

- **[Delivery-Robots] Case studies on the usability, acceptability and functionality of autonomous mobile delivery robots in real-world healthcare settings**<br>
  `Intelligent Service Robotics 2021` | [[doi]](https://doi.org/10.1007/s11370-021-00368-5)<br>
  Real-world healthcare deployment evidence for mobile delivery robots.

- **[Inpatient-RNA] An Assessment of an Inpatient Robotic Nurse Assistant: A Mixed-Method Study**<br>
  `Journal of Medical Systems 2024` | [[pdf]](https://link.springer.com/content/pdf/10.1007/s10916-024-02117-4.pdf) | [[doi]](https://doi.org/10.1007/s10916-024-02117-4)<br>
  Ward-level assessment of robotic assistance for vital signs, medicine delivery, and reminders.

- **[Hospital-Risk] Boosting the hospital by integrating mobile robotic assistance systems: a comprehensive classification of the risks to be addressed**<br>
  `Autonomous Robots 2024` | [[pdf]](https://link.springer.com/content/pdf/10.1007/s10514-023-10154-0.pdf) | [[doi]](https://doi.org/10.1007/s10514-023-10154-0)<br>
  Risk taxonomy for translating mobile robot systems into hospitals.

- **[Hospital-Logistics] Application management and effectiveness analysis of intelligent logistics robots in hospital drug and specimen delivery scenarios**<br>
  `Scientific Reports 2026` | [[doi]](https://doi.org/10.1038/s41598-026-49800-9)<br>
  Six-month hospital deployment of drug and specimen delivery robots.

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

- **[VP-Robot-JMIR] Virtual Patient Simulations Using Social Robotics Combined With Large Language Models for Clinical Reasoning Training in Medical Education**<br>
  `JMIR 2025` | [[doi]](https://doi.org/10.2196/63312)<br>
  LLM plus social robot embodiment for clinical reasoning practice.

## Datasets, Simulators, and Benchmarks

- **[JIGSAWS] JHU-ISI Gesture and Skill Assessment Working Set (JIGSAWS): A Surgical Activity Dataset for Human Motion Modeling**<br>
  `M2CAI MICCAI Workshop 2014` | [[pdf]](https://cirl.lcsr.jhu.edu/wp-content/uploads/2015/11/JIGSAWS.pdf) | [[data]](https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/)<br>
  Video, kinematics, and skill labels for robot-assisted surgical training tasks.

- **[EndoNet] EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos**<br>
  `IEEE TMI 2016` | [[pdf]](https://hal.science/hal-03511473v1/document) | [[doi]](https://doi.org/10.1109/TMI.2016.2593957)<br>
  Cholec80-style laparoscopic workflow and tool recognition benchmark lineage.

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

## Embodied Intelligence Foundations

These papers are not healthcare papers. They are kept as compact conceptual and technical background because embodied healthcare builds on embodied intelligence.

- **[EmbodiedAI-Survey] A Survey of Embodied AI: From Simulators to Research Tasks**<br>
  `IEEE TETCI 2022` | [[doi]](https://doi.org/10.1109/TETCI.2022.3141105)<br>
  General embodied AI tasks and simulators.

- **[SayCan] Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**<br>
  `CoRL 2022` | [[pdf]](https://arxiv.org/pdf/2204.01691) | [[project]](https://say-can.github.io/)<br>
  Combines language priors with robot affordances.

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

- **[Code-as-Policies] Code as Policies: Language Model Programs for Embodied Control**<br>
  `ICRA 2023` | [[pdf]](https://arxiv.org/pdf/2209.07753) | [[project]](https://code-as-policies.github.io/)<br>
  LLM-generated executable robot policies.

- **[VoxPoser] VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**<br>
  `CoRL 2023` | [[pdf]](https://arxiv.org/pdf/2307.05973) | [[project]](https://voxposer.github.io/)<br>
  Language-conditioned 3D value maps for manipulation.

- **[EmbodiedIntelligence-AIR] A Comprehensive Survey on Embodied Intelligence: Advancements, Challenges, and Future Perspectives**<br>
  `CAAI AIR 2024` | [[doi]](https://doi.org/10.26599/AIR.2024.9150042)<br>
  Concept survey around perception-cognition-behavior integration.

- **[Open-X] Open X-Embodiment: Robotic Learning Datasets and RT-X Models**<br>
  `ICRA 2024` | [[pdf]](https://arxiv.org/pdf/2310.08864) | [[project]](https://robotics-transformer-x.github.io/)<br>
  Dataset consolidation for multi-robot generalization.

- **[EmbodiedIntelligence-CSUR] Embodied Intelligence: A Synergy of Morphology, Action, Perception and Learning**<br>
  `ACM CSUR 2025` | [[doi]](https://doi.org/10.1145/3717059)<br>
  Frames intelligence as a body-action-perception-learning synergy.

- **[ELLMER] Embodied large language models enable robots to complete complex tasks in unpredictable environments**<br>
  `Nature Machine Intelligence 2025` | [[pdf]](https://www.nature.com/articles/s42256-025-01005-x.pdf) | [[doi]](https://doi.org/10.1038/s42256-025-01005-x)<br>
  RAG plus LLM-enabled embodied robot execution in unpredictable environments.

## Excluded From This Strict Version

- Screen-only medical foundation models: Med-PaLM, GMAI, LLaVA-Med, Med-Flamingo, and generalist biomedical VLMs.
- Screen-only medical agents and benchmarks: EHRAgent, MedAgents, MedAgentsBench, AgentClinic, and clinical decision agent benchmarks.
- Generic healthcare AI, IoT, digital twin, and hospital informatics papers without a robot body, simulated embodiment, or action loop.

## Feedback

Suggested additions should be directly embodied, healthcare-relevant, and preferably supported by top venue acceptance, strong citations, real deployment evidence, open robot data or code, or clear community adoption.

If you find this project useful, a star is appreciated.
