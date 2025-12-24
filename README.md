# SBA Data Call Prep Assistant

An AI guide to help small businesses prepare, validate, and organize documentation requested by the U.S. Small Business Administration (SBA), with a primary focus on 8(a) Business Development Program data calls.

## Overview

The SBA Data Call Prep Assistant is a set of instructions for general purpose Large Language Models (LLMs) designed to reduce errors, delays, and follow-up inquiries by ensuring submissions are complete, correctly formatted, and internally consistent before upload to SBA systems.

## What It Does

This assistant functions as a pre-submission quality-control and organization tool that helps businesses:

- ✅ Interpret SBA data call requests in plain language
- ✅ Map each requested item to the correct internal source records
- ✅ Confirm coverage of the last three completed fiscal years
- ✅ Ensure documents are in the required file format (CSV vs PDF)
- ✅ Perform internal validation checks across financial, payroll, and banking records
- ✅ Identify common SBA reviewer red flags and gaps
- ✅ Prepare clear explanations when records do not exist

## What It Does NOT Do

- ❌ Provide legal advice or regulatory opinions
- ❌ Certify eligibility for the 8(a) Program
- ❌ Override official SBA request letters
- ❌ Create, alter, or backdate accounting or payroll records

**Final responsibility for submissions remains with company management and its CPA and/or legal counsel.**

## Repository Structure

```
sba-data-call-assistant/
├── guides/
│   ├── sba-data-call-prep-assistant.md    # Main assistant guide
│   └── llm-setup/                          # LLM-specific setup instructions
│       ├── chatgpt-setup.md                # ChatGPT custom GPT setup
│       ├── claude-setup.md                 # Claude Projects setup
│       ├── copilot-setup.md                # Microsoft Copilot Studio setup
│       ├── gemini-setup.md                 # Google Gemini setup
│       └── perplexity-setup.md             # Perplexity Spaces setup
├── reference_documents/                    # Supporting PDFs and reference materials
├── LICENSE
└── README.md
```

## Getting Started

1. **Read the main guide**: Start with [`guides/sba-data-call-prep-assistant.md`](guides/sba-data-call-prep-assistant.md) to understand the full process
2. **Choose your LLM**: Follow the setup instructions for your preferred AI platform:
   - [ChatGPT Setup](guides/llm-setup/chatgpt-setup.md) - Custom GPT configuration
   - [Claude Setup](guides/llm-setup/claude-setup.md) - Claude Projects configuration
   - [Microsoft Copilot Setup](guides/llm-setup/copilot-setup.md) - Copilot Studio configuration
   - [Google Gemini Setup](guides/llm-setup/gemini-setup.md) - Gemini Gems configuration
   - [Perplexity Setup](guides/llm-setup/perplexity-setup.md) - Perplexity Spaces configuration
3. **Prepare your documents**: Gather your financial records, payroll data, and banking statements
4. **Work through the checklist**: Use the assistant to validate each required item before submission

## Use Cases

- Preparing for initial 8(a) certification data calls
- Annual review submissions
- Ad-hoc SBA documentation requests
- Internal compliance audits before SBA submission

## Contributing

Contributions are welcome! If you have improvements to the guides or want to add setup instructions for additional LLM platforms, please:

1. Fork this repository
2. Create a feature branch
3. Submit a pull request with your changes

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Attribution Required**: If you modify this work, please provide appropriate credit to the original authors.

## Disclaimer

This tool is provided for informational purposes only and does not constitute legal, accounting, or professional advice. Users should consult with qualified professionals for specific guidance related to SBA compliance and certification requirements.

## Contact

For questions or issues, please [open an issue](https://github.com/coforma/sba-data-call-assistant/issues) on GitHub.