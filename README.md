<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:07111F,45:123E68,100:00D4FF&text=RETELL%20AI%20%7C%20TOPIC%208&fontColor=FFFFFF&fontSize=36&fontAlignY=38&desc=Call%20Disconnection%20%26%20Post-Call%20Summaries&descAlignY=58&animation=fadeIn" width="100%" alt="Animated Retell AI Topic 8 banner" />

<br/>

<a href="https://www.loom.com/share/fc3fc3af5b20441492e8dc54978d363b"><img src="https://img.shields.io/badge/▶_WATCH_LOOM_DEMO-00BFA6?style=for-the-badge&logo=loom&logoColor=white" alt="Watch Loom demo"/></a>
<a href="Retell_AI_Topic_8_Assessment_Report.pdf"><img src="https://img.shields.io/badge/⬇_ASSESSMENT_REPORT-PDF-EA4335?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Assessment PDF"/></a>
<a href="#-screenshots"><img src="https://img.shields.io/badge/VIEW_SCREENSHOTS-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Jump to screenshots"/></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00D4FF&center=true&vCenter=true&width=650&lines=Configuring+AI+Receptionist+Behavior;Testing+Silence+Handling;Extracting+Post-Call+Insights;Documenting+Real+Test+Results" alt="Animated project tagline" />

<br/>

![Retell AI](https://img.shields.io/badge/Platform-Retell%20AI-0B7285?style=flat-square)
![Model](https://img.shields.io/badge/Model-GPT--5.6%20Terra-5B5BD6?style=flat-square)
![Status](https://img.shields.io/badge/Assessment-Documented-success?style=flat-square)
![License](https://img.shields.io/badge/Project-Educational-blue?style=flat-square)

</div>

---

## ✨ Project Overview

This project documents **Topic 8: Call Disconnection & Post-Call Summaries** using a Retell AI receptionist named `Trainee_Sarah_Receptionist`.

The work focuses on configuring silence handling, reminders, transcription settings, and custom post-call extraction fields, then reviewing the resulting call history.

> **Evidence-first reporting:** the values below reflect the call result observed in the dashboard. The repository documents the tests performed; it does not claim every setting or integration was independently validated end to end.

## 🚀 Quick Navigation

| Resource | Open |
|---|---|
| 🎥 Loom walkthrough | [Watch the video](https://www.loom.com/share/fc3fc3af5b20441492e8dc54978d363b) |
| 📄 Assessment report | [Open the PDF](Retell_AI_Topic_8_Assessment_Report.pdf) |
| 🖼️ Configuration evidence | [Browse screenshots](#-screenshots) |
| 🧪 Test results | [Read observations](#-test-observations) |

## 🎯 What Was Configured

<div align="center">

| Setting | Configured value |
|:--|:--|
| End Call on Silence | **15 seconds** |
| Reminder Message Frequency | **8 seconds** |
| Maximum Reminder Count | **1** |
| Interruption Sensitivity | **0.7** |
| Denoising Mode | **Remove noise** |
| Transcription Mode | **Optimize for speed** |
| Post-call memory | **Off** |

</div>

## 🧩 Custom Post-Call Extraction

| Field | Purpose |
|---|---|
| `is_lead_qualified` | Marks appointment booking/scheduling/confirmation requests as qualified |
| `caller_main_issue` | Summarizes the main request in 10 words or fewer |
| `caller_sentiment` | Classifies the caller as Positive, Neutral, or Negative |
| `satisfaction_score` | Records a satisfaction score from 1 to 5 |

## 🧪 Test Observations

### Test 1 — Silence handling
The user reports that the silence test ended with the call disconnecting. The configured silence timeout is **15 seconds** and the reminder configuration is **8 seconds / 1 reminder**.

### Test 2 — Appointment-booking conversation
The call history screenshot shows the following observed post-call output:

- **Call status:** Ended
- **Disconnection reason:** `User_hangup`
- **Caller main issue:** “Wants to book tomorrow at 3 PM”
- **Lead qualified:** `true`
- **Caller sentiment:** `Neutral`
- **Satisfaction score:** `3`
- **Summary:** The caller requested an appointment for tomorrow at 3 PM and provided the name John. The agent requested a callback number, which was not provided before hang-up.

These are the values displayed in the call history; they are not altered to match the expected sample answers.

## 🖼️ Screenshots

The image files are currently stored in the repository root. Click each card to open its full-size screenshot.

<div align="center">

### 01 · Agent overview and test panel
<a href="Screenshot%202026-10-04%20111348.png"><img src="Screenshot%202026-10-04%20111348.png" width="82%" alt="Retell AI agent overview"/></a>
<br/>
<a href="Screenshot%202026-10-04%20111348.png">🔍 Open full screenshot</a>

### 02 · Post-call extraction fields
<a href="Screenshot%202026-10-04%20111458.png"><img src="Screenshot%202026-10-04%20111458.png" width="82%" alt="Post-call extraction configuration"/></a>
<br/>
<a href="Screenshot%202026-10-04%20111458.png">🔍 Open full screenshot</a>

### 03 · Agent configuration panel
<a href="Screenshot%202026-10-04%20112922.png"><img src="Screenshot%202026-10-04%20112922.png" width="82%" alt="Agent configuration panel"/></a>
<br/>
<a href="Screenshot%202026-10-04%20112922.png">🔍 Open full screenshot</a>

### 04 · Reminder frequency
<a href="Screenshot%202026-10-04%20113044.png"><img src="Screenshot%202026-10-04%20113044.png" width="82%" alt="Reminder message frequency configuration"/></a>
<br/>
<a href="Screenshot%202026-10-04%20113044.png">🔍 Open full screenshot</a>

### 05 · Call settings and timeout
<a href="Screenshot%202026-10-04%20113132.png"><img src="Screenshot%202026-10-04%20113132.png" width="82%" alt="Call settings including silence timeout"/></a>
<br/>
<a href="Screenshot%202026-10-04%20113132.png">🔍 Open full screenshot</a>

### 06 · Transcription and denoising settings
<a href="Screenshot%202026-10-04%20113531.png"><img src="Screenshot%202026-10-04%20113531.png" width="82%" alt="Transcription and denoising settings"/></a>
<br/>
<a href="Screenshot%202026-10-04%20113531.png">🔍 Open full screenshot</a>

### 07 · Call history and observed extraction results
<a href="Screenshot%202026-10-04%20121010.png"><img src="Screenshot%202026-10-04%20121010.png" width="82%" alt="Call history with summary and custom analysis results"/></a>
<br/>
<a href="Screenshot%202026-10-04%20121010.png">🔍 Open full screenshot</a>

</div>

## 📦 Assessment Document

<a href="Retell_AI_Topic_8_Assessment_Report.pdf">**📄 Download / open the Topic 8 Assessment Report (PDF)**</a>

The report summarizes the configuration and assessment scenarios. Refer to the screenshots above for evidence of the dashboard settings and observed results.

## 🛠️ Tools Used

- **Retell AI** — voice agent configuration and call history
- **Loom** — recorded project walkthrough
- **GitHub** — project documentation and evidence

## 👨‍💻 Author

**Shaik Mohammad Shaheed**  
AI Automation · Voice AI · Workflow Automation

<div align="center">

<a href="https://www.loom.com/share/fc3fc3af5b20441492e8dc54978d363b"><img src="https://img.shields.io/badge/▶_WATCH_PROJECT_DEMO-00BFA6?style=for-the-badge&logo=loom&logoColor=white" alt="Watch project demo"/></a>
<a href="Retell_AI_Topic_8_Assessment_Report.pdf"><img src="https://img.shields.io/badge/📄_READ_ASSESSMENT-1D4ED8?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Read assessment"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:00D4FF,100:07111F" width="100%" alt="Decorative animated footer banner"/>

</div>
