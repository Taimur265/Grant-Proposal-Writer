# Grant Proposal Writer

A comprehensive AI-powered tool for generating professional, submission-ready grant proposals. Upload your grant documents (RFPs, guidelines, requirements) and receive a customized prompt that generates complete grant proposals tailored to your specific funding opportunity.

## Features

### Document Processing
- **File Upload**: Upload PDF, Word (.docx), and Text (.txt) files
- **Paste Text**: Directly paste grant document content for reliable processing
- **Multi-Document Support**: Process multiple grant documents simultaneously

### 24+ Specialized Proposal Types

**General**
- Standard Grant Proposal
- Research Grant
- Nonprofit Program Grant
- Education/School Grant
- Community Development Grant
- Healthcare Grant
- Arts & Culture Grant
- Technology Grant

**Climate & Environment**
- Climate Initiative Grant
- Renewable Energy Grant
- Water & Sanitation Grant
- Environmental Grant

**Business & Economic Development**
- SME Development Grant
- Social Enterprise Grant
- Financial Inclusion Grant
- Tourism Development Grant

**Social Development**
- Women Empowerment Grant
- Youth Development Grant
- Capacity Building Grant
- Governance & Democracy Grant

**Infrastructure & Development**
- Agriculture & Rural Development Grant
- Infrastructure Development Grant
- Disaster Relief & Recovery Grant
- Humanitarian Aid Grant

**Other**
- Sports & Recreation Grant

### Comprehensive Proposal Sections

The AI grant writer generates all standard sections including:

1. **Executive Summary** - Funding request, problem statement, solution overview
2. **Organizational Background** - History, capacity, track record
3. **Needs Assessment** - Data-driven problem analysis with evidence
4. **Project Description** - SMART objectives, theory of change, activities
5. **Implementation Plan** - Timeline, milestones, resource allocation
6. **Monitoring & Evaluation** - KPIs, data collection, evaluation design
7. **Sustainability Plan** - Financial, institutional, and technical sustainability
8. **Budget Narrative** - Line-item budget with justifications
9. **Partnerships** - Collaborations, community engagement
10. **Annexes** - Supporting document recommendations

### Expert Grant Writing Features

- Analyzes funder priorities and evaluation criteria
- Aligns proposal language with funder terminology
- Uses persuasive, action-oriented writing
- Includes quantifiable metrics and evidence
- Addresses all RFP requirements systematically
- Sector-specific guidance for specialized grants

## How to Use

### Option 1: HTML File (Standalone)

1. Open `grant-proposal-writer.html` in any modern web browser
2. Choose input method (Upload Files or Paste Text)
3. Input your grant documents
4. Select the appropriate proposal type
5. Add any additional organizational context
6. Click "Generate Grant Proposal Prompt"
7. The prompt is automatically copied to your clipboard
8. Paste it into a new Claude conversation to generate your complete proposal

### Option 2: React Component (For Integration)

Import and use the React component in your project:

```jsx
import GrantProposalWriter from './GrantProposalWriter';

function App() {
    return <GrantProposalWriter />;
}
```

### Option 3: Claude Artifact

Copy the JSX code from `GrantProposalWriter.jsx` into a Claude artifact for direct use within Claude conversations.

## File Structure

```
Grant-Proposal-Writer/
├── README.md                    # This documentation
├── grant-proposal-writer.html   # Standalone HTML version
└── GrantProposalWriter.jsx      # React component version
```

## Tips for Best Results

1. **Use Complete Documents**: Include full RFP text, guidelines, and evaluation criteria
2. **Add Organizational Context**: Provide details about your organization, mission, and past achievements
3. **Select Accurate Proposal Type**: Choose the type that best matches your funding opportunity
4. **Include Budget Parameters**: Mention any budget limits or requirements in the additional context
5. **Review and Customize**: Use the generated proposal as a strong foundation, then customize with organization-specific details

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Internet connection (for loading React and Tailwind CDN in HTML version)

## Supported File Types

- PDF (.pdf)
- Microsoft Word (.doc, .docx)
- Plain Text (.txt)
- Rich Text Format (.rtf)

**Note**: For best results with file uploads, use text-based files (.txt, .docx). PDFs may have extraction limitations depending on how they were created.

## Version

v1.0 - Initial Release

## License

MIT License
