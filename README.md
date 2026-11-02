# Seojin Bae

**Software Engineering · Computer Vision · Applied AI**

I'm a **Data Science B.S. student at the University of Wisconsin–Madison**, graduating in **May 2027**. I build backend tools, data pipelines, and on-device vision features that connect models and system data to practical applications.

**Seeking 2027 new-grad software engineering and data engineering opportunities.**

## Focus

- **Backend & Cloud** — APIs, data migration, PostgreSQL, and reproducible validation.
- **Computer Vision** — event-camera processing, mobile inference, and temporal tracking.
- **Applied ML** — pretrained-model integration, retrieval, reranking, and quantitative evaluation.

## Selected Projects

### MoDoc AI · FeverCoach Web & CMS Migration
**Full-stack & cloud contribution · Industry-academic collaboration · Oct 2026–present**

Moving a multilingual content site from Wix to a custom web and CMS stack.

- **My work:** integrated a Next.js frontend with a teammate-built Payload CMS, deployed the CMS to GCP staging, and connected Cloud SQL PostgreSQL, private GCS, and a Vercel Preview.
- Migrated **3,679 posts and 7,128 media assets** to staging with SHA-256 integrity checks; validated **3,688 content URLs** for HTTP status, headings, and canonical metadata.

**Stack:** Next.js, TypeScript, Payload CMS, PostgreSQL, GCP, GCS, Vercel  
**Status:** staging/Preview verified; production domain cutover remains pending.  
[MoDoc AI](https://www.modoc-ai.com/) · [FeverCoach](https://www.fevercoach.us/)

### AI Incident Copilot
**Backend contributor · Team 1st Place, UW–Madison LikeLion Hackathon 2026**

A team-built incident-response prototype that turns logs into diagnosis and recovery workflows.

- **My work:** designed a Python/FastAPI pipeline for ranked root-cause hypotheses, supporting evidence, and runbook-based action plans.
- Implemented severity/confidence scoring, human approval gates for remediation, and post-action health checks.

**Stack:** Python, FastAPI, Next.js, Server-Sent Events  
[Original team repository](https://github.com/joannemiki57/IncidentCopilot) · [Backend implementation](https://github.com/joannemiki57/IncidentCopilot/tree/main/backend)

### SENSEA
**Computer vision contributor · Team accessibility app**

A mobile navigation prototype for blind and low-vision users.

- **My work:** integrated on-device object detection and temporal tracking with speech and vibration feedback, including repeated-alert suppression.
- Built camera analysis with a **200 ms scheduling interval**, reusable input buffers, stale-result rejection, and camera/model resource cleanup.

**Stack:** React Native, TypeScript, VisionCamera, TensorFlow Lite  
**Status:** assistive prototype; formal user evaluation is in preparation.  
[Original team repository](https://github.com/jjaeyun01/SENSEA) · [Camera & inference pipeline](https://github.com/jjaeyun01/SENSEA/blob/main/mobile/src/vision/createNativeSession.ts) · [Tracking logic](https://github.com/jjaeyun01/SENSEA/blob/main/mobile/src/vision/hazards.mjs)

### CASMI 2026 · Molecular Structure Retrieval
**ML pipeline contribution · Team competition project**

Ranking molecular structure candidates from tandem mass spectra.

- **My work:** integrated pretrained MIST, FRIGID, ICEBERG, and public DreaMS components, with structure deduplication and weighted reciprocal rank fusion.
- Improved the **official public MRR@25 from 0.239 to 0.265**; validated 25 unique candidates for each of 400 public inputs and reused cached scores in expanded-pool experiments.

**Stack:** Python, PyTorch, RDKit, rank fusion  
**Status:** ongoing competition work; the score is a public evaluation result.

## Work Highlights

### DeePix · Software Development
**Cheongju, South Korea · June–August 2026**

- Built **C#/C++ sensor-data viewing tools** for Metavision RAW, DAT, and HDF5 recordings, with playback, polarity filtering, event-rate monitoring, and packaged delta updates.
- Developed **C++ and Python/Cython workflows** for IMX636 event-camera data: EVT3 decoding, denoising, multi-object tracking, and trajectory/velocity visualization.
- Contributed to DeePix's project recognized with the **Smart Factory Machine Vision Hardware Category Grand Prize** at the **20th Science and Technology Innovation Awards** in October 2026 — a company/team award.

## More Project Contributions

<details>
<summary><strong>Contoro Robotics · ROS-MCP / RobotMCP</strong></summary>

**Industry-academic collaboration with a Texas-based robotics company**

Configured ROS 2/rosbridge simulation tests, contributed Noetic/Gemini setup documentation, and implemented Docusaurus website improvements and GA4 event instrumentation.

This work is listed as a collaboration project.

</details>

<details>
<summary><strong>OralQ · Image Analysis Web Prototype</strong></summary>

**Team project · Flutter, Python, Docker**

Improved session restoration/expiry handling, image previews, saved-result comparison/deletion, and mobile layouts. Added upload validation and replaced hard-coded findings with actual model output.

**Verification:** 17 backend tests + 16 Flutter tests, web build, and Docker build passed. Changes remain in an open draft PR; clinical accuracy has not been established.

[My draft PR](https://github.com/ys06146/likelion/pull/2) · [CI validation](https://github.com/ys06146/likelion/actions/runs/39190369730)

</details>

## Tech Stack

- **Languages:** Python · C++ · Cython · TypeScript · SQL · C# · Java
- **Web & Cloud:** FastAPI · Next.js · Payload CMS · PostgreSQL · GCP · GCS · Vercel
- **Vision & ML:** PyTorch · NumPy · pandas · RDKit · TensorFlow Lite · Metavision SDK
- **Mobile & Tools:** React Native · VisionCamera · Flutter · .NET 8 · ROS 2 · Docker · Git · Linux

## Contact & Code

[LinkedIn](https://www.linkedin.com/in/seojin-bae-904546297/) · [Repositories](https://github.com/ys06146?tab=repositories)

This is my primary GitHub account. Earlier academic contributions may appear under [@sbae56-art](https://github.com/sbae56-art). Team projects above link to their original repositories, with my contribution described separately.
