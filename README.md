# 🤖 AI Feature Spec Writer

**with CrewAI Multi-Agent System**

> **Transform vague feature ideas into production-ready PRDs, implementation tasks, and acceptance criteria using a 3-agent AI workflow. Get comprehensive specifications—instantly and accurately.** ⚡

---

## ✨ Features

### 🎯 **Core Functionality**
- 🤖 **3-Agent AI Pipeline** - PM → Engineer → Tech Writer sequential workflow
- 📝 **Comprehensive PRDs** - Structured product requirements documents with all sections
- ✅ **Implementation Tasks** - Broken down, actionable engineering tasks
- 🎯 **Acceptance Criteria** - Testable, specific acceptance criteria in Given-When-Then format
- 🔄 **Real-Time Progress** - Live agent timeline with step-by-step updates
- 💾 **Persistent History** - All runs stored in Supabase database
- 🔗 **GitHub Integration** - Optional sync with GitHub Projects (with fallback)

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Clean, professional interface with smooth animations
- 🌙 **Dark Mode** - Full theme support with smooth transitions (default: dark)
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- ♿ **Accessible** - WCAG AA compliant with keyboard navigation
- 🎯 **Intuitive Interface** - 3-pane layout for optimal workflow

### 📊 **Dashboard Features**
- 📈 **PRD History** - View all previous feature specs with search and filter
- 📝 **PRD Preview** - Quick preview of PRDs with metadata
- 🔍 **Search & Filter** - Find PRDs by title, content, or input
- 👁️ **Full PRD View** - Click to view complete PRD in playground
- 📋 **Export Options** - Download or copy PRD as Markdown

### 🚀 **Advanced Features**
- ✏️ **Interactive PRD Editor** - Edit PRDs inline with save/cancel
- ✨ **AI-Powered Refinement** - Refine PRDs with commands like "Make more technical" or "Simplify"
- 💡 **Smart Suggestions** - AI autocomplete for feature descriptions
- 📜 **Version History** - Track PRD changes, compare versions, rollback
- 🌍 **Multi-Language Support** - Generate PRDs in 8 languages (EN, ES, FR, DE, PT, IT, JA, ZH)
- 📋 **Project Templates** - Quick-start templates for common project types
- 🔄 **Real-Time Collaboration** - Server-Sent Events for live updates
- 📊 **Agent Conversation View** - See how agents collaborate and pass information

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern Python web framework
- **CrewAI** - Multi-agent orchestration framework
- **OpenAI API** - GPT-4.1-mini for AI agent capabilities
- **Python 3.11+** - Latest features and performance
- **Pydantic v2** - Data validation and settings

### **Frontend** ⚛️
- **Next.js 15** - React framework with App Router
- **React 19.2** - Latest React features
- **Tailwind CSS** - Utility-first styling
- **shadcn/ui** - Beautiful component library
- **TypeScript** - Type-safe development
- **next-themes** - Theme management

### **Database & Cache** 💾
- **Supabase** - PostgreSQL with `featurespecwriter` schema
- **Upstash Redis** - Serverless job queue & caching
- **Version Tracking** - PRD version history support

### **External APIs** 🔌
- **GitHub Projects v2** - Project management integration
- **OpenAI API** - AI agent capabilities

### **Deployment** 🚀
- **Railway** - Backend API deployment
- **Vercel** - Frontend deployment
- **GitHub** - Source control and CI/CD

---

## 📸 Application Overview

### 🏠 Landing Page
*Beautiful landing page with hero video backgrounds, clear value proposition, and call-to-action buttons*

### 🎮 Playground
*Interactive 3-pane interface:*
- **Left Panel:** Feature brief input with AI suggestions and templates
- **Center Panel:** Real-time agent timeline showing PM → Engineer → Tech Writer progress
- **Right Panel:** Tabbed output (PRD / Tasks / Acceptance Criteria) with edit, export, and sync options

### 📊 Dashboard
*Comprehensive history page:*
- PRD cards with previews
- Search and filter functionality
- Click to view full PRD in playground

---

## 📖 User Guide

### 🎮 Using the Playground

1. **Enter Feature Description**
   - Type your feature idea in the left panel
   - Use **📋 Templates** for quick-start (Web App, Mobile, API, etc.)
   - Get **💡 AI Suggestions** as you type (appears after 3+ characters)
   - Select **🌍 Language** for PRD generation (default: English)

2. **Run the Pipeline**
   - Click **"Run"** button
   - Watch the **Agent Timeline** in the center panel:
     - PM Agent analyzes scope and goals
     - Engineer Agent creates technical breakdown
     - Tech Writer Agent generates PRD and acceptance criteria

3. **View Results**
   - Switch between **PRD**, **Tasks**, and **Acceptance** tabs
   - Each tab shows structured, comprehensive output

4. **Refine & Edit**
   - **✏️ Edit** - Click to edit PRD inline
   - **✨ Refine** - Use AI to refine PRD with commands:
     - Quick commands: "Make this more technical", "Simplify this", "Add more detail"
     - Custom commands: "Focus on security aspects", "Add performance requirements"
   - **📜 Versions** - View version history and rollback if needed

5. **Export & Sync**
   - **📄 Export** - Download or copy PRD as Markdown
   - **🔗 GitHub** - Sync to GitHub Projects (requires token)

### 📊 Using the Dashboard

1. **View History**
   - See all previous PRDs with previews
   - View metadata: task count, acceptance criteria count, date

2. **Search & Filter**
   - Search by title, content, or input text
   - Filter and sort results

3. **View Full PRD**
   - Click any PRD card
   - Opens in playground for full view and editing

---

## 🎨 Customization

### Theme Options
- ☀️ **Light Mode** - Clean, bright interface
- 🌙 **Dark Mode** - Easy on the eyes (default)
- 🖥️ **System** - Follows OS preference

### Language Options
- 🌍 **8 Languages Supported**: English, Spanish, French, German, Portuguese, Italian, Japanese, Chinese
- Select language before running pipeline
- All output (PRD, tasks, acceptance) generated in selected language

### Template Options
- 📋 **6 Project Templates**: Web App, Mobile App, API Service, Database Migration, Authentication System, E-commerce Platform
- Click "Use Template" to apply structured starting point
- Edit template content before running

---

**Features:**
- Real-time job polling with progress updates
- Agent progress visualization with expandable conversation view
- Tabbed output display
- Interactive PRD editor
- AI-powered refinement
- Version history management
- Multi-language support
- Project templates
- Export to Markdown
- GitHub Projects sync



---

## 🎯 Features Implemented

### ✅ Core Features (MVP)
1. **Real-time Agent Progress** - Live updates as agents work
2. **Dashboard History** - View all previous PRDs
3. **Export PRD as Markdown** - Download or copy PRD

### ✅ Enhanced Features
4. **Interactive PRD Editor** - Edit PRDs inline
5. **Smart Feature Suggestions** - AI autocomplete
6. **Agent Conversation View** - See agent collaboration
7. **Project Templates Library** - Quick-start templates

### ✅ Advanced Features
8. **Real-time Collaboration** - Server-Sent Events
9. **Version History** - Track changes, compare, rollback
10. **AI-powered PRD Refinement** - Refine with commands
11. **Multi-language Support** - 8 languages supported

---

## 👨‍💻 Creator

**Created by Derril Filemon**

- 💼 **GitHub**: [@derril-tech](https://github.com/derril-tech)

---

## 🙏 Acknowledgments

- **CrewAI** - For multi-agent orchestration framework
- **OpenAI** - For GPT-4.1-mini API
- **Supabase** - For database & real-time capabilities
- **Upstash** - For Redis caching
- **Railway** - For backend deployment
- **Vercel** - For frontend deployment
- **shadcn/ui** - For beautiful components
- **Next.js Team** - For amazing framework

---

## 📞 Support


---

## 📄 License

MIT License - see LICENSE file for details

---

<div align="center">

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
