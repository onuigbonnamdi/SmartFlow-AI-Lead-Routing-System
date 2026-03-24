# SmartFlow AI Lead Routing System
AI system that captures, classifies, and routes leads automatically using intelligent workflow automation.

![Workflow Overview] <img width="1744" height="663" alt="image" src="https://github.com/user-attachments/assets/86fa9fcc-97ee-446d-a082-e020f8624def" />

## Demo

This system captures leads from a website form and processes them through an AI-powered workflow.

### Live Flow

Form Submission → AI Classification → Routing → Action → Logging
## How It Works

1. User submits details via a contact form  
2. Data is sent to an n8n webhook  
3. OpenAI classifies the message into:
   - intent  
   - priority  
   - route  
4. Workflow routes the lead:
   - Qualified → booking email  
   - Low Priority → acknowledgement email  
   - Human Review → alert notification  
5. All data is logged into Google Sheets

## Key Highlights

- AI-based decision making  
- Multi-path workflow routing  
- Real-time automation  
- Email response system  
- Lead tracking and logging  
- Webhook-based integration

## Architecture

Frontend (HTML Form)  
→ Webhook (n8n)  
→ OpenAI Classification  
→ Decision Logic  
→ Google Sheets Logging  
→ Email Automation

## Use Cases

- Lead qualification for service businesses  
- Automated customer enquiry handling  
- AI-powered contact form processing  
- Internal escalation systems

## Results

- Automatically classifies incoming leads in real time  
- Reduces response delay to near zero  
- Routes high-value leads directly to conversion  
- Filters out low-priority enquiries automatically  
- Escalates sensitive cases for human review  

This demonstrates a complete AI-powered decision and automation system ready for real-world deployment.
