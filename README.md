# AI Product Suite

The following is part of a collection of tools I use to streamline parts of my day-to-day as a Product Manager.


If you're interested in collaborating or have questions, feel free to reach out over email (**kylenewman1214@gmail.com**), [LinkedIn](https://www.linkedin.com/in/kylenewman2023/), or [subscribe to my substack](https://substack.com/@kylenewman1214), where I will be sharing my thoughts and practical applications on ways to find leverage as a Product Manager in a rapidly evolving landscape.  

## Projects

### [Claude Code Build-Kit](https://github.com/kylenewm/council-v3)
**Status:** Completed

**Goal:** Expand Claude Code's capabilities to enable building other productivity tools

A set of features on top of Claude Code that addresses its rough edges. Claude Code is powerful but inconsistent, it rushes through tasks, over-engineers simple requests, loses context mid-session, and sometimes claims completion on broken code. Council adds mode injection (switching between rapid prototyping and careful building per-prompt), build frameworks with quality gates, path protection for sensitive files, and multi-agent orchestration with circuit breakers to catch stuck loops. Includes multi-model planning where different models critique each other's approaches. The next steps are integrations accross other agentic coding tools to allow for more robust testing, planning, and execution to account for issues such as overfitting test cases to existing code and more. 


### [Deep Research](https://github.com/kylenewm/personalized-deep-research)
**Status:** Completed

**Goal**: Develop a product that is more trustworthy than most current deep research providers, since focus is on accuracy vs. coverage. This product allows me to run large amounts of research while working on other tasks 

Deep research with a layered anti-hallucination architecture that searches the web, gathers sources, and generates verified research reports. This project helps overcome trust issues with current deep research agents that prioritize speed and flashiness over accuracy and is embedded in my workflow when doing research for new product features or higher-level planning.  See [example report](https://kylenewm.github.io/deep-research-v0/reports/observability_voice_agents_report.html).

### [Code Visualizer](https://github.com/kylenewm/code-visualizer)
**Status:** Completed

**Goal:** Understand changes in real-time when using AI assisted coding

A developer observability tool built for the AI-assisted coding era. As product teams increasingly rely on tools like Cursor and Claude Code to accelerate development, a gap emerges: how do you maintain oversight of code you didn't write line-by-line? CodeFlow solves this by analyzing codebases in real-time, visualizing function relationships, and automatically flagging when code drifts from its documentation. It integrates directly with Claude Code, enabling the AI to check its own work against project standards before committing. Built from firsthand experience managing AI-augmented development workflows where speed is high but visibility is low.


### [AI Morning Briefing](https://github.com/kylenewm/ai-morning-briefing)
**Status:** Completed (With Future Iterations)

**Goal:** To streamline and personalize my ingestion of AI-related news 

An automated daily briefing system that delivers personalized AI insights every weekday at 9:30 AM ET. It intelligently curates AI articles, summarizes podcasts, and processes newsletters into a single, digestible morning update. A future iteration will replace third-party search with my own research module and improve the source quality and structure of the briefing.
