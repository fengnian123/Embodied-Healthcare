# Awesome-Embodied-Healthcare-Strict **If you find this project helpful, please consider giving it a star.**

**Last Updated: 2026-06-08**

New updates are added directly to their corresponding sections.

This is a stricter re-screened list for **Embodied Healthcare**. The main list keeps papers where healthcare meets embodied intelligence through a robot body, physical interaction, simulated embodiment, clinical action loop, or human-robot interaction. Pure medical LLMs, EHR agents, static medical VLMs, and screen-only clinical decision papers are intentionally excluded from the main sections.

## Contents

- [Awesome-Embodied-Healthcare-Strict](#awesome-embodied-healthcare-strict-if-you-find-this-project-helpful-please-consider-giving-it-a-star)
- [Contents](#contents)
- [Surveys and Scope](#surveys-and-scope)
- [Surgical Embodied Intelligence](#surgical-embodied-intelligence)
- [Rehabilitation and Physical Assistance](#rehabilitation-and-physical-assistance)
- [Caregiving, Elderly Care, and Social Robots](#caregiving-elderly-care-and-social-robots)
- [Hospital Service and Nursing Robots](#hospital-service-and-nursing-robots)
- [Healthcare LLM/VLA Robot Prototypes](#healthcare-llmvla-robot-prototypes)
- [Datasets, Simulators, and Benchmarks](#datasets-simulators-and-benchmarks)
- [Embodied Intelligence Foundations](#embodied-intelligence-foundations)
- [Excluded From This Strict Version](#excluded-from-this-strict-version)
- [Feedback](#feedback)

## Surveys and Scope

1. **[Screens2Scenes]** | **Information Fusion'25** | From screens to scenes: A survey of embodied AI in healthcare | [`[pdf]`](https://arxiv.org/pdf/2501.07468) | [`[doi]`](https://doi.org/10.1016/j.inffus.2025.103033) | _Key: defines healthcare EAI as perception-action systems rather than screen-only medical AI._
2. **[LLM-HCR]** | **Robotics'24** | The Future of Intelligent Healthcare: A Systematic Analysis and Discussion on the Integration and Impact of Robots Using Large Language Models for Healthcare | [`[pdf]`](https://www.mdpi.com/2218-6581/13/8/112/pdf) | [`[doi]`](https://doi.org/10.3390/robotics13080112) | _Key: identifies multimodal communication, semantic reasoning, and task planning as core LLM-healthcare-robot requirements._
3. **[Healthcare-EAI-SR]** | **Healthcare'26** | Embodied Artificial Intelligence in Healthcare: A Systematic Review of Robotic Perception, Decision-Making, and Clinical Impact | [`[pdf]`](https://www.mdpi.com/2227-9032/14/5/572/pdf) | [`[doi]`](https://doi.org/10.3390/healthcare14050572) | _Key: maps EAI evidence across surgery, rehabilitation, logistics, and telepresence._
4. **[Robotic-Caregiving]** | **Artificial Intelligence Review'26** | Feeding, grooming, dressing, and body repositioning: categorizing four pillars of learning-based manipulation for robotic caregiving | [`[doi]`](https://doi.org/10.1007/s10462-026-11524-7) | _Key: organizes physical caregiving manipulation around daily living tasks._

## Surgical Embodied Intelligence

1. **[STAR]** | **Sci. Transl. Med.'16** | Supervised autonomous robotic soft tissue surgery | [`[doi]`](https://doi.org/10.1126/scitranslmed.aad9398) | _Key: landmark supervised-autonomous soft-tissue surgery with perception, planning, and control._
2. **[EndoNet]** | **TMI'16** | EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos | [`[pdf]`](https://hal.science/hal-03511473v1/document) | [`[doi]`](https://doi.org/10.1109/TMI.2016.2593957) | _Key: surgical phase and tool recognition for embodied surgical perception._
3. **[GestureBench]** | **TBME'17** | A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery | [`[pmc]`](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5559351/) | [`[doi]`](https://doi.org/10.1109/TBME.2016.2647680) | _Key: standardizes gesture segmentation and recognition for robot-assisted surgery._
4. **[STAR-Shared]** | **IROS'18** | A Confidence-Based Shared Control Strategy for the Smart Tissue Autonomous Robot (STAR) | [`[doi]`](https://doi.org/10.1109/IROS.2018.8594290) | _Key: assigns autonomy based on robot confidence for safer human-robot surgical collaboration._
5. **[Lap-Suturing]** | **ICRA'19** | Autonomous Laparoscopic Robotic Suturing with a Novel Actuated Suturing Tool and 3D Endoscope | [`[pmc]`](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7901147/) | [`[doi]`](https://doi.org/10.1109/ICRA.2019.8794306) | _Key: extends autonomous suturing toward constrained laparoscopic settings._
6. **[Auto-Electrosurgery]** | **TMRB'19** | Supervised Autonomous Electrosurgery via Biocompatible Near-Infrared Tissue Tracking Techniques | [`[pmc]`](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7810241/) | [`[doi]`](https://doi.org/10.1109/TMRB.2019.2949870) | _Key: uses NIR tissue tracking for supervised autonomous surgical path execution._
7. **[AI-SurgRob]** | **Annals of Surgery'19** | Artificial Intelligence and the Future of Surgical Robotics | [`[doi]`](https://doi.org/10.1097/SLA.0000000000003262) | _Key: early clinical perspective on surgical robots evolving from teleoperation to autonomy._
8. **[SurRoL]** | **IROS'21** | SurRoL: An Open-source Reinforcement Learning Centered and dVRK Compatible Platform for Surgical Robot Learning | [`[doi]`](https://doi.org/10.1109/IROS51168.2021.9635867) | [`[code]`](https://github.com/med-air/SurRoL) | _Key: dVRK-compatible simulator for surgical robot learning._
9. **[STAR-Lap]** | **Science Robotics'22** | Autonomous robotic laparoscopic surgery for intestinal anastomosis | [`[pmc]`](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8992572/) | [`[doi]`](https://doi.org/10.1126/scirobotics.abj2908) | _Key: advances STAR to laparoscopic intestinal anastomosis with tissue tracking and adaptive control._
10. **[SRT]** | **CoRL'24** | Surgical Robot Transformer (SRT): Imitation Learning for Surgical Tasks | [`[pdf]`](https://arxiv.org/pdf/2407.12998) | [`[project]`](https://surgical-robot-transformer.github.io/) | _Key: adapts imitation learning to da Vinci data via relative actions._
11. **[SRT-H]** | **Science Robotics'25** | SRT-H: A Hierarchical Framework for Autonomous Surgery via Language Conditioned Imitation Learning | [`[pdf]`](https://arxiv.org/pdf/2505.10251) | [`[doi]`](https://doi.org/10.1126/scirobotics.adt5254) | [`[data]`](https://doi.org/10.5281/zenodo.15637074) | _Key: language-conditioned hierarchy for long-horizon autonomous surgical steps._
12. **[Surgical-EI]** | **Science Robotics'25** | Surgical embodied intelligence for generalized task autonomy in laparoscopic robot-assisted surgery | [`[doi]`](https://doi.org/10.1126/scirobotics.adt3093) | [`[code]`](https://github.com/med-air/SurRoL) | _Key: VPPV pipeline and simulator for generalized laparoscopic task autonomy._
13. **[RoboNurse-VLA]** | **IROS'25** | RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model | [`[pdf]`](https://arxiv.org/pdf/2409.19590) | [`[project]`](https://robonurse-vla.github.io/) | _Key: VLA-based surgical instrument grasping and handover._

## Rehabilitation and Physical Assistance

1. **[UpperLimb-Rehab]** | **JNER'14** | A survey on robotic devices for upper limb rehabilitation | [`[pdf]`](https://jneuroengrehab.biomedcentral.com/counter/pdf/10.1186/1743-0003-11-3) | [`[doi]`](https://doi.org/10.1186/1743-0003-11-3) | _Key: classic map of upper-limb rehabilitation robot mechanisms and clinical needs._
2. **[Shared-pHRI]** | **Applied Mechanics Reviews'18** | A Review of Intent Detection, Arbitration, and Communication Aspects of Shared Control for Physical Human-Robot Interaction | [`[pdf]`](https://asmedigitalcollection.asme.org/appliedmechanicsreviews/article-pdf/70/1/010804/5964415/amr_070_01_010804.pdf) | [`[doi]`](https://doi.org/10.1115/1.4039145) | _Key: foundation for shared control in rehabilitation, prosthetics, and assistive robots._
3. **[AssistiveGym]** | **ICRA'20** | Assistive Gym: A Physics Simulation Framework for Assistive Robotics | [`[pdf]`](https://arxiv.org/pdf/1910.04700) | [`[code]`](https://github.com/Healthcare-Robotics/assistive-gym) | _Key: simulation tasks for feeding, dressing, bathing, and physical assistance._
4. **[RATULS]** | **Health Technology Assessment'20** | Robot-assisted training compared with enhanced upper limb therapy and usual care after stroke: the RATULS three-group RCT | [`[pdf]`](https://njl-admin.nihr.ac.uk/document/download/2034515) | [`[doi]`](https://doi.org/10.3310/hta24540) | _Key: multicenter clinical trial evidence for upper-limb rehabilitation robots._
5. **[Robotic-Caregiving]** | **Artificial Intelligence Review'26** | Feeding, grooming, dressing, and body repositioning: categorizing four pillars of learning-based manipulation for robotic caregiving | [`[doi]`](https://doi.org/10.1007/s10462-026-11524-7) | _Key: links embodied intelligence with ADL-centered robotic caregiving._

## Caregiving, Elderly Care, and Social Robots

1. **[SAR-Elderly]** | **JAMDA'10** | Socially Assistive Robots in Elderly Care: A Systematic Review into Effects and Effectiveness | [`[doi]`](https://doi.org/10.1016/j.jamda.2010.10.002) | _Key: early evidence map for social robot interventions in elderly care._
2. **[Robot-Therapist]** | **JMIR'19** | Your Robot Therapist Will See You Now: Ethical Implications of Embodied Artificial Intelligence in Psychiatry, Psychology, and Psychotherapy | [`[pdf]`](https://www.jmir.org/2019/5/e13216/PDF) | [`[doi]`](https://doi.org/10.2196/13216) | _Key: ethical analysis of embodied AI in mental health care._
3. **[SAR-Implementation]** | **BMJ Open'20** | Enablers and barriers to the implementation of socially assistive humanoid robots in health and social care: a systematic review | [`[pdf]`](https://bmjopen.bmj.com/content/bmjopen/10/1/e033096.full.pdf) | [`[doi]`](https://doi.org/10.1136/bmjopen-2019-033096) | _Key: explains why healthcare robots fail or succeed in real care organizations._
4. **[Social-Health]** | **Int. J. Social Robotics'20** | Assistive Robots for the Social Management of Health: A Framework for Robot Design and Human-Robot Interaction Research | [`[pdf]`](https://link.springer.com/content/pdf/10.1007/s12369-020-00634-z.pdf) | [`[doi]`](https://doi.org/10.1007/s12369-020-00634-z) | _Key: frames health support as socially mediated robot interaction._
5. **[Affective-SAR]** | **TCDS'21** | Conversational Affective Social Robots for Ageing and Dementia Support | [`[doi]`](https://doi.org/10.1109/TCDS.2021.3115228) | _Key: emphasizes affective conversation, trust, and long-term dementia support._
6. **[SAR-Dementia]** | **Ageing Research Reviews'22** | Socially assistive robots for people with dementia: Systematic review and meta-analysis | [`[doi]`](https://doi.org/10.1016/j.arr.2022.101633) | _Key: evaluates feasibility, acceptability, and clinical effects of dementia-care robots._
7. **[VP-Robot-LLM]** | **ACM HRI Companion'24** | Creating Virtual Patients using Robots and Large Language Models: A Preliminary Study with Medical Students | [`[pdf]`](https://dl.acm.org/doi/pdf/10.1145/3610978.3640592) | [`[doi]`](https://doi.org/10.1145/3610978.3640592) | _Key: social robot embodiment for interactive medical education._
8. **[VP-Robot-JMIR]** | **JMIR'25** | Virtual Patient Simulations Using Social Robotics Combined With Large Language Models for Clinical Reasoning Training in Medical Education | [`[doi]`](https://doi.org/10.2196/63312) | _Key: journal version of embodied virtual-patient training with LLM-driven interaction._

## Hospital Service and Nursing Robots

1. **[RoNA]** | **ICRA'11** | An advanced medical robotic system augmenting healthcare capabilities - robotic nursing assistant | [`[doi]`](https://doi.org/10.1109/ICRA.2011.5980213) | _Key: early mobile nursing assistant for patient handling and hospital support._
2. **[ARNA]** | **JMIR'20** | Acceptability of Using a Robotic Nursing Assistant in Health Care Environments: Experimental Pilot Study | [`[pdf]`](https://www.jmir.org/2020/11/e17509/PDF) | [`[doi]`](https://doi.org/10.2196/17509) | _Key: pilot evidence on nurse acceptance of an adaptive robotic nursing assistant._
3. **[Delivery-Robots]** | **Intelligent Service Robotics'21** | Case studies on the usability, acceptability and functionality of autonomous mobile delivery robots in real-world healthcare settings | [`[doi]`](https://doi.org/10.1007/s11370-021-00368-5) | _Key: real-world healthcare deployment evidence for mobile delivery robots._
4. **[Inpatient-RNA]** | **Journal of Medical Systems'24** | An Assessment of an Inpatient Robotic Nurse Assistant: A Mixed-Method Study | [`[pdf]`](https://link.springer.com/content/pdf/10.1007/s10916-024-02117-4.pdf) | [`[doi]`](https://doi.org/10.1007/s10916-024-02117-4) | _Key: ward-level assessment of robotic assistance for vital signs, medicine delivery, and reminders._
5. **[Hospital-Risk]** | **Autonomous Robots'24** | Boosting the hospital by integrating mobile robotic assistance systems: a comprehensive classification of the risks to be addressed | [`[pdf]`](https://link.springer.com/content/pdf/10.1007/s10514-023-10154-0.pdf) | [`[doi]`](https://doi.org/10.1007/s10514-023-10154-0) | _Key: risk taxonomy for translating mobile robot systems into hospitals._
6. **[Hospital-Logistics]** | **Scientific Reports'26** | Application management and effectiveness analysis of intelligent logistics robots in hospital drug and specimen delivery scenarios | [`[doi]`](https://doi.org/10.1038/s41598-026-49800-9) | _Key: six-month hospital deployment of drug and specimen delivery robots._

## Healthcare LLM/VLA Robot Prototypes

1. **[RHA-LLM]** | **Applied Sciences'24** | Framework for Integrating Large Language Models with a Robotic Health Attendant for Adaptive Task Execution in Patient Care | [`[pdf]`](https://www.mdpi.com/2076-3417/14/21/9922/pdf) | [`[doi]`](https://doi.org/10.3390/app14219922) | _Key: LLM-mediated task execution framework for a robotic health attendant._
2. **[RoboNurse-VLA]** | **IROS'25** | RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model | [`[pdf]`](https://arxiv.org/pdf/2409.19590) | [`[project]`](https://robonurse-vla.github.io/) | _Key: direct healthcare VLA prototype for surgical tool handover._
3. **[Home-HCR-LLM]** | **IEEE Access'25** | Task Decomposition and Self-Evaluation Mechanisms for Home Healthcare Robots Using Large Language Models | [`[doi]`](https://doi.org/10.1109/access.2025.3559076) | _Key: LLM task decomposition and self-evaluation for home healthcare robot manipulation._
4. **[VP-Robot-JMIR]** | **JMIR'25** | Virtual Patient Simulations Using Social Robotics Combined With Large Language Models for Clinical Reasoning Training in Medical Education | [`[doi]`](https://doi.org/10.2196/63312) | _Key: LLM plus social robot embodiment for clinical reasoning practice._

## Datasets, Simulators, and Benchmarks

1. **[JIGSAWS]** | **M2CAI MICCAI Workshop'14** | JHU-ISI Gesture and Skill Assessment Working Set (JIGSAWS): A Surgical Activity Dataset for Human Motion Modeling | [`[pdf]`](https://cirl.lcsr.jhu.edu/wp-content/uploads/2015/11/JIGSAWS.pdf) | [`[data]`](https://cirl.lcsr.jhu.edu/research/hmm/datasets/jigsaws_release/) | _Key: video, kinematics, and skill labels for robot-assisted surgical training tasks._
2. **[EndoNet]** | **TMI'16** | EndoNet: A Deep Architecture for Recognition Tasks on Laparoscopic Videos | [`[pdf]`](https://hal.science/hal-03511473v1/document) | [`[doi]`](https://doi.org/10.1109/TMI.2016.2593957) | _Key: Cholec80-style laparoscopic workflow and tool recognition benchmark lineage._
3. **[GestureBench]** | **TBME'17** | A Dataset and Benchmarks for Segmentation and Recognition of Gestures in Robotic Surgery | [`[pmc]`](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5559351/) | [`[doi]`](https://doi.org/10.1109/TBME.2016.2647680) | _Key: benchmark protocol for robotic surgery gesture analysis._
4. **[AssistiveGym]** | **ICRA'20** | Assistive Gym: A Physics Simulation Framework for Assistive Robotics | [`[pdf]`](https://arxiv.org/pdf/1910.04700) | [`[code]`](https://github.com/Healthcare-Robotics/assistive-gym) | _Key: embodied simulation for physical assistance tasks._
5. **[SurRoL]** | **IROS'21** | SurRoL: An Open-source Reinforcement Learning Centered and dVRK Compatible Platform for Surgical Robot Learning | [`[doi]`](https://doi.org/10.1109/IROS51168.2021.9635867) | [`[code]`](https://github.com/med-air/SurRoL) | _Key: surgical robot learning simulator aligned with dVRK._
6. **[Open-X]** | **ICRA'24** | Open X-Embodiment: Robotic Learning Datasets and RT-X Models | [`[pdf]`](https://arxiv.org/pdf/2310.08864) | [`[project]`](https://robotics-transformer-x.github.io/) | _Key: cross-embodiment robot data model, useful as a reference for future medical robot datasets._
7. **[SRT-H-Data]** | **Science Robotics'25** | SRT-H supplementary data | [`[data]`](https://doi.org/10.5281/zenodo.15637074) | _Key: public artifact for language-conditioned surgical imitation learning._

## Embodied Intelligence Foundations

These papers are not healthcare papers. They are kept as a compact conceptual and technical background because embodied healthcare is derived from embodied intelligence.

1. **[EmbodiedAI-Survey]** | **IEEE TETCI'22** | A Survey of Embodied AI: From Simulators to Research Tasks | [`[doi]`](https://doi.org/10.1109/TETCI.2022.3141105) | _Key: general embodied AI tasks and simulators._
2. **[SayCan]** | **CoRL'22** | Do As I Can, Not As I Say: Grounding Language in Robotic Affordances | [`[pdf]`](https://arxiv.org/pdf/2204.01691) | [`[project]`](https://say-can.github.io/) | _Key: combines language priors with robot affordances._
3. **[PaLM-E]** | **ICML'23** | PaLM-E: An Embodied Multimodal Language Model | [`[pdf]`](https://arxiv.org/pdf/2303.03378) | [`[project]`](https://palm-e.github.io/) | _Key: injects visual and robot-state tokens into language models._
4. **[RT-1]** | **RSS'23** | RT-1: Robotics Transformer for Real-World Control at Scale | [`[doi]`](https://doi.org/10.15607/RSS.2023.XIX.025) | [`[project]`](https://robotics-transformer1.github.io/) | _Key: large-scale real-world robot policy learning._
5. **[RT-2]** | **CoRL'23** | RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control | [`[pdf]`](https://proceedings.mlr.press/v229/zitkovich23a/zitkovich23a.pdf) | [`[project]`](https://robotics-transformer2.github.io/) | _Key: transfers web-scale VLM knowledge into robot actions._
6. **[DiffusionPolicy]** | **RSS'23** | Diffusion Policy: Visuomotor Policy Learning via Action Diffusion | [`[doi]`](https://doi.org/10.15607/RSS.2023.XIX.026) | [`[code]`](https://github.com/real-stanford/diffusion_policy) | _Key: diffusion-based action generation for dexterous manipulation._
7. **[Code-as-Policies]** | **ICRA'23** | Code as Policies: Language Model Programs for Embodied Control | [`[pdf]`](https://arxiv.org/pdf/2209.07753) | [`[project]`](https://code-as-policies.github.io/) | _Key: LLM-generated executable robot policies._
8. **[VoxPoser]** | **CoRL'23** | VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models | [`[pdf]`](https://arxiv.org/pdf/2307.05973) | [`[project]`](https://voxposer.github.io/) | _Key: language-conditioned 3D value maps for manipulation._
9. **[EmbodiedIntelligence-AIR]** | **CAAI AIR'24** | A Comprehensive Survey on Embodied Intelligence: Advancements, Challenges, and Future Perspectives | [`[doi]`](https://doi.org/10.26599/AIR.2024.9150042) | _Key: concept survey around perception-cognition-behavior integration._
10. **[Open-X]** | **ICRA'24** | Open X-Embodiment: Robotic Learning Datasets and RT-X Models | [`[pdf]`](https://arxiv.org/pdf/2310.08864) | [`[project]`](https://robotics-transformer-x.github.io/) | _Key: dataset consolidation for multi-robot generalization._
11. **[EmbodiedIntelligence-CSUR]** | **ACM CSUR'25** | Embodied Intelligence: A Synergy of Morphology, Action, Perception and Learning | [`[doi]`](https://doi.org/10.1145/3717059) | _Key: frames intelligence as a body-action-perception-learning synergy._
12. **[ELLMER]** | **Nature Machine Intelligence'25** | Embodied large language models enable robots to complete complex tasks in unpredictable environments | [`[pdf]`](https://www.nature.com/articles/s42256-025-01005-x.pdf) | [`[doi]`](https://doi.org/10.1038/s42256-025-01005-x) | _Key: RAG plus LLM-enabled embodied robot execution in unpredictable environments._

## Excluded From This Strict Version

- Screen-only medical foundation models: Med-PaLM, GMAI, LLaVA-Med, Med-Flamingo, generalist biomedical VLMs.
- Screen-only medical agents and benchmarks: EHRAgent, MedAgents, MedAgentsBench, AgentClinic, clinical decision agent benchmarks.
- Generic healthcare AI, IoT, digital twin, and hospital informatics papers without a robot body, simulated embodiment, or action loop.

## Feedback

Suggested additions should be directly embodied, healthcare-relevant, and preferably supported by top venue acceptance, strong citations, real deployment evidence, open robot data/code, or clear community adoption.
