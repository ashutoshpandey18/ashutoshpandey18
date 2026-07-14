```text
                  ':!;I([{,                     ashutosh@pandey
                (%M#######@@%[,                 ---------------
             ,lM####@@@@@@####@(                OS: ................. macOS, Ubuntu, Android
            :M##@@@@###@@#@@@@@#x               Uptime: ............. 21 years (Born June 23, 2005)
            x#@@@@##@#@@@@@@@#@@#{              Host: ............... YC-Style Product Engineer
            k@@#@xx@#@###@@##@@@@l              Kernel: ............. Full-Stack & Agentic Systems Developer
            *#@kx[;:[k%%@@#####@#{              IDE: ................ Cursor, VSCode 1.96.0
            !#k*xl[(;;!l@@@M@@@#[               
            ;@llkkkxx!,*%%kxxl@x                Languages.Programming: .. TypeScript, JavaScript, C++, SQL
            'x(;!;:,!''!!I([IIx!                Languages.Computer: ..... HTML, CSS, JSON, Markdown, YAML
            .l[,   ,I',!'  .,({                 Languages.Real: ......... English, Hindi
             IkI,,:Il([[,.',Ix!                 
              xk{(ll{I{[l{!(%;                  Flagships.AI: ........... Harness.ai (Frontline RAG Agent)
              'M*;:!III!!IlM{                   Flagships.DevTools: ..... SketchFlow AI (Visual React IDE)
          .,;I{%@xI:,,,:IxM%({I!,               Flagships.SaaS: ......... Atlas AI (Location Intel Copilot)
        [M#####*k##M%%kM#Mll#####*              
       I###@@@M[{l%MMMMM*!;[@@@@@#{             - Contact -------------------------------------------
      IM@@##@#@[I!{[(({{;:;*#@###@#*            Email.Personal: ......... ashutoshpandey23june2005@gmail.com
     I#######@#%(!!I!!!;:!l@@@####@#x'          LinkedIn: ............... linkedin.com/in/ashutosh-pandey-87543b269
 'I*M#@@######@#M*I:!!;;{%#########@##M*!.      GitHub: ................. github.com/ashutoshpandey18
k####@#########@##M*II*%@#@#########@@###@xI    Portfolio: .............. tinyurl.com/3jfeu52m
#@@@@############@#######@############@@@@##    
[##@@@############@@@#@@###############@@##l    - GitHub Stats --------------------------------------
 ,x###@@############################@@###k:     Repos: ... 10+ {Contributed: 20+} | Stars: ... 15+
   ,l@################################@*:       Commits: ................. 1,000+ | Followers: 35+
     .{%@@########################@@M('         Lines of Code on GitHub: . 150,000+
```

---

I build production-grade applications that bridge complex backend services, agentic workflows, and high-fidelity user experiences. My focus is on robust system architecture, developer tooling, and building intuitive interfaces that solve real-world operational problems.

---

## Flagship Projects

### Harness.ai — Frontline AI Platform
An agentic, multi-channel communication platform designed for frontline industrial operations, enabling standard operating procedure (SOP) retrieval and incident escalation for factory workers.
* **Problem Solved:** Bridges the gap between complex industrial compliance manuals and shop-floor workers via zero-training voice, text, and visual interfaces.
* **Key Architecture:**
  * **Multi-Channel Pipeline:** Receives inputs from WhatsApp, Twilio SMS, and Line.
  * **Audio & Vision Processing:** Processes voice notes through FFmpeg noise filters and Whisper transcribing; routes shop floor images through Claude Vision for OCR and status tagging.
  * **Reasoning Loop:** Embeds SOPs into a `pgvector` database (Supabase catalog) and queries via cosine similarity. Includes a deterministic confidence threshold router: queries under 0.75 confidence are automatically logged as incidents and escalated to supervisors via WhatsApp notifications.
