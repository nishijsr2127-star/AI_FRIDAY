# AI_FRIDAY
AI Friday Season 2 – Problem StatementsConsumer Packaged Goods Social Media Review AnalyzerPROBLEM STATEMENTCPG companies receive vast amounts of social media feedback that is difficult to analyze manually to gauge product sentiment and identify emerging issues. There is a need for an AI agent that summarizes customer opinions and extracts actionable insights quickly.Data Considerations (Guidelines):Social media posts and reviews scraped from public APIs (Twitter, Reddit) related to specific CPG products, labeled sentiment datasets for validation.Feel free to generate synthetic data where appropriate using the provided environment.SOLUTION EXPECTATIONSAn AI agent generating textual sentiment summaries and topic highlights accessible via a simple interface. Deliverables include sentiment reports, documentation, and a demo video. Success measured by classification accuracy and analysis speed improvement.Be creative to go beyond as you solve the above needs.


question 2: 


2. AI Friday Season 2 – Problem Statements
Business Analysis Automated Impact Analysis Summarizer
PROBLEM STATEMENT
Business analysts often perform impact analysis to understand how proposed changes affect systems, processes, and stakeholders. This requires consolidating information from multiple documents and stakeholder inputs, which is time-consuming and prone to omissions. Existing tools do not automate impact summarization or provide consistent formats, leading to delays and inconsistent documentation quality.
An AI summarizer that generates clear impact analysis reports from input documents can enhance analyst productivity and project alignment.
Data Considerations
Change request documents, stakeholder feedback, and system specifications in text or PDF format.
Data sourced from internal project archives or synthetic generation.
Volume sufficient for demo with 20 documents.
Preprocessing includes OCR and text extraction.
Privacy considerations require anonymization or synthetic data.
Consider using synthetic or anonymized data where appropriate. Ensure data quality and relevance to the problem context.
SOLUTION EXPECTATIONS
An AI summarization tool that:
Accepts multiple documents
Generates structured impact analysis reports using GenAI capabilities
Features include:
Document upload
Summary display
Export options
Constraints:
Integration limited to local files
Success Metrics:
Summary completeness
User satisfaction
Demo should include:
Interactive document upload
Summary generation
Feel free to explore creative solutions that align with the problem context and objectives.

AI Friday Season 2 – Problem Statements

1. Back Office Compliance Document Reviewer

Problem Statement

Back office teams must review compliance documents to ensure regulatory adherence. Manual review is tedious and time-consuming. An AI agent that identifies compliance risks and highlights key clauses can assist in faster, more accurate document assessment.

Data Considerations (Guidelines)

Sample compliance documents and regulations

Public regulatory guidelines

Synthetic documents with annotated risks

Feel free to generate synthetic data where appropriate using the provided environment


Solution Expectations

Build a prototype AI reviewer that:

Accepts document uploads

Outputs risk flags and summary highlights

Includes a document viewer and risk annotation display


Success will be measured by:

Detection accuracy

Reviewer feedback


Be creative and go beyond while solving the above needs.


---

2. Legacy Modernization Code Impact Analyzer

Problem Statement

Assessing the impact of changes in legacy systems is critical for modernization but is often done manually through code reviews, which is time-consuming and error-prone. An AI agent that analyzes legacy code changes and predicts impacted modules can assist developers in risk assessment.

Data Considerations (Guidelines)

Sample legacy codebases with module dependencies

Change logs and impact annotations

Public programming language parsers and code analysis tools

Feel free to generate synthetic data where appropriate using the provided environment


Solution Expectations

Build a prototype AI assistant that:

Processes code change inputs

Generates impact reports listing affected modules and risk levels

Includes text input UI and report generation


Success will be measured by:

Prediction accuracy

Developer feedback


Be creative and go beyond while solving the above needs.


---

3. Application Maintenance Knowledge Base Q&A Agent

Problem Statement

Develop an AI chatbot for application maintenance support that responds to user queries using knowledge base articles and FAQs.

Data Considerations (Guidelines)

Sample application maintenance knowledge base articles and FAQs

Public IT support documentation

Synthetic query-answer pairs for testing

Feel free to generate synthetic data where appropriate using the provided environment


Solution Expectations

Build a prototype AI chatbot that:

Responds to maintenance queries with relevant knowledge base excerpts and explanations

Includes natural language input, answer generation, and source citation


Success will be measured by:

Answer accuracy

User satisfaction


Be creative and go beyond while solving the above needs.


