---
title: "Hermes Agent."
source: "https://www.aibyaakash.com/p/hermes-agent"
author:
  - "[[Aakash Gupta]]"
published: 2026-05-01
created: 2026-05-06
description: "Here's what you need to know about the hottest new tool in AI - plus, this week's AI news."
tags:
  - "clippings"
---
### Here's what you need to know about the hottest new tool in AI - plus, this week's AI news.

Hermes just crossed 100K GitHub stars in seven weeks. Faster than LangChain, faster than AutoGPT, faster than anything open-source I have tracked.

Everyone is fixating on the growth numbers. The real story is what they are actually using it for.

I’ve been running Hermes for six weeks. Today’s deep dive is your complete guide to what makes it different from every AI tool you already use.

![](https://substackcdn.com/image/fetch/$s_!Uw5W!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fbf71770a-c20a-4ec6-a101-a9a0bc23d48b_1536x1024.png)

*And before that, we’ll have a word from our sponsor and the week’s AI news.*

![](https://substackcdn.com/image/fetch/$s_!Mki6!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fbb766e44-65fe-47da-a080-3f9735c59a82_4000x240.png)

### The Chatbot Tax

*Last year you added Claude or ChatGPT to Slack. Two people use it daily. Everyone else opens it twice a month. The Monday metrics deck still gets built by hand. That’s the chatbot tax.*

*[Viktor](https://ref.getviktor.com/vik-cta-primary1) lives inside Slack and Teams alongside the rest of your team, plugs into 3,000+ tools, and ships actual work. A landscaping owner is running 63 Viktor workflows across collections, payroll, and equipment reports. A $10M DTC brand had Viktor build a Klaviyo audit, a 2026 cash flow model, and a checkout debug report in week one. Every action goes through your team for approval first. 11,000+ teams now trust it.*

![](https://substackcdn.com/image/fetch/$s_!Xw9i!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Feb521122-bb05-40ef-9953-625577366cca_1920x1080.webp)

***Try [Viktor](https://ref.getviktor.com/vik-cta-primary1) free, $100 in starting credits.***

![](https://substackcdn.com/image/fetch/$s_!gIlq!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa0cb985e-2de2-49ed-a14a-b319206aa672_4000x240.png)

*There’s a billion AI news articles every week. Here’s what actually mattered:*

## The Week’s Top News: Claude Just Moved Into Your Creative Tools

[Claude launched connectors](https://www.anthropic.com/news/claude-for-creative-work) for Blender, Autodesk Fusion, Adobe, Ableton, SketchUp, Splice, and more this week.

Most people I know still think of Claude as a writing and coding tool. That changed this week. If you spend your days in design software, 3D tools, or a DAW, Claude is now inside those tools with you. Not in a separate tab. Not something you copy-paste between. Actually inside your workflow, acting on your real files.

[

![X avatar for @claudeai](https://substackcdn.com/image/fetch/$s_!pIkX!,w_40,h_40,c_fill,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fpbs.substack.com%2Fprofile_images%2F1950950107937185792%2FQOfEjFoJ.jpg)

Claude@claudeai

Claude now connects to the tools creative professionals already use. With the new Blender connector, you can debug a scene, build new tools, or batch-apply changes across every object, directly from Claude.

<video controls="" src="https://video.twimg.com/amplify_video/2049136962385375235/vid/avc1/1280x720/K83A7h_7MfAiBeVO.mp4"></video>

11:07 AM · Apr 28, 2026 · 11.6M Views

---

1.52K Replies · 4.29K Reposts · 45.9K Likes

](https://x.com/claudeai/status/2049143438281445811?s=20)

The Autodesk Fusion integration is the one that stopped me. You describe a change to your 3D model in plain language and Claude executes it inside Fusion. That is it. The thing that used to require knowing which menu, which panel, which parameter, now requires knowing what you want. That is a different kind of tool.

The Blender one I keep thinking about for a different reason. Blender has had a full automation layer since 2011. Anyone who has tried to use it knows the problem: you needed someone who could write Python AND knew Blender’s internals well enough to actually do something useful with it. That person is hard to find and expensive to hire. [That barrier is now a chat window.](https://x.com/aakashgupta/status/2049155952583287119?s=20) Rename objects, fix UV maps, batch changes across an entire scene. No code required.

Here’s where I land: Anthropic [announced](https://www.blender.org/news/upcoming-blender-development-fund-and-ai-policies/) patron-level support for the Blender Development Fund alongside the connector launch. €240K/year, dedicated to Blender’s Python API, the layer the connector itself depends on. Then today, after community pushback, Blender reversed course and accepted the funds as a one-time donation instead. Anthropic agreed to it.

Read that sequence carefully. The Blender community is wary of AI companies funding the tools they depend on. Anthropic still wrote the check. The integration is shipping either way. The bet on open-source 3D infrastructure is real even when the donation structure changes shape.

The connector is the thing that matters here, not the funding mechanism. Anyone who works in 3D should try it this week.

**The Other News That Mattered**

- Sundar Pichai [announced](https://www.androidcentral.com/apps-software/gemini-can-now-generate-google-docs-pdf-word) that Gemini now generates and downloads Word docs, Excel sheets, PDFs, and presentations directly from chat, for free, for all 750M Gemini users. Microsoft charges $360/user/year for Copilot to do the same thing. Only 3.3% of Microsoft’s 450M M365 users have paid for Copilot so far. [I wrote about](https://x.com/aakashgupta/status/2049561363010503009?s=20) why this breaks the entire Copilot pricing thesis and why the market has not caught up yet.
- OpenAI and Microsoft [rewrote their deal](https://www.axios.com/2026/04/28/openai-microsoft-cloud-amazon) and the AGI clause is gone. The provision that would have let OpenAI exit its Microsoft obligations the moment it declared AGI has been removed completely. OpenAI still pays Microsoft 20% of revenue through 2030 regardless of any technical milestone. [My read](https://x.com/aakashgupta/status/2048931213059215414?s=20): Microsoft gave up leverage and got certainty on a $135B stake. The quiet winner is Amazon, which can now formally take on the OpenAI workloads Azure exclusivity was blocking.
- Cursor [launched its SDK](https://cursor.com/blog/typescript-sdk) this week. The same agents that power the Cursor app can now run inside your own products, pipelines, and backend systems. Rippling and Notion are [already using it](https://x.com/cursor_ai/status/2049499866217185492?s=20) to catch bugs and open fixes automatically without anyone prompting anything. Cursor crossed $2B ARR. The SDK is how they stop being a product you open and start being infrastructure you run on.
- xAI [launched Grok Imagine Agent Mode (beta)](https://phemex.com/news/article/xais-grok-imagine-agent-beta-tests-short-film-creation-77616) with zero announcement. One prompt, one infinite canvas, and the agent plans, generates, edits, and iterates on its own until it is done. Films, manga sets, product ads. Users just started posting it.

**Resources**

- Two Anthropic engineers [broke down exactly how to prompt Claude for better outputs](https://x.com/aakashgupta/status/2049689446581506283?s=20). If you use Claude every day, this is worth 10 minutes. Most people are still prompting it like a search engine.
- If you use Claude Code and keep running into limits, [read this first](https://x.com/aakashgupta/status/2048497322276065549?s=20). Pawel Huryn mapped the four reasons people hit limits that have nothing to do with Claude, with copy-paste fixes for each. The limits are more generous than people assume. The harness is usually the problem.

**Tools**

- The [Claude Blender connector](https://x.com/aakashgupta/status/2049155952583287119?s=20) deserves its own mention beyond the main news. The thing that makes it worth paying attention to is not what it does. It is what it replaces. The bottleneck in 3D workflows was never Blender’s capability. It was always finding someone who could speak both Python and Blender fluently at the same time. That skill set is gone as a requirement now. Anyone who works in 3D should try this week.

![](https://substackcdn.com/image/fetch/$s_!ic7W!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F45137c5f-5742-4027-857c-58645b245aff_4000x240.png)

## The AI Agent That Doesn't Forget You

Look at that blue line.

![](https://substackcdn.com/image/fetch/$s_!16s5!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Feb7639d5-a0c8-42f3-a805-f9df5f48e5bb_1838x1232.png)

[Hermes](https://github.com/NousResearch/hermes-agent), from Nous Research. Released February 25. 100K GitHub stars in seven weeks. Six weeks of running it later, here is what makes it different from every AI tool you already use.

In January 2026, a security audit found 512 vulnerabilities in OpenClaw, the agent most developers had been running. One of them let an attacker take full control of your machine through a single malicious link (CVE-2026-25253). Developers left. But the ones who switched to Hermes kept telling me the same thing: they did not stay because of the security. They stayed because it was the first agent that kept working after they closed their laptop.

Here is the thing every AI tool you use today has in common. It only works when you are there. You open ChatGPT, ask a question, get an answer. You close it, and it stops. Nothing happens until you come back and ask something again.

Hermes is built around a completely different idea. It runs in the background, executes tasks on a schedule, and gets better at those tasks every time it runs them. You set something up once and it keeps going. Week after week. Without you.

That is the thing no other AI tool does. And it is the thing I want to show you today.

---

**Here’s what you need to know:**

![](https://substackcdn.com/image/fetch/$s_!RHJC!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fc1019bc2-4d0f-4337-97fb-bf5073f6e9a6_2400x2950.png)

1. What makes this possible
2. Setting it up (20 minutes, then it runs forever)
3. Use case 1: A weekly briefing that arrives before you wake up
4. Use case 2: A health coach that actually knows your patterns
5. Use case 3: Generate images from your phone
6. Three honest limitations

---

### 1\. What makes this possible

Two things sit underneath everything Hermes does.

**SOUL.md** is a short file you write once. It is your standing brief to the agent. Who you are, what matters to you, how you like answers delivered. Mine has things like: I have two kids, my wife is vegetarian, I follow F1 and the NBA, keep answers short unless I ask otherwise.

You write it once. It loads automatically before every session, every scheduled task, every message it sends you. Forever. You never explain yourself again.

**The learning loop.** Every time Hermes runs a task, it evaluates what worked and saves an improved version of the procedure. The briefing it sends you in week six is sharper than week one. Not because you changed anything. Because it has been running the same task six times and quietly improving each time.

ChatGPT Tasks can fire a prompt on a schedule. That is where the overlap ends. The procedure never improves between runs. The same query goes out Sunday after Sunday with no memory of what worked last week, no skill stored from the last successful execution. And it lives inside ChatGPT. If you want it to reach you in WhatsApp, Telegram, or Slack, you build that yourself. Hermes is the first consumer agent built around the idea that the value compounds the longer it runs.

---

#### 2\. Setting it up

Hermes runs on Mac, Linux, and Windows (WSL2). One command installs everything:

```markup
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
hermes setup
```

The installer detects your OS, sets up Python if needed, and walks you through the rest. About five minutes.

![](https://substackcdn.com/image/fetch/$s_!5Dbl!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa28e1b09-0bf3-4d22-87ee-2dd7bbb9d16e_1174x714.png)

**Step 1: Pick a model.**

*Free Option A: NVIDIA NIM.* NVIDIA hosts over 100 open-weight AI models in the cloud at [build.nvidia.com/models](https://build.nvidia.com/models). No GPU. No credit card. Create a free developer account, click any model, and click Get API Key.

![](https://substackcdn.com/image/fetch/$s_!vtX4!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F46e13dac-b22e-451b-9b15-b8ac767289d7_3024x1722.png)

```markup
hermes model
# Select: Custom endpoint
# Base URL: https://integrate.api.nvidia.com/v1
# API key: nvapi-xxxxxxxxxxxx
# Model: meta/llama-3.1-70b-instruct
# Context length: 65536
```

*Free Option B: Ollama.* Runs entirely on your laptop. Nothing leaves your machine. One line most people miss — Hermes needs a 64K context window minimum and Ollama defaults to 4K. Skip this and things break silently:

```markup
OLLAMA_CONTEXT_LENGTH=65536 ollama serve
ollama pull llama3.1:8b
hermes model
# Base URL: http://localhost:11434/v1
# API key: ollama
# Model: llama3.1:8b
# Context length: 65536
```

Already paying for Claude, GPT-4o, or Gemini? Run `hermes model` and pick your provider. No new cost.

```markup
hermes model
# Select: Anthropic → uses your ANTHROPIC_API_KEY
# Select: OpenAI   → uses your OPENAI_API_KEY
# Select: Google   → uses your GOOGLE_API_KEY
```

**Step 2: Connect your phone.**

This is the step most people skip. Without it, Hermes only exists when you are sitting at your terminal. With it, it reaches you anywhere.

Hermes works with WhatsApp, Telegram, Slack, and Signal from a single gateway process.

*WhatsApp* needs no developer account.

During `hermes setup`, select WhatsApp. A QR code appears in your terminal window.

Open WhatsApp on your phone. Go to **Settings → Linked Devices → Link a Device**. Point your camera at the QR code. Done. Your agent now lives in your WhatsApp contacts.

```markup
# In ~/.hermes/.env — restrict to your number only:
WHATSAPP_ALLOWED_USERS=+1XXXXXXXXXX
```

*I link my personal WhatsApp number directly. Once paired, the agent shows up under Linked Devices exactly like WhatsApp Web.*

*Telegram* is faster if you just want to try it first. Open Telegram, search for @BotFather, type `/newbot`, follow the prompts, copy the token.

```markup
# In ~/.hermes/.env:
TELEGRAM_BOT_TOKEN=your-bot-token
TELEGRAM_ALLOWED_USERS=your-telegram-user-id
```

Send `/start` to your bot. Five minutes total.

**Step 3: Start the gateway.**

```markup
hermes gateway
```

This keeps Hermes connected to your phone. Right now it only runs while your terminal is open. To make it run permanently, surviving reboots:

```markup
hermes gateway install
```

This is the line that makes the Sunday 7am briefing actually land at 7am. Without it, your agent stops the moment you restart your computer.

**Step 4: Back up before you touch anything.**

```markup
hermes backup --quick
```

**Migrating from OpenClaw?**

```markup
hermes claw migrate
```

Hermes detects your OpenClaw installation automatically. Everything transfers except API keys, which it skips deliberately for security.

![](https://substackcdn.com/image/fetch/$s_!Wg_3!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F1651ac98-536f-4602-b8b5-d389f36558e8_1062x496.png)

---

#### 3\. Use case 1: A weekly briefing that arrives before you wake up

Every Sunday morning, before my family is up, my WhatsApp gets a message. I did not send it. I did not schedule it manually each week. I set it up once and it has arrived every Sunday since.

This is what it looks like:

![](https://substackcdn.com/image/fetch/$s_!eAWE!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F9e437bad-b2d5-4b17-b308-f132fdfd7bac_814x666.png)

I set this up in one message to Hermes:

*“Every Sunday at 7am, check the school calendar, the week’s weather, F1 and NBA schedules, and flight prices to Miami. Send me a summary on WhatsApp.”*

![](https://substackcdn.com/image/fetch/$s_!CeE8!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F01655c38-89a9-4a52-a978-87fde0784ea6_1432x942.png)

That was the entire setup. It has been running every Sunday since. I have not touched it.

ChatGPT Tasks can deliver a Sunday briefing. What it cannot do is get sharper at it. Run a ChatGPT Task for eight weeks and week eight is the same as week one. The prompt is fixed. The procedure does not improve. There is no record of which sections you read first or which ones you skipped. Hermes watches all of that and adjusts.

And here is what changes over time. In week one the briefing was basic. By week eight it had learned I care about flight prices specifically in the second week of each month, that I want sports results only for teams I mentioned, and that I like the weather section first because I am getting dressed when I read it. It figured all of that out from watching how I responded each week.

Week one: useful. Week eight: it feels like something that knows your life.

---

#### 4\. Use case 2: A health coach that actually knows your patterns

Everyone has tried a fitness app. You log your workout for four days, miss one, the streak breaks, and you never open the app again. The apps track. They do not think.

I started messaging Hermes my health data the same way I would text a friend. After a run: *“30 min run, felt good.”* After a bad night: *“Slept 5 hours, woke up twice.”* After skipping the gym: *“Missed today, long day at work.”*

After five weeks of this, on a Sunday evening, my WhatsApp buzzed with something I did not ask for:

![](https://substackcdn.com/image/fetch/$s_!b5Hp!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F77774990-67db-4bc1-8355-9b64be54ee2c_776x680.png)

I did not ask it to find that pattern. I did not ask it to message me proactively. It had been watching 34 log entries across five weeks, connected the skip days to the meeting days, and surfaced it before the day even arrived.

That is the thing no app does. Apps record. Hermes watches.

By week six, it had learned that I sleep better when I stop eating before 8pm, that my workouts are longer on days I have had at least seven hours of sleep, and that I almost always skip Friday exercise if I skipped Wednesday too. It sent me a nudge on Wednesday: *“You skipped Monday. Based on your pattern, skipping today makes Friday very unlikely too.”*

A health app shows you your data. Hermes tells you what your data means before you need to ask.

This is the use case where compounding is most visible. Month three is genuinely more useful than month one because it knows you better. It has more data, more patterns, more history to work from. A price alert fires once. A health tracker that has been watching you for twelve weeks never stops getting sharper.

---

#### 5\. Use case 3: Generate images/videos from your phone

Nous shipped a ComfyUI skill last week. ComfyUI is the most powerful open-source media generation tool out there, but using it normally means sitting at a computer wiring nodes together every time you want an image.

One install:

```markup
hermes install comfyui
```

Now you message Hermes the image you want from WhatsApp. It builds the workflow, runs it on your laptop, sends the result back. No app to open. No nodes to wire. No data leaving your machine.

The difference from ChatGPT image generation: it runs on your own hardware. Every image is free and private after the local setup. The difference from running ComfyUI directly: you do not have to be at the computer.

[

![X avatar for @NousResearch](https://substackcdn.com/image/fetch/$s_!Vsyl!,w_40,h_40,c_fill,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fpbs.substack.com%2Fprofile_images%2F1816254738234761216%2FTX7TW-Mp.jpg)

Nous Research@NousResearch

ComfyUI is the most flexible, composable, and powerful open-source media generation tool with a massive ecosystem of workflows and custom nodes. Your Hermes Agent can now install, launch, manage, and run sophisticated @ComfyUI workflows on demand.

<video controls="" src="https://video.twimg.com/amplify_video/2049583882396172289/vid/avc1/720x720/2zCc8JeRwbp-6FFL.mp4"></video>

4:20 PM · Apr 29, 2026 · 274K Views

---

184 Replies · 269 Reposts · 3.05K Likes

](https://x.com/NousResearch/status/2049584595465572752?s=20)

---

#### 6\. Three honest limitations

*Your machine has to be on.* Scheduled tasks need your laptop running when they fire. If it is closed at 7am Sunday, the briefing waits until you open it. macOS has a setting called Wake for Network Access that wakes the machine automatically before a scheduled job. Worth enabling. The other option is running Hermes on a $5 VPS, which is the path I would recommend if you want any of this to actually work without you babysitting it.

*The learning loop can learn the wrong thing.* It pattern-matches on what you respond to. If you accidentally reply enthusiastically to one bad briefing, it doubles down. There is no “unlearn” command. You either edit the underlying skill file directly or wipe the memory and start over.

*Privacy depends on your model choice.* The Sunday briefing knows my kids’ school schedule. The health coach has 34 entries of my sleep and workouts. If you point Hermes at GPT-4o or Claude, that data is going to OpenAI or Anthropic on every run. Run Ollama locally if that bothers you. You give up some quality, you get full privacy.

---

*That’s it for today’s deep dive.*

*I wrote the [full version for PMs](https://www.news.aakashg.com/p/hermes-agent-guide) with three product-specific workflows and a starter kit you can drop in and run today. it’s at [news.aakashg.com.](https://www.news.aakashg.com/p/hermes-agent-guide)*

![](https://substackcdn.com/image/fetch/$s_!mBvP!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd31bd22f-efa6-4397-8c57-4f519443941d_3372x218.png)

I am co-hosting the [AI Skills Virtual Conf](https://conf.cosprints.ai/?32) on May 14, free, on Zoom.

![](https://substackcdn.com/image/fetch/$s_!ivYu!,w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F77ff1c16-cd62-425c-a9e5-15e2f93609ee_1600x1561.jpeg)

30 speakers from Meta, Google, AWS, Scale AI, Bolt, DeepMind, and more. The whole thing is built around practical use cases, not theory. What actually works in 2026, how companies are deciding which AI tools to adopt, and what the real AI stack looks like for founders and small teams.

I am giving a session on how to use Claude specifically for job search: positioning, applications, interview prep, the whole thing.

If any of that sounds useful, [register for free here](https://conf.cosprints.ai/?32). May 14, 8 AM SF / 11 AM NYC / 4 PM London.

---

POLL

### What did you think of today's post?

Awesome - 5/5

Okay - 3/5

Bad - 1/5

---

*That’s all for today. See you next week,*

Aakash

*P.S. Want my AI tool stack? [Join my bundle](https://bundle.aakashg.com/). Want my job search coaching? [Apply to my cohort](https://www.landpmjob.com/).*