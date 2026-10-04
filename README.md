<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:050816,35:102A56,70:075985,100:00E5FF&text=RETELL%20AI%20%E2%80%A2%20TOPIC%2008&fontColor=FFFFFF&fontSize=38&fontAlignY=36&desc=CALL%20DISCONNECTION%20%7C%20POST-CALL%20SUMMARIES&descAlignY=57&animation=fadeIn" width="100%" alt="Animated Retell AI Topic 8 banner"/>

<h1>📞 Call Disconnection & Post-Call Summaries</h1>

<p><b>AI Voice Agent Configuration • Silence Handling • Post-Call Extraction</b></p>

<a href="https://www.loom.com/share/fc3fc3af5b20441492e8dc54978d363b"><img src="https://img.shields.io/badge/▶_WATCH_PROJECT_DEMO-00CBA9?style=for-the-badge&logo=loom&logoColor=white" alt="Watch project demo"/></a>
<a href="Retell_AI_Topic_8_Assessment_Report.pdf"><img src="https://img.shields.io/badge/📄_ASSESSMENT_REPORT-DC2626?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Open assessment report"/></a>
<a href="#-screenshots"><img src="https://img.shields.io/badge/🖼️_SCREENSHOTS-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Browse screenshots"/></a>
<a href="#-observed-test-results"><img src="https://img.shields.io/badge/🧪_TEST_RESULTS-7C3AED?style=for-the-badge&logo=checkmarx&logoColor=white" alt="View test results"/></a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1000&color=00D4FF&center=true&vCenter=true&width=720&lines=Building+clearer+voice+AI+experiences;Configuring+silence+and+reminder+behavior;Extracting+useful+post-call+insights;Documenting+observed+results+honestly" alt="Animated project tagline"/>

<br/>

<img src="https://img.shields.io/badge/Platform-Retell_AI-0E7490?style=flat-square" alt="Retell AI"/>
<img src="https://img.shields.io/badge/Model-GPT--5.6_Terra-5B5BD6?style=flat-square" alt="GPT-5.6 Terra"/>
<img src="https://img.shields.io/badge/Project-Topic_08-111827?style=flat-square" alt="Topic 8"/>
<img src="https://img.shields.io/badge/Focus-Voice_AI-0891B2?style=flat-square" alt="Voice AI"/>

</div>

---

## 🧭 Project Navigation

| Resource | Description | Link |
|---|---|---|
| 🎬 Video walkthrough | Recorded project walkthrough | [Watch on Loom](https://www.loom.com/share/fc3fc3af5b20441492e8dc54978d363b) |
| 📄 Assessment report | Configuration and assessment notes | [Open PDF](Retell_AI_Topic_8_Assessment_Report.pdf) |
| 🖼️ Evidence gallery | Screenshots of settings and call history | [View screenshots](#-screenshots) |
| 🧪 Test observations | Results shown in call history | [View results](#-observed-test-results) |

## 💡 Project Overview

This repository documents **Topic 8: Call Disconnection & Post-Call Summaries**. The Retell AI agent used for the assessment is named `Trainee_Sarah_Receptionist`.

The work covers receptionist behavior, silence and reminder settings, transcription configuration, and custom post-call extraction fields. The results section records what was visible in the dashboard rather than replacing actual outputs with ideal sample answers.

## ⚙️ Configuration Snapshot

| Setting | Value shown in configuration |
|---|---:|
| End Call on Silence | **15 seconds** |
| Reminder Message Frequency | **8 seconds** |
| Maximum Reminder Count | **1** |
| Interruption Sensitivity | **0.7** |
| Denoising Mode | **Remove noise** |
| Transcription Mode | **Optimize for speed** |
| Post-call memory | **Off** |

## 🧠 Custom Post-Call Extraction

| Field | Type / purpose |
|---|---|
| `is_lead_qualified` | Boolean — qualifies appointment booking, scheduling, or confirmation requests |
| `caller_main_issue` | Text — short summary of the caller's main request |
| `caller_sentiment` | Selector — Positive, Neutral, or Negative |
| `satisfaction_score` | Number — caller satisfaction score from 1 to 5 |

## 🧪 Observed Test Results

### Appointment-booking conversation

The call history screenshot showed these values:

| Output | Observed value |
|---|---|
| Call status | Ended |
| Disconnection reason | `User_hangup` |
| `caller_main_issue` | Wants to book tomorrow at 3 PM |
| `is_lead_qualified` | `true` |
| `caller_sentiment` | `Neutral` |
| `satisfaction_score` | `3` |

**Call summary shown:** The caller requested an appointment for tomorrow at 3 PM and provided the name John. The agent requested a callback number, which the caller did not provide before hanging up.

### Silence handling

The configured timeout is 15 seconds, with a reminder configured for 8 seconds and a maximum of one reminder. The screenshots document the configuration and the user-reported disconnect behavior; they do not establish that every timing condition was independently measured.

<details>
<summary><b>ℹ️ Important testing note</b></summary>

Observed post-call extraction values can differ from sample expected answers. This README preserves the dashboard values. A call ending with `User_hangup` should not be described as a verified silence-timeout disconnection.
</details>

## 🖼️ Screenshots

Click an image to open its full-size version.

<div align="center">

### 01 · Agent overview and test panel
<a href="Screenshot%202026-10-04%20111348.png"><img src="Screenshot%202026-10-04%20111348.png" width="88%" alt="Retell AI agent overview and test panel"/></a>

### 02 · Post-call extraction fields
<a href="Screenshot%202026-10-04%20111458.png"><img src="Screenshot%202026-10-04%20111458.png" width="88%" alt="Post-call extraction configuration"/></a>

### 03 · Agent configuration
<a href="Screenshot%202026-10-04%20112922.png"><img src="Screenshot%202026-10-04%20112922.png" width="88%" alt="Agent configuration panel"/></a>

### 04 · Reminder frequency
<a href="Screenshot%202026-10-04%20113044.png"><img src="Screenshot%202026-10-04%20113044.png" width="88%" alt="Reminder frequency settings"/></a>

### 05 · Call settings and silence timeout
<a href="Screenshot%202026-10-04%20113132.png"><img src="Screenshot%202026-10-04%20113132.png" width="88%" alt="Call settings and silence timeout"/></a>

### 06 · Transcription and denoising
<a href="Screenshot%202026-10-04%20113531.png"><img src="Screenshot%202026-10-04%20113531.png" width="88%" alt="Transcription and denoising settings"/></a>

### 07 · Call history and extraction output
<a href="Screenshot%202026-10-04%20121010.png"><img src="Screenshot%202026-10-04%20121010.png" width="88%" alt="Call history with post-call results"/></a>

</div>

## 🧰 Tools Used

- **Retell AI** — voice agent setup and call history
- **Loom** — video walkthrough
- **GitHub** — documentation and evidence

## 👨‍💻 Author

**Shaik Mohammad Shaheed**  
AI Automation • Voice AI • Workflow Automation

<div align="center">

<a href="https://www.loom.com/share/fc3fc3af5b20441492e8dc54978d363b"><img src="https://img.shields.io/badge/▶_WATCH_DEMO-00CBA9?style=for-the-badge&logo=loom&logoColor=white" alt="Watch demo"/></a>
<a href="Retell_AI_Topic_8_Assessment_Report.pdf"><img src="https://img.shields.io/badge/📄_OPEN_PDF-2563EB?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Open PDF"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=130&section=footer&color=0:00E5FF,45:075985,100:050816" width="100%" alt="Decorative banner footer"/>

</div>
