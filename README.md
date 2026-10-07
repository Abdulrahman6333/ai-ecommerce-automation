# AI E-commerce Automation & Product Intelligence

A portfolio collection of n8n workflows for AI-assisted e-commerce research, product evaluation, affiliate content planning, and automated short-form video production.

## Case Study 1 — Noon Affiliate Marketing & Video Automation
A Telegram-driven workflow focused on Beauty & Cosmetics affiliate content for Noon Saudi Arabia.

### Flow
`Telegram → Coupon → Product Research → Validation → Product Selection → Real Product Images → AI Creative Strategy → TTS → FFmpeg Video → Telegram Delivery`

### Highlights
- Telegram-based user interaction
- AI-agent orchestration with structured output
- Noon Saudi product research and URL validation
- Evidence-aware product filtering
- Session image handling
- 4-scene vertical TikTok planning
- Arabic TTS voiceover generation
- FFmpeg-based video assembly
- Automated delivery of the final video

## Case Study 2 — Lunara Product Intelligence
Two complementary workflows for evaluating e-commerce opportunities in Saudi Arabia.

### Product Hunter
- Calculates gross profit and margin
- Uses AI analysis for market fit and creative potential
- Applies weighted product scoring
- Ranks and returns top opportunities

### Saudi Market Research
- Uses live web research through OpenRouter
- Separates market presence from actual demand evidence
- Classifies Saudi / GCC / Global evidence
- Validates source and price evidence
- Calculates an evidence-aware Saudi market score
- Ranks the strongest researched opportunities

## Tech stack
- n8n
- OpenRouter
- AI Agents / LLM workflows
- JavaScript Code nodes
- REST APIs
- Telegram
- Live Web Research
- Structured JSON
- FFmpeg
- TTS

## Security
The public workflow files are sanitized. Credential blocks, webhook IDs, instance identifiers, and environment-specific references have been removed or replaced. Reconnect your own credentials and resources after importing.
