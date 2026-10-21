---
theme:
  path: theme.yaml
---

<!-- no_footer -->
<!-- new_lines: 2 -->
<!-- alignment: center -->

# Anyone remember the early days of the public preview of ChatGPT-3?
<!-- pause -->
# Seems like it were only 4 years ago...
<!-- pause -->
<!-- new_lines: 2 -->

<!-- alignment: left -->
# All those crazy ideas we had back then:
<!-- pause -->
<!-- new_lines: 1 -->
Let's fork VS Code and deeply integrate it with AI-assisted coding features
<!-- pause -->
-> <span class="acc">Cursor, sold for $60 billion to SpaceX</span>
<!-- pause -->
<!-- new_lines: 1 -->
Let's build a search engine without indexing but with AI
<!-- pause -->
-> <span class="acc">Perplexity, in talks with Nvidia at a $30B+ valuation</span>
<!-- pause -->
<!-- new_lines: 1 -->
Let's paste all our proprietary knowledge into Chat-GPT
<!-- pause -->
-> <span class="red">Shadow AI is born</span>
<!-- pause -->
-> <span class="red">Samsung bans AI in early 2023</span>
<!-- pause -->
-> <span class="acc">Samsung lifts the ban and launches a full-scale AI Transformation in June 2026</span>
<!-- end_slide -->

<!-- no_footer -->
<!-- new_lines: 2 -->
<!-- alignment: center -->

           ▄▀▀▀▄ ▀█▀    █▀▀▀▄ █▀▀▀▀ █   █ ▀█▀ █   █ █▀▀▀▄           \
           █▄▄▄█  █     █▄▄▄▀ █▄▄▄  █▄▄▄█  █  █▀▄ █ █   █           \
           █   █  █     █   █ █     █   █  █  █  ▀█ █   █           \
           ▀   ▀ ▀▀▀    ▀▀▀▀  ▀▀▀▀▀ ▀   ▀ ▀▀▀ ▀   ▀ ▀▀▀▀            \
                                                                    \
▄▀▀▀▀ █     ▄▀▀▀▄ ▄▀▀▀▀ █▀▀▀▀ █▀▀▀▄    █▀▀▀▄ ▄▀▀▀▄ ▄▀▀▀▄ █▀▀▀▄ ▄▀▀▀▀\
█     █     █   █ ▀▄▄▄  █▄▄▄  █   █    █   █ █   █ █   █ █▄▄▄▀ ▀▄▄▄ \
█     █     █   █     █ █     █   █    █   █ █   █ █   █ █ ▀▄      █\
 ▀▀▀▀ ▀▀▀▀▀  ▀▀▀  ▀▀▀▀  ▀▀▀▀▀ ▀▀▀▀     ▀▀▀▀   ▀▀▀   ▀▀▀  ▀   ▀ ▀▀▀▀ 

<!-- new_lines: 2 -->

<span class="acc">What CxOs told us about AI readiness</span>

<span class="dim">Rafał Król · Head of AWS Technologies, Trek2Summit</span>

<span class="dim">AIBA Conference · Katowice, Ślůnsk · 22 Oct 2026</span>
<!-- end_slide -->

<span class="dim">00 · THE WHO</span>

![image:width:100%](images/microsoft_solutions_partner.png)
<!-- end_slide -->

<span class="dim">00 · THE WHO</span>

![image:width:100%](images/aws_partner.png)
<!-- end_slide -->

<span class="dim">00 · THE WHO</span>

<!-- column_layout: [1, 1] -->
<!-- column: 0 -->
How it started
![image:width:100%](images/flight_attendant.jpeg)
<!-- column: 1 -->
How's it going
![image:width:100%](images/my_active_certs.jpg)
+ 10+ years working with AWS
+ 10+ AWS exams passed
+ AWS Community Builder
+ <span class="acc">DevOpsBoss @ YouTube, Instagram<span>
+ rafalkrol-xyz @ GitHub

<!-- end_slide -->

<span class="dim">01 · THE WHAT</span>
<!-- alignment: center -->

What keeps the C-suite up at night?
<!-- new_lines: 1 -->
<!-- pause -->

<span class="red">1. Indirect Corporate Espionage</span>
<!-- pause -->
<span class="red">2. Shadow AI</span>
<!-- pause -->
<span class="acc">3. Competitive Obsolescence</span>