AI Friday Season 2 – Problem Statements
Personalized Retail Product Description Generator for eCommerce
Problem Statement
Retailers often struggle to create compelling and unique product descriptions at scale, especially for large inventories with frequent updates or new arrivals. Many product descriptions are generic, poorly optimized for customer engagement, and lack personalization, reducing conversion rates.
Marketing teams and content creators face the burden of manually writing or adapting descriptions for thousands of SKUs, which slows time-to-market and incurs high labor costs. Existing template-based approaches are rigid and fail to capture nuanced product features or customer preferences.
There is an unmet need for an AI-powered solution that can generate attractive, tailored product descriptions based on minimal input data, enabling faster content creation and improved customer experience.
This would help retailers:
Increase sales
Reduce bounce rates
Enhance brand voice consistency across channels
Data Considerations
Structured product attribute data in JSON or CSV format, including:
Product name
Features
Category
Price
Sample datasets may come from:
Internal retail catalogs
Public eCommerce product datasets
Data volume should be moderate (hundreds to low thousands of SKUs) for demo purposes.
Minimal preprocessing should be required beyond normalization of attribute fields.
No sensitive data is involved.
Synthetic product data can be generated to simulate diverse catalogs.
Consider using synthetic or anonymized data where appropriate.
Ensure data quality and relevance to the problem context.
Solution Expectations
Develop a simple web application or command-line tool where users can:
Upload product attribute files, or
Input single product details
and receive AI-generated product descriptions optimized for clarity and customer appeal.
Expected Features
Tone adjustment:
Formal
Casual
Length control
Batch generation
Export options
Success Criteria
Positive user feedback on description relevance and attractiveness
Demonstration of reduced content creation time
Ability to scale content generation efficiently
Technology Focus
The solution should leverage Generative AI (GenAI) and natural language generation to automate creative content production, enabling faster and more scalable retail marketing workflows.
Teams are encouraged to explore creative solutions that align with the problem context and objectives.

==============================================================================================
Generate a complete end-to-end full stack AI application for the attached problem statement.

The project must be fully runnable locally in VS Code after installing dependencies. Generate complete executable code only. No pseudocode, TODOs or placeholders.

Requirements:

- Generate complete frontend and backend.
- Include folder structure, requirements.txt, package.json, README.md, app.py and .env.example.
- Generate synthetic data through data/generate_data.py that asks the user for the number of records and creates realistic postal datasets instead of static CSV files.
- Use FastAPI for backend and React + TypeScript + Tailwind for frontend.
- Use LangChain + ChromaDB for Retrieval Augmented Generation.
- Keep all LLM logic inside backend/llm.py.
- Keep all RAG logic inside backend/rag.py.
- Keep prompts inside backend/prompts.py.
- Never call the LLM directly from API routes.
- Use Azure OpenAI configured only through environment variables.
- Implement agent-based architecture with separate agents for address resolution, delivery exception analysis, recommendation generation, complaint analysis and operational insights.
- Build reusable services for address parsing, geospatial analysis, confidence scoring, historical pattern analysis and analytics.
- Generate realistic synthetic datasets including parcel records, delivery history, failed deliveries, return-to-sender cases, PIN code directory, post office directory, GPS coordinates, delivery remarks and customer complaints.
- RAG knowledge base should index postal rules, delivery guidelines, PIN code directory, historical delivery records and operational manuals.
- AI must retrieve relevant context before generating recommendations.
- Predict the most probable delivery address for incomplete or ambiguous addresses.
- Generate delivery confidence scores with explanations.
- Recommend corrective actions for delivery staff.
- Detect recurring failure patterns and operational bottlenecks.
- Provide explainable AI reasoning for every recommendation.
- Include an AI Copilot where postal staff can ask questions in natural language about delivery exceptions, addresses, complaints and delivery history.
- Include CSV upload for batch delivery exception analysis.
- Include export of generated recommendations.
- Build an enterprise-grade dashboard inspired by Microsoft Fabric and Power BI with dark mode, responsive layout, interactive charts and maps.
- Dashboard should display delivery success rate, RTS trends, delivery exception trends, confidence score distribution, hotspot regions, complaint analytics, address quality metrics and operational KPIs.
- Include geospatial visualization of delivery hotspots using Leaflet or Mapbox with synthetic coordinates.
- Generate a flow diagram showing complete application architecture and request flow.
- Optimize the solution for hackathon judging with emphasis on business value, AI capability, usability, explainability and visual appeal.
- Do not generate Docker, Kubernetes, CI/CD, deployment, DevOps, monitoring or testing files.
