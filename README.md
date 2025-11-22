# Grant Proposal Writer Pro v5.0

A professional-grade AI-powered tool for generating comprehensive, submission-ready grant proposals. Upload your grant documents and receive an expertly crafted prompt that leverages 30+ years of grant writing expertise to generate winning proposals.

## What's New in v5.0

### Major Enhancements
- **SDG Alignment Selector** - Visual badges for all 17 Sustainable Development Goals
- **Logical Framework Builder** - Goal, Outcomes, Indicators, Means of Verification, Assumptions
- **Risk Matrix** - Likelihood x Impact assessment with mitigation strategies
- **M&E Indicators Section** - Baseline, Target, Frequency, Data Source tracking
- **Self-Evaluation Scorecard** - Rate your proposal against 6 weighted evaluation criteria
- **Attachment Checklist** - Track 20 common required and optional attachments
- **Deadline Countdown** - Visual countdown with color-coded urgency warnings
- **Word/Page Limit Tracking** - Real-time word count monitoring
- **21 Funder Presets** - Added Oak, Hewlett, MacArthur, GEF foundations
- **8-Tab Workflow** - Documents → Organization → Team → LogFrame → M&E → Budget → Checklist → Output

### Enhanced AI Prompt
- Common rejection reasons to avoid
- Sector-specific excellence guidance
- Cross-cutting themes integration
- Quality standards checklist

## Features

### Document Processing
- **File Upload**: Upload text files (.txt recommended)
- **Paste Text**: Directly paste grant document content (most reliable)
- **Multi-Document Support**: Process multiple grant documents simultaneously
- **Auto-Save**: All data saved to localStorage automatically

### 60+ Specialized Proposal Types

**General**
- Standard Grant, Pilot/Seed, Scaling/Expansion, Research, Capacity Building

**Climate & Environment**
- Climate Adaptation, Climate Mitigation, Renewable Energy, WASH
- Biodiversity Conservation, Forestry & Reforestation, Ocean & Marine
- Waste Management, Circular Economy

**Business & Economic Development**
- SME Development, Startup & Innovation, Social Enterprise
- Financial Inclusion, Trade & Export, Tourism, Agribusiness, Digital Economy

**Education**
- K-12, Higher Education, Vocational Training, STEM, Girls Education
- Inclusive Education, Literacy Programs, Digital Learning

**Healthcare**
- Primary Healthcare, Maternal & Child Health, Mental Health
- Disease Prevention, Nutrition & Food Security, HIV/AIDS
- Digital Health/mHealth, NCD Prevention

**Social Development**
- Women Empowerment, Youth Development, Human Rights
- Disability Inclusion, Refugee & Migration, Governance & Democracy
- Peacebuilding, Child Protection

**Infrastructure**
- Agriculture & Rural Development, Infrastructure Development
- Urban Development, Housing & Shelter, Transport & Connectivity
- Rural Electrification

**Humanitarian**
- Disaster Relief & Recovery, Humanitarian Aid, Emergency Response, Food Security

**Other**
- Arts & Culture, Media & Journalism, Sports & Recreation
- Digital Transformation, Civic Tech

### 21 Funder Presets

| Funder | Key Requirements |
|--------|------------------|
| USAID | DUNS/UEI, SAM.gov, MEL plan, cost-share, environmental compliance |
| European Union | PADOR, LogFrame, co-financing 10-20%, visibility requirements |
| World Bank | Poverty reduction focus, economic analysis, procurement compliance |
| Green Climate Fund | Climate impact, paradigm shift, ESS compliance, accredited entity |
| Global Environment Facility | Focal area alignment, incremental cost reasoning, co-financing |
| Bill & Melinda Gates Foundation | Innovation, scalability, measurable impact, milestone-based |
| FCDO (UK) | Value for Money, Theory of Change, GESI analysis |
| Sida (Sweden) | Results-Based Management, HRBA approach |
| GIZ (Germany) | Capacity development focus, knowledge management |
| JICA (Japan) | Technical cooperation, PDM matrix |
| KOICA (Korea) | ODA alignment, detailed work plan |
| UN Agencies | UN framework alignment, HACT compliance |
| Global Fund | Disease-specific, CCM endorsement, PUDR reporting |
| GAVI | Immunization focus, sustainability transition |
| Mastercard Foundation | Youth employment, Africa priority, systems change |
| Ford Foundation | Social justice, systems change, flexible funding |
| Rockefeller Foundation | Innovation, resilience, equity |
| Oak Foundation | Issue-specific alignment, learning focus |
| Hewlett Foundation | Strategy alignment, outcome focus, OE support |
| MacArthur Foundation | Big bets approach, evidence-based |