<!-- end_slide -->

<span class="dim">02 · THE HOW</span>
<!-- alignment: center -->

How we got privy with the CxOs?
<!-- pause -->
<!-- new_lines: 1 -->
<span class="acc">Over a dozen AWS AI Assessments this year</span>

<span class="acc">(aviation · finance · FMCG · telecom · manufacturing)</span>
<!-- end_slide -->

<span class="dim">02 · THE HOW</span>
<!-- alignment: center -->

What's an AWS AI Assessment?
<!-- new_lines: 1 -->
<!-- pause -->

+ Structured engagement, usually done within a calendar month
<!-- pause -->
+ Financed by AWS, for eligible customers
<!-- pause -->
+ Delivered by selected Partners based on their audited competencies and experience
<!-- pause -->

<span class="acc">Where AI makes business sense for us,</span>

<span class="acc">where it doesn't,</span>

<span class="acc">and how to distinguish one from the other?</span>
<!-- end_slide -->

<span class="dim">03 · THE WHY</span>
<!-- alignment: center -->

Why would you even need one? Part 1
<!-- new_lines: 1 -->
<!-- pause -->

Inventory, filtering, and prioritization of AI initiatives
<!-- pause -->

via use case discovery, pattern matching, readiness scorecard, architecture roadmap
<!-- pause -->

<span class="acc">A cure for the AI noise.</span>
<!-- end_slide -->

<span class="dim">03 · THE WHY</span>
<!-- alignment: center -->

Why would you even need one? Part 2
<!-- new_lines: 1 -->
<!-- pause -->

Interest in AI is ubiquitous
<!-- pause -->

<span class="dim">However, according to McKinsey’s State of AI 2026 report,</span>

<span class="red">only 37% of organizations attribute a positive EBIT impact.</span>
<!-- pause -->

<span class="acc">Calculate Return on Investment (ROI)</span>
<!-- end_slide -->

<span class="dim">04 · THE REMEDY</span>
<!-- alignment: center -->
<span class="red">Swap Indirect Corporate Espionage</span> <span class="acc">for Zero Data Retention</span>
<!-- pause -->

1. **Amazon Bedrock**: ZDR by default, and operators have no access (ZOA, enforced in hardware)
2. **Azure Foundry**: flagged prompts can be stored and human-reviewed; opting out needs an Enterprise Agreement and Microsoft's approval
3. **Anthropic API**: ZDR only with a dedicated agreement; otherwise 30 days
4. **Gemini Enterprise Agent Platform**: turn off project-level caching, and without an Enterprise Agreement, also opt out of abuse monitoring

<span class="dim">There are exceptions, e.g. Anthropic's _Covered models_ (**Claude Mythos** and **Claude Fable 5**) which require a 30-day data retention</span>

<!-- end_slide -->

<span class="dim">04 · THE REMEDY</span>
<!-- alignment: center -->
<span class="red">Swap Shadow AI</span> <span class="acc">for Governed AI</span>
<!-- pause -->

1. Amazon Quick + Kiro + Bedrock Guardrails + Claude Code with Bedrock
2. Microsoft Copilot + GitHub Copilot (in VS Code) + Purview DLP (Data Loss Prevention) and Sensitivity Labels + Codex with Azure Foundry

<span class="dim">Avoid consumer and free tiers as these usually train models with your data</span>
<!-- end_slide -->

<span class="dim">04 · THE REMEDY</span>
<!-- alignment: center -->
<span class="red">Swap Competitive Obsolescence</span> <span class="acc">for AI Readiness and Adoption</span>
<!-- pause -->
<span class="dim">The future is now, old man</span>

<span class="dim">The only constant in life is change</span>

<span class="dim">Adapt or perish</span>
<!-- pause -->
<span class="acc">What a time to be alive</span>
<!-- end_slide -->

<!-- column_layout: [2, 2] -->

<!-- column: 0 -->
<span class="acc">Ta muchly!</span>
<!-- new_lines: 2 -->
+ www.trek2summit.com
+ linkedin.com/company/trek2summit
+ linkedin.com/in/rafal-krol
+ kiro.dev
+ github.com/rafalkrol-xyz/ukyo-clicker
+ youtube.com/@DevOpsBoss
+ instagram.com/devopsboss

<!-- column: 1 -->
![image:width:100%](./images/coffee_talk.jpeg)
