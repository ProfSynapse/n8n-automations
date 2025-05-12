# N8N Automations

A collection of ready-to-use automation workflows for [n8n](https://n8n.io/), the open-source workflow automation tool.

## About This Repository

This repository contains JSON workflow files that can be directly imported into your n8n instance. Each automation is designed to solve specific productivity challenges and can be customized to fit your specific needs.

## Getting Started

### Prerequisites

- An n8n instance (self-hosted or cloud)
- For self-hosted setup, check out our [Railway + n8n setup tutorial](https://youtu.be/Q_VNgDsI8lo)

### How to Import Workflows

1. Download the desired JSON file from this repository
2. In your n8n instance, click on the menu (three dots in the top right)
3. Select "Import from File"
4. Choose the downloaded JSON file
5. Configure credentials and parameters as needed

## Available Automations

### Transcription Summarizer

**File:** `transcript-summarizer.json`

**Description:** Automatically detects new transcript documents in a Google Drive folder, uses AI to create a summary, updates the original document with the summary, and sends an email notification.

**Tutorial:** [Watch the step-by-step guide](https://youtu.be/)

**Requirements:**
- Google Drive account and API credentials
- Email account for sending notifications
- AI provider (OpenRouter or similar)

### (More automations coming soon!)

## Customization

Each workflow can be customized by:

1. Changing the trigger conditions
2. Modifying AI prompts for different outputs
3. Adding additional nodes for extended functionality
4. Adjusting notification preferences

## Contributing

Feel free to contribute your own n8n automations by creating a pull request. Please include:

- The JSON workflow file
- A brief description of what the automation does
- Any specific setup requirements
- Screenshots or examples (optional)

## Resources

- [n8n Documentation](https://docs.n8n.io/)
- [Synaptic Labs Blog](https://blog.synapticlabs.ai)
- [Professor Synapse YouTube Channel](https://www.youtube.com/c/ProfessorSynapse)
- [Synaptic Labs Discord Community](https://discord.gg/z5DgD5ZHNJ)

## License

This project is licensed under the MIT License - see the LICENSE file for details.
