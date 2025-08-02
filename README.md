# SDR
Automations for Sales Development Representative

<img width="1352" height="451" alt="Screenshot 2025-08-01 at 19 01 37" src="https://github.com/user-attachments/assets/5aebfcba-4455-4737-93f2-52684b2a03a4" />


This automation flow is designed to generate comprehensive, research-backed lead magnet articles based on a user-submitted topic, conduct deep research across multiple sources, and automatically create a professional Google Doc ready for LinkedIn sharing.

## Targets

🚀 Ideal Use Cases:
B2B companies building thought leadership content
Sales teams creating industry-specific lead magnets
Marketing departments scaling content production
Consultants developing expertise-demonstrating resources
SaaS companies creating feature-focused educational content
Startups establishing market presence without content teams

⚙️ Flow (Step-by-Step):

📝 Chat Input (Entry Point)

A user submits a topic through the chat interface:
Topic for lead magnet content
Target audience (automatically detected)
Company context (when relevant)

🔍 Query Builder Agent

An AI agent refines the input by:
Converting the topic into 5 targeted research queries
Determining if topic relates to *company for specialized research
Using structured output parsing for consistent results

📚 Research Leader Agent

Conducts comprehensive research that:
Uses Perplexity API for real-time web research
Integrates *company knowledge base when relevant
Creates detailed table of contents with research insights
Identifies key trends, expert opinions, and case studies

📋 Project Planner Agent

Structures the content by:
Generating professional title and subtitle
Creating 8-10 logical chapter outlines
Developing detailed writing prompts for each section
Ensuring step-by-step actionable guidance

✍️ Research Assistant Team

Multiple AI agents write simultaneously:
Each agent writes one chapter with proper citations
Maintains consistent voice across all sections
Includes real-world examples and implementation steps
Uses both web research and *company knowledge

📝 Editor Agent

Professional content polishing:
Refines tone for authenticity and engagement
Adds image placeholders where appropriate
Ensures proper flow between chapters
Optimizes for LinkedIn lead magnet format

📄 Google Docs Creation

Automated document generation:
Creates new Google Doc with formatted content
Sets proper sharing permissions (public link)
Organizes in designated company folder
Returns shareable URL for immediate use

🛠️ Tools Used:

n8n: Workflow orchestration platform
Anthropic Claude: Primary AI model for content generation
OpenRouter: Backup AI model options
Perplexity API: Real-time research capabilities
*Company Knowledge Hub: Internal documentation access
Google Docs API: Document creation and formatting
Google Drive API: File management and sharing

📦 Key Features:

End-to-end automation from topic to published document
Multi-agent approach ensures comprehensive coverage
Real-time research with proper citations
Company-specific knowledge integration
Professional editing and formatting
Automatic Google Docs creation with sharing
Scalable content generation (3-5 minutes per article)


