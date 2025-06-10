# GitHub Project Board Setup for Co-Design Pipeline

## 🚀 Quick Setup (5 minutes)

### Step 1: Create New Project
1. In your repository, go to the **"Projects"** tab
2. Click **"Link a project"** → **"New project"**
3. Choose **"Board"** template
4. Name it: `[Solution Name] Co-Design Pipeline` (e.g., "HLS-LL Co-Design Pipeline")
5. Click **"Create"**

### Step 2: Configure Columns
Delete the default columns and create these 5 columns in order:

| Column Name | Purpose |
|-------------|---------|
| **📋 Stakeholder Identification** | Identifying and mapping stakeholders |
| **📝 Touchpoint Planning** | Planning upcoming touchpoints and working sessions |
| **🤝 Active Engagement** | Currently executing touchpoints and communications |
| **💬 Feedback Integration** | Processing and responding to stakeholder feedback |
| **✅ Documentation Complete** | Completed touchpoints and documented outcomes |

### Step 3: Set Up Automation
For each column, set these automation rules:

- **📋 Stakeholder Identification**: Auto-add issues with `stakeholder-mapping` label
- **📝 Touchpoint Planning**: Auto-add issues with `touchpoint` or `working-session` labels  
- **💬 Feedback Integration**: Auto-add issues with `stakeholder-feedback` label
- **✅ Documentation Complete**: Auto-add closed issues

## 🤖 Automatic Setup Option

**Even easier:** Use the automated setup action in your repository!

1. Go to **"Actions"** tab in your repository
2. Find **"Setup Co-Design Project Board"** workflow
3. Click **"Run workflow"**
4. Enter your solution name (e.g., "HLS-LL")
5. Select your project phase
6. Click **"Run workflow"**

This will automatically create your project board with all columns and starter issues!

## 📊 Using Your Project Board

### Daily Workflow
1. Check **"Active Engagement"** - What needs attention today?
2. Review **"Feedback Integration"** - Any stakeholder input to address?
3. Plan ahead in **"Touchpoint Planning"** - What's coming up?

### Moving Issues
- **Drag and drop** issues between columns as work progresses
- Issues **automatically move** based on labels and status
- **Close issues** when touchpoints are complete (auto-moves to Documentation Complete)

Need help? Check the full Co-Design Guide in `/docs/CODESIGN-GUIDE.md`