* **Tech Stack:** Next.js (App Router), TypeScript, Vanilla CSS, Supabase, pgvector, OpenAI Whisper, Claude Vision, Sarvam AI API.
* **[View Repository](https://github.com/ashutoshpandey18/Harness)**

### SketchFlow AI — Visual Creative IDE
A visual development workspace that interprets hand-drawn layouts and renders interactive web layouts in real time.
* **Problem Solved:** Allows founders and developers to sketch layouts on a digital canvas and see them compiled into functional, production-ready React code instantly.
* **Key Architecture:**
  * **Dynamic DOM Syncing:** Translates user strokes and node graphs in the Sketch Deck into React components using React state hooks.
  * **Design System:** Built with an industrial bone-white and deep onyx aesthetic, featuring custom SVGs, charcoal filters, felt-textures, and Framer Motion transitions.
  * **System Telemetry:** Real-time logging page (`/system`) that visualizes rendering performance, event loop states, and component translation logic.
* **Tech Stack:** Next.js 14, TypeScript, Vanilla CSS, Framer Motion.

### Atlas AI — Location Intelligence Copilot
An interactive geospatial assessment workspace built on top of the Mireye Coordinate API.
* **Problem Solved:** Simplifies complex spatial evaluation by translating raw GIS attributes into clear, explainable site-selection decisions for warehouses, battery factories, and EV charging stations.
* **Key Architecture:**
  * **Decision & Recommendation Engine:** Queries the Mireye `/v1/fetch` endpoint, running deterministic business rules to generate a 0–100 suitability score for up to 5 sites simultaneously.
  * **Siting Copilot:** Integrates the `/v1/ask` endpoint to answer natural language questions about land constraints and coordinates.
  * **Site-Shifting Logic:** Automatically computes and proposes nearby coordinate adjustments to avoid flood zones, conservation easements, or steep slopes while estimating the score improvement.
* **Tech Stack:** Next.js, React, Groq LLM, Turso DB (SQLite), Prisma ORM, Tailwind CSS.
* **[View Repository](https://github.com/ashutoshpandey18/AtlasAI)**

---

## Additional Projects

### College Email SaaS
Automated institutional email provisioning and verification system.
* **Features:** JWT authentication with role-based guards, password reset flows, secure SMTP email delivery with automatic retries, and Tesseract.js OCR verification for ID cards.
* **Tech Stack:** NestJS 11, React 19, TypeScript, PostgreSQL, Prisma, Docker.
* **[View Repository](https://github.com/ashutoshpandey18/college-email-saas)**

## Core Capabilities

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <strong>[ AI Workflows ]</strong>
      <p>Designing agentic reasoning loops, custom RAG search models, and automated LLM validation pipelines with confidence-based threshold routing.</p>
    </td>
    <td width="50%" valign="top">
      <strong>[ Voice Systems ]</strong>
      <p>Deploying real-time speech-to-text models, audio noise reduction filtering, and zero-training multilingual transcription pipelines.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>[ Secure Auth ]</strong>
      <p>Implementing secure enterprise authentication patterns with JWT, bcrypt, role-based guards, and database credential encryption.</p>
    </td>
    <td width="50%" valign="top">
      <strong>[ Real-Time APIs ]</strong>
      <p>Architecting low-latency, event-driven web hooks, and server-side background execution layers using Next.js and NestJS.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>[ OCR Pipelines ]</strong>
      <p>Developing client-side document processing engines, automated status verification, and document layout parsing.</p>
    </td>
    <td width="50%" valign="top">
      <strong>[ SaaS Platforms ]</strong>
      <p>Building production-ready software systems with modular design patterns, database orchestration, and interactive simulator interfaces.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>[ Analytics & Databases ]</strong>
      <p>Integrating vector databases (pgvector), spatial APIs (Mireye), and relational engines (PostgreSQL, SQLite, Turso DB).</p>
    </td>
    <td width="50%" valign="top">
      <strong>[ Responsive Web Systems ]</strong>
      <p>Developing high-fidelity client workspaces, custom design systems, and responsive layout architectures.</p>
    </td>
  </tr>
</table>

---

## Technical Stack

* **Languages:** TypeScript, JavaScript, C++, SQL, HTML, CSS
* **Frontend:** React, Next.js, Vite, Tailwind CSS, Framer Motion
* **Backend & Database:** NestJS, Node.js, Express, PostgreSQL, MongoDB, Prisma, pgvector
* **DevOps & Infrastructure:** Docker, Git, VS Code, Postman, Turso

---

## GitHub Performance & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ashutoshpandey18&show_icons=true&theme=radical" alt="GitHub Stats" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=ashutoshpandey18&theme=radical&hide_border=false" alt="GitHub Streak" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ashutoshpandey18&layout=compact&theme=radical" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ashutoshpandey18&color=blue&style=flat-square" alt="Profile Views" />
</p>
