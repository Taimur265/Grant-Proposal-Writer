# Grant Proposal Writer

A comprehensive AI-powered tool for generating professional, submission-ready grant proposals. Upload your grant documents (RFPs, guidelines, requirements) and receive a customized prompt that generates complete grant proposals tailored to your specific funding opportunity.

## What's New in v2.0

- **Improved UI/UX**: Tab-based navigation for better workflow
- **Drag & Drop Support**: Easily drag files into the upload area
- **File Content Preview**: Verify uploaded documents loaded correctly
- **Character & Word Count**: Track content length in real-time
- **Clear All Functionality**: Reset form with one click
- **Organization Details Form**: Structured fields for organization information
- **Better Error Handling**: Clear warnings for PDF/Word file limitations
- **Clipboard Fallback**: Works in more browsers
- **30+ Proposal Types**: Additional grant categories added

## Features

### Document Processing
- **File Upload**: Upload text files (PDF/Word have limited browser support)
- **Paste Text**: Directly paste grant document content (recommended)
- **Drag & Drop**: Drag files directly into the upload area
- **File Preview**: Preview uploaded file content to verify extraction
- **Multi-Document Support**: Process multiple grant documents simultaneously

### 30+ Specialized Proposal Types

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
- Biodiversity Conservation Grant

**Business & Economic Development**
- SME Development Grant
- Social Enterprise Grant
- Financial Inclusion Grant
- Tourism Development Grant
- Trade & Export Development Grant

**Social Development**
- Women Empowerment Grant
- Youth Development Grant
- Capacity Building Grant
- Governance & Democracy Grant
- Human Rights Grant
- Disability Inclusion Grant

**Infrastructure & Development**
- Agriculture & Rural Development Grant
- Infrastructure Development Grant
- Disaster Relief & Recovery Grant
- Humanitarian Aid Grant
- Urban Development Grant
- Housing & Shelter Grant

**Other**
- Sports & Recreation Grant
- Media & Journalism Grant
- Digital Transformation Grant

### Comprehensive Proposal Sections

The AI grant writer generates all standard sections including:

1. **Cover Page & Executive Summary** - Project title, funding request, problem statement, solution overview
2. **Organizational Background** - History, capacity, track record, governance
3. **Needs Assessment** - Data-driven problem analysis with evidence, stakeholder analysis
4. **Project Description** - Theory of change, SMART objectives, LogFrame, activities
5. **Implementation Plan** - Timeline, work plan, resource allocation
6. **Monitoring & Evaluation** - KPIs, data collection, evaluation design
7. **Sustainability Plan** - Financial, institutional, technical sustainability
8. **Budget Narrative** - Line-item budget with justifications
9. **Partnerships** - Collaborations, MOUs, community engagement
10. **Annexes** - Supporting document recommendations

### Expert Grant Writing Features

- Analyzes funder priorities and evaluation criteria
- Aligns proposal language with funder terminology
- Uses persuasive, action-oriented writing
- Includes quantifiable metrics and evidence
- Addresses all RFP requirements systematically
- Sector-specific guidance for specialized grants
- Cross-cutting themes (gender, environment, disability)
- International donor experience (USAID, World Bank, EU, GIZ, DFID/FCDO)

## How to Use

### Step 1: Input Grant Documents

Choose your preferred input method:

**Option A: Paste Text (Recommended)**
- Copy the full text from your grant documents
- Paste directly into the text area
- Include RFP text, eligibility requirements, evaluation criteria

**Option B: Upload Files**
- Click or drag files into the upload area
- Best for `.txt` files
- Note: PDF and Word files have limited extraction in browsers

### Step 2: Organization Details (Optional)

Fill in details about your organization:
- Organization name
- Geographic location/focus
- Budget request
- Project duration
- Mission statement
- Target beneficiaries

### Step 3: Generate Prompt

1. Click "Generate Proposal Prompt"
2. Prompt is automatically copied to your clipboard
3. Open [claude.ai](https://claude.ai) in a new tab
4. Paste the prompt and press Enter
5. Claude generates your complete proposal

## File Structure

```
Grant-Proposal-Writer/
├── README.md                    # This documentation
├── grant-proposal-writer.html   # Standalone HTML version (v2.0)
└── GrantProposalWriter.jsx      # React component version
```

## Tips for Best Results

1. **Use Paste Text Mode**: Most reliable method for document input
2. **Include Complete Documents**: Full RFP text, guidelines, evaluation criteria, annexes
3. **Fill Organization Details**: More context = better customized proposal
4. **Select Correct Proposal Type**: Enables sector-specific guidance
5. **Include Budget Parameters**: Mention limits or requirements
6. **Review Generated Proposal**: Use as strong foundation, customize as needed

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Internet connection (for CDN resources)

## Supported File Types

| Format | Support Level |
|--------|---------------|
| .txt   | Full support  |
| .pdf   | Limited (binary files not extracted) |
| .docx  | Limited (binary files not extracted) |
| .rtf   | Partial support |

**Recommendation**: For PDF and Word documents, copy the text content and use the "Paste Text" option.

## Changelog

### v2.0 (Current)
- Tab-based navigation UI
- Drag and drop file upload
- File content preview
- Character and word count
- Organization details form
- Clear all functionality
- Clipboard fallback for older browsers
- Better file format handling with warnings
- 8 new proposal types added
- Enhanced grant writer prompt with more sector guidance
- Cross-cutting themes integration

### v1.0
- Initial release
- Basic file upload and paste text
- 24 proposal types
- Comprehensive grant writer prompt

## License

MIT License
