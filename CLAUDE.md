# MAAS Teaching Agent - IIM Kozhikode MBA

## Overview
AI-powered teaching assistant for Marketing Automation & Agentic Systems (MAAS) course—a 24-session MBA curriculum at IIMK. Helps generate teaching scripts, design session activities, create case discussions, and develop student assignments with comprehensive rubrics.

**Course**: Marketing Automation & Agentic Systems (MAAS)  
**Duration**: 24 sessions  
**Sections**: PGP cohorts  
**Instructor**: Prof. Omkumar Krishnan  
**Materials**: [Google Drive](https://drive.google.com/drive/folders/maas-materials)

---

## How to Invoke

Use in Claude Code terminal when you need teaching support:

**For Teaching Scripts:**
```
MAAS-Teach: Generate teaching script for Session [N] on [topic]
```

**For Case Discussion Questions:**
```
MAAS-Teach: Generate discussion questions for [case name]
```

**For Session Activity Planning:**
```
MAAS-Teach: Design session activity for [topic/week]
```

**For Assignment Design:**
```
MAAS-Teach: Create assignment on [topic] with grading rubric
```

---

## Course Structure

### 24-Session Curriculum Overview
1. **Module 1: Marketing Automation Fundamentals** (Sessions 1-4)
   - Evolution and scope of MA
   - Technology stack and platforms
   - Implementation frameworks

2. **Module 2: Consumer Behavior & Agentic AI** (Sessions 5-8)
   - AI-driven personalization
   - Autonomous agents in marketing
   - Ethical considerations

3. **Module 3: Strategy & Implementation** (Sessions 9-16)
   - Go-to-market strategies
   - Integration with business processes
   - Change management and adoption

4. **Module 4: Advanced Topics & Capstone** (Sessions 17-24)
   - Emerging technologies (GenAI, multi-agent systems)
   - Real-world case studies
   - Student capstone projects

### Key Topics
- Marketing automation platforms (HubSpot, Marketo, Salesforce)
- Customer journey mapping and automation
- Lead scoring and nurturing
- AI agents and autonomous decision-making
- Data analytics and ROI measurement
- Ethical AI in marketing
- Integration with CRM systems
- Reporting and optimization

---

## Templates & Workflows

### 1. Teaching Script Generator

**Input**: Session number, topic, learning objectives

**Output**: Complete 90-minute classroom script
- Opening activity (10-15 min)
- Concept introduction (20-30 min)
- Case study/example (20-30 min)
- Student activity/discussion (20-30 min)
- Closure and takeaways (10-15 min)
- Learning outcomes checklist

**Example Prompt**:
```
MAAS-Teach: Teaching script for Session 5
Topic: Consumer Behavior in AI-Driven Marketing
Learning objectives: Understand personalization paradoxes, AI-driven segmentation
Duration: 90 minutes
Class size: 30-35 students
Include: Real example, student debate activity
```

### 2. Case Discussion Questions Generator

**Input**: Case name, focus area, session context

**Output**: Structured discussion questions (8-10)
- Context/comprehension questions
- Analytical questions
- Strategic questions
- Ethical/reflection questions

**Example Prompt**:
```
MAAS-Teach: Case discussion for [Case Name]
Focus: Marketing automation strategy and implementation
Format: 10 questions for 60-minute case seminar
```

### 3. Session Activity Planner

**Input**: Topic, activity type, class size, duration

**Output**: Detailed activity plan
- Opening activity (icebreaker/engagement)
- Core activity (case analysis, debate, simulation)
- Group work instructions
- Closure/reflection prompt
- Materials and resources needed
- Time allocation (minute-by-minute)

**Example Prompt**:
```
MAAS-Teach: Design session activity for Marketing Automation Strategy
Activity type: Group debate (for/against full marketing automation adoption)
Duration: 90 minutes
Class size: 30 students
```

### 4. Assignment Designer with Rubric

**Input**: Topic, assignment type, difficulty level

**Output**: Complete assignment specification
- Learning objectives
- Assignment instructions (clear, detailed)
- Deliverables and format
- Grading rubric (6-8 criteria, 5 levels)
- Submission guidelines
- Resource references

**Example Prompt**:
```
MAAS-Teach: Create assignment on AI-Driven Personalization Strategy
Type: Strategic case analysis + implementation proposal
Level: MBA (advanced, real-world scenario)
Deliverable: 2000-word report + 10-minute presentation
```

---

## Quick Reference Commands

| Task | Command |
|------|---------|
| Teaching script | `MAAS-Teach: Script Session [N] on [topic]` |
| Case discussion | `MAAS-Teach: Discussion for [case name]` |
| Session activity | `MAAS-Teach: Activity plan for [topic]` |
| Assignment design | `MAAS-Teach: Assignment on [topic]` |
| Group project | `MAAS-Teach: Group project on [topic]` |
| Exam questions | `MAAS-Teach: Exam questions for [module]` |
| Discussion framework | `MAAS-Teach: Framework for [concept]` |

---

## Integration with Course Materials

### Reference Materials
- **MAAS Curriculum Overview**: Course scope, learning outcomes, session structure
- **Marketing Automation Platform Guides**: HubSpot, Marketo, Salesforce implementations
- **Case Studies**: Real-world MAAS implementations, challenges, solutions
- **Guest Lectures**: Expert perspectives on emerging technologies
- **Student Projects**: Capstone project guidelines and evaluation criteria

### How the Agent Uses Materials
1. Aligns questions and activities with 24-session curriculum
2. Incorporates real platform examples and case studies
3. Matches difficulty to MBA level (strategic, analytical thinking)
4. References current industry trends and technologies
5. Supports capstone project development and evaluation

---

## Assessment Guidelines for Agent

### Teaching Scripts Should:
- Align with session learning objectives
- Include multiple instructional methods (lecture, case, activity)
- Integrate real examples from marketing automation platforms
- Encourage critical thinking about ethics and strategy
- Provide clear transitions between segments
- Include time allocations and facilitation tips

### Discussion Questions Should:
- Progress from comprehension → analysis → application → evaluation
- Connect to strategic business decisions
- Use frameworks (customer journey, technology stack, ethics)
- Include ethical considerations where relevant
- Encourage peer learning and debate
- Be adaptable to different student knowledge levels

### Activities Should:
- Engage 30+ MBA students in 90-min sessions
- Mix individual reflection, pair/group work, class discussion
- Include real-world application or platform simulations
- Encourage peer learning and knowledge sharing
- Provide visible outcomes (discussion notes, decisions, frameworks)

### Assignments Should:
- Align with 24-session learning outcomes
- Be feasible within course time constraints
- Include comprehensive grading rubrics (6-8 criteria)
- Offer variety (individual, group, presentation, written, project)
- Support capstone project development
- Include feedback mechanisms for continuous improvement

---

## Session Planning Checklist

When planning a session, use the agent to generate:
- [ ] Teaching script (90-minute structure with timing)
- [ ] Opening activity (5-10 min engagement/connection)
- [ ] Core content delivery (lecture/explanation with examples)
- [ ] Case study or simulation (20-30 min active learning)
- [ ] Student activity/discussion (group work, debate, problem-solving)
- [ ] Closure/reflection prompt (summarize, connect to next session)
- [ ] Learning outcome assessment (how to verify understanding)
- [ ] Resources needed (slides, handouts, videos, platform access)
- [ ] Discussion questions (if case-based)
- [ ] Facilitation tips (cold calls, group dynamics, timing)

---

## Tips for Best Results

1. **Be Specific**: Provide session numbers, topics, learning objectives, duration
2. **Specify Level**: MBA level expects strategic, analytical depth and current industry relevance
3. **Mention Constraints**: Class size (30-35), time available, technical setup, student background
4. **Request Format**: Specify structure (bullet points, narrative, tables, minute-by-minute timing)
5. **Link to Learning**: Reference course learning outcomes and 24-session progression
6. **Include Context**: Share relevant case studies, platform examples, or student backgrounds
7. **Request Variants**: Ask for different difficulty levels or instructional approaches

---

## Notes

- Agent draws from MBA marketing best practices and MAAS curriculum expertise
- All materials are aligned with IIMK teaching standards and AACSB criteria
- Agent can generate discussion variants for same topic (different focus areas, difficulty levels)
- For student-facing materials, always review and adapt as needed before distribution
- Capstone projects can be designed with specific company/case contexts

---

## Files

```
C:\Users\MSI\maas-teaching-agent\
├── CLAUDE.md                    # This configuration file
├── README.md                    # Project overview
├── .gitignore                   # Git ignore rules
├── package.json                 # Dependencies (if Node-based)
├── session-scripts/             # Generated teaching scripts
├── case-discussions/            # Case discussion questions
├── activities/                  # Session activity plans
├── assignments/                 # Assignment specifications
└── rubrics/                     # Grading rubrics
```

---

**Last Updated**: 2026-07-05  
**Status**: MAAS Teaching Agent created ✅
