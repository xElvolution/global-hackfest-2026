# Submission checklist

Use this to make sure you’ve got everything in before the deadline.

**Note:** If any required submission item (other than optional items clearly marked as such) is missing, your project may be disqualified from prize consideration.

## Before you submit

**Project**
- [ ] It runs and does what you demo
- [ ] Built in the 6-week window
- [ ] Uses Conflux in a real way
- [ ] Team of 1–5, all registered
- [ ] Your own work (or properly attributed)

**Repo**
- [ ] Public on GitHub, clear name
- [ ] README per template, MIT or Apache 2.0
- [ ] Code builds and runs

**Docs**
- [ ] README with setup and usage
- [ ] Go-to-market plan (required)
- [ ] Architecture/API/user guide as needed
- [ ] Known issues or limits noted

**Demo**
- [ ] 3–5 min video
- [ ] Participant intro video (see below)
- [ ] Live link if you have one, screenshots
- [ ] Slides optional

**Ecosystem**
- [ ] PR to electric-capital/open-dev-data (migration file with `repadd Conflux https://github.com/your-username/your-repo`)
- [ ] Tweet (or similar) tagging @ConfluxDevs and @ConfluxNetwork
- [ ] Grant proposal on Conflux Forum = +5 pts (optional)
- [ ] Submission PR to hackathon repo includes Electric Capital PR link and tweet link

## Steps

### 1. Repo ready

Your GitHub repo should have:

```
your-project-repo/
├── README.md                 # Project overview and setup
├── LICENSE                   # Open source license
├── package.json             # Dependencies (if applicable)
├── src/                     # Source code
├── docs/                    # Additional documentation
├── demo/                    # Demo materials
│   ├── video.mp4           # Demo video
│   ├── screenshots/        # UI screenshots
│   └── presentation.pdf    # Slides (if applicable)
├── contracts/              # Smart contracts (if applicable)
├── tests/                  # Test files
└── deployment/             # Deployment scripts/configs
```

### 2. Add to hackathon repo

