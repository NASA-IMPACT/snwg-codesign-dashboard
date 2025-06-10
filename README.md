# SNWG Co-Design Repository Template

This repository template provides Solution Project implementation teams with a complete workflow for managing co-design throughout their project lifecycle.

## 🚀 Quick Start for Project Leads

### 1. Create Your Project Repository
1. Click "Use this template" button above
2. Name your repository: `[solution-name]-codesign` (e.g., `hls-ll-codesign`)
3. Make it public or private based on your needs
4. Click "Create repository from template"

### 2. Set Up Your Project Board
1. Go to "Projects" tab in your new repository
2. Click "Link a project" → "New project"
3. Choose "Board" template
4. Import the co-design columns (instructions in `/docs/PROJECT-BOARD-SETUP.md`)

### 3. Customize for Your Solution
1. Edit `/stakeholders/STAKEHOLDER-MAP.md` with your actual stakeholders
2. Update `/milestones/PROJECT-TIMELINE.md` with your solution timeline
3. Review and customize email templates in `/templates/communications/`

### 4. Start Your Co-Design Process
1. Create your first issue using "Touchpoint Planning" template
2. Schedule Working Session 1 using the WS1 template
3. Begin stakeholder identification and mapping

## 📋 Repository Structure

```
.github/
├── ISSUE_TEMPLATES/
│   ├── touchpoint-planning.yml      # Plan Touchpoints 1-8
│   ├── working-session.yml          # Schedule WS1, WS2, WS3
│   ├── stakeholder-feedback.yml     # Capture stakeholder input
│   ├── action-item.yml              # Track follow-up tasks
│   └── milestone-tracking.yml       # Track major milestones
├── workflows/
│   └── project-automation.yml       # Optional automation
└── pull_request_template.md

docs/
├── CODESIGN-GUIDE.md               # Complete co-design reference
├── TOUCHPOINT-REFERENCE.md        # Detailed guide for each touchpoint
├── WORKING-SESSION-AGENDAS.md      # Ready-to-use agendas for WS1-3
├── PROJECT-BOARD-SETUP.md          # How to configure project board
└── STAKEHOLDER-ROLES.md            # Understanding different stakeholder types

templates/
├── communications/
│   ├── touchpoint-emails/
│   │   ├── touchpoint-1-introduction.md
│   │   ├── touchpoint-4-screening.md
│   │   └── touchpoint-5-requirements.md
│   ├── meeting-invitations/
│   │   ├── working-session-1-invite.md
│   │   ├── working-session-2-invite.md
│   │   └── working-session-3-invite.md
│   └── feedback-forms/
│       ├── stakeholder-survey.md
│       └── requirements-checklist.md
├── project-planning/
│   ├── project-plan-codesign-section.md
│   ├── budget-template.md
│   └── timeline-template.md
└── reporting/
    ├── touchpoint-summary.md
    ├── working-session-notes.md
    └── stakeholder-engagement-report.md

stakeholders/
├── STAKEHOLDER-MAP.md              # Master stakeholder database
├── requirements-tracker.md         # Stakeholder requirements
├── engagement-log.md              # Communication history
└── feedback-archive/              # Organized feedback storage

milestones/
├── PROJECT-TIMELINE.md             # Based on SNWG timeline
├── touchpoint-schedule.md         # Specific touchpoint dates
└── decision-gates.md              # Key decision points

README.md                          # This file
```

## 🎯 How This Works

### For Project Leads
- **No coding required** - just fill out templates and track progress
- **Guided workflow** - templates walk you through each step
- **Visual progress tracking** via GitHub Project Board
- **Team collaboration** built-in with assignments and notifications
- **Professional stakeholder communication** with pre-written templates

### The Co-Design Pipeline
Your project board will have these columns matching the SNWG co-design process:

1. **📋 Stakeholder Identification** - Identify and prioritize stakeholders
2. **📝 Touchpoint Planning** - Plan upcoming touchpoints and working sessions  
3. **🤝 Active Engagement** - Currently executing touchpoints and communications
4. **💬 Feedback Integration** - Processing and responding to stakeholder feedback
5. **✅ Documentation Complete** - Completed touchpoints and documented outcomes

### Issue Templates Available
- **🤝 Touchpoint Planning** - Plan any of the 8 touchpoints
- **🔧 Working Session** - Schedule and track WS1, WS2, WS3
- **💬 Stakeholder Feedback** - Capture and track stakeholder input
- **✅ Action Item** - Track follow-up tasks and commitments
- **🎯 Milestone Tracking** - Track major project milestones

## 📚 Documentation Included

### Complete Guides
- **Co-Design Guide** - Everything you need to know about the SNWG co-design process
- **Touchpoint Reference** - Detailed instructions for each of the 8 touchpoints
- **Working Session Agendas** - Copy-paste agendas for all working sessions

### Templates Ready to Use
- **Email Templates** - Professional communications for each touchpoint
- **Meeting Invitations** - Standard invitations for working sessions
- **Feedback Forms** - Standardized ways to collect stakeholder input
- **Project Planning** - Templates for integrating co-design into project plans

### Tracking Tools
- **Stakeholder Map** - Based on the HLS-LL format for consistency
- **Requirements Tracker** - Document and track stakeholder requirements
- **Engagement Log** - History of all stakeholder communications

## 🔄 Typical Workflow

### Week 1: Setup
1. Create repository from template
2. Set up project board
3. Customize stakeholder map with your actual stakeholders
4. Create first "Touchpoint 1 Planning" issue

### Month 1: Initial Engagement
1. Execute Touchpoint 1 (Solution Introduction)
2. Schedule and run Working Session 1 (Co-Design 101)
3. Begin stakeholder identification and mapping
4. Plan Touchpoint 4 (Outreach & Screening)

### Month 2-3: Requirements Gathering
1. Execute Touchpoint 4 and 5
2. Run Working Session 2 (Strategy Meeting)
3. Document stakeholder requirements
4. Plan Working Session 3

### Ongoing: Iterative Co-Design
1. Regular touchpoints based on project needs
2. Continuous stakeholder feedback integration
3. Progress tracking via project board
4. Regular working sessions as needed

## 🎓 Training and Support

### Getting Started
1. Read `/docs/CODESIGN-GUIDE.md` for complete overview
2. Review your solution's timeline in Assessment documents
3. Identify your stakeholders using the provided template
4. Start with Touchpoint 1 planning

### Need Help?
- Check `/docs/` folder for detailed guides
- Use issue templates - they include helpful guidance
- Contact SEP team for co-design support
- Reference working session agendas for meeting structure

## 📊 Success Metrics

Track your co-design success with these built-in metrics:
- **Touchpoint Completion Rate** - % of planned touchpoints completed
- **Stakeholder Engagement Rate** - % of stakeholders actively participating  
- **Feedback Integration Rate** - % of stakeholder feedback addressed
- **Requirements Documentation** - Completeness of stakeholder requirements
- **Timeline Adherence** - On-time completion of co-design milestones

## 🔗 Integration with SNWG Process

This template aligns with:
- **Assessment Phase** - Leverages stakeholder identification from assessment
- **Solution Development** - Integrates co-design into project planning
- **Implementation** - Ongoing stakeholder engagement throughout development
- **SEP Reporting** - Standardized documentation for SEP team
- **SNWG Timeline** - Matches decision gates and milestones

---

**Ready to start?** Click "Use this template" and begin your solution's co-design journey!