### Advanced Features

#### SDG Alignment
- Visual badge selector for all 17 SDGs
- Color-coded by official SDG colors
- Multiple selection supported

#### Logical Framework Builder
- Overall Objective/Goal
- Multiple Outcomes with:
  - Outcome statement
  - Indicators
  - Means of Verification
  - Assumptions & Risks

#### Risk Matrix
- Risk description
- Likelihood rating (Low/Medium/High)
- Impact rating (Low/Medium/High)
- Mitigation strategies

#### M&E Indicators
- Indicator description
- Baseline value
- Target value
- Collection frequency
- Data source

#### Self-Evaluation Scorecard
Rate your proposal on 6 criteria:
| Criteria | Weight |
|----------|--------|
| Relevance & Alignment | 20% |
| Technical Approach & Methodology | 25% |
| Organizational Capacity | 15% |
| Budget & Cost Effectiveness | 15% |
| Expected Impact & Outcomes | 15% |
| Sustainability | 10% |

#### Attachment Checklist
Track 20 common documents:
- Organization Registration Certificate (Required)
- Audited Financial Statements (Required)
- CVs of Key Personnel (Required)
- Logical Framework (Required)
- Detailed Budget (Required)
- Budget Narrative (Required)
- Work Plan/Gantt Chart (Required)
- And 13 more optional documents

## How to Use

1. **Open the HTML file** in any modern browser
2. **Step 1 - Documents**: Paste your grant RFP/guidelines and select proposal type
3. **Step 2 - Organization**: Enter your organization details
4. **Step 3 - Team**: Add key personnel and partner organizations
5. **Step 4 - LogFrame**: Build your logical framework with outcomes and risks
6. **Step 5 - M&E**: Add indicators and complete self-evaluation
7. **Step 6 - Budget**: Enter budget line items
8. **Step 7 - Checklist**: Track required attachments
9. **Step 8 - Output**: Generate and copy your prompt
10. **Paste into Claude** and receive your complete proposal

## Quick Reference Guides

### Built-in Modals
- **Grant Writing Tips**: 7 expert tips for winning proposals
- **Sample RFP**: Example format with "Use This Sample" button
- **LogFrame Guide**: Explains Goal → Outcomes → Outputs → Activities
- **Budget Categories Guide**: Typical percentages and line items

## Technical Details

- **Framework**: React 18 with Babel for JSX
- **Styling**: Tailwind CSS
- **Storage**: Browser localStorage (auto-save)
- **Compatibility**: All modern browsers
- **Print**: Optimized print stylesheet

## Files

| File | Description |
|------|-------------|
| `grant-proposal-writer.html` | Main application (standalone, no build required) |
| `GrantProposalWriter.jsx` | React component for integration |
| `README.md` | This documentation |

## Version History

| Version | Key Features |
|---------|--------------|
| v5.0 | SDG alignment, LogFrame builder, Risk matrix, M&E indicators, Self-evaluation, Attachment checklist |
| v4.0 | 60+ grant types, 16 funder presets, 5-step workflow, Key personnel, Budget framework |
| v3.0 | Dark theme, Progress indicators, Auto-save, Sample RFP, 45+ grant types |
| v2.0 | Tab navigation, Drag & drop, File preview, Character count, 33 grant types |
| v1.0 | Initial release with 24 grant types |

## License

MIT License - Free to use and modify.