Fork [global-hackfest-2026](https://github.com/conflux-fans/global-hackfest-2026), add your project under `/projects/` (e.g. `my-awesome-project`), put in README and demo (and any extra materials), then open a PR.

### 3. Electric Capital PR

So your project shows up in Conflux ecosystem stats, open a PR to electric-capital/open-dev-data.

1. **Fork the repository**: [electric-capital/open-dev-data](https://github.com/electric-capital/open-dev-data)
2. **Create a migration file**: 
   - Navigate to the `migrations/` folder
   - Create a new file with format: `YYYY-MM-DDThhmmss_your_project_name`
   - Example: `2026-05-01T120000_my_awesome_project`
3. **Add the migration content**:
   ```
   repadd Conflux https://github.com/your-username/your-project-repo
   ```
   Optionally add tags:
   ```
   repadd Conflux https://github.com/your-username/your-project-repo #protocol
   ```
4. **Submit the pull request** with a clear description
5. **Reference example PR**: See [PR #2475](https://github.com/electric-capital/open-dev-data/pull/2475) for format reference

**Note**: The PR does not need to be merged before submission deadline, but it must be created and submitted.

### Step 4: Post Social Media Announcement

Create a tweet on Twitter/X announcing your project submission:

1. **Post on Twitter/X** with your project announcement
2. **Tag required accounts**: 
   - @ConfluxDevs
   - @ConfluxNetwork
3. **Include relevant hashtags**: #ConfluxHackathon #globalhackfest26
4. **Share project highlights**: Brief description, demo link, and what makes it unique
5. **Include link to your project**: GitHub repository or live demo URL

**Example tweet format**:
```
🚀 Excited to submit [Project Name] for Global Hackfest 2026! 

[Brief description]

🔗 [Demo/Repo Link]

@ConfluxDevs @ConfluxNetwork #globalhackfest26
```

### Step 5: Create Submission PR

1. **Go to the hackathon repository**: [global-hackfest-2026](https://github.com/conflux-fans/global-hackfest-2026)
2. **Create a Pull Request** from your fork with your `/projects/` folder changes
3. **Use the README.md template** and fill out all required fields completely and accurately, including:
   - Link to your Electric Capital PR
   - Link to your social media post
4. **Submit the Pull Request** before the deadline (2026-04-20 @ 11:59:59)


# 📄 Required Documentation

# README.md Template

Your project README must include the following sections:

# Project Name

## Overview
Brief description of your project and its purpose.

## Hackathon
Global Hackfest 2026 (2026-03-23 – 2026-04-20)

## Team
- Team Member 1 (GitHub: @username, Discord: username#1234)
- Team Member 2 (GitHub: @username, Discord: username#1234)
- Team Member 3 (GitHub: @username, Discord: username#1234)
- Team Member 4 (GitHub: @username, Discord: username#1234)
- Team Member 5 (GitHub: @username, Discord: username#1234)

## Problem Statement
What problem does your project solve?

## Solution
How does your project address the problem?

## Go-to-Market Plan
Your strategy for launching and scaling the project (target users, distribution, growth, metrics).

## Conflux Integration
How does your project use Conflux features?
- [ ] Core Space
- [ ] eSpace
- [ ] Cross-Space Bridge
- [ ] Gas Sponsorship
- [ ] Built-in Contracts
- [ ] Partner Integrations (Privy/Pyth/LayerZero)

## Features
- Feature 1
- Feature 2
- Feature 3

## Technology Stack
- Frontend: React, Next.js, etc.
- Backend: Node.js, Python, etc.
- Blockchain: Conflux Core/eSpace
- Smart Contracts: Solidity
- Other: Additional tools and libraries

## Setup Instructions

### Prerequisites
- Node.js v18+
- Git
- Conflux wallet (Fluent, MetaMask)

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/your-project
   cd your-project
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Configure environment
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. Run the application
   ```bash
   npm start
   ```

### Testing
```bash
npm test
```

## Usage
Step-by-step guide on how to use your application.

## Demo
- **Live Demo**: [https://your-demo-link.com](https://your-demo-link.com)
- **Demo Video**: [Link to video](https://youtube.com/watch?v=your-video)
- **Screenshots**: See `/demo/screenshots/` folder

## Architecture
High-level overview of your system architecture.

## Smart Contracts
If applicable, list deployed contracts with addresses:
- Contract Name: `0x123...` (Testnet)
- Contract Name: `0x456...` (Mainnet)

## Future Improvements
- Planned feature 1
- Planned feature 2
- Known limitations to address

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Conflux Network
- Partner acknowledgments
- Third-party libraries used


# Demo Video Requirements

Your demo video should:
- **Duration**: 3-5 minutes maximum
- **Format**: MP4, MOV, or YouTube/Vimeo link
- **Quality**: 720p minimum, 1080p preferred
- **Audio**: Clear narration explaining the project
- **Content**: Cover all sections below

**Video Structure:**
1. **Introduction** (30 seconds)
   - Team introduction
   - Project name and hackathon
   - Problem statement

2. **Solution Overview** (60 seconds)
   - High-level solution explanation
   - Key features and benefits
   - Conflux integration highlights

3. **Live Demo** (2-3 minutes)
   - User journey walkthrough
   - Key features demonstration
   - Technical highlights

4. **Technical Implementation** (60 seconds)
   - Architecture overview
   - Conflux features used
   - Challenges overcome

5. **Conclusion** (30 seconds)
   - Impact and future plans
   - Call to action

### Participant intro video (required)

All participants must submit a short personal intro video with their submission. This is separate from the demo video and from the winner video (which only winners submit later).

**Video requirements:**
- **Duration:** 30–60 seconds total
- **Language:** Your native language or English
- **Format:** 16:9 landscape
- **Framing:** Front facing, clean audio, not a messy background

**Content:** Say who you are, what you're building for Global Hackfest 2026, and that you're excited to participate. Example: "I'm [Name] from [Country/City], building [Project Name] for Conflux Network's Global Hackfest 2026 and I'm excited to participate."

These videos will be used at a conference in Hong Kong.



### Presentation
- **Demo Quality**: Professional and engaging demonstration
- **Communication**: Clear explanation of project value
- **Storytelling**: Compelling narrative and vision

## 🚨 Common Submission Mistakes

### Avoid These Issues:
- **Late submission** - Submit well before deadline
- **Broken links** - Test all URLs and demo links
- **Missing demo video** - Required for all submissions
- **Missing participant video** - Required for all submissions
- **Incomplete README** - Follow template completely
- **Non-functional code** - Ensure everything works
- **Missing license** - Include open source license
- **Private repository** - Must be publicly accessible
- **Oversized files** - Use external hosting for large assets

### Best Practices:
- **Test everything** - Verify all links and functionality
- **Get feedback** - Have others review your submission
- **Document thoroughly** - Assume judges are unfamiliar with your project
- **Show, don't tell** - Use screenshots and videos effectively
- **Be professional** - Maintain high quality standards

## 📅 Important Deadlines

### Global Hackfest 2026
- **Submission Deadline**: 2026-04-20 @ 11:59:59
- **Late Submissions**: Not accepted
- **Judging Period**: 1 week (starting 2026-04-21; no live presentations)
- **Winners Announced**: 2026-04-27 (winner showcase videos used for the official winners video)

## 🆘 Getting Help

### Before Submission
- **Discord**: https://discord.gg/4A2q3xJKjC - Real-time assistance
- **Office Hours** - Weekly live Q&A sessions
- **GitHub Discussions** - Technical questions

### Technical Issues
- **Repository Problems** - GitHub support or Discord
- **Demo Video Issues** - Video hosting recommendations
- **Build Failures** - Technical support channels
- **Integration Questions** - Conflux developer resources

### Last-Minute Support
- **24 hours before deadline** - Extended Discord support
- **Emergency contact** - Contact through Discord or Telegram
- **Status updates** - Follow updates in our Discord community

## 📞 Contact Information

- **Discord**: https://discord.gg/4A2q3xJKjC
- **Telegram**: https://t.me/ConfluxDevs
- **Documentation**: https://doc.confluxnetwork.org/

## 🎯 Success Tips

1. **Start early** - Don't wait until the last minute
2. **Test thoroughly** - Ensure everything works perfectly
3. **Document well** - Clear documentation helps judges understand your project
4. **Show impact** - Demonstrate real-world value and potential
5. **Be authentic** - Let your passion and innovation shine through
6. **Follow guidelines** - Adherence to requirements shows professionalism
7. **Get feedback** - Have others review your submission before submitting

---

**Ready to submit?** Double-check this list and make your mark on the Conflux ecosystem!

*Good luck, and thank you for participating in Global Hackfest 2026!* 
