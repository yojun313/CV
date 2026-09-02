# Yojun Moon (문요준)

✉️ [yojun313@postech.ac.kr](mailto:yojun313@postech.ac.kr) &nbsp;&nbsp; 🔗 [github.com/yojun313](https://github.com/yojun313) &nbsp;&nbsp; 💼 [linkedin.com/in/yojun-moon](https://www.linkedin.com/in/yojun-moon/) &nbsp;&nbsp; 🌐 [yojun313.github.io](https://yojun313.github.io/)

## Education

**POSTECH (Pohang University of Science and Technology)** — *Mar 2023 – Present*

B.S. in Computer Science and Engineering

## Work Experience

### [Samsung Fire & Marine Insurance](https://www.samsungfire.com) — *Jul 2026 – Aug 2026*

**AI Engineer Intern, AI Development Part**

Built two computer vision modules for insurance claim data, each delivered as an end-to-end pipeline with a web service.

### Korean National Police University — [FPEI (Future Public Safety Engineering Institute)](https://knpu.re.kr/) — *Nov 2023 – Present*

**Research System Developer**

Core developer of the institute's research platform: 8 services on a shared FastAPI backend, deployed in production at [*.knpu.re.kr](https://knpu.re.kr/systems) ([github.com/yojun313/knpu](https://github.com/yojun313/knpu)).

- Data Collection — *CRAWLER*, an asynchronous, queue-based crawler with proxy IP rotation, gathering about 1,500 articles and 60,000+ comments per hour from Naver News, and also supporting Naver Blog, Naver Cafe, and YouTube.
- Analysis — *STATISTICS* (statistical analysis and visualization), *NETWORK* (social network extraction and visualization from natural language), and *KEMKIM* (future signal prediction), unified by *MANAGER*, the research resource and big data platform.
- AI Legal Complaint Drafting — built an LLM-based service that drafts complaints meeting legal requirements; received a Letter of Appreciation from the Korean National Police University (Apr 2024).
- Skills: Python, FastAPI, MongoDB, vLLM, PyQt, PM2

### [POSTECH HAiV Lab](https://sites.google.com/view/haiv/) — *Jan 2026 – Feb 2026*

**Undergraduate Researcher**

Researching ACCIDENTOR, a multi-VLM framework that estimates traffic accident fault ratios from dashcam video.

- Skills: Python, PyTorch, Vision-Language Models

### Startup Team (founded by a POSTECH CSE alumnus) — *Feb 2025 – Jul 2025*

**Backend Developer Intern**

Developed the backend of a social networking service and supported data-driven product decisions.

- Key Contributions:
  - Developed the SNS backend with NestJS.
  - Built web crawlers and analyzed the collected data.
  - Completed the 2025 I-Corps program, including 3 weeks of entrepreneurship training at UC Berkeley (KIC Tech Frontier Program).
- Skills: NestJS, TypeScript, Python, MongoDB, Crawler

## Projects

### [PCSS (POSTECH Computer Scientist Search)](https://pcss.postech.ac.kr/) — *Jan 2025 – Mar 2026*

*In-house service for the POSTECH CSE department.* Faculty candidate search service, developed on commission.

- Key Implementations:
  - Parsed DBLP XML dumps and stored normalized publication records in MongoDB.
  - Identified Korean-name authors at scale with an LLM API.
  - Reduced the search for Korean authors of top-venue papers within a given year and venue range from hours to seconds (several hundred times faster).
- Deployed at [pcss.postech.ac.kr](https://pcss.postech.ac.kr/)
- Skills: Python, MongoDB, LLM APIs

### [Commeet](https://commeet.postech.ac.kr) — *Aug 2026 – Present*

*In-house service for the POSTECH CSE department.* Group scheduling service that collects everyone's availability and assigns the meeting times.

- Key Implementations:
  - Automatic time slot assignment — reduced the conflict-free schedule to a degree-constrained bipartite matching and solved it optimally with min-cost max-flow, maximizing the number of people scheduled while packing them into as few sessions as possible.
  - Contact management — a reusable address book for frequent invitees, covering both registered users and people who have not signed up.
  - Professor-only tools — consultation records in the four categories required by POVIS, with per-student notes, a drawn signature, and a printable form; plus student guidance fee settlement with receipt upload. All records are encrypted at rest, as they hold student personal data.
- Deployed at [commeet.postech.ac.kr](https://commeet.postech.ac.kr)
- Skills: FastAPI, MongoDB (Motor), Jinja2, JavaScript

### [POPO](https://popo.poapper.club/) — *Jan 2026 – Feb 2026*

Campus web service operated by PoApper, POSTECH's student developer club.

- Developing the backend with NestJS.
- Skills: NestJS, TypeScript

## Activities

### POSTECH Broadcasting Station (PBS) — *Mar 2023 – Dec 2025*

Member of the Programming & Production Department.

- Filmed, edited, and live-broadcast campus entertainment programs.

### Programming Tutor — *Jan 2025 – Present*

Teaching Python and C to middle and high school students.

- Topics include object-oriented programming, MongoDB, and FastAPI.

## Skills

| | |
|---|---|
| **Programming Languages** | Python, C, C++, TypeScript, JavaScript |
| **AI / Machine Learning** | PyTorch, Ultralytics YOLO, OpenCV, vLLM, LLM APIs |
| **Backend** | FastAPI, NestJS, MongoDB |
| **Tools / Miscellaneous** | Docker, Git, Linux, PyQt, FFmpeg |
