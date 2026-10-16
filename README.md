# Seojin Bae

**Software engineering · Computer vision · Applied AI**

I'm a Data Science B.S. student at the **University of Wisconsin–Madison**, graduating in **May 2027**. I build software that turns model outputs and system data into practical tools, from incident diagnosis APIs to on-device visual assistance.

**Seeking 2027 new-grad software engineering and data engineering roles.**  
[LinkedIn](https://www.linkedin.com/in/seojin-bae-904546297) · [Repositories](https://github.com/ys06146?tab=repositories)

## Selected projects

### AI Incident Copilot
**1st Place — UW–Madison LikeLion Hackathon 2026**  
A team-built incident response console that turns logs into triage, root-cause hypotheses, supporting evidence, and proposed recovery steps.

**My focus: backend diagnosis logic, pipeline design, and API integration.**
- Designed the incident diagnosis pipeline and contributed backend logic for triage, root-cause analysis, evidence mapping, and action planning.
- Worked on the log/metric analysis flow and FastAPI integration that connects backend results to the user-facing workflow.
- Contributed to the MVP demo and presentation. The integrated app streams analysis stages to the frontend and includes human approval gates for proposed actions.

**Stack:** Python, FastAPI, Next.js, Server-Sent Events  
[Original team repository](https://github.com/joannemiki57/IncidentCopilot) · [Backend implementation](https://github.com/joannemiki57/IncidentCopilot/tree/main/backend)

### SENSEA
A team-built, voice-first campus navigation app for blind and low-vision users.

**My focus: the computer vision implementation.**
- Integrated EfficientDet-Lite0 / TensorFlow Lite with VisionCamera for on-device object detection in a React Native app.
- Built a bounded camera-analysis pipeline with a 200 ms scheduling interval, stale-result rejection, reusable input buffers, and camera/model resource cleanup.
- Implemented temporal object tracking and image-based attention cues, connected to spoken feedback and haptic alerts with repeated-alert suppression.

The vision component is an experimental assistive feature; it does not establish a safe walking path or predict collisions.

**Stack:** TypeScript / JavaScript, React Native, VisionCamera, TensorFlow Lite  
[Original team repository](https://github.com/jjaeyun01/SENSEA) · [Camera & inference pipeline](https://github.com/jjaeyun01/SENSEA/blob/main/mobile/src/vision/createNativeSession.ts) · [Tracking & attention cues](https://github.com/jjaeyun01/SENSEA/blob/main/mobile/src/vision/hazards.mjs)

## Current collaboration

### MoDoc AI · FeverCoach Web Migration
**Selected team member · Industry-academic collaboration · October 2026–present**

Participating in the initial planning phase of FeverCoach's migration from Wix to a custom-built website.

**Planned project scope:**
- Inventory existing URLs, page content, and metadata to preserve search visibility during the migration.
- Rebuild the website while retaining indexed URLs and maintaining publishing workflows.
- Migrate and test content-generation scripts, then validate SEO and analytics continuity after the domain cutover.

[MoDoc AI](https://www.modoc-ai.com/) · [FeverCoach](https://www.fevercoach.us/)

## Technologies I work with

**Languages:** Python, C++, C#, Java, TypeScript, SQL  
**Tools & frameworks:** FastAPI, React Native, .NET, PyTorch, TensorFlow / TensorFlow Lite, Git, Linux

---

This is my primary GitHub account. Earlier academic contributions may appear under [@sbae56-art](https://github.com/sbae56-art).
