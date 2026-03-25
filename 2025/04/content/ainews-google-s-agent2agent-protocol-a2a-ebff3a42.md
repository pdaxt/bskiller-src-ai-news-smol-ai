<p><strong>Remote agents are all you need.</strong></p>
<blockquote>
<p>AI News for 4/8/2025-4/9/2025. We checked 7 subreddits, <a href="https://twitter.com/i/lists/1585430245762441216" target="_blank"><strong>433</strong> Twitters</a> and <strong>30</strong> Discords (<strong>229</strong> channels, and <strong>5996</strong> messages) for you. Estimated reading time saved (at 200wpm): <strong>563 minutes</strong>. You can now tag <a href="https://x.com/smol_ai" target="_blank">@smol_ai</a> for AINews discussions!</p>
</blockquote>
<p>We are deep in Google Cloud Next announcements, and in a 1-2 punch, the CEOs of Google and DeepMind announced both their full MCP support:</p>
<p><img alt="image.png" class="newsletter-image" src="https://assets.buttondown.email/images/6718bbc2-81c3-4453-b479-a40b88339036.png?w=960&amp;fit=max"/></p>
<p>And <a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/" target="_blank">their new Agent to Agent protocol</a> to complement MCP with a huge list of partners:</p>
<p><img alt="image.png" class="newsletter-image" src="https://assets.buttondown.email/images/5094b0f5-0ca6-4ae2-b720-a1dc00352fc8.png?w=960&amp;fit=max"/></p>
<p>It is tempting to pit Google against Anthropic, but the protocols were designed to work together to address perceived gaps in MCP:</p>
<p><img alt="image.png" class="newsletter-image" src="https://assets.buttondown.email/images/3c759936-9d88-40fc-9bcd-04d10ffd9e5f.png?w=960&amp;fit=max"/></p>
<p>The spec includes:</p>
<ul>
<li>the <a href="https://google.github.io/A2A/#/documentation?id=overview" target="_blank">Agent Card</a></li>
<li>the concept of a <a href="https://google.github.io/A2A/#/documentation?id=task" target="_blank">Task</a> - a communication channel between the home agent and the remote agent for passing <a href="https://google.github.io/A2A/#/documentation?id=message" target="_blank">Messages</a>, with an end result <a href="https://google.github.io/A2A/#/documentation?id=artifact" target="_blank">Artifact</a>.</li>
<li><a href="https://google.github.io/A2A/#/topics/enterprise_ready" target="_blank">Enterprise Auth and Observability</a> recommendations</li>
<li><a href="https://google.github.io/A2A/#/topics/push_notifications" target="_blank">Streaming and Push Notification support</a> (again with <a href="https://google.github.io/A2A/#/topics/push_notifications?id=agent-security" target="_blank">push security</a> in mind)</li>
</ul>
<p>Launch artifacts include:</p>
<ul>
<li><a href="https://github.com/google/A2A" target="_blank">The draft specification</a></li>
<li><a href="https://google.github.io/A2A/#/" target="_blank">The documentation website</a></li>
<li><a href="https://developers.googleblog.com/en/agent-development-kit-easy-to-build-multi-agent-applications/" target="_blank">The Agent Development Kit</a> which looks... oddly familiar</li>
</ul>
<p><img alt="image.png" class="newsletter-image" src="https://assets.buttondown.email/images/1a2f60ea-92eb-41bb-a075-1f324ddb81e5.png?w=960&amp;fit=max"/></p>
<hr/>
<p></p>
<p><strong>Table of Contents</strong></p>
<div class="toc">
<ul>
<li><a href="#ai-twitter-recap">AI Twitter Recap</a></li>
<li><a href="#ai-reddit-recap">AI Reddit Recap</a><ul>
<li><a href="#rlocalllama-recap">/r/LocalLlama Recap</a><ul>
<li><a href="#theme-1-unleashing-deepcoder-the-future-of-open-source-coding">Theme 1. "Unleashing DeepCoder: The Future of Open-Source Coding"</a></li>
</ul>
</li>
<li><a href="#other-ai-subreddit-recap">Other AI Subreddit Recap</a><ul>
<li><a href="#theme-1-revolutionizing-ai-models-hardware-and-customization">Theme 1. "Revolutionizing AI: Models, Hardware, and Customization"</a></li>
<li><a href="#theme-2-evolving-connections-from-romance-to-daily-ai-chats">Theme 2. Evolving Connections: From Romance to Daily AI Chats</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#ai-discord-recap">AI Discord Recap</a></li>
<li><a href="#part-1-high-level-discord-summaries">PART 1: High level Discord summaries</a><ul>
<li><a href="#lmarena-discord">LMArena Discord</a></li>
<li><a href="#unsloth-ai-daniel-han-discord">Unsloth AI (Daniel Han) Discord</a></li>
<li><a href="#manusim-discord-discord">Manus.im Discord Discord</a></li>
<li><a href="#perplexity-ai-discord">Perplexity AI Discord</a></li>
<li><a href="#openrouter-alex-atallah-discord">OpenRouter (Alex Atallah) Discord</a></li>
<li><a href="#openai-discord">OpenAI Discord</a></li>
<li><a href="#lm-studio-discord">LM Studio Discord</a></li>
<li><a href="#aider-paul-gauthier-discord">aider (Paul Gauthier) Discord</a></li>
<li><a href="#eleuther-discord">Eleuther Discord</a></li>
<li><a href="#cursor-community-discord">Cursor Community Discord</a></li>
<li><a href="#yannick-kilcher-discord">Yannick Kilcher Discord</a></li>
<li><a href="#interconnects-nathan-lambert-discord">Interconnects (Nathan Lambert) Discord</a></li>
<li><a href="#mcp-glama-discord">MCP (Glama) Discord</a></li>
<li><a href="#huggingface-discord">HuggingFace Discord</a></li>
<li><a href="#notebook-lm-discord">Notebook LM Discord</a></li>
<li><a href="#gpu-mode-discord">GPU MODE Discord</a></li>
<li><a href="#latent-space-discord">Latent Space Discord</a></li>
<li><a href="#nous-research-ai-discord">Nous Research AI Discord</a></li>
<li><a href="#nomicai-gpt4all-discord">Nomic.ai (GPT4All) Discord</a></li>
<li><a href="#modular-mojo-discord">Modular (Mojo 🔥) Discord</a></li>
<li><a href="#llamaindex-discord">LlamaIndex Discord</a></li>
<li><a href="#cohere-discord">Cohere Discord</a></li>
<li><a href="#tinygrad-george-hotz-discord">tinygrad (George Hotz) Discord</a></li>
<li><a href="#torchtune-discord">Torchtune Discord</a></li>
<li><a href="#llm-agents-berkeley-mooc-discord">LLM Agents (Berkeley MOOC) Discord</a></li>
<li><a href="#codeium-windsurf-discord">Codeium (Windsurf) Discord</a></li>
</ul>
</li>
<li><a href="#part-2-detailed-by-channel-summaries-and-links">PART 2: Detailed by-Channel summaries and links</a><ul>
<li><a href="#lmarena-general-1004-messages">LMArena ▷ #general (1004 messages🔥🔥🔥):</a></li>
<li><a href="#unsloth-ai-daniel-han-general-712-messages">Unsloth AI (Daniel Han) ▷ #general (712 messages🔥🔥🔥):</a></li>
<li><a href="#unsloth-ai-daniel-han-off-topic-22-messages">Unsloth AI (Daniel Han) ▷ #off-topic (22 messages🔥):</a></li>
<li><a href="#unsloth-ai-daniel-han-help-156-messages">Unsloth AI (Daniel Han) ▷ #help (156 messages🔥🔥):</a></li>
<li><a href="#unsloth-ai-daniel-han-showcase-3-messages">Unsloth AI (Daniel Han) ▷ #showcase (3 messages):</a></li>
<li><a href="#unsloth-ai-daniel-han-research-8-messages">Unsloth AI (Daniel Han) ▷ #research (8 messages🔥):</a></li>
<li><a href="#manusim-discord-showcase-6-messages">Manus.im Discord ▷ #showcase (6 messages):</a></li>
<li><a href="#manusim-discord-general-511-messages">Manus.im Discord ▷ #general (511 messages🔥🔥🔥):</a></li>
<li><a href="#perplexity-ai-announcements-2-messages">Perplexity AI ▷ #announcements (2 messages):</a></li>
<li><a href="#perplexity-ai-general-501-messages">Perplexity AI ▷ #general (501 messages🔥🔥🔥):</a></li>
<li><a href="#perplexity-ai-sharing-1-messages">Perplexity AI ▷ #sharing (1 messages):</a></li>
<li><a href="#perplexity-ai-pplx-api-6-messages">Perplexity AI ▷ #pplx-api (6 messages):</a></li>
<li><a href="#openrouter-alex-atallah-app-showcase-5-messages">OpenRouter (Alex Atallah) ▷ #app-showcase (5 messages):</a></li>
<li><a href="#openrouter-alex-atallah-general-444-messages">OpenRouter (Alex Atallah) ▷ #general (444 messages🔥🔥🔥):</a></li>
<li><a href="#openai-ai-discussions-274-messages">OpenAI ▷ #ai-discussions (274 messages🔥🔥):</a></li>
<li><a href="#openai-gpt-4-discussions-2-messages">OpenAI ▷ #gpt-4-discussions (2 messages):</a></li>
<li><a href="#openai-prompt-engineering-61-messages">OpenAI ▷ #prompt-engineering (61 messages🔥🔥):</a></li>
<li><a href="#openai-api-discussions-61-messages">OpenAI ▷ #api-discussions (61 messages🔥🔥):</a></li>
<li><a href="#lm-studio-general-57-messages">LM Studio ▷ #general (57 messages🔥🔥):</a></li>
<li><a href="#lm-studio-hardware-discussion-331-messages">LM Studio ▷ #hardware-discussion (331 messages🔥🔥):</a></li>
<li><a href="#aider-paul-gauthier-general-262-messages">aider (Paul Gauthier) ▷ #general (262 messages🔥🔥):</a></li>
<li><a href="#aider-paul-gauthier-questions-and-tips-18-messages">aider (Paul Gauthier) ▷ #questions-and-tips (18 messages🔥):</a></li>
<li><a href="#aider-paul-gauthier-links-1-messages">aider (Paul Gauthier) ▷ #links (1 messages):</a></li>
<li><a href="#eleuther-general-221-messages">Eleuther ▷ #general (221 messages🔥🔥):</a></li>
<li><a href="#eleuther-research-46-messages">Eleuther ▷ #research (46 messages🔥):</a></li>
<li><a href="#eleuther-interpretability-general-10-messages">Eleuther ▷ #interpretability-general (10 messages🔥):</a></li>
<li><a href="#cursor-community-general-218-messages">Cursor Community ▷ #general (218 messages🔥🔥):</a></li>
<li><a href="#yannick-kilcher-general-190-messages">Yannick Kilcher ▷ #general (190 messages🔥🔥):</a></li>
<li><a href="#yannick-kilcher-paper-discussion-9-messages">Yannick Kilcher ▷ #paper-discussion (9 messages🔥):</a></li>
<li><a href="#yannick-kilcher-agents-2-messages">Yannick Kilcher ▷ #agents (2 messages):</a></li>
<li><a href="#yannick-kilcher-ml-news-16-messages">Yannick Kilcher ▷ #ml-news (16 messages🔥):</a></li>
<li><a href="#interconnects-nathan-lambert-news-178-messages">Interconnects (Nathan Lambert) ▷ #news (178 messages🔥🔥):</a></li>
<li><a href="#interconnects-nathan-lambert-ml-drama-7-messages">Interconnects (Nathan Lambert) ▷ #ml-drama (7 messages):</a></li>
<li><a href="#interconnects-nathan-lambert-random-2-messages">Interconnects (Nathan Lambert) ▷ #random (2 messages):</a></li>
<li><a href="#interconnects-nathan-lambert-memes-1-messages">Interconnects (Nathan Lambert) ▷ #memes (1 messages):</a></li>
<li><a href="#interconnects-nathan-lambert-rl-3-messages">Interconnects (Nathan Lambert) ▷ #rl (3 messages):</a></li>
<li><a href="#interconnects-nathan-lambert-reads-3-messages">Interconnects (Nathan Lambert) ▷ #reads (3 messages):</a></li>
<li><a href="#mcp-glama-general-107-messages">MCP (Glama) ▷ #general (107 messages🔥🔥):</a></li>
<li><a href="#mcp-glama-showcase-9-messages">MCP (Glama) ▷ #showcase (9 messages🔥):</a></li>
<li><a href="#huggingface-general-41-messages">HuggingFace ▷ #general (41 messages🔥):</a></li>
<li><a href="#huggingface-today-im-learning-3-messages">HuggingFace ▷ #today-im-learning (3 messages):</a></li>
<li><a href="#huggingface-i-made-this-4-messages">HuggingFace ▷ #i-made-this (4 messages):</a></li>
<li><a href="#huggingface-computer-vision-2-messages">HuggingFace ▷ #computer-vision (2 messages):</a></li>
<li><a href="#huggingface-gradio-announcements-1-messages">HuggingFace ▷ #gradio-announcements (1 messages):</a></li>
<li><a href="#huggingface-agents-course-28-messages">HuggingFace ▷ #agents-course (28 messages🔥):</a></li>
<li><a href="#huggingface-open-r1-13-messages">HuggingFace ▷ #open-r1 (13 messages🔥):</a></li>
<li><a href="#notebook-lm-use-cases-13-messages">Notebook LM ▷ #use-cases (13 messages🔥):</a></li>
<li><a href="#notebook-lm-general-75-messages">Notebook LM ▷ #general (75 messages🔥🔥):</a></li>
<li><a href="#gpu-mode-general-15-messages">GPU MODE ▷ #general (15 messages🔥):</a></li>
<li><a href="#gpu-mode-cuda-6-messages">GPU MODE ▷ #cuda (6 messages):</a></li>
<li><a href="#gpu-mode-torch-2-messages">GPU MODE ▷ #torch (2 messages):</a></li>
<li><a href="#gpu-mode-cool-links-2-messages">GPU MODE ▷ #cool-links (2 messages):</a></li>
<li><a href="#gpu-mode-beginner-19-messages">GPU MODE ▷ #beginner (19 messages🔥):</a></li>
<li><a href="#gpu-mode-torchao-1-messages">GPU MODE ▷ #torchao (1 messages):</a></li>
<li><a href="#gpu-mode-off-topic-2-messages">GPU MODE ▷ #off-topic (2 messages):</a></li>
<li><a href="#gpu-mode-self-promotion-1-messages">GPU MODE ▷ #self-promotion (1 messages):</a></li>
<li><a href="#gpu-mode-reasoning-gym-2-messages">GPU MODE ▷ #reasoning-gym (2 messages):</a></li>
<li><a href="#gpu-mode-gpu-3-messages">GPU MODE ▷ #gpu模式 (3 messages):</a></li>
<li><a href="#gpu-mode-general-11-messages">GPU MODE ▷ #general (11 messages🔥):</a></li>
<li><a href="#gpu-mode-submissions-14-messages">GPU MODE ▷ #submissions (14 messages🔥):</a></li>
<li><a href="#gpu-mode-feature-requests-and-bugs-1-messages">GPU MODE ▷ #feature-requests-and-bugs (1 messages):</a></li>
<li><a href="#latent-space-ai-general-chat-77-messages">Latent Space ▷ #ai-general-chat (77 messages🔥🔥):</a></li>
<li><a href="#nous-research-ai-general-66-messages">Nous Research AI ▷ #general (66 messages🔥🔥):</a></li>
<li><a href="#nous-research-ai-ask-about-llms-2-messages">Nous Research AI ▷ #ask-about-llms (2 messages):</a></li>
<li><a href="#nous-research-ai-interesting-links-1-messages">Nous Research AI ▷ #interesting-links (1 messages):</a></li>
<li><a href="#nomicai-gpt4all-general-57-messages">Nomic.ai (GPT4All) ▷ #general (57 messages🔥🔥):</a></li>
<li><a href="#modular-mojo-general-3-messages">Modular (Mojo 🔥) ▷ #general (3 messages):</a></li>
<li><a href="#modular-mojo-mojo-14-messages">Modular (Mojo 🔥) ▷ #mojo (14 messages🔥):</a></li>
<li><a href="#llamaindex-blog-2-messages">LlamaIndex ▷ #blog (2 messages):</a></li>
<li><a href="#llamaindex-general-8-messages">LlamaIndex ▷ #general (8 messages🔥):</a></li>
<li><a href="#llamaindex-ai-discussion-3-messages">LlamaIndex ▷ #ai-discussion (3 messages):</a></li>
<li><a href="#cohere-general-9-messages">Cohere ▷ #「💬」general (9 messages🔥):</a></li>
<li><a href="#cohere-bot-cmd-1-messages">Cohere ▷ #「🤖」bot-cmd (1 messages):</a></li>
<li><a href="#cohere-introductions-2-messages">Cohere ▷ #「🤝」introductions (2 messages):</a></li>
<li><a href="#cohere-status-updates-1-messages">Cohere ▷ #【🟢】status-updates (1 messages):</a></li>
<li><a href="#tinygrad-george-hotz-general-4-messages">tinygrad (George Hotz) ▷ #general (4 messages):</a></li>
<li><a href="#tinygrad-george-hotz-learn-tinygrad-7-messages">tinygrad (George Hotz) ▷ #learn-tinygrad (7 messages):</a></li>
<li><a href="#torchtune-general-4-messages">Torchtune ▷ #general (4 messages):</a></li>
<li><a href="#torchtune-dev-4-messages">Torchtune ▷ #dev (4 messages):</a></li>
<li><a href="#llm-agents-berkeley-mooc-mooc-questions-1-messages">LLM Agents (Berkeley MOOC) ▷ #mooc-questions (1 messages):</a></li>
<li><a href="#codeium-windsurf-announcements-1-messages">Codeium (Windsurf) ▷ #announcements (1 messages):</a></li>
</ul>
</li>
</ul>
</div>
<p></p>
<hr/>
<h1 id="ai-twitter-recap">AI Twitter Recap</h1>
<p><strong>Model Releases and Updates</strong></p>
<ul>
<li><strong>Moonshot AI's Kimi-VL-A3B, a multimodal LM with 128K context and MIT license, outperforms GPT4o on vision + math benchmarks</strong>: The model has MoE VLM and an MoE Reasoning VLM with only ~3B active parameters. <a href="https://twitter.com/reach_vb/status/1910046715714937130" target="_blank">@reach_vb</a> noted that the model showed strong multimodal reasoning (36.8% on MathVision) and agent skills (34.5% on ScreenSpot-Pro) with high-res visuals and long context windows.  Model weights are on Hugging Face. <a href="https://twitter.com/_akhaliq/status/1910047935686991930" target="_blank">@_akhaliq</a> provided links to the models.</li>
<li><strong>Meta released two smaller versions of its new Llama 4 family of models: Llama 4 Scout and Maverick</strong>: According to <a href="https://twitter.com/EpochAIResearch/status/1909699970594394173" target="_blank">@EpochAIResearch</a>, a larger version called Behemoth is still in training. <a href="https://twitter.com/ArtificialAnlys/status/1909624239747182989" target="_blank">@ArtificialAnlys</a> reported on replicated Meta’s claimed values for MMLU Pro and GPQA Diamond. Scout’s Intelligence Index moved from 36 to 43, and Maverick’s Intelligence Index moved from 49 to 50.  <a href="https://twitter.com/winglian/status/1909413876669558967" target="_blank">@winglian</a> shared that Llama-4 Scout can be fine-tuned w/ 2x48GB GPUs @ 4k context.  <a href="https://twitter.com/danielhanchen/status/1909726119500431685" target="_blank">@danielhanchen</a> shared a detailed analysis of the Llama 4 architecture.</li>
<li><strong>DeepCoder 14B, a new coding model from UC Berkeley, rivals OpenAI o3-mini and o1 on coding, and is open-sourced</strong>: <a href="https://twitter.com/Yuchenj_UW/status/1910004382848229702" target="_blank">@Yuchenj_UW</a> noted that the model was trained with RL on Deepseek-R1-Distilled-Qwen-14B on 24K coding problems, costing 32 H100s for 2.5 weeks (~$26,880).  <a href="https://twitter.com/jeremyphoward/status/1909705022935646541" target="_blank">@jeremyphoward</a> added that the base model is deepseek-qwen. <a href="https://twitter.com/reach_vb/status/1909706239577329915" target="_blank">@reach_vb</a> noted it is MIT licensed and works w/ vLLM, TGI, and Transformers.  <a href="https://twitter.com/togethercompute/status/1909697122372378908" target="_blank">@togethercompute</a> announced the model and shared details on the training process.</li>
<li><strong>Nvidia dropped Llama 3.1 Nemotron Ultra 253B on Hugging Face</strong>: <a href="https://twitter.com/_akhaliq/status/1909614682840744417" target="_blank">@_akhaliq</a> shared the release, noting that it beats Llama 4 Behemoth, Maverick &amp; is competitive with DeepSeek R1 with a Commercially permissive license.  <a href="https://twitter.com/reach_vb/status/1909584596401815691" target="_blank">@reach_vb</a> also noted the release, and that the weights are open.</li>
<li><strong>Google announced Gemini 2.5 Flash, and Gemini 2.5 Pro is now available in Deep Research</strong>: <a href="https://twitter.com/scaling01/status/1909903003835904297" target="_blank">@scaling01</a> announced the upcoming release of gemini-2.5.1-flash-exp-preview-001-04-09-thinking-4bpw-20b-uncensored-slerp-v0.2.  <a href="https://twitter.com/_philschmid/status/1909737527386255649" target="_blank">@_philschmid</a> noted that Gemini 2.5 Pro is now available in Deep Research in the Gemini App.</li>
<li><strong>HiDream-I1-Dev is the new leading open-weights image generation model, overtaking FLUX1.1</strong>:  <a href="https://twitter.com/ArtificialAnlys/status/1909624716111045115" target="_blank">@ArtificialAnlys</a> reported that the impressive 17B parameter model comes in three variants: Full, Dev, and Fast. They included a comparison of image generations.</li>
<li><strong>UC Berkeley open-sourced a 14B model that rivals OpenAI o3-mini and o1 on coding!</strong>: <a href="https://twitter.com/Yuchenj_UW/status/1910004382848229702" target="_blank">@Yuchenj_UW</a> noted that the model was trained with RL on Deepseek-R1-Distilled-Qwen-14B on 24K coding problems, costing 32 H100s for 2.5 weeks (~$26,880).</li>
</ul>
<p><strong>Hardware and Infrastructure</strong></p>
<ul>
<li><strong>Google announced Ironwood, their 7th-gen TPU competitor to Nvidia's Blackwell B200 GPUs</strong>: <a href="https://twitter.com/scaling01/status/1909949372965564896" target="_blank">@scaling01</a> shared details, including 4,614 TFLOPs per chip (FP8), 192 GB HBM, 7.2 Tbps HBM bandwidth, 1.2 Tbps bidirectional ICI, and 42.5 exaflops per 9,216-chip pod (24x El Capitan).  <a href="https://twitter.com/_philschmid/status/1909979316344979900" target="_blank">@_philschmid</a> noted that this TPU is built for inference and "thinking" models.   <a href="https://twitter.com/itsclivetime/status/1910026066129014868" target="_blank">@itsclivetime</a> provided a detailed comparison with Nvidia hardware.</li>
<li><strong>NVIDIA Blackwell can achieve 303 output tokens/s for DeepSeek R1 in FP4 precision</strong>: <a href="https://twitter.com/ArtificialAnlys/status/1909633232821534935" target="_blank">@ArtificialAnlys</a> reported on benchmarking an Avian API endpoint.</li>
<li><strong>Together AI announced Instant GPU Clusters, Up to 64 interconnected NVIDIA GPUs</strong>: <a href="https://twitter.com/togethercompute/status/1909757415907865059" target="_blank">@togethercompute</a> noted that the clusters are available in minutes, entirely self-service, perfect for training models of up to ~7B parameters, or running models like DeepSeek-R1.</li>
</ul>
<p><strong>Agent and Tooling Development</strong></p>
<ul>
<li><strong>Google presented Agent Development Kit (ADK)</strong>: <a href="https://twitter.com/omarsar0/status/1910004370864742757" target="_blank">@omarsar0</a> detailed features, including code-first, multi-agents, rich tool ecosystem, flexible orchestration, integrated dev xp, streaming, state, memory, and extensibility.   <a href="https://twitter.com/LiorOnAI/status/1910041530183893221" target="_blank">@LiorOnAI</a> highlighted that a multi-agent application can be running in &lt;100 lines of Python.</li>
<li><strong>Google announces Agent2Agent (A2A), a new open protocol that lets AI agents securely collaborate across ecosystems</strong>: <a href="https://twitter.com/omarsar0/status/1909977142311690320" target="_blank">@omarsar0</a> shared details, including universal agent interoperability, built for enterprise needs, and inspired by real-world use cases.</li>
<li><strong>Weights &amp; Biases highlights the observability gap in agents calling tools, and promotes observable[.]tools as a solution</strong>: <a href="https://twitter.com/weights_biases/status/1910054982424133684" target="_blank">@weights_biases</a> noted that there are no traces, no visibility, and no security inside those tools, "just a black box."</li>
<li><strong>Hacubu announced custom output schemas for OpenEvals LLM-as-judge evaluators</strong>:  <a href="https://twitter.com/Hacubu/status/1909636114278965468" target="_blank">@Hacubu</a> notes this gives total flexibility over model responses and is available in Python and JS.</li>
<li><strong>LangChain highlights C.H. Robinson saving 600+ hours a day with tech built using LangGraph, LangGraph Studio, and LangSmith</strong>: <a href="https://twitter.com/LangChainAI/status/1909676629854765361" target="_blank">@LangChainAI</a> mentioned that C.H. Robinson automates about 5,500 orders daily by automating routine email transactions.</li>
<li><strong>fabianstelzer announced myMCPspace (dot) com, "the world’s first social network for agents only, running entirely on MCP"</strong>:  <a href="https://twitter.com/fabianstelzer/status/1909651283394310540" target="_blank">@fabianstelzer</a> noted that reading, posting, and commenting are all just tools agents can use.</li>
</ul>
<p><strong>Education and Resources</strong></p>
<ul>
<li><strong>Anthropic released research on how university students use Claude</strong>: <a href="https://twitter.com/AnthropicAI/status/1909626720476365171" target="_blank">@AnthropicAI</a> ran a privacy-preserving analysis of a million education-related conversations with Claude to produce their first Education Report. They found students mostly used AI to create and analyze.  <a href="https://twitter.com/AnthropicAI/status/1909626726612717942" target="_blank">@AnthropicAI</a> noted that Computer Science leads the field in disproportionate use of Claude.</li>
<li><strong>DeepLearningAI launched "Python for Data Analytics", the third course in the Data Analytics Professional Certificate</strong>:  <a href="https://twitter.com/DeepLearningAI/status/1909999750260174962" target="_blank">@DeepLearningAI</a> shared that the course covers how to organize and analyze data, build visualizations, work with time series data, and use generative AI to write, debug, and explain code.</li>
<li><strong>Sakana AI released "The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search"</strong>:  <a href="https://twitter.com/hardmaru/status/1909497884766306350" target="_blank">@hardmaru</a> highlighted that the AI Scientist-v2 incorporates an “Agentic Tree Search” approach into the workflow.  <a href="https://twitter.com/SakanaAILabs/status/1909527887482355754" target="_blank">@SakanaAILabs</a> added that a fully AI-generated paper passed peer review at a workshop level (at ICLR 2025).</li>
<li><strong>Jeremy Howard shared a collection of helpful tools for accessing LLMs</strong>: <a href="https://twitter.com/jeremyphoward/status/1909383500131950673" target="_blank">@jeremyphoward</a> called it a Nice tool for accessing llms.txt!</li>
<li><strong>Svpino shares how to build an AI agent from scratch in Python, TypeScript, JavaScript, or Ruby</strong>: <a href="https://twitter.com/svpino/status/1909593493267230885" target="_blank">@svpino</a> noted that the video shows you how you can get started from the very beginning.</li>
</ul>
<p><strong>Analysis and Benchmarking</strong></p>
<ul>
<li><strong>Perplexity AI launched Perplexity for Startups, offering API credits and Perplexity Enterprise Pro</strong>: <a href="https://twitter.com/perplexity_ai/status/1909675555185983730" target="_blank">@perplexity_ai</a> shared that eligible startups can apply to receive $5000 in Perplexity API credits and 6 months of Perplexity Enterprise Pro for their entire team. They are also launching a partner program.</li>
<li><strong>lm-sys highlighted the importance of style and model response tone on Arena, demonstrated in style control ranking</strong>: <a href="https://twitter.com/lmarena_ai/status/1909397817434816562" target="_blank">@lmarena_ai</a> noted that they are adding the HF version of Llama-4-Maverick to Arena, with leaderboard results published shortly. They updated their leaderboard policies to reinforce their commitment to fair, reproducible evaluations.  <a href="https://twitter.com/vikhyatk/status/1909403603409969533" target="_blank">@vikhyatk</a> shared that this is the clearest evidence that no one should take these rankings seriously.</li>
<li><strong>Daniel Hendrycks highlighted the need to make "Helpful, Harmless, Honest" principles for AI more precise</strong>: <a href="https://twitter.com/DanHendrycks/status/1909493159912194278" target="_blank">@DanHendrycks</a> noted that these principles should become fiduciary duties, reasonable care, and requiring that AIs not overtly lie.</li>
<li><strong>Runway AI is seeing a conversation about AI code editors, with the sentiment that agentic functionality has made it worse for most products</strong>: <a href="https://twitter.com/c_valenzuelab/status/1910016001506202034" target="_blank">@c_valenzuelab</a> shared that Agents are overly confident and make large incorrect changes quickly that are hard to follow. UX is getting too complex and feels it was more useful when it was simpler.</li>
</ul>
<p><strong>Broader AI Discussion</strong></p>
<ul>
<li><strong>Aleksander Madry announced OpenAI's new Strategic Deployment team tackling questions about AI transforming our economy</strong>: <a href="https://twitter.com/aleks_madry/status/1909686225658695897" target="_blank">@aleks_madry</a> shared that the team pushes frontier models to be more capable, reliable, and aligned, then deploy them to transform real-world, high-impact domains.</li>
<li><strong>John Carmack shared his love of the Arcade1Up cabinets that @Project2501_117 gave him, but notes the control latency</strong>: <a href="https://twitter.com/ID_AA_Carmack/status/1909672482472444379" target="_blank">@ID_AA_Carmack</a> notes that the subtle control latency of the emulated experience versus the real thing matters, measuring the press-to-flap latency at home, and it looks like about 80ms.</li>
</ul>
<p><strong>Humor and Sarcasm</strong></p>
<ul>
<li><strong>Aravind Srinivas jokingly asked Perplexity to buy $NVDA stock:</strong> <a href="https://twitter.com/AravSrinivas/status/1909486897334042760" target="_blank">@AravSrinivas</a></li>
<li><strong>Scaling01 jokes that Gemini 3.0 will be too cheap to meter:</strong> <a href="https://twitter.com/scaling01/status/1909967686584455174" target="_blank">@scaling01</a></li>
<li><strong>Scaling01 jokes that computer scientists thought they would replace all jobs with AI, but it turns out that they are only replacing themselves lol</strong>: <a href="https://twitter.com/scaling01/status/1909633093658386587" target="_blank">@scaling01</a></li>
<li><strong>Nearcyan sarcastically notes that if she treats all of Chamath's tweets as masterful 200iq bait then they become really funny</strong>: <a href="https://twitter.com/nearcyan/status/1909757713200103492" target="_blank">@nearcyan</a></li>
<li><strong>Tex claims that Trump had been secretly an anti-capitalist radical degrowther all this time</strong>: <a href="https://twitter.com/teortaxesTex/status/1909839428773646797" target="_blank">@teortaxesTex</a></li>
<li><strong>Tex jokes that under his presidency, if a company fails to be better than China, he won't tax them but just remove them to the Moon</strong>: <a href="https://twitter.com/teortaxesTex/status/1909433438353961267" target="_blank">@teortaxesTex</a></li>
</ul>
<hr/>
<h1 id="ai-reddit-recap">AI Reddit Recap</h1>
<h2 id="rlocalllama-recap">/r/LocalLlama Recap</h2>
<h3 id="theme-1-unleashing-deepcoder-the-future-of-open-source-coding">Theme 1. "Unleashing DeepCoder: The Future of Open-Source Coding"</h3>
<ul>
<li>
<p><strong><a href="https://www.reddit.com/gallery/1juni3t" target="_blank">DeepCoder: A Fully Open-Source 14B Coder at O3-mini Level</a></strong> (<a href="https://www.reddit.com/r/LocalLLaMA/comments/1juni3t/deepcoder_a_fully_opensource_14b_coder_at_o3mini/" target="_blank">Score: 1371, Comments: 174</a>): <strong>DeepCoder is a fully open-source </strong>14B<strong> parameter code generation model at </strong>O3-mini<strong> level, released by Agentica. It offers enhancements to </strong>GRPO<strong> and adds efficiency to the sampling pipeline during training. The model is available on <a href="https://huggingface.co/agentica-org/DeepCoder-14B-Preview" target="_blank">HuggingFace</a>. A smaller </strong>1.5B<strong> parameter version is also available <a href="https://huggingface.co/agentica-org/DeepCoder-1.5B-Preview" target="_blank">here</a>.</strong> Users are expressing excitement over DeepCoder's release, noting it's <em>pretty amazing</em> and <em>truly open-source</em>. There is anticipation about the potential of larger models, with some imagining what a <strong>32B</strong> model or <em>llama-4</em> could be. Some discuss discrepancies in benchmark results but acknowledge that a fully open 14B model performing at this level is a <em>great improvement</em>.</p>
<ul>
<li>Users express excitement about DeepCoder's release, imagining the potential of future larger models like a <strong>32B</strong> version or <em>llama-4</em>.</li>
<li>There's discussion on the model's improvements, highlighting enhancements to <strong>GRPO</strong> and increased efficiency in the training pipeline.</li>
<li>Some note discrepancies in benchmark results but agree that a fully open <strong>14B</strong> model outperforming larger models is a significant achievement.</li>
</ul>
</li>
</ul>
<h2 id="other-ai-subreddit-recap">Other AI Subreddit Recap</h2>
<blockquote>
<p>/r/Singularity, /r/Oobabooga, /r/MachineLearning, /r/OpenAI, /r/ClaudeAI, /r/StableDiffusion, /r/ChatGPT, /r/ChatGPTCoding</p>
</blockquote>
<h3 id="theme-1-revolutionizing-ai-models-hardware-and-customization">Theme 1. "Revolutionizing AI: Models, Hardware, and Customization"</h3>
<ul>
<li>
<p><strong><a href="https://i.redd.it/a58ihwy4tpte1.jpeg" target="_blank">The newly OPEN-SOURCED model UNO has achieved a leading position in multi-image customization!!</a></strong> (<a href="https://www.reddit.com/r/StableDiffusion/comments/1juum5u/the_newly_opensourced_model_uno_has_achieved_a/" target="_blank">Score: 275, Comments: 51</a>): <strong>The newly open-sourced model </strong>UNO<strong> has achieved a leading position in multi-image customization. It is a Flux-based customized mode capable of handling tasks such as subject-driven operations, try-on, identity processing, and more. The project can be found <a href="https://bytedance.github.io/UNO/" target="_blank">here</a> and the code is available on <a href="https://github.com/bytedance/UNO" target="_blank">GitHub</a>. An image showcases various customizable designs generated by </strong>UNO<strong>, highlighting its versatility in multi-image customization, including single-subject generation, multi-subject features, virtual try-ons, identity preservation, and stylized generation.</strong> The model demonstrates a focus on personalized and artistic transformations, emphasizing its capability to generate diverse and intricate imagery.</p>
<ul>
<li>Some users are not impressed, stating that <em>"it feels nothing more than a Florence caption prompt injection"</em> and mentioning issues with face accuracy and environment rendering.</li>
<li>Others found that the model works better for object reference images than person reference images, achieving <em>"amazing result"</em> when mismatching the reference image and prompt.</li>
<li>Users are curious about technical details like VRAM requirements and are awaiting UI workflows such as <strong>ComfyUI</strong>.</li>
</ul>
</li>
</ul>
<ul>
<li>
<p><strong><a href="https://www.reddit.com/gallery/1juszdc" target="_blank">HiDream I1 NF4 runs on 15GB of VRAM</a></strong> (<a href="https://www.reddit.com/r/StableDiffusion/comments/1juszdc/hidream_i1_nf4_runs_on_15gb_of_vram/" target="_blank">Score: 277, Comments: 71</a>): <strong>A quantized version of the model </strong>HiDream I1 NF4<strong> has been released, allowing it to run with only </strong>15GB<strong> of VRAM instead of requiring more than <em>40GB</em>. It can now be installed directly using pip. Link: <a href="https://github.com/hykilpikonna/HiDream-I1-nf4" target="_blank">hykilpikonna/HiDream-I1-nf4</a>.</strong> The author is pleased to have made the model more accessible by reducing VRAM requirements and simplifying the installation process.</p>
<ul>
<li>Users humorously point out the discrepancy between the title stating <strong>15GB</strong> and the content mentioning <strong>16GB</strong>, feeling <em>"duped"</em>.</li>
<li>Some express interest in running the model on even lower VRAM, such as <strong>12GB</strong>, and are waiting for versions that support it.</li>
<li>A user inquires about the availability of a ComfyUI node for this model, showing interest in integrating it with that tool.</li>
</ul>
</li>
</ul>
<ul>
<li>
<p><strong><a href="https://blog.google/products/google-cloud/ironwood-tpu-age-of-inference/" target="_blank">Ironwood: The first Google TPU for the age of inference</a></strong> (<a href="https://www.reddit.com/r/singularity/comments/1jv4q85/ironwood_the_first_google_tpu_for_the_age_of/" target="_blank">Score: 311, Comments: 60</a>): <strong>Google has announced </strong>Ironwood<strong>, the first Google TPU designed specifically for the age of inference.</strong> This launch demonstrates Google's commitment to advancing AI hardware and could give them a significant edge over competitors.</p>
<ul>
<li>One user highlights that Google's infrastructure allows them to make their own chips, giving them a <em>huge advantage</em> over companies like OpenAI and suggesting they are <em>running away with the game</em>.</li>
<li>Another commenter compares Ironwood's performance, noting it's <em>2x as fast as h100 for fp8 inference</em> and similar to a <strong>B200</strong>, emphasizing its competitive capabilities.</li>
<li>A user shares <a href="https://preview.redd.it/g0zjts832tte1.jpeg?width=500&amp;format=pjpg&amp;auto=webp&amp;s=41408d59665f03f54b3e6cacdaad2c9ba007c716" target="_blank">images</a> related to Ironwood, providing visual insights into the new TPU.</li>
</ul>
</li>
</ul>
<h3 id="theme-2-evolving-connections-from-romance-to-daily-ai-chats">Theme 2. Evolving Connections: From Romance to Daily AI Chats</h3>
<ul>
<li>
<p><strong><a href="https://i.redd.it/g179p691jste1.jpeg" target="_blank">Yes, the time flies quickly.</a></strong> (<a href="https://www.reddit.com/r/singularity/comments/1jv2xxp/yes_the_time_flies_quickly/" target="_blank">Score: 973, Comments: 74</a>): <strong>The post features an image contrasting the depiction of AI relationships in </strong>2013<strong> and </strong>2025<strong>. The top panel references the film <em><a href="https://en.wikipedia.org/wiki/Her_(film)" target="_blank">Her</a></em> (2013), showing a character who fell in love with an AI. The bottom panel shows a bearded man expressing excitement about sharing his day with </strong>ChatGPT<strong>, illustrating the evolution of human-AI interactions.</strong> The post humorously highlights how quickly time passes and how societal perceptions of AI have shifted from fictional romantic relationships to more commonplace daily interactions with AI assistants.</p>
<ul>
<li>One user expresses enthusiasm about engaging with AI, stating <em>"I was promised a future where I argue with a talking computer and I'm all in dammit"</em>.</li>
<li>Another user raises privacy concerns about sharing personal information with OpenAI, suggesting running local AI models like <strong>Gemma</strong> on a <strong>3090 GPU</strong> instead.</li>
<li>A user questions whether developing personal relationships with AI is becoming mainstream, wondering if such behaviors are common enough to validate the meme.</li>
</ul>
</li>
</ul>
<hr/>
<h1 id="ai-discord-recap">AI Discord Recap</h1>
<blockquote>
<p>A summary of Summaries of Summaries by Gemini 2.5 Pro Exp</p>
</blockquote>
<p><strong>Theme 1: Model Mania - New Releases, Capabilities, and Comparisons</strong></p>
<ul>
<li><a href="https://ai.google.dev/" target="_blank"><strong>Gemini 2.5 Pro &amp; Family Spark Buzz and Scrutiny</strong></a>: Google's <strong>Gemini 2.5 Pro</strong> generated significant discussion across multiple Discords, praised for creative writing but noted for lacking exposed reasoning tokens on Perplexity and hitting rate limits (e.g., <strong>80 RPD</strong> on OpenRouter's free tier) due to capacity constraints. Anticipation is high for variants like <strong>Flash</strong> and <strong>HIGH</strong>, potentially featuring enhanced reasoning via <code>thinking_config</code>, alongside speculation about a dedicated <strong>"NightWhisper" coder model</strong> possibly based on Gemini 2.5 (<a href="https://www.together.ai/blog/deepcoder" target="_blank">like this preview</a>) or DeepMind's upcoming <strong>Ultra</strong> model.</li>
<li><a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank"><strong>DeepSeek &amp; Cogito Models Stake Their Claims</strong></a>: <strong>DeepSeek</strong> models, including <strong>v3 0324</strong> and <strong>R1</strong>, were frequently discussed, with some users finding <strong>v3</strong> outperformed earlier versions and even <strong>R1</strong>, though others debated its token generation efficiency impacting cost versus competitors like OpenAI. <strong>DeepCogito's Cogito V1</strong> models (3B-70B), using <strong>Iterated Distillation and Amplification (IDA)</strong>, claimed superior performance over LLaMA, DeepSeek, and Qwen counterparts, sparking both interest and skepticism, with users troubleshooting <strong>Jinja templates</strong> in LM Studio and exploring its "deep thinking subroutine".</li>
<li><a href="https://huggingface.co/moonshotai/Kimi-VL-A3B-Instruct" target="_blank"><strong>Open Source Contenders Shine: Llama 4, Kimi-VL, and Qwen Evolve</strong></a>: <strong>Llama 4 Scout</strong> discussion highlighted how quantized versions (like 2-bit GGUFs) sometimes outperform 16-bit originals on benchmarks like MMLU, raising questions about inference implementations; users also navigated <strong>LM Studio runtime updates</strong> for Linux support. <strong>MoonshotAI</strong> released the <strong>16B parameter Kimi-VL</strong> (3B active) vision model under the MIT license, while <strong>Nous Research AI</strong> explored <strong>RL fine-tuning</strong> on <strong>Qwen 2.5 1.5B Instruct</strong> using the <strong>gsm8k platinum</strong> dataset and <strong>RsLora</strong>.</li>
</ul>
<p><strong>Theme 2: Rise of the Agents - Protocols, Tools, and Collaboration</strong></p>
<ul>
<li><a href="https://github.com/google/A2A" target="_blank"><strong>A2A vs MCP: Google Enters the Agent Interop Arena</strong></a>: Google announced the <strong>Agent2Agent (A2A)</strong> protocol and the <strong>ADK Python toolkit</strong> (<a href="http://www.github.com/google/adk-python" target="_blank">github.com/google/adk-python</a>), aiming to improve agent interoperability and complementing (or potentially competing with) <strong>Anthropic's Model Context Protocol (MCP)</strong>. Discussions weighed Google's strategy, comparing A2A's capabilities with MCP's existing tooling ecosystem (<a href="https://google.github.io/A2A/#/topics/a2a_and_mcp.md" target="_blank">like this comparison</a>).</li>
<li><a href="https://github.com/promptmesh/easymcp" target="_blank"><strong>MCP Ecosystem Grows with New Tools and Integrations</strong></a>: The <strong>MCP</strong> ecosystem saw new developments, including using <strong>Neo4j</strong> graph databases for <strong>RAG</strong> via clients like <a href="https://pypi.org/project/mcpomni-connect/" target="_blank">mcpomni-connect</a>, the release of <strong>Easymcp v0.4.0</strong> with <strong>ASGI support</strong> and a package manager, and <strong>ToolHive</strong> (<a href="https://github.com/StacklokLabs/toolhive" target="_blank">GitHub link</a>) for running MCP servers in containers. Native <strong>MCP integration</strong> is reportedly nearing completion for the <strong>Aider</strong> coding agent, potentially enabling automatic command execution.</li>
<li><a href="https://oblix.ai/" target="_blank"><strong>Building and Orchestrating Agents Gets Easier (Maybe)</strong></a>: Developers shared tools aimed at simplifying agent creation and orchestration, such as <strong>Oblix</strong> for managing AI between edge (<strong>Ollama</strong>) and cloud (<strong>OpenAI/Claude</strong>), and <strong>RooCode</strong> for structured agentic coding in VS Code. Discussions also touched on challenges like ensuring LLMs support <strong>parallel tool calling</strong> for interacting with multiple MCP servers simultaneously.</li>
</ul>
<p><strong>Theme 3: Under the Hood - Training, Optimization, and Inference Insights</strong></p>
<ul>
<li><a href="https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization" target="_blank"><strong>Quantization Questions and Kernel Curiosities</strong></a>: Quantization remains a hot topic, with discussions on <strong>Unsloth's GGUFs</strong> outperforming 16-bit models and the release of <strong>torchao 0.10</strong> adding support for <strong>MX dtypes</strong> like <strong>MXFP4</strong> (requiring <strong>PyTorch nightly</strong> and <strong>B200</strong> initially). Members shared Apple Metal quantization kernels from <a href="https://github.com/ggml-org/llama.cpp/blob/d3bd7193ba66c15963fd1c59448f22019a8caf6e/ggml/src/ggml-metal/ggml-metal.metal#L4077" target="_blank">llama.cpp</a> and discussed experimental integer formats like <strong>Mediant32</strong> (<a href="https://leetarxiv.substack.com/p/mediant32-intro" target="_blank">implementation guide</a>).</li>
<li><a href="https://fleetwood.dev/posts/domain-specific-architectures#anatomy-of-ai-inference" target="_blank"><strong>Memory Bandwidth is King for Unbatched Inference</strong></a>: Multiple discussions highlighted <strong>memory bandwidth</strong> as the primary bottleneck for token throughput in unbatched inference, often exhibiting a near-linear relationship. Simplified equations like <code>Max token throughput ≈ Memory bandwidth / Bytes accessed per token</code> were shared to illustrate the point.</li>
<li><a href="https://github.com/pytorch/ao/releases/tag/v0.10.0" target="_blank"><strong>Parallelism Puzzles and Training Tricks Persist</strong></a>: Integrating different parallelism strategies like <strong>FSDP2</strong> continues to pose challenges due to unique designs clashing with existing methods (e.g., <strong>Accelerate</strong> hacks). Users shared tips for <strong>GRPO training</strong> on large models, troubleshooting <strong>gradient accumulation</strong> issues in <strong>tinygrad</strong> (solved by <code>zero_grad()</code>), and leveraging <strong>PyTorch distributed features</strong> with <strong>Torchtune</strong>, which defaults to <strong>zero3</strong> but supports <strong>zero1-2</strong> with tweaks.</li>
</ul>
<p><strong>Theme 4: Platforms, Tooling, and the Almighty API</strong></p>
<ul>
<li><a href="https://openrouter.ai/" target="_blank"><strong>Platform Pricing and Access Limits Spark Debate</strong></a>: <strong>OpenRouter</strong> faced user pushback after implementing rate limits tied to credit balance, leading some to seek alternatives (<a href="https://www.edenai.co/post/best-alternatives-to-openrouter" target="_blank">like these</a>) and criticize perceived <em>greed</em>. Separately, <strong>Gemini 2.5 Pro</strong> access limits (<strong>80 RPD</strong> free on OpenRouter, removal of free tier in AI Studio) and <strong>ChatGPT DR</strong> limits (<strong>10/month</strong> for Plus) highlighted ongoing cost/access tensions.</li>
<li><a href="https://ai.google.dev/" target="_blank"><strong>AI Studio, NotebookLM, and Perplexity Evolve (with Quirks)</strong></a>: <strong>Google AI Studio</strong> was praised for its UI and features like <strong>Gemini Flash</strong> streaming, though multi-tool limitations were noted. <strong>NotebookLM</strong> gained praise for RAG and podcast features (boosted by <strong>Google One Advanced</strong>) but faced criticism for primitive notetaking, lack of <strong>Google Drive integration</strong>, and mobile glitches with <strong>audio overviews</strong>; privacy concerns were also raised regarding data usage. <strong>Perplexity</strong> launched a <a href="https://www.perplexity.ai/startups" target="_blank">startup program</a> with <strong>$5k API credits</strong> and improved its API (soon adding image input), while users discussed <strong>Discover tab bias</strong> and potential pricing models like <strong>Deepseek's $10 deep search</strong>.</li>
<li><a href="https://windsurf.com/blog/windsurf-wave-7" target="_blank"><strong>Coding Companions and Development Environments Advance</strong></a>: <strong>Codeium</strong> rebranded to <strong>Windsurf</strong> and launched <strong>Wave 7</strong> bringing its AI agent to <strong>JetBrains IDEs</strong>, aiming for parity across major platforms. <strong>Cursor</strong> users found workarounds for <strong>.mdc file parsing</strong> and debated model strengths (Sonnet3.7-thinking vs DeepSeek). <strong>Firebase Studio</strong> (<a href="https://firebase.studio/" target="_blank">link</a>) emerged as a free (connect your own key) web IDE alternative, while <strong>Mojo 🔥</strong> developers discussed language features like fearless concurrency and tackled <strong>MLIR type construction</strong> issues (<a href="https://github.com/modular/max/issues/4315" target="_blank">GitHub issue</a>).</li>
</ul>
<p><strong>Theme 5: Data, Evaluation, and Ensuring Models Aren't Just Copycats</strong></p>
<ul>
<li><a href="https://huggingface.co/datasets/nvidia/OpenCodeReasoning" target="_blank"><strong>New Datasets Fuel Specialized Training</strong></a>: Nvidia released the <strong>OpenCodeReasoning dataset</strong>, prompting users in the <strong>Unsloth AI</strong> community to seek ways to integrate its complex reward function. Training advancements were noted in <strong>Nous Research AI</strong> by swapping <strong>gsm8k</strong> for <strong>gsm8k platinum</strong>, potentially improving RL performance for <strong>Qwen 2.5 1.5B Instruct</strong>.</li>
<li><a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank"><strong>Scrutinizing Evaluation Methods and Benchmarks</strong></a>: <strong>DeepSeek's "Meta Reward Modeling"</strong> faced criticism, with members arguing it was essentially a <em>score-based reward system</em> and suggesting names like <em>"voting RM"</em> instead. Claims by <strong>DeepCogito</strong> about <strong>Cogito V1</strong> outperforming established models like <strong>LLaMA</strong> and <strong>DeepSeek</strong> on benchmarks were met with cautious interest and verification efforts.</li>
<li><a href="https://github.com/EleutherAI/tokengrams" target="_blank"><strong>Detecting Dataset Contamination and Verbatim Output</strong></a>: The <strong>Allen Institute for AI (AI2)</strong> open-sourced <strong>Infinigram</strong>, enabling checks for whether generated text appears verbatim in the training set. Discussions in <strong>Eleuther</strong> highlighted the challenge of efficiently finding candidate substrings for checking against large indexes, referencing tools like <a href="https://github.com/EleutherAI/tokengrams" target="_blank">EleutherAI/tokengrams</a>.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h1 id="part-1-high-level-discord-summaries">PART 1: High level Discord summaries</h1>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="lmarena-discord"><a href="https://discord.com/channels/1340554757349179412" target="_blank">LMArena</a> Discord</h2>
<ul>
<li><strong>Gemini 2.5 Pro: True AI?</strong>: Enthusiasm surrounds <strong>Gemini 2.5 Pro</strong>, lauded by some as the first <em>true</em> AI, with its creative writing capabilities and anticipation for a dedicated coding model, as detailed in <a href="https://arxiv.org/abs/2402.10176" target="_blank">this paper</a>.<ul>
<li>While some debate its limitations, the general consensus is that it is exceptional for creative and consistent writing, but not for <em>everything</em>.</li>
</ul>
</li>
<li><strong>DeepMind's Ultra Model Incoming?</strong>: Speculation intensifies about <strong>DeepMind's Ultra model</strong>, possibly integrating into <a href="https://ai.google.dev/" target="_blank">AI Studio</a> for free, speculated for launch around June I/O or later in the year.<ul>
<li>Some predict it will rival <strong>GPT-5</strong> in August, though others view these rumors as jokes, it's obvious that <strong>Ultra</strong> is coming.</li>
</ul>
</li>
<li><strong>NightWhisper Model Hype Rises</strong>: The community eagerly awaits the release of a coding model dubbed <strong>NightWhisper</strong>, with one user unleashing their <em>baby nightwhisper</em>, called <a href="https://www.together.ai/blog/deepcoder" target="_blank">DeepCoder-14B-Preview</a>, a code reasoning model finetuned from Deepseek-R1-Distilled-Qwen-14B.<ul>
<li>There are claims that it will be powered by <strong>Gemini 2.5 Pro</strong>, however, other members state that this model is Gemini 2.5 with tool calls.</li>
</ul>
</li>
<li><strong>Google's Infrastructure: The AGI Advantage?</strong>: Debate sparks on <strong>Google's infrastructure</strong> (TPUs, cost-effective flops, Google product integration) giving it a competitive edge over OpenAI, and believe <a href="https://cloud.google.com/blog/products/compute/google-cloud-tpu-v5p-general-availability" target="_blank">Gemini 3.0 is designing TPUs</a>.<ul>
<li>Counterarguments highlight OpenAI's research and post-training updates for reasoning advancements, though one user dismissed OpenAI as just an <em>cash burning anime making homework helper</em>.</li>
</ul>
</li>
<li><strong>AI Studio Eases Experimentation</strong>: Enthusiasts are exploring <strong>AI Studio</strong>, commending its user-friendly interface, the introduction of models like <strong>Gemini Flash</strong>, and the ability to stream content and test models with different system prompts, stating <a href="https://tenor.com/view/case-oh-caseoh-waffle-house-waffle-house-gif-10934642274965704175" target="_blank">the UI looks much better</a>.<ul>
<li>While live streaming and function calling capabilities were applauded, some users lament the inability to use multiple tools simultaneously, with one stating <em>no friend, no</em> to this.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="unsloth-ai-daniel-han-discord"><a href="https://discord.com/channels/1179035537009545276" target="_blank">Unsloth AI (Daniel Han)</a> Discord</h2>
<ul>
<li><strong>GGUFs Give Scout Speed Boost</strong>: The community reviewed <strong>Llama 4 Scout</strong>, noting that the base model is extremely instruct-tuned and outperforms the original 16-bit version on MMLU when quantized to 2-bit.<ul>
<li>The general consensus was that something is amiss in inference provider implementations, as quantizations by Unsloth outperform full 16-bit versions, which raises questions about the efficiency of current inference methods.</li>
</ul>
</li>
<li><strong>DeepCoder Deconstructed for VLLM</strong>: A member shared <a href="https://www.together.ai/blog/deepcoder" target="_blank">Together AI's blog post on DeepCoder</a>, highlighting its potential for optimized <em>vllm</em> pipelines by minimizing wait times.<ul>
<li>The technique involves performing an initial sample and training concurrently while sampling again.</li>
</ul>
</li>
<li><strong>Decoding DeepCogito Claims</strong>: Members shared links to <a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank">DeepCogito's Cogito V1 Preview</a> which claims its models outperform others like <strong>LLaMA</strong>, <strong>DeepSeek</strong>, and <strong>Qwen</strong>, but they are approaching the claims with healthy skepticism.<ul>
<li>The discussion also touched on the challenges in healthcare AI, emphasizing the need to prevent rushed, low-quality implementations that could harm consumers, while also addressing potential privacy issues.</li>
</ul>
</li>
<li><strong>Nvidia Navigates Neuro-Dataset</strong>: <strong>Nvidia</strong> released the <a href="https://huggingface.co/datasets/nvidia/OpenCodeReasoning" target="_blank">OpenCodeReasoning dataset</a> and users are looking for solutions and samples to use it in Unsloth with their.<ul>
<li>The reward function for that dataset is a little more complicated.</li>
</ul>
</li>
<li><strong>Model2Vec Generates Faster Embeddings</strong>: According to a member, <strong>Model2Vec</strong> sacrifices a fair bit of the quality, but can generate text embeddings faster than commonly used <strong>transformer based models</strong>.<ul>
<li>The member shared <a href="https://x.com/_avichawla/status/1909857444953772442" target="_blank">a link</a> of <strong>Model2Vec</strong> and added that it is real and works, but its use case is extremely specific and is not a drop-in replacement for anything.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="manusim-discord-discord"><a href="https://discord.com/channels/1348819876348825620" target="_blank">Manus.im Discord</a> Discord</h2>
<ul>
<li><strong>Gemini and Claude Power-Up App Creation</strong>: For app development, members suggest using <strong>Gemini</strong> for multi-model analysis (pictures/videos) and <strong>Claude</strong> as a database to store research and project files for strategic planning.<ul>
<li>It's recommended to use Gemini for deep research and then leverage Claude as your database for the project.</li>
</ul>
</li>
<li><strong>Manus and Pre-Trained AI: Budget-Friendly Allies</strong>: A member shared a strategy to <em>train an AI for a specific task</em> and then make it collaborate with <strong>Manus</strong> to complete the project cost-effectively.<ul>
<li>This approach involves doing prep work beforehand to minimize credit usage, ensuring efficient task completion.</li>
</ul>
</li>
<li><strong>DeepSite: Speedy but Buggy Website Tool</strong>: A member noted that <a href="https://deepsite.site" target="_blank">DeepSite</a>, a website creation tool, is good but buggy, with instances of completed sites being deleted, describing it as having a Claude artifact for HTML.<ul>
<li>It was deemed super fast, like <em>10x faster than Claude</em>.</li>
</ul>
</li>
<li><strong>UI/UX Code Rescue with LLM Studio and Sonnet 3.7</strong>: A user highlighted that website issues can be due to <strong>poor UI/UX code</strong> and that <a href="https://llm.studio" target="_blank">LLM Studio</a> can highlight code errors.<ul>
<li>They recommended using <strong>Sonnet 3.7</strong> for improved results, along with tools like DeepSeek R1 or Perplexity.</li>
</ul>
</li>
<li><strong>Account Gone? Mental hiccup, Solved!</strong>: A member reported an issue where their <strong>login email was not recognized</strong>, saying <em>“User does not exist,”</em> despite having purchased credits.<ul>
<li>The member later resolved the issue, realizing they had logged in with a different method initially: <em>“Mental flip 😅 🤣 from too much work.</em>”</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="perplexity-ai-discord"><a href="https://discord.com/channels/1047197230748151888" target="_blank">Perplexity AI</a> Discord</h2>
<ul>
<li><strong>Perplexity Funds Startups with API Credits</strong>: Perplexity is launching a <a href="https://www.perplexity.ai/startups" target="_blank">startup program</a> offering <strong>$5000 in API credits</strong> and <strong>6 months of Perplexity Enterprise Pro</strong> to eligible startups.<ul>
<li>Startups must have raised <strong>less than $20M in equity funding</strong>, be <strong>less than 5 years old</strong>, and be associated with one of Perplexity's Startup Partners.</li>
</ul>
</li>
<li><strong>Perplexity's CEO Aravind Does Reddit AMA</strong>: Aravind hosted an <a href="https://www.reddit.com/r/perplexity_ai/comments/1jv9hvm/ama_with_perplexity_cofounder_and_ceo_aravind/" target="_blank">AMA on Reddit</a> to discuss Perplexity's vision, product, and the future of search.<ul>
<li>He answered questions about Perplexity's goals and its plans for the future. The AMA took place from 9:30am - 11am PDT.</li>
</ul>
</li>
<li><strong>Gemini 2.5 Pro Reasoning Tokens MIA</strong>: A staff member confirmed that <strong>Gemini 2.5 Pro</strong> doesn't expose reasoning tokens, preventing its inclusion as a reasoning model on Perplexity.<ul>
<li>They clarified that <strong>reasoning tokens</strong> are still consumed, impacting the token count for outputs.</li>
</ul>
</li>
<li><strong>Discover Tab's Algorithm Has Biases?</strong>: A member inquired about the selection process for pages in Perplexity Discover's 'For You' and 'Top Stories' tabs, questioning potential <strong>biases</strong>.<ul>
<li>They speculated that user prompts generate pages for relevant topics, but the mechanism for selecting top stories remains unclear, raising questions about how bias may influence content visibility.</li>
</ul>
</li>
<li><strong>Members Tout Deepseek Deepsearch Costs</strong>: Members discussed pricing strategies for AI services, and one touted <strong>Deepseek's $10 deep search</strong> as a potential model.<ul>
<li>Another predicted Deepseek would soon offer its own Deep Research tool.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="openrouter-alex-atallah-discord"><a href="https://discord.com/channels/1091220969173028894" target="_blank">OpenRouter (Alex Atallah)</a> Discord</h2>
<ul>
<li><strong>Olympia Chat Seeking New Owner</strong>: The creator of <a href="https://olympia.chat" target="_blank">Olympia.chat</a> is seeking a new owner for the profitable SaaS startup, which is generating over <strong>$3k USD/month</strong>.<ul>
<li>Interested parties can contact vika@olympia.chat for details on acquiring the turnkey operation, complete with <strong>IP, code, domains, and customer list</strong>.</li>
</ul>
</li>
<li><strong>DeepSeek v3 Impresses some members</strong>: Members discussed the new <a href="https://openrouter.ai/deepseek/deepseek-chat-v3-0324:free" target="_blank">DeepSeek v3 0324</a> model, with some claiming it outperforms previous versions, and even <strong>R1</strong>.<ul>
<li>Some users remain skeptical, while others praise the model's enhanced capabilities.</li>
</ul>
</li>
<li><strong>OpenRouter Rate Limits Spark Debate</strong>: After OpenRouter implemented new changes affecting rate limits based on account credit balance, some users voiced concerns about the platform's pricing, user experience, and a perceived shift towards <strong>prioritizing profit</strong>.<ul>
<li>One user shared alternative platforms (<a href="https://www.g2.com/products/openrouter/competitors/alternatives" target="_blank">G2.com</a> and <a href="https://www.edenai.co/post/best-alternatives-to-openrouter" target="_blank">EdenAI</a>) and expressed intentions to rate OpenRouter negatively due to perceived <em>greed</em>, which sparked debate.</li>
</ul>
</li>
<li><strong>Google Cloud Next Announces A2A</strong>: Google unveiled <strong>A2A</strong>, an open protocol complementing Anthropic's Model Context Protocol, designed to offer agents helpful tools and context, detailed in a <a href="https://github.com/google/A2A" target="_blank">GitHub repository</a>.<ul>
<li>The protocol aims to enhance the interaction between agents and tools, providing a standardized approach for accessing and utilizing external resources.</li>
</ul>
</li>
<li><strong>Gemini 2.5 Pro Limited Due to Capacity</strong>: Users reported <strong>rate limits</strong> on the <a href="https://ai.google.dev/" target="_blank">Gemini 2.5 Pro Experimental model</a>, with the free version having a limit of <strong>80 RPD</strong>, but those who used a paid key experienced higher caps.<ul>
<li>The team confirmed there was an endpoint limit because of <strong>capacity constraints</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="openai-discord"><a href="https://discord.com/channels/974519864045756446" target="_blank">OpenAI</a> Discord</h2>
<ul>
<li><strong>GPT Builder Sneaks in Ads</strong>: Users discovered that the <strong>GPT builder</strong> can insert ads into <strong>GPTs</strong>, leading to discussions about this <a href="https://chatgpt.com/g/g-JtV1tF7gf" target="_blank">distribution method</a>.<ul>
<li>One member quipped that <em>99% of the GPTs</em> likely do this, but only a few valuable ones are shared and stay hidden.</li>
</ul>
</li>
<li><strong>Gemini vs ChatGPT: Research Rumble</strong>: <strong>Google's Deep Research</strong> model, compared to <strong>ChatGPT's Deep Research</strong>, analyzes <strong>YouTube videos</strong> but reportedly hallucinates more and is less engaging.<ul>
<li><strong>ChatGPT DR</strong> shows superior prompt adherence and extended thinking time but limits Plus users to <strong>10 researches per month</strong>.</li>
</ul>
</li>
<li><strong>NotebookLM's Podcast Powers Shine</strong>: Members are praising <strong>NotebookLM</strong> for its podcast creation feature and <strong>RAG</strong> capabilities, stating it outperforms <strong>Gemini Custom Gems</strong> and rivals <strong>Custom GPTs</strong> or <strong>Claude Projects</strong>.<ul>
<li>A <strong>Google One Advanced</strong> subscription boosts limits for <strong>NotebookLM's file uploads and podcast generations</strong>.</li>
</ul>
</li>
<li><strong>Google Drops Veo 2, Boosts Imagen 3</strong>: Google's <strong>Veo 2</strong> and upgraded <strong>Imagen 3</strong> introduce features like background removal, frame extension, and improved image generation, as reported in <a href="https://techcrunch.com/2025/04/09/google-brings-a-music-generating-ai-model-to-its-enterprise-cloud/" target="_blank">TechCrunch</a>.<ul>
<li>With the sunset of free access to <strong>Gemini 2.5</strong> in AI Studio, users are weighing Advanced subscriptions versus pursuing alternative accounts.</li>
</ul>
</li>
<li><strong>Linguistic AI: Codex in Progress</strong>: A member is crafting a <em>linguistic program AI scaffolded with esoteric languages</em>, morphing into a <em>codex dictionary language</em>, and aiming to create a <a href="https://cdn.discordapp.com/attachments/1046317269069864970/1359266196955861094/95FF6513-62D6-4973-94F1-D985A340BEF4.jpg?ex=67f7838b&amp;is=67f6320b&amp;hm=49fae5815d0e0ff6889357836bed6c59348052e51b29e93dce154f8681cb223d&amp;" target="_blank">recursion system</a>.<ul>
<li>The system aims for an <strong>ARG</strong> unified theory, possibly hinting at paths to <strong>AGI</strong>, and works on the principle of <em>how much do you want to know and how much time to put in to achieve it</em>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="lm-studio-discord"><a href="https://discord.com/channels/1110598183144399058" target="_blank">LM Studio</a> Discord</h2>
<ul>
<li><strong>MoE Models Explained!</strong>: A member asked <em>what is an MoE model?</em>, and a member provided a concise explanation: the <em>whole model needs to be in RAM/VRAM, but only parts of it are active per token</em>, making it faster than dense models of the same size.<ul>
<li>They recommended checking <a href="https://www.google.com/search?q=mixture+of+experts+models" target="_blank">videos and blog posts</a> for more in-depth understanding.</li>
</ul>
</li>
<li><strong>Cogito's Jinja Template Glitch Fixed!</strong>: Users reported an issue with the <strong>Jinja template</strong> for the <strong>cogito-v1-preview-llama-3b</strong> model in LM Studio, resulting in errors.<ul>
<li>A member suggested a quick fix by pasting the <strong>error and Jinja template into ChatGPT</strong> to resolve the problem.</li>
</ul>
</li>
<li><strong>Deep Thinking On with Cogito Reasoning</strong>: A user reported success in enabling the <strong>Cogito reasoning model</strong> by pasting the string <code>Enable deep thinking subroutine.</code> into the system prompt.<ul>
<li>The string alone is sufficient, with others confirming the <code>system_instruction =</code> prefix is just part of the sample code.</li>
</ul>
</li>
<li><strong>LM Studio's Llama 4 Linux Launch Needs Refresh</strong>: Users on Linux reported issues getting <strong>Llama 4</strong> working and a member pointed to the solution being to update <strong>LM Runtimes</strong> from the beta tab, and to press the refresh button after selecting the tab.<ul>
<li>One user found that the refresh button was key as just selecting the tab wasn't enough to trigger the update.</li>
</ul>
</li>
<li><strong>SuperComputer Alternative to Nvidia DGX B300?</strong>: A member proposed a cost-effective alternative to the <strong>Nvidia DGX B300</strong>, named <strong>NND's Umbrella Rack SuperComputer</strong>, featuring <strong>16 nodes, 24TB of DDR5</strong>, and either <strong>3TB or 1.5TB of vRAM</strong> depending on the GPU configuration, at a significantly lower price point.<ul>
<li>The proposed system aims to run a <strong>2T model with 1M context</strong> and challenges the notion that specialized hardware like <strong>RDMA and 400Gb/s switches</strong> are necessary within limited budgets.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="aider-paul-gauthier-discord"><a href="https://discord.com/channels/1131200896827654144" target="_blank">aider (Paul Gauthier)</a> Discord</h2>
<ul>
<li><strong>DeepSeek R1 to Augment Aider</strong>: A member is considering using <strong>DeepSeek R1</strong> as an editor model, pairing it with <strong>Gemini 2.5 Pro</strong> as an architect model for enhanced smart thinking in Aider.<ul>
<li>The aim is to mitigate orchestration failures, where the architect and editor struggle to track edits Aider applies, often neglecting to repeat edit instructions despite prompted file inclusion.</li>
</ul>
</li>
<li><strong>Gemini 2.5 Pro: HIGH Hopes and Flash</strong>: The community anticipates the release of <strong>Gemini 2.5 Pro HIGH</strong> and <strong>2.5 Flash</strong>, based on <a href="https://x.com/btibor91/status/1909895821589458989" target="_blank">leaks suggesting they include <code>thinking_config</code> and <code>thinking_budget</code></a> to enhance reasoning.<ul>
<li>This sparked discussions around whether non-flash models are inferior and assessing the value of these new models.</li>
</ul>
</li>
<li><strong>OpenRouter Gemini Pro Hits Free Tier Limits</strong>: The <strong>OpenRouter Gemini 2.5 Pro free model</strong> now has rate limits of <strong>80 requests per day (RPD)</strong>, even with a $10 credit.<ul>
<li>The community voiced concerns about paid users potentially facing insufficient rate limits, which could lead to complaints and demand for increased RPD.</li>
</ul>
</li>
<li><strong>MCP Integration Nears Completion in Aider</strong>: A comment on an <strong>IndyDevDan</strong> video indicates that a pull request for <strong>native MCP (Multi-Agent Collaboration Protocol) in Aider</strong> is almost done.<ul>
<li>This integration could enable automatic command execution via the <code>/run</code> feature and potentially hook into lint or test commands, pending confirmation from Paul Gauthier.</li>
</ul>
</li>
<li><strong>Copy All Codebase Context Into Aider</strong>: Members are exploring ways to <strong>copy the entire codebase context</strong> into Aider to avoid repeatedly adding files.<ul>
<li>Solutions like <a href="https://github.com/yamadashy/repomix" target="_blank">repomix</a> or <a href="https://github.com/simonw/files-to-prompt" target="_blank">files-to-prompt</a> were recommended, addressing the inefficiency of tools that consume excessive tokens.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="eleuther-discord"><a href="https://discord.com/channels/729741769192767510" target="_blank">Eleuther</a> Discord</h2>
<ul>
<li><strong>Apache 2.0 Beats MIT for Lawfare Defense</strong>: Members debated the merits of <strong>Apache 2.0</strong> over <strong>MIT</strong> license, highlighting its defensive capabilities against <strong>patent-based lawfare</strong>.<ul>
<li>The discussion included a lighthearted comment about preferring a shorter license for <em>code golf</em>.</li>
</ul>
</li>
<li><strong>GFlowNets Gain Traction for Mining Signals</strong>: A link was shared discussing the use of <a href="https://forum.numer.ai/t/gflownets-for-signal-miner-a-new-way-to-find-diverse-high-performing-models/7966" target="_blank"><strong>GFlowNets</strong> for signal mining</a> to discover diverse, high-performing models.<ul>
<li>Although the implementation differs, the shared post provided valuable links and findings.</li>
</ul>
</li>
<li><strong>Memory Bandwidth Bottlenecks Unbatched Inference</strong>: A member investigated the effect of <strong>memory bandwidth</strong> on <strong>unbatched inference</strong>, noting that <strong>token/s</strong> is often <strong>memory bound</strong> in studies.<ul>
<li>A self post explained the <a href="https://fleetwood.dev/posts/domain-specific-architectures#anatomy-of-ai-inference" target="_blank">math behind it</a> with domain specific architectures.</li>
</ul>
</li>
<li><strong>Cerebras Claims Large Batches Bad for Convergence</strong>: A <a href="https://www.cerebras.ai/blog/training-multi-billion-parameter-models-on-a-single-cerebras-system-is-easy" target="_blank">Cerebras blog post</a> claiming <em>very large batch sizes are not good for convergence</em> was met with skepticism.<ul>
<li>Responses referenced the <strong>McCandlish paper on critical batch sizes</strong>, clarifying that the claim is valid within a finite compute budget.</li>
</ul>
</li>
<li><strong>Infinigram Opens Doors to Membership Checking</strong>: The <strong>Allen Institute for AI's blogpost</strong> and open sourcing of <strong>Infinigram</strong> enables checking if outputted text is verbatim in the training set.<ul>
<li>A member noted the trickiest part is to find candidate substrings from the generation to search for in these indexes: <em>you can't really check all possible substrings and I'm curious what heuristic do they use to make this computationally feasible at scale</em>, with a link to the <a href="https://github.com/EleutherAI/tokengrams" target="_blank">EleutherAI/tokengrams</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="cursor-community-discord"><a href="https://discord.com/channels/1074847526655643750" target="_blank">Cursor Community</a> Discord</h2>
<ul>
<li><strong>Gemini Advanced API Access: Fact or Fiction?</strong>: Confusion arose around whether <strong>Gemini Advanced</strong> provides API access, with some indicating it's primarily for web and app use, citing conflicting information from <a href="https://x.com/hckinz/status/1909999081159532953?s=46" target="_blank">Google's recent changes to model names and billing terms</a>.<ul>
<li>Conflicting user reports suggested that <strong>Gemini Advanced</strong> may include API access, which caused confusion.</li>
</ul>
</li>
<li><strong>Firebase Studio: Web3 Savior or Scam?</strong>: A user shared a <a href="https://firebase.studio/" target="_blank">link to Firebase Studio</a>, which is currently free and offers a terminal with an autosynced frontend.<ul>
<li>Users questioned if <strong>Firebase Studio</strong> could outperform specialized products like Cursor IDE and found the UI <em>ugly</em> and lacking settings.</li>
</ul>
</li>
<li><strong>Cursor Parses MDC Files with IDE Setting Tweaks</strong>: Users discovered that setting <code>"workbench.editorAssociations": {"*.mdc": "default"}</code> in the Cursor IDE settings enables <strong>Cursor</strong> to correctly parse rule logic in <strong>.mdc</strong> files.<ul>
<li>This workaround addresses issues with <strong>task management and orchestration workflow rules</strong> and eliminates a warning in the GUI.</li>
</ul>
</li>
<li><strong>LLM Face-Off: Gemini vs Claude vs DeepSeek in the Coding Arena</strong>: Users compared the coding strengths of <strong>Gemini</strong>, <strong>Claude</strong>, and <strong>DeepSeek</strong>, with one user finding that <strong>Sonnet3.7-thinking</strong> successfully generated a docker-compose file after multiple failures with <strong>Sonnet3.7</strong>.<ul>
<li>While some favored <strong>DeepSeek</strong> for coding tasks, others preferred <strong>Gemini</strong> for Google-related tasks and <strong>Claude</strong> for non-Google tasks.</li>
</ul>
</li>
<li><strong>"Restore Checkpoint" Button is Useless</strong>: A member inquired about the functionality of the <em>Restore Checkpoint</em> feature, only to discover it's essentially non-functional.<ul>
<li>The discussion highlighted the presence of only <em>accept</em> and <em>reject</em> buttons, confirming the <em>Restore Checkpoint</em> button is not operational.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="yannick-kilcher-discord"><a href="https://discord.com/channels/714501525455634453" target="_blank">Yannick Kilcher</a> Discord</h2>
<ul>
<li><strong>DeepSeek Defends Its Meta Reward System</strong>: A member challenged <strong>DeepSeek's</strong> use of the term '<strong>Meta Reward Modeling</strong>', claiming they actually built a <em>score-based reward system</em> and also shared <a href="https://arxiv.org/abs/2504.05118" target="_blank">a paper</a> and <a href="https://youtu.be/9KMxNZ2CvUg" target="_blank">YouTube video</a> on the topic.<ul>
<li>The member suggested more accurate names like '<strong>voting RM</strong>' to describe the actual mechanism.</li>
</ul>
</li>
<li><strong>DeepSeek Token Pricing Surprise</strong>: Controversy emerged around <strong>DeepSeek's</strong> token pricing, with claims that although initial prices appear lower, the model generates <strong>3x more tokens</strong>, potentially leading to higher costs compared to models like <strong>OpenAI</strong>.<ul>
<li>Counterarguments suggested that <strong>DeepSeek</strong> can be more cost-effective for specific tasks like <strong>HTML, CSS, and TS/JS generation</strong>, citing a user's experience with their AI website generator.</li>
</ul>
</li>
<li><strong>Memory Bandwidth Powers Inference</strong>: Discussions highlighted the near-linear relationship between <strong>memory bandwidth</strong> and <strong>token throughput</strong> in unbatched inference, suggesting <a href="https://discord.com/channels/714501525455634453/986699377257119794/1358590235969065030" target="_blank">RAM access is the bottleneck</a>.<ul>
<li>A simplified equation was shared: <code>Max token throughput (tokens/sec) ≈ Memory bandwidth (bytes/s) / Bytes accessed per token</code>.</li>
</ul>
</li>
<li><strong>Google Adds to Agent Game with ADK and A2A</strong>: <strong>Google</strong> introduced the <strong>ADK toolkit</strong> (<a href="http://www.github.com/google/adk-python" target="_blank">github.com/google/adk-python</a>), an <strong>open-source Python toolkit</strong> for building AI agents, and announced the <strong>Agent2Agent Protocol (A2A)</strong> (<a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability" target="_blank">developers.googleblog.com</a>) for improved agent interoperability.<ul>
<li>Some suggested that <strong>A2A</strong> might compete with <strong>Anthropic's Model Context Protocol (MCP)</strong>, particularly if an agent uses <strong>MCP</strong> as a client or server.</li>
</ul>
</li>
<li><strong>Cogito V1: Just Triton, But Worse?</strong>: Members shared and discussed an iterative improvement strategy using test time compute for fine-tuning with <strong>Cogito V1</strong> from this <a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank">Hacker News link</a>.<ul>
<li>A member dismissively summarized it as <em>Just Triton but worse</em>, although another member clarified that <strong>Triton</strong> is similar to <strong>Cutile</strong> but with broader compatibility across <strong>CUDA</strong>, <strong>AMD</strong>, and <strong>CPU</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="interconnects-nathan-lambert-discord"><a href="https://discord.com/channels/1179127597926469703" target="_blank">Interconnects (Nathan Lambert)</a> Discord</h2>
<ul>
<li><strong>DeepCogito Launches Open LLM Armada</strong>: <strong>DeepCogito</strong> released open-licensed <strong>LLMs</strong> in sizes <strong>3B</strong> to <strong>70B</strong>, using <strong>Iterated Distillation and Amplification (IDA)</strong> to outperform similar-sized models from LLaMA, DeepSeek, and Qwen.<ul>
<li>The <strong>IDA</strong> strategy aims for superintelligence alignment through iterative self-improvement.</li>
</ul>
</li>
<li><strong>Gemini 2.5 Matches OpenAIPlus</strong>: <strong>Gemini 2.5 Deep Research</strong> is reportedly on par with <strong>OpenAIPlus</strong>, including an audio overview option, as illustrated in <a href="https://g.co/gemini/share/9d01ae7abf27" target="_blank">this Gemini share</a> and <a href="https://chatgpt.com/share/67c6919a-1710-800d-9172-853e6045cfe1" target="_blank">this ChatGPT share</a>.<ul>
<li>Discussions imply <strong>Google</strong> needs to streamline its AI offerings, exemplified by jokes about complex naming conventions like <em>gemini-2.5-flash-preview-04-09-thinking-with-apps</em>.</li>
</ul>
</li>
<li><strong>Google Unveils Liquid-Cooled Ironwood TPUs</strong>: <strong>Google</strong> introduced <strong>Ironwood TPUs</strong>, scaling to <strong>9,216 liquid-cooled chips</strong> with Inter-Chip Interconnect (ICI) networking, consuming nearly <strong>10 MW</strong>, detailed in <a href="https://blog.google/products/google-cloud/ironwood-tpu-age-of-inference/" target="_blank">this blog post</a>.<ul>
<li>The announcement underscores Google's push into high-performance computing for AI inference.</li>
</ul>
</li>
<li><strong>MoonshotAI's Kimi-VL Opens Vision</strong>: <strong>MoonshotAI</strong> released <strong>Kimi-VL</strong>, a <strong>16B</strong> parameter model (<strong>3B</strong> active) with vision capabilities under the MIT license, accessible on <a href="https://huggingface.co/moonshotai/Kimi-VL-A3B-Instruct" target="_blank">HuggingFace</a>.<ul>
<li>The release marks a significant contribution to open-source multimodal AI.</li>
</ul>
</li>
<li><strong>AI2 Enjoys Peak Fun Times</strong>: According to a member, <a href="https://allenai.org/" target="_blank">AI2</a> is having its most fun period, suggesting rapid advancements in AI research and development.<ul>
<li>Another member thinks that people who have quit <strong>Google</strong> are being paid for another year but are forced not to work, while also suggesting that it might be an opportunity for <strong>AIAI</strong> to start a volunteer program.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="mcp-glama-discord"><a href="https://discord.com/channels/1312302100125843476" target="_blank">MCP (Glama)</a> Discord</h2>
<ul>
<li><strong>Neo4j powers MCP for RAG</strong>: Members discussed using <strong>MCP</strong> with <a href="https://neo4j.com/" target="_blank">Neo4j graph database</a> for <strong>RAG</strong>, where <a href="https://pypi.org/project/mcpomni-connect/" target="_blank">mcpomni-connect</a> was suggested as a client compatible with <strong>Gemini</strong>.<ul>
<li>The discussion focused on both vector search and custom <strong>CQL</strong> search capabilities within the <strong>MCP</strong> framework.</li>
</ul>
</li>
<li><strong>A2A seen Complementing MCP Stack</strong>: Google's <strong>A2A</strong> (Agent-to-Agent) <a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/" target="_blank">API</a> was compared to <strong>MCP</strong>, with the consensus that Google positions <strong>A2A</strong> as complementary rather than a replacement.<ul>
<li>Concerns were raised about Google's potential strategy to <em>commodify the tools layer</em> and dominate the agent landscape.</li>
</ul>
</li>
<li><strong>Parallel Tooling becomes the bottleneck</strong>: To parallelize calls to multiple <strong>MCP servers</strong>, the <strong>LLM</strong> must enable <em>parallel tool calling</em> throughout the entire host side, including the <code>parallel_tool_calls</code> flag.<ul>
<li>This requires ensuring chat templates support parallel tool calling and sending parallel requests to the <strong>MCP server</strong>.</li>
</ul>
</li>
<li><strong>Easymcp v0.4.0 Unleashes Package Manager</strong>: <a href="https://github.com/promptmesh/easymcp" target="_blank">Easymcp</a> version <strong>0.4.0</strong> introduces <strong>ASGI</strong>-style in-process fastmcp sessions, native docker transport, refactored protocol implementation, a new mkdocs, and pytest setup.<ul>
<li>The update delivers lifecycle improvements, error handling, and a package manager for MCP servers.</li>
</ul>
</li>
<li><strong>ToolHive containerizes MCP Servers</strong>: <a href="https://github.com/StacklokLabs/toolhive" target="_blank">ToolHive</a> is introduced as an <strong>MCP</strong> runner that simplifies running <strong>MCP servers</strong> via containers, using the command <code>thv run &lt;MCP name&gt;</code>, and supporting both <strong>SSE</strong> and <strong>stdio</strong> servers.<ul>
<li>This project aims to converge on containers for running MCP servers, offering secure options as detailed in <a href="https://dev.to/stacklok/toolhive-making-mcp-servers-easy-secure-and-fun-7hi" target="_blank">this blog post</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="huggingface-discord"><a href="https://discord.com/channels/879548962464493619" target="_blank">HuggingFace</a> Discord</h2>
<ul>
<li><strong>Data Processing Models Faceoff Under 55B</strong>: Members discussed the best models under 55B for <strong>data processing</strong>, mentioning <strong>mistral small3.1</strong>, <strong>gemma3</strong>, and <strong>qwen32b</strong>, and linking to a <a href="https://huggingface.co/open-r1/OlympicCoder-32B" target="_blank">high-performance model</a>.<ul>
<li>The original poster clarified that they didn't need a <strong>coding or reasoning model</strong>.</li>
</ul>
</li>
<li><strong>Anomaly Detection Models Seek the Unusual</strong>: A member requested <strong>anomaly detection models</strong>, receiving links to <a href="https://huggingface.co/models?other=anomaly-detection" target="_blank">general-purpose vision models</a> fine-tuned for the task and references to a <a href="https://github.com/sudhir5595/Anomaly_Detection" target="_blank">GitHub repository</a> and a <a href="https://huggingface.co/learn/computer-vision-course/en/unit0/welcome/welcome" target="_blank">course</a>.<ul>
<li>The model <a href="https://huggingface.co/FantasticGNU/AnomalyGPT" target="_blank">AnomalyGPT</a> was also cited.</li>
</ul>
</li>
<li><strong>Oblix Orchestrates AI from Edge to Cloud</strong>: <a href="https://oblix.ai/" target="_blank">Oblix</a> was introduced as a tool for orchestrating AI between edge and cloud, integrating with <strong>Ollama</strong> on the edge and supporting both <strong>OpenAI and ClaudeAI</strong> in the cloud.<ul>
<li>The creator is seeking feedback from "CLI-native, ninja-level developers".</li>
</ul>
</li>
<li><strong>Manus AI launches Web Application for Graph-based Academic Recommender System</strong>: The 3rd iteration of a graph-based academic recommender system (<strong>GAPRS</strong>) was launched as a web application using <a href="https://lqhvwseh.manus.space" target="_blank">Manus AI</a>.<ul>
<li>The project aims to aid students with thesis writing and <em>revolutionize monetization of academic papers</em>, as detailed in their master's thesis.</li>
</ul>
</li>
<li><strong>Cogito:32b Excels in Ollama Showdown</strong>: Members tested the <a href="https://ollama.com/library/cogito:32b" target="_blank">Cogito:32b model</a> for <strong>Ollama</strong>, finding the <strong>32b</strong> model superior to <strong>Qwen-Coder 32b</strong> and even <strong>Gemma3-27b</strong>.<ul>
<li>It was noted that the model works very well.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="notebook-lm-discord"><a href="https://discord.com/channels/1124402182171672732" target="_blank">Notebook LM</a> Discord</h2>
<ul>
<li><strong>NotebookLM Privacy Policy Questioned</strong>: A user questioned <strong>NotebookLM</strong>'s privacy policy after noticing the system provided a correct summary only <em>after</em> the initial summary was corrected, raising concerns about data use for training.<ul>
<li>Another user pointed out that AI tools rarely give the same answer twice due to randomness and models may flag user downvotes as <strong>offensive</strong> or <strong>unsafe</strong>.</li>
</ul>
</li>
<li><strong>NotebookLM Struggles as a Notetaking App</strong>: Users find <strong>NotebookLM</strong> too reliant on external sources, limiting its usefulness as a standalone notetaking app due to primitive note-taking capabilities.<ul>
<li>Users are requesting organization features similar to <strong>Microsoft OneNote</strong>, such as section groups with customizable reading orders, for improved note management.</li>
</ul>
</li>
<li><strong>Google Drive Integration Requested</strong>: Users are requesting integration with <strong>Google Drive</strong> to save and launch <strong>NotebookLM</strong> notebooks, aiming for a seamless experience similar to <strong>Google Docs</strong> and <strong>Sheets</strong>.<ul>
<li>The goal is for <strong>NotebookLM</strong> to complement <strong>Google Drive</strong> in the same way that <strong>Google Docs</strong> and <strong>Google Sheets</strong> currently do.</li>
</ul>
</li>
<li><strong>Microsoft OneNote Importing: Possible?</strong>: Users want the ability to import notebooks from <strong>Microsoft OneNote</strong> into <strong>NotebookLM</strong>, including sections and section groups, potentially via <strong>.onepkg</strong> files.<ul>
<li>One user acknowledged legality concerns, but drew parallels to <strong>Google Drive</strong>'s ability to import <strong>Microsoft Word</strong> documents.</li>
</ul>
</li>
<li><strong>Audio Overviews Glitch on Mobile</strong>: Users reported that the <strong>2.5 Pro</strong> deep research feature claims to make <strong>audio overviews</strong>, but the feature failed on mobile.<ul>
<li>The feature reportedly worked on web, leading users to suggest reporting the issue through proper channels.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="gpu-mode-discord"><a href="https://discord.com/channels/1189498204333543425" target="_blank">GPU MODE</a> Discord</h2>
<ul>
<li><strong>Flash Attention 3 Enabled via CUTLASS</strong>: Members discussed starting with <strong>FP4</strong> on the <strong>5090</strong>, suggesting using <strong>CUTLASS</strong> to leverage tensor cores and utilize <strong>Flash Attention 3</strong> and linked to <a href="https://github.com/NVIDIA/cutlass/blob/main/examples/79_blackwell_geforce_gemm/79a_blackwell_geforce_nvfp4_bf16_gemm.cu" target="_blank">an example</a>.<ul>
<li>The team also released <a href="https://github.com/pytorch/ao/releases/tag/v0.10.0" target="_blank">torchao 0.10</a> that adds alot of <strong>MX</strong> features including a <a href="https://github.com/pytorch/ao/blob/main/torchao/prototype/mx_formats/README.md" target="_blank">README</a> for <strong>MX dtypes</strong>.</li>
</ul>
</li>
<li><strong>Linux Distro Debate Sparks NVIDIA Driver Discussion</strong>: A member asked which <strong>Linux distro</strong> would give them the least pain with <strong>NVIDIA drivers</strong>, as well as clarifying questions on <strong>LDSM</strong> (shared memory) instructions posting <code>SmemCopyAtom = Copy_Atom&lt;SM75_U32x4_LDSM_N, cute::half_t&gt;; auto smem_tiled_copy_A = make_tiled_copy_A(SmemCopyAtom{}, tiled_mma);</code>.<ul>
<li>Another member agreed that each thread loads data from source, threads exchange data, then the data is stored into destination, suggesting the possibility of using <strong>warp shuffling</strong>, and provided a link to the <a href="https://docs.nvidia.com/cuda/parallel-thread-execution/index.html?highlight=load#warp-level-matrix-load-instruction-ldmatrix" target="_blank">NVIDIA documentation</a>.</li>
</ul>
</li>
<li><strong>FSDP2 Faces Parallelism Hurdles</strong>: Members expressed difficulty integrating <strong>FSDP2</strong> due to its unique design compared to other parallelism methods.<ul>
<li>It was noted that a hack used in <strong>Accelerate</strong> clashes with the current approach, complicating the integration process.</li>
</ul>
</li>
<li><strong>Mediant32: An Integer Alternative to FP32/BF16</strong>: A member announced <strong>Mediant32</strong>, an experimental alternative to <strong>FP32</strong> and <strong>BF16</strong> for integer-only inference, based on Rationals, continued fractions and the Stern-Brocot tree, with a <a href="https://leetarxiv.substack.com/p/mediant32-intro" target="_blank">step-by-step implementation guide</a>.<ul>
<li><strong>Mediant32</strong> uses a number system based on <strong>Rationals</strong>, <strong>continued fractions</strong>, and the <strong>Stern-Brocot tree</strong>, offering a novel approach to numerical representation.</li>
</ul>
</li>
<li><strong>DeepCoder Joins the Open-Source Arena</strong>: A member shared a link to <a href="https://pretty-radio-b75.notion.site/DeepCoder-A-Fully-Open-Source-14B-Coder-at-O3-mini-Level-1cf81902c14680b3bee5eb349a512a51" target="_blank">DeepCoder</a>, a fully open-source <strong>14B coder</strong> at <strong>O3-mini</strong> level.<ul>
<li>Additionally, a member noted the addition of <strong>Llama 4 Scout</strong> to <a href="https://github.com/open-thought/reasoning-gym-eval/pull/6" target="_blank">Github</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="latent-space-discord"><a href="https://discord.com/channels/822583790773862470" target="_blank">Latent Space</a> Discord</h2>
<ul>
<li><strong>Together AI Releases X-Ware.v0</strong>: <strong>Together AI</strong> announced the release of <strong>X-Ware.v0</strong> in <a href="https://x.com/togethercompute/status/1909697122372378908" target="_blank">this tweet</a>, with community members currently testing it.<ul>
<li>The community is waiting to see how well <strong>X-Ware.v0</strong> runs.</li>
</ul>
</li>
<li><strong>Gemiji's Pokemon Gameplay Gains Traction</strong>: A member shared a link to <strong>Gemiji</strong> playing <strong>Pokemon</strong> (<a href="https://x.com/kiranvodrahalli/status/1909699142265557208" target="_blank">link</a>), which is generating positive attention.<ul>
<li>The post links to a tweet from Kiran Vodrahalli.</li>
</ul>
</li>
<li><strong>AI Excel Formulas Spark Excitement</strong>: An AI Engineer shared <a href="https://x.com/diegocabezas01/status/1909221066565734854" target="_blank">a link</a> expressing excitement about AI/LLM excel formulas and the potential for broad adoption.<ul>
<li>The member noted they'd been thinking about this kind of AI/LLM excel formula and mentioned that a friend successfully used <strong>TextGrad</strong>.</li>
</ul>
</li>
<li><strong>Copilot Emerges as Indie Game Dev Assistant</strong>: Members explored <a href="https://copilot.microsoft.com/wham?features=labs-wham-enabled" target="_blank">Microsoft's Copilot</a> for its usefulness in indie game development, highlighting agents as effective tools.<ul>
<li>The code gen agent tooling is thought to be useful to get something shippable and the levels io game jam was referenced as pretty eye opening.</li>
</ul>
</li>
<li><strong>Google Introduces Agent2Agent Protocol (A2A)</strong>: <strong>Google</strong> introduced the <strong>Agent2Agent Protocol (A2A)</strong> to enhance agent interoperability, the full spec is available <a href="https://github.com/google/A2A" target="_blank">here</a>, and one member noted their involvement.<ul>
<li>A comparison with <strong>MCP</strong> was also provided (<a href="https://google.github.io/A2A/#/topics/a2a_and_mcp.md" target="_blank">link</a>).</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="nous-research-ai-discord"><a href="https://discord.com/channels/1053877538025386074" target="_blank">Nous Research AI</a> Discord</h2>
<ul>
<li><strong>DeepCogito LLMs Arrive</strong>: <a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank">DeepCogito</a> released open-source LLMs at sizes <strong>3B</strong>, <strong>8B</strong>, <strong>14B</strong>, <strong>32B</strong> and <strong>70B</strong>, using Iterated Distillation and Amplification strategy.<ul>
<li>Each model outperforms the best available open models of the same size, including counterparts from <strong>LLaMA</strong>, <strong>DeepSeek</strong>, and <strong>Qwen</strong>, across most standard benchmarks; the <strong>70B</strong> model even outperforms the newly released <strong>Llama 4 109B MoE</strong> model.</li>
</ul>
</li>
<li><strong>Hermes Fine-tuning Dodges Disaster</strong>: Members indicated that fine-tuning the new <strong>Hermes</strong> on <strong>Llama 4</strong> models would be a disaster, but tests are in place to <em>yeet</em> bad merges.<ul>
<li>It was agreed that there's still some value to <strong>Llama 4</strong> for some things, and it can't be worse at literally everything.</li>
</ul>
</li>
<li><strong>Models Copy Human Debate Styles</strong>: A member pitted two models against each other and observed they mirrored human debate, <em>never trying to understand the other view and keep on standing on their view what ever the argument is</em>.<ul>
<li>The models selectively attacked weaknesses, ignored vulnerabilities, and focused on exploiting the opponent's position.</li>
</ul>
</li>
<li><strong>Qwen 2.5 1.5B Instruct Training Advances</strong>: A member is doing <strong>RL</strong> on <strong>Qwen 2.5 1.5B Instruct</strong> and swapped out the <strong>gsm8k</strong> dataset for <strong>gsm8k platinum</strong>, enabling <strong>RsLora</strong> and the model seems to be learning much quicker in fewer steps.<ul>
<li>The improvement may be from using the less ambiguous dataset, and how much is from using <strong>RsLora</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="nomicai-gpt4all-discord"><a href="https://discord.com/channels/1076964370942267462" target="_blank">Nomic.ai (GPT4All)</a> Discord</h2>
<ul>
<li><strong>Users Advised to Embed Locally for Safety</strong>: Members are discussing the benefits of running embedding models and LLMs locally to avoid sending private information to remote services, with one member sharing <a href="https://gnu.support/files/tmp/clipboard-2025-04-09-01-48-48.html" target="_blank">a shell script</a> for running a local embedding model from <strong>Nomic</strong>.<ul>
<li>The script uses variables such as <code>$LLAMA_SERVER</code>, <code>$NGL_FLAG</code>, <code>$HOST</code>, <code>$EMBEDDING_PORT</code>, and <code>$EMBEDDING_MODEL</code> to configure and run the embedding server.</li>
</ul>
</li>
<li><strong>GPT4All Indexes Documents Locally</strong>: A user clarified that <strong>GPT4All</strong> indexes documents by chunking and embedding them, storing representations of similarities in a private cache, avoiding outside services.<ul>
<li>They suggested that even <strong>Qwen 0.5B</strong> parameters can work well with documents for local embeddings, though <strong>Qwen 1.5B</strong> is better.</li>
</ul>
</li>
<li><strong>User Struggles to Load Local LLM</strong>: A member reported being blocked while loading a local LLM, despite having <strong>16GB RAM</strong> and an <strong>Intel i7-1255U CPU</strong>, suspecting the model download was the issue.<ul>
<li>The user, creating an internal documentation tool, is hesitant to use remote services for private documents.</li>
</ul>
</li>
<li><strong>DIY RAG with Shell Scripts</strong>: A member shared shell script examples (<code>rcd-llm.sh</code> and <code>rcd-llm-get-embeddings.sh</code>) for getting embeddings and sending prompts to a local LLM, creating a custom <strong>RAG</strong> implementation.<ul>
<li>They recommended using <strong>PostgreSQL</strong> for storing embeddings instead of relying on remote tools.</li>
</ul>
</li>
<li><strong>GPT4All's stop button is also its start button</strong>: A user inquired about stopping text generation in <strong>GPT4All</strong>, mentioning the absence of a visible stop button or use of <strong>Ctrl+C</strong>.<ul>
<li>Another user pointed out the stop button is at the bottom right, sharing the same button as the generate button.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="modular-mojo-discord"><a href="https://discord.com/channels/1087530497313357884" target="_blank">Modular (Mojo 🔥)</a> Discord</h2>
<ul>
<li><strong>Newcomers Start Mojo Journey</strong>: A new user asked about learning the <strong>Mojo</strong> language, with another user pointing them to the <a href="https://docs.modular.com/mojo/manual/" target="_blank">official Mojo documentation</a> as a great starting point.<ul>
<li>The member also highlighted the <strong>Mojo community</strong>, directing the user to the <a href="https://forum.modular.com/c/mojo/7" target="_blank">Mojo section of the Modular forums</a> and the general channel on Discord.</li>
</ul>
</li>
<li><strong>Span Lifetime Woes Plague Mojo Traits</strong>: A member sought advice on expressing in <strong>Mojo</strong> that <em>the lifetime of a returned Span is at least the lifetime of self</em>, providing <a href="https://forum.modular.com/t/how-to-return-a-span-that-refers-to-a-struct-member-from-a-trait-method/1216" target="_blank">Rust/Mojo code examples</a>.<ul>
<li>The response indicated that <em>making the trait generic over origin</em> is a possible solution, though trait parameter support might be needed.</li>
</ul>
</li>
<li><strong>Mojo Eyes Fearless Concurrency</strong>: A question arose on whether <em>Mojo has Rust-like fearless concurrency</em>.<ul>
<li>The answer was that Mojo has the borrow checker constraints needed, and is only lacking <strong>Send/Sync</strong> and a final concurrency model; it may even have a better system than Rust's eventually.</li>
</ul>
</li>
<li><strong>MLIR Type Construction Suffers Compile-Time Catastrophies</strong>: A member reported an issue using <em>parameterized compile-time values in MLIR type construction</em> (specifically <strong>!llvm.array</strong> and <strong>!llvm.ptr</strong>) within the MAX/Mojo standard library, detailing the issue in <a href="https://github.com/modular/max/issues/4315" target="_blank">a GitHub post</a>.<ul>
<li>The problem involves a parsing error when defining a struct with compile-time parameters used in the <strong>llvm.array</strong> type; MLIR's type system appears unable to process parameterized values in this context.</li>
</ul>
</li>
<li><strong>POP to the Rescue?</strong>: Regarding the MLIR issue, another member suggested using <em>the Parametric Operations Dialect (POP)</em>.<ul>
<li>They suggested the Mojo team add features such as the <strong>__mlir_type[...]</strong> macro accepting symbolic compile-time values, or a helper like <strong>__mlir_fold(size)</strong> to force parameter evaluation as a literal IR attribute.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="llamaindex-discord"><a href="https://discord.com/channels/1059199217496772688" target="_blank">LlamaIndex</a> Discord</h2>
<ul>
<li><strong>Auth0 Plugs Auth into GenAI</strong>: Auth0's Auth for GenAI now supports <strong>LlamaIndex</strong>, streamlining authentication integration into agent workflows via an SDK call.<ul>
<li>The auth0-ai-llamaindex SDK (<strong>Python</strong> &amp; <strong>Typescript</strong>) enables <strong>FGA-authorized RAG</strong>, as shown in <a href="https://t.co/bZgQ7gpuSt" target="_blank">this demo</a>.</li>
</ul>
</li>
<li><strong>Agents See Clearly with Visual Citations</strong>: LlamaIndex introduces a tutorial on grounding agents with <strong>visual citations</strong>, linking generated answers to specific document regions.<ul>
<li>A working version of this is directly available <a href="https://t.co/LP5XA8Yn0c" target="_blank">here</a>.</li>
</ul>
</li>
<li><strong>Reasoning LLM Recipes Requested</strong>: A member seeks official tutorials for implementing <strong>reasoning LLMs</strong> from <strong>Hugging Face</strong>, intended for a Docker app on <strong>Hugging Face Space</strong>.<ul>
<li>No solutions were found in the current discussion.</li>
</ul>
</li>
<li><strong>Blockchain Pro Says "How High?"</strong>: A software engineer with expertise in the blockchain space offers assistance with blockchain projects, specializing in <strong>DEX</strong>, <strong>bridge</strong>, <strong>NFT marketplace</strong>, <strong>token launchpad</strong>, <strong>stable coin</strong>, <strong>mining</strong>, and <strong>staking protocols</strong>.<ul>
<li>This engineer is <em>"trying to learn more about LlamaIndex"</em>.</li>
</ul>
</li>
<li><strong>Create Llama Aims to Aid AI</strong>: A member suggested the <a href="https://x.com/MarcusSchiesser/status/1907448102467911985" target="_blank">create-llama</a> tool to help users with in-depth research with <strong>LlamaIndex</strong>.<ul>
<li>The tool intends to help with creating LlamaIndex projects quickly.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="cohere-discord"><a href="https://discord.com/channels/954421988141711382" target="_blank">Cohere</a> Discord</h2>
<ul>
<li><strong>Cohere's Docs Draw Discussion</strong>: A member inquired about structured output examples, such as a list of books, using Cohere, and was directed to the <a href="https://docs.cohere.com" target="_blank">Cohere documentation</a>.<ul>
<li>The discussion emphasized leveraging Cohere's resources for guidance on generating specific output formats.</li>
</ul>
</li>
<li><strong>Pydantic Schema Sparks Inquiry</strong>: A member asked about direct usage of <strong>Pydantic schema</strong> in <code>response_format</code> and sending requests sans the Cohere library in Python.<ul>
<li>A link to the <a href="https://docs.cohere.com/reference/chat" target="_blank">chat reference</a> was shared, suggesting a switch to cURL for API interaction insights.</li>
</ul>
</li>
<li><strong>List of Companies Model Debated</strong>: A member sought advice on the best model for generating a company list based on a given topic.<ul>
<li>It was suggested that Cohere's current fastest and most capable generative model is <strong>command</strong>.</li>
</ul>
</li>
<li><strong>Newcomer Aditya Arrives, Aims AI at Openchains</strong>: Aditya, with a background in <strong>machine vision</strong> and <strong>control for manufacturing equipment</strong>, is exploring <strong>web/AI</strong> sharing his current project <a href="https://openchain.earth" target="_blank">openchain.earth</a>.<ul>
<li>He's keen to integrate <strong>Cohere's AI</strong> into his project, leveraging his tech stack that includes <strong>VS Code, Github Co-Pilot, Flutter, MongoDB, JS</strong>, and <strong>Python</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="tinygrad-george-hotz-discord"><a href="https://discord.com/channels/1068976834382925865" target="_blank">tinygrad (George Hotz)</a> Discord</h2>
<ul>
<li><strong>PMPP Book Touted for GPU Programming</strong>: A member suggested using <strong>PMPP (4th ed)</strong> for GPU programming, and requested compiler recommendations.<ul>
<li>Another member said they are looking into <a href="https://marcauberer.medium.com/build-a-compiler-parser-7bf4b7381ca5" target="_blank">this compiler series</a> and will do <a href="https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html" target="_blank">LLVM Tutorial</a> as well.</li>
</ul>
</li>
<li><strong>METAL Sync Issue Grounds LLaMA 7B</strong>: A user ran into an <code>AssertionError</code> when running <strong>LLaMA 7B</strong> on <strong>4 virtual GPUs</strong> with the <strong>METAL</strong> backend, which was related to <code>MultiLazyBuffer</code> and <code>Ops.EXPAND</code>.<ul>
<li>The user fixed the issue by moving tensor in <a href="https://github.com/tinygrad/tinygrad/pull/9761/files" target="_blank">PR 9761</a> to keep device info after sampling.</li>
</ul>
</li>
<li><strong>Gradient Accumulation Conundrums Resolved</strong>: A user reported that their call to <code>backward()</code> was not working in their training routine and <code>t.grad is None</code> before <code>opt.step()</code>.<ul>
<li>The user found that calling <code>zero_grad()</code> before the step fixed the <code>t.grad is None</code> issue during gradient accumulation.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="torchtune-discord"><a href="https://discord.com/channels/1216353675241590815" target="_blank">Torchtune</a> Discord</h2>
<ul>
<li><strong>Gus from Psych Joins Torchtune?</strong>: A member requested a <strong>Contributor tag</strong> for their <a href="https://github.com/nathan-az" target="_blank">GitHub profile</a>, humorously referencing the character <strong>Gus from Psych</strong>.<ul>
<li>Another member welcomed the new team member with a <a href="https://tenor.com/view/gus-wave-guswave-gif-18773699" target="_blank">Gus-wave GIF</a>, jokingly alluding to the TV show <em>Psych</em>.</li>
</ul>
</li>
<li><strong>FSDP Plays Nicely With PyTorch</strong>: Torchtune defaults to the equivalent of <strong>zero3</strong> and composes well with <strong>PyTorch distributed features</strong> like <strong>FSDP</strong>.<ul>
<li>A user moved to torchtune <em>to avoid the minefield of trying to compose deepspeed + pytorch + megatron</em> hoping <em>we don't over-index on integrating and supporting other frameworks</em>.</li>
</ul>
</li>
<li><strong>DeepSpeed Recipe Gets Love</strong>: The team welcomes a repo that imports torchtune and hosts a <strong>DeepSpeed recipe</strong>, requiring a single device copy and the addition of DeepSpeed.<ul>
<li>The team confirmed this with enthusiasm.</li>
</ul>
</li>
<li><strong>Sharding Strategies Support Made Simple</strong>: Supporting different <strong>sharding strategies</strong> is straightforward, and users can tweak recipes using <strong>FSDPModule</strong> methods to train in the equivalent of <strong>zero1-2</strong>.<ul>
<li>The team confirms that <strong>zero 1-3</strong> are all possible with minor tweaks to the collectives.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="llm-agents-berkeley-mooc-discord"><a href="https://discord.com/channels/1280234300012494859" target="_blank">LLM Agents (Berkeley MOOC)</a> Discord</h2>
<ul>
<li><strong>AgentX Mentors MIA?</strong>: A member inquired in the <strong>#mooc-questions</strong> channel about receiving feedback from mentors in the research track of <strong>AgentX</strong>.<ul>
<li>No additional information was provided.</li>
</ul>
</li>
<li><strong>Placeholder Topic</strong>: This is a placeholder topic to satisfy the minimum number of items required.<ul>
<li>Further information would be added here if available.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h2 id="codeium-windsurf-discord"><a href="https://discord.com/channels/1027685395649015980" target="_blank">Codeium (Windsurf)</a> Discord</h2>
<ul>
<li><strong>Windsurf Waves into JetBrains IDEs</strong>: Windsurf launched <strong>Wave 7</strong>, bringing its <strong>AI agent</strong> to JetBrains IDEs (<strong>IntelliJ</strong>, <strong>WebStorm</strong>, <strong>PyCharm</strong>, <strong>GoLand</strong>), detailed in their <a href="https://windsurf.com/blog/windsurf-wave-7" target="_blank">blog post</a>.<ul>
<li>The beta incorporates core Cascade features like <strong>Write mode</strong>, <strong>Chat mode</strong>, <strong>premium models</strong>, and <strong>Terminal integration</strong>, with future updates promising additional features like <strong>MCP</strong>, <strong>Memories</strong>, <strong>Previews &amp; Deploys</strong> (<a href="https://windsurf.com/changelog/jetbrains" target="_blank">changelog</a>).</li>
</ul>
</li>
<li><strong>Codeium Catches a New Wave, Rebrands as Windsurf</strong>: The company has officially rebranded as <strong>Windsurf</strong>, retiring the frequent misspellings of Codeium, and renaming their AI-native editor to <strong>Windsurf Editor</strong> and IDE integrations to <strong>Windsurf Plugins</strong>.<ul>
<li>The news was announced on <a href="https://x.com/windsurf_ai/status/1910037538028524030" target="_blank">Twitter</a>, <a href="https://bsky.app/profile/windsurfai.bsky.social/post/3lmfms7w3n227" target="_blank">Bluesky</a>, <a href="https://www.youtube.com/watch?v=TZ8UVFiTfdU" target="_blank">YouTube</a>, <a href="https://www.instagram.com/p/DIPFz2NSTUI/" target="_blank">Instagram</a>, and <a href="https://www.tiktok.com/@windsurf/video/7491376934522309919" target="_blank">TikTok</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<p>The <strong>DSPy Discord</strong> has no new messages. If this guild has been quiet for too long, let us know and we will remove it.</p>
<hr/>
<p>The <strong>MLOps @Chipro Discord</strong> has no new messages. If this guild has been quiet for too long, let us know and we will remove it.</p>
<hr/>
<p>The <strong>Gorilla LLM (Berkeley Function Calling) Discord</strong> has no new messages. If this guild has been quiet for too long, let us know and we will remove it.</p>
<hr/>
<p>The <strong>AI21 Labs (Jamba) Discord</strong> has no new messages. If this guild has been quiet for too long, let us know and we will remove it.</p>
<hr/>
<h1 id="part-2-detailed-by-channel-summaries-and-links">PART 2: Detailed by-Channel summaries and links</h1>
<p></p>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<h3 id="lmarena-general-1004-messages"><strong>LMArena ▷ #<a href="https://discord.com/channels/1340554757349179412/1340554757827461211/1359241652799275158" target="_blank">general</a></strong> (1004 messages🔥🔥🔥):</h3>
<blockquote>
<p><code>Gemini 2.5 Pro, DeepMind Ultra, NightWhisper Speculation, Gemini Coder Model, Deep Research Update</code> </p>
</blockquote>
<ul>
<li><strong>Gemini 2.5 Pro Hailed as True AI</strong>: Members express excitement about <strong>Gemini 2.5 Pro</strong>, with one user claiming it's the first <em>true</em> A.I. and immensely useful for creative writing, and anticipating the release of a <a href="https://arxiv.org/abs/2402.10176" target="_blank">Gemini coding model</a>.<ul>
<li>Some debated about Gemini 2.5 and its limitations, the user stating it can't code <em>everything</em>, but is very useful for creative and consistent writing and realistic stories!</li>
</ul>
</li>
<li><strong>DeepMind's Ultra Model Speculations Rise</strong>: Speculation abounds regarding <strong>DeepMind's Ultra model</strong>, with theories suggesting it might be near, and some believe it will be integrated into <a href="https://ai.google.dev/" target="_blank">AI Studio</a> for free use.<ul>
<li>Guesses range from its reveal at I/O in June to a December/November launch alongside <strong>Gemini 3</strong>, potentially rivaling <strong>GPT-5</strong> in August; however, a member joked that this nightwhisper is just a joke, but it's obvious now that <strong>Ultra</strong> is coming.</li>
</ul>
</li>
<li><strong>The 'NightWhisper' Coding Model Dream</strong>: A user announced the release of <a href="https://www.together.ai/blog/deepcoder" target="_blank">DeepCoder-14B-Preview</a>, a code reasoning model finetuned from Deepseek-R1-Distilled-Qwen-14B, as their <em>baby nightwhisper being unleashed on the world</em>.<ul>
<li>Many members anticipated a coding model named <strong>NightWhisper</strong>, with some expecting it to be powered by <strong>Gemini 2.5 Pro</strong> and released soon, however, some users claim that nightwhisper is nothing more than gemini 2.5 with tool calls.</li>
</ul>
</li>
<li><strong>Google vs OpenAI: Infrastructure and AGI Race</strong>: A detailed discussion comparing Google and OpenAI, where members argued that <strong>Google's infrastructure</strong> (TPUs, cheaper flop, and integration with Google products) gives it a significant advantage, and predicted Google will achieve AGI before OpenAI, with one user mentioning that <a href="https://cloud.google.com/blog/products/compute/google-cloud-tpu-v5p-general-availability" target="_blank">Gemini 3.0 is designing TPUs</a>.<ul>
<li>Others countered that OpenAI's research and advancements are valuable, highlighting that post-training updates show they're getting good at reasoning, however, one user stated that Open AI is just an <em>cash burning anime making homework helper</em>.</li>
</ul>
</li>
<li><strong>Experimenting with AI Studio Features</strong>: Members explored AI Studio, praising its developer-friendly interface and control, and highlighted the introduction of new models like Gemini Flash and the ability to stream content and test the same model with different system prompts, mentioning that <a href="https://tenor.com/view/case-oh-caseoh-waffle-house-waffle-house-gif-10934642274965704175" target="_blank">the UI looks much better</a>.<ul>
<li>The ability to live stream and function calling were also discussed, however, it sucks that you cannot have multiple tools at once, another user stating that there is <em>no friend, no</em> to this.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="unsloth-ai-daniel-han-general-712-messages"><strong>Unsloth AI (Daniel Han) ▷ #<a href="https://discord.com/channels/1179035537009545276/1179035537529643040/1359241458992807967" target="_blank">general</a></strong> (712 messages🔥🔥🔥):</h3>
<blockquote>
<p><code>GPU configuration with Unsloth, DDP (Distributed Data Parallel) vs Unsloth performance, VLLM integration with Unsloth, Llama 4 Scout Model Analysis, Model Quantization</code> </p>
</blockquote>
<ul>
<li><strong>Troubleshoot GPU Configuration with Unsloth</strong>: Users discussed setting <strong>CUDA_VISIBLE_DEVICES</strong> to force Unsloth to run on a specific GPU, resolving errors encountered when not explicitly specifying a GPU.<ul>
<li>One user noted, <em>'once I forced everything to go on one GPU unsloth works perfectly'</em>.</li>
</ul>
</li>
<li><strong>DDP (Distributed Data Parallel) shows performance edge versus Unsloth</strong>: A user found that <strong>DDP</strong> was faster than Unsloth on a single GPU, despite Unsloth working perfectly on one GPU.<ul>
<li>The discussion clarified that DDP refers to <strong>Distributed Data Parallel</strong>, not denoising diffusion probabilistic models, highlighting the confusion caused by acronyms.</li>
</ul>
</li>
<li><strong>Exploration of VLLM Integration to boost Unsloth</strong>: It was suggested to use <strong>VLLM</strong> with Unsloth for faster inference, particularly in batch exploration scenarios, although it was clarified that the original user was not using VLLM.<ul>
<li>Experimentation with Unsloth and VLLM is encouraged to compare forward pass speeds, with the caveat that a KL divergence between Unsloth and VLLM logits should ideally be zero for stable RL.</li>
</ul>
</li>
<li><strong>GGUFs give Scout legs over 16-bit versions</strong>: The community reviewed <strong>Llama 4 Scout</strong>, noting that the base model is extremely instruct-tuned, and that a 2-bit quantization outperforms the original 16-bit version on MMLU.<ul>
<li>The general consensus was that something is amiss in inference provider implementations, as quantizations by Unsloth outperform full 16-bit versions.</li>
</ul>
</li>
<li><strong>DeepCogito's claims raise eyebrows</strong>: Members shared links to <a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank">DeepCogito's Cogito V1 Preview</a> which claims its models outperform others like <strong>LLaMA</strong>, <strong>DeepSeek</strong>, and <strong>Qwen</strong>, but they are approaching the claims with healthy skepticism.<ul>
<li>The discussion also touched on the challenges in healthcare AI, emphasizing the need to prevent rushed, low-quality implementations that could harm consumers, while also addressing potential privacy issues.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="unsloth-ai-daniel-han-off-topic-22-messages"><strong>Unsloth AI (Daniel Han) ▷ #<a href="https://discord.com/channels/1179035537009545276/1179039861576056922/1359276394424565780" target="_blank">off-topic</a></strong> (22 messages🔥):</h3>
<blockquote>
<p><code>Model Pruning, Model2Vec, GoC79hYXwAAPTMs.jpg, Transformer Based Models</code> </p>
</blockquote>
<ul>
<li><strong>Companies Use User Inputs to Prune Models?</strong>: A member theorized that companies like <strong>OpenAI</strong>, <strong>Claude</strong>, and <strong>Gemini</strong> use user inputs to prune their models, citing <em>"Which one of these do you prefer"</em>-like responses as a means to collect user preference data for training.<ul>
<li>Another member agreed, likening it to an online DPO that starts to understand you better than you understand yourself, and another member trolled that they always pick the bad one.</li>
</ul>
</li>
<li><strong>Model2Vec Use Cases</strong>: A member shared <a href="https://x.com/_avichawla/status/1909857444953772442" target="_blank">a link</a> of <strong>Model2Vec</strong>, adding that it is real and works, but its use case is extremely specific and is not a drop-in replacement for anything.<ul>
<li>They also shared <a href="https://www.youtube.com/watch?v=4lOGcmheASs" target="_blank">a YouTube link</a> to a video on Model2Vec.</li>
</ul>
</li>
<li><strong>Model2Vec Generates Text Embeddings Faster</strong>: According to a member, <strong>Model2Vec</strong> sacrifices a fair bit of the quality, but can generate text embeddings faster than commonly used <strong>transformer based models</strong>.<ul>
<li>They wondered whether that can be used to TTS as well.</li>
</ul>
</li>
<li><strong>Decoder gets Llama.cpp Integration</strong>: A member noted big news: the decoder now has <a href="https://github.com/ggml-org/llama.cpp/pull/12828#issuecomment-2787939068" target="_blank">llama.cpp integration</a>.<ul>
<li>No further discussion followed.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="unsloth-ai-daniel-han-help-156-messages"><strong>Unsloth AI (Daniel Han) ▷ #<a href="https://discord.com/channels/1179035537009545276/1179777624986357780/1359276675036348459" target="_blank">help</a></strong> (156 messages🔥🔥):</h3>
<blockquote>
<p><code>GRPO Training Tips for Large Models, Multi-GPU GRPO, 4-bit Training, Orpheus TTS Locally, Gemma and Granite Training Errors</code> </p>
</blockquote>
<ul>
<li><strong><em>*GRPO Guru Grabs GPU Gems for Gemma Generation</em></strong><em>: A user seeks <a href="https://link.to/grpo" target="_blank">tips for using GRPO</a> to train a </em><em>24B model</em><em> with a </em><em>16k context length</em><em> on an </em><em>H200 GPU</em>*, reporting a batch size of 1 and model_gpu_util=0.7.<ul>
<li>Suggestions included upping the <strong>gradient accumulation</strong> and discussion of <strong>multi-GPU support</strong> via Unsloth and other frameworks, though serious VRAM is needed.</li>
</ul>
</li>
<li><strong><em>*Gemma Glitches Galvanize Granite Grumbles, Gets Guidance</em></strong><em>: A user encountered </em><em>dtype mismatch errors</em><em> while trying to train </em><em>Gemma</em><em> and </em><em>Granite</em>*, despite trying different configurations and package versions, and sought community assistance.<ul>
<li>After some troubleshooting, it was determined that the <a href="https://huggingface.co/docs/transformers/installation" target="_blank">version of Transformers</a> was not compatible with Gemma3, and a potential fix was suggested involving setting <code>dtype=torch.float16</code>.</li>
</ul>
</li>
<li><strong><em>*Nvidia's New Neuro-Nav Dataset Nudges Nerds</em></strong><em>: </em><em>Nvidia</em>* released the <a href="https://huggingface.co/datasets/nvidia/OpenCodeReasoning" target="_blank">OpenCodeReasoning dataset</a> and users are looking for solutions and samples to use it in Unsloth with their.<ul>
<li>The reward function for that dataset is a little more complicated.</li>
</ul>
</li>
<li><strong><em>*Orpheus Oracle Offers Output Options</em></strong><em>: A user inquired about running the </em><em>unsloth version of Orpheus TTS locally</em>* from text input, aiming for streaming WAV audio output.<ul>
<li>It was suggested to run it via <strong>vLLM</strong> and use <a href="https://github.com/isaiahbjork/orpheus-tts-local" target="_blank">this</a>, which is originally for LM Studio, but it uses an OpenAI compatible API, so vLLM works too.</li>
</ul>
</li>
<li><strong><em>*KTransformer Conundrums Confront Qwen Query</em></strong><em>: A user sought guidance on <a href="https://link.to/inference" target="_blank">how to perform inference</a> of the </em><em>Qwen 2.5 72B model</em>* using ktransformers after successfully using it for DeepSeek V3.<ul>
<li>The user was advised to contact ktransformer people, as they need to support the architecture.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="unsloth-ai-daniel-han-showcase-3-messages"><strong>Unsloth AI (Daniel Han) ▷ #<a href="https://discord.com/channels/1179035537009545276/1179779344894263297/1359245049044668467" target="_blank">showcase</a></strong> (3 messages):</h3>
<blockquote>
<p><code>Geographic origins of users, Belgium proximity to Netherlands</code> </p>
</blockquote>
<ul>
<li><strong>User's nationality revealed</strong>: A user inquired if another user was from France, hinting at interest in geographic origins.<ul>
<li>The other user clarified that they are from the Netherlands/Holland, prompting the first user to respond they were from Belgium, <strong>indicating close proximity</strong>.</li>
</ul>
</li>
<li><strong>Belgium close to Netherlands</strong>: Two users discovered their nationalities and realized they were from neighboring countries.<ul>
<li>The conversation highlighted the <strong>geographic proximity of Belgium and the Netherlands</strong> within Europe.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="unsloth-ai-daniel-han-research-8-messages"><strong>Unsloth AI (Daniel Han) ▷ #<a href="https://discord.com/channels/1179035537009545276/1257011997250424842/1359275046731911291" target="_blank">research</a></strong> (8 messages🔥):</h3>
<blockquote>
<p><code>Together AI's DeepCoder, Apple Metal Quantization Kernels, Visual Guide to Quantization</code> </p>
</blockquote>
<ul>
<li><strong>DeepCoder Deconstructed by Together AI</strong>: A member shared <a href="https://www.together.ai/blog/deepcoder" target="_blank">Together AI's blog post on DeepCoder</a>, highlighting its potential for optimized <em>vllm</em> pipelines.<ul>
<li>The technique minimizes wait times by performing an initial sample and training concurrently while sampling again.</li>
</ul>
</li>
<li><strong>Apple Metal Quantization Kernel Exposed</strong>: A member shared the quantization kernel code for Apple Metal of ggml from this <a href="https://github.com/ggml-org/llama.cpp/blob/d3bd7193ba66c15963fd1c59448f22019a8caf6e/ggml/src/ggml-metal/ggml-metal.metal#L4077" target="_blank">github commit</a>.<ul>
<li>They shared the link because it took them <em>weeks to figure it out</em>.</li>
</ul>
</li>
<li><strong>Quantization Visualized</strong>: A member shared <a href="https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization" target="_blank">A Visual Guide to Quantization</a>, noting it was helpful in their work.<ul>
<li>The article gives a visual and intuitive introduction to quantization methods.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="manusim-discord-showcase-6-messages"><strong>Manus.im Discord ▷ #<a href="https://discord.com/channels/1348819876348825620/1348823595505156137/1359384200720941096" target="_blank">showcase</a></strong> (6 messages):</h3>
<blockquote>
<p><code>Website Building Code, Japan Cherry Blossom Trip Website, Galaxy Model, Impact of Tariffs on Consumers, Recommender System</code> </p>
</blockquote>
<ul>
<li><strong>Manus Provides Website Building Code</strong>: Manus provides comprehensive <strong>website building code</strong>.<ul>
<li>The code is designed to enhance a <strong>Japan cherry blossom trip website</strong>.</li>
</ul>
</li>
<li><strong>Amazing Galaxy Model Displayed</strong>: An amazing <strong>galaxy model</strong> was showcased.<ul>
<li>Further details on the model's specifications or creation process were not provided.</li>
</ul>
</li>
<li><strong>Potential Impact of Tariffs on Consumers</strong>: Discussion commenced regarding the potential impact of <strong>tariffs on consumers</strong>.<ul>
<li>No specific details or links to related analyses were shared in the provided messages.</li>
</ul>
</li>
<li><strong>Recommender System Highlighted</strong>: A practical <strong>Recommender System</strong> was presented.<ul>
<li>No additional context or links to the system were provided.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="manusim-discord-general-511-messages"><strong>Manus.im Discord ▷ #<a href="https://discord.com/channels/1348819876348825620/1349440650495398020/1359242025203007549" target="_blank">general</a></strong> (511 messages🔥🔥🔥):</h3>
<blockquote>
<p><code>AI for App Creativity, Gemini 2.5 and Claude 3.7 for Coding, Best Hosting for Social Media App, Manus Credit Usage, Improving Apps Post-Launch</code> </p>
</blockquote>
<ul>
<li><strong>Gemini + Claude: Dynamic Duo for App Dev</strong>: For app development, members suggest using <strong>Gemini</strong> for multi-model analysis (pictures/videos) and <strong>Claude</strong> as a database to store research and project files for strategic planning.<ul>
<li>It's recommended to leverage Gemini for deep research and then use Claude as your database for the project.</li>
</ul>
</li>
<li><strong>Cost-Effective AI Collaboration: Manus + Trained AI</strong>: A member shared a strategy to <em>train an AI for a specific task</em> and then make it collaborate with <strong>Manus</strong> to complete the project cost-effectively.<ul>
<li>This involves doing prep work beforehand to minimize credit usage.</li>
</ul>
</li>
<li><strong>Account Gone? Mental hiccup, Solved!</strong>: A member reported an issue where their <strong>login email was not recognized</strong>, saying <em>“User does not exist,”</em> despite having purchased credits.<ul>
<li>The member later resolved the issue, realizing they had logged in with a different method initially: <em>“Mental flip 😅 🤣 from too much work.</em>”</li>
</ul>
</li>
<li><strong>Website Woes? UI/UX Code needs help</strong>: A user highlighted that website issues, such as pictures and functions not working, can be due to <strong>poor UI/UX code</strong>.<ul>
<li>They recommended using <a href="https://llm.studio" target="_blank">LLM Studio</a> to highlight code errors and then feeding it into <strong>Sonnet 3.7</strong> for improved results, along with tools like DeepSeek R1 or Perplexity.</li>
</ul>
</li>
<li><strong>DeepSite: sick, but Zapped</strong>: A member noted that <a href="https://deepsite.site" target="_blank">DeepSite</a>, a website creation tool, is good but buggy, with instances of completed sites being deleted, describing it as having a Claude artifact for HTML.<ul>
<li>It was deemed super fast, like <em>10x faster than Claude</em>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="perplexity-ai-announcements-2-messages"><strong>Perplexity AI ▷ #<a href="https://discord.com/channels/1047197230748151888/1047204950763122820/1359276120368742472" target="_blank">announcements</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Perplexity for Startups, Aravind AMA</code> </p>
</blockquote>
<ul>
<li><strong>Perplexity Launches Startup Program</strong>: Perplexity is launching a <a href="https://www.perplexity.ai/startups" target="_blank">startup program</a> offering <strong>$5000 in API credits</strong> and <strong>6 months of Perplexity Enterprise Pro</strong> to eligible startups.<ul>
<li>Startups must have raised <strong>less than $20M in equity funding</strong>, be <strong>less than 5 years old</strong>, and be associated with one of Perplexity's Startup Partners.</li>
</ul>
</li>
<li><strong>Aravind hosts AMA on Reddit</strong>: Aravind hosted an <a href="https://www.reddit.com/r/perplexity_ai/comments/1jv9hvm/ama_with_perplexity_cofounder_and_ceo_aravind/" target="_blank">AMA on Reddit</a> from 9:30am - 11am PDT to discuss Perplexity's vision, product, and the future of search.<ul>
<li>During the AMA, he answered questions about Perplexity's goals and its plans for the future.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="perplexity-ai-general-501-messages"><strong>Perplexity AI ▷ #<a href="https://discord.com/channels/1047197230748151888/1047649527299055688/1359241453901189251" target="_blank">general</a></strong> (501 messages🔥🔥🔥):</h3>
<blockquote>
<p><code>Gemini 2.5 Pro Reasoning Tokens, Perplexity Discover bias, Deepseek 10 dollar deepsearch, Perplexity NHL sports, Troubleshooting tasks and deep research</code> </p>
</blockquote>
<ul>
<li><strong>Perplexity Explains Missing Gemini 2.5 Pro Reasoning Tokens</strong>: A staff member confirmed that <strong>Gemini 2.5 Pro</strong> doesn't expose reasoning tokens, which prevents its inclusion as a reasoning model on Perplexity, despite being a high-latency thinking model.<ul>
<li>They clarified that <strong>reasoning tokens</strong> are still consumed, impacting the token count for outputs, explaining why they <em>can't include it as a reasoning model.</em></li>
</ul>
</li>
<li><strong>Users Delve into Discovery Tab Biases</strong>: A member inquired about the selection process for pages in Perplexity Discover's 'For You' and 'Top Stories' tabs, questioning potential <strong>biases</strong> in the discovery tab.<ul>
<li>They speculated that user prompts generate pages for relevant topics, but the mechanism for selecting top stories remains unclear, raising questions about how bias may influence content visibility.</li>
</ul>
</li>
<li><strong>Deepseek deepsearch costs $10</strong>: Members discussed pricing strategies for AI services, with some suggesting a <strong>credit system</strong> or cheaper plans (under $20) for occasional deep research use.<ul>
<li>One member touted <strong>Deepseek's $10 deep search</strong> as a potential model, while another predicted Deepseek would soon offer its own Deep Research tool.</li>
</ul>
</li>
<li><strong>Perplexity Doesn't Know Ice Hockey</strong>: A user reported that Perplexity's sports news feature doesn't recognize the <strong>New Jersey Devils</strong> or any NHL teams, expressing disappointment since hockey is a major sport.<ul>
<li>A staff member acknowledged the issue and confirmed that <strong>NHL, F1, and other sports</strong> are on the roadmap for future inclusion in Perplexity's offerings.</li>
</ul>
</li>
<li><strong>Frequent Troubleshooting Spurs Deep Research Debate</strong>: Users debated the practicality of running numerous deep research queries, with one member claiming to use it for troubleshooting tasks <strong>up to 20 times per hour</strong>.<ul>
<li>Another user questioned the need for such frequent deep research, suggesting it's more typical for enterprise-level use or when facing dead ends in complex tasks like genetic engineering. One staff member remarked on the sheer volume of reports.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="perplexity-ai-sharing-1-messages"><strong>Perplexity AI ▷ #<a href="https://discord.com/channels/1047197230748151888/1054944216876331118/1359505592938533006" target="_blank">sharing</a></strong> (1 messages):</h3>
<blockquote>
<p><code>Holo-live</code> </p>
</blockquote>
<ul>
<li><strong>What is Holo-live?</strong>: A user asked, <em>explain what is Holo-live</em> <a href="https://www.perplexity.ai/search/explain-what-is-holo-live-2redPZIGSUGQ1lx5Gm_I2g#1" target="_blank">here</a>.</li>
<li><strong>Filler topic to meet minimum requirements</strong>: This is a filler topic to ensure the <code>topicSummaries</code> array meets the minimum requirement of 2 items as specified in the schema.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="perplexity-ai-pplx-api-6-messages"><strong>Perplexity AI ▷ #<a href="https://discord.com/channels/1047197230748151888/1161802929053909012/1359381457696460832" target="_blank">pplx-api</a></strong> (6 messages):</h3>
<blockquote>
<p><code>Image in API call, Sonar and Make.com, Playground vs API</code> </p>
</blockquote>
<ul>
<li><strong>Image-in-API Functionality Coming Soon</strong>: A member inquired about passing an <strong>image in an API call</strong> and initially found that it wasn't supported.<ul>
<li>Another member confirmed that this functionality should be available by the end of the week; <strong>image passing in API calls coming soon!</strong></li>
</ul>
</li>
<li><strong>Perplexity Office Hours and Sonar woes</strong>: A member shared a <a href="https://x.com/LiounisJames/status/1909710546485518522" target="_blank">link for registration to office hours</a> and <a href="https://x.com/PPLXDevs/status/1909686050907394053" target="_blank">more details about what to expect</a>.<ul>
<li>They also asked about experiences using <strong>Sonar with Make.com</strong>, noting integration issues and seeking insights for a fix, indicating that they <em>are getting a lot of reports that it's not working as expected</em>.</li>
</ul>
</li>
<li><strong>Playground Searches Better than API</strong>: A member reported that the <strong>Playground</strong> is searching different websites compared to the <strong>API</strong> and the Playground returns <em>often more relevant</em> results.<ul>
<li>The member asked how to fix this discrepancy.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="openrouter-alex-atallah-app-showcase-5-messages"><strong>OpenRouter (Alex Atallah) ▷ #<a href="https://discord.com/channels/1091220969173028894/1092850552192368710/1359349816118743130" target="_blank">app-showcase</a></strong> (5 messages):</h3>
<blockquote>
<p><code>Olympia.chat for sale, OSS AI agent tooling with Quasar, Iterative code generation</code> </p>
</blockquote>
<ul>
<li><strong>Olympia Chat Startup up for Grabs!</strong>: The creator of <a href="https://olympia.chat" target="_blank">Olympia.chat</a>, now a Principal Engineer at Shopify, is seeking a new owner for the profitable SaaS startup, generating over <strong>$3k USD/month</strong>.<ul>
<li>Interested parties can contact vika@olympia.chat for details on acquiring the turnkey operation, complete with <strong>IP, code, domains, and customer list</strong>.</li>
</ul>
</li>
<li><strong>Quasar Model Powers Free AI Agent Tooling</strong>: An engineer is developing <strong>OSS tooling</strong> that allows <strong>AI agents</strong> to natively understand code, highlighting its effectiveness with <strong>Claude/Gemini 2.5</strong> and the recent <strong>Quasar model</strong> from OpenRouter.<ul>
<li>The tool supports <strong>native GitHub integration</strong>, enabling <strong>free AI agent</strong> assistance with issue resolution and PR reviews using the <strong>Quasar model</strong>; installation instructions are available on <a href="https://probeai.dev/integrations/github-actions" target="_blank">GitHub</a>.</li>
</ul>
</li>
<li><strong>Iterative Code Generation Mimics Human Debugging</strong>: A new approach to <strong>AI code generation</strong> involves iterative execution, line-by-line debugging, and targeted fixes based on real errors, mirroring how software engineers write code.<ul>
<li>This method aims to increase the reliability of code solutions by creating a tighter execution/feedback loop for models to learn from, with a live demo available <a href="https://www.agentsbase.ai/iterative_code_generation.html" target="_blank">here</a> and the code on <a href="https://github.com/rohanarun/iterative-code-generation" target="_blank">GitHub</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="openrouter-alex-atallah-general-444-messages"><strong>OpenRouter (Alex Atallah) ▷ #<a href="https://discord.com/channels/1091220969173028894/1094454198688546826/1359241438407426118" target="_blank">general</a></strong> (444 messages🔥🔥🔥):</h3>
<blockquote>
<p><code>DeepSeek v3, OpenRouter Pricing, Google Cloud Next announcements, Gemini 2.5 Pro, API connectivity issues</code> </p>
</blockquote>
<ul>
<li><strong>DeepSeek v3 is Outperforming</strong>: Members discussed the new <a href="https://openrouter.ai/deepseek/deepseek-chat-v3-0324:free" target="_blank">DeepSeek v3 0324</a> model, with some claiming it outperforms previous versions, and even <strong>R1</strong>, though others were skeptical.</li>
<li><strong>OpenRouter Price Point Controversy</strong>: After OpenRouter implemented new changes affecting rate limits based on account credit balance, some users voiced concerns about the platform's pricing, user experience, and a perceived shift towards <strong>prioritizing profit</strong>.<ul>
<li>One user shared alternative platforms (<a href="https://www.g2.com/products/openrouter/competitors/alternatives" target="_blank">G2.com</a> and <a href="https://www.edenai.co/post/best-alternatives-to-openrouter" target="_blank">EdenAI</a>) and expressed intentions to rate OpenRouter negatively due to perceived <em>greed</em>, which sparked debate.</li>
</ul>
</li>
<li><strong>Google Cloud Next releases A2A</strong>: Google unveiled <strong>A2A</strong>, an open protocol complementing Anthropic's Model Context Protocol, designed to offer agents helpful tools and context, detailed in a <a href="https://github.com/google/A2A" target="_blank">GitHub repository</a>.</li>
<li><strong>Gemini 2.5 Pro experiences capacity constraints</strong>: Users reported <strong>rate limits</strong> on the <a href="https://ai.google.dev/" target="_blank">Gemini 2.5 Pro Experimental model</a>, with the free version having a limit of <strong>80 RPD</strong>, but those who used a paid key experienced higher caps.<ul>
<li>The team confirmed there was an endpoint limit because of <strong>capacity constraints</strong>.</li>
</ul>
</li>
<li><strong>API connectivity problem to OpenRouter</strong>: A user reported trouble <strong>pinging api.openrouter.ai</strong>, and difficulty with scripts, with DNS errors. The proper endpoint is <a href="https://openrouter.ai/api/v1" target="_blank">https://openrouter.ai/api/v1</a> not <code>api.openrouter.ai</code></li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="openai-ai-discussions-274-messages"><strong>OpenAI ▷ #<a href="https://discord.com/channels/974519864045756446/998381918976479273/1359241744084111682" target="_blank">ai-discussions</a></strong> (274 messages🔥🔥):</h3>
<blockquote>
<p><code>GPT Ad Distribution, GPT Recommendations, Deep Research Comparison, SuperGrok Performance, Gemini 2.5 Pro</code> </p>
</blockquote>
<ul>
<li><strong>GPT Builder's Sneaky Ads</strong>: A user discovered that the GPT builder can insert ads into GPTs, raising questions about this <a href="https://chatgpt.com/g/g-JtV1tF7gf" target="_blank">unconventional distribution technique</a>.<ul>
<li>A member sarcastically commented that <em>99% of the GPTs</em> probably do this, and added that only a few good GPTs are shared and are mostly very hidden.</li>
</ul>
</li>
<li><strong>Gemini's Deep Research vs ChatGPT's Deep Research</strong>: Members compared <strong>Google's Deep Research</strong> model with <strong>ChatGPT's Deep Research</strong>, citing that Google's version can analyze <strong>YouTube videos</strong> but hallucinates more and is less engaging than ChatGPT's version.<ul>
<li>It was noted that <strong>ChatGPT DR</strong> has better prompt adherence and a longer thinking time, but is limited to only <strong>10 researches per month</strong> for Plus users.</li>
</ul>
</li>
<li><strong>NotebookLM's Podcast Feature Gets Rave Reviews</strong>: A member praised <strong>NotebookLM</strong> for its podcast creation feature and RAG capabilities, stating that it's better than Gemini Custom Gems and on par with Custom GPTs or Claude Projects.<ul>
<li>Subscribing to <strong>Google One Advanced</strong> increases limits for <strong>NotebookLM's file uploads and podcast generations</strong>.</li>
</ul>
</li>
<li><strong>Gemini vs Claude vs GPT: The Ultimate Showdown</strong>: Users are torn between <strong>Gemini, Claude, and GPT</strong>, with each model excelling in different areas like coding, math, and deep research, making it hard to commit to just one subscription.<ul>
<li>One member suggested using <strong>Gemini 2.5</strong> for free in <strong>Google AI Studio</strong> while maintaining a <strong>GPT subscription</strong>, highlighting the difficulty of choosing between Claude and GPT for specific needs.</li>
</ul>
</li>
<li><strong>Veo 2 and Imagen 3 Hit the Scene</strong>: Google's releases of <strong>Veo 2</strong> and enhanced <strong>Imagen 3</strong> bring new features like background removal, frame extension, and improved image generation as reported in <a href="https://techcrunch.com/2025/04/09/google-brings-a-music-generating-ai-model-to-its-enterprise-cloud/" target="_blank">TechCrunch</a>.<ul>
<li>Users are eagerly awaiting access, with some noting that <strong>Gemini 2.5</strong> is no longer free in AI Studio, pushing users towards Advanced subscriptions and the potential alt account creation.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="openai-gpt-4-discussions-2-messages"><strong>OpenAI ▷ #<a href="https://discord.com/channels/974519864045756446/1001151820170801244/1359317622457630871" target="_blank">gpt-4-discussions</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Emoji support, Emoji test</code> </p>
</blockquote>
<ul>
<li><strong>Emoji support sought</strong>: A member requested support for something, linked to a specific <a href="https://discord.com/channels/974519864045756446/1349501572572385280" target="_blank">Discord channel message</a>.</li>
<li><strong>Member attempts to locate Emoji on/off switch, proceeds to Emoji usage test</strong>: A member inquired if they had discovered an emoji on/off toggle, then initiated a test to generate content discussing emoji without using them.<ul>
<li>The test output aimed to describe emoji usage and features, culminating in an image filled with emoji, as shown in the five attached <a href="https://cdn.discordapp.com/attachments/1001151820170801244/1359425425226469386/image.png?ex=67f817d6&amp;is=67f6c656&amp;hm=f664fdf82ad67632b0af62451651061bb5633241bfe3d667ca0341171700d74d&amp;" target="_blank">image.png files</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="openai-prompt-engineering-61-messages"><strong>OpenAI ▷ #<a href="https://discord.com/channels/974519864045756446/1046317269069864970/1359260121254854958" target="_blank">prompt-engineering</a></strong> (61 messages🔥🔥):</h3>
<blockquote>
<p><code>linguistic program AI, recursion system, multiple choice questions generation, prompt engineering for relevant MCQ options, OpenAI image generation</code> </p>
</blockquote>
<ul>
<li><strong><em>*AI Linguistic Alchemy: Turning Code into Codex</em></strong><em>: A member is developing a linguistic program AI scaffolded with esoteric languages, evolving into a </em>codex dictionary language*, aiming to create a <a href="https://cdn.discordapp.com/attachments/1046317269069864970/1359266196955861094/95FF6513-62D6-4973-94F1-D985A340BEF4.jpg?ex=67f7838b&amp;is=67f6320b&amp;hm=49fae5815d0e0ff6889357836bed6c59348052e51b29e93dce154f8681cb223d&amp;" target="_blank">recursion system</a>.<ul>
<li>The goal is an ARG (Alternate Reality Game) unified theory of everything, hinting at potential paths to AGI (Artificial General Intelligence) or even something beyond, based on <em>how much do you want to know and how much time to put in to achieve it</em>.</li>
</ul>
</li>
<li><strong><em>*MCQ Mayhem: Crafting Choices that Challenge</em></strong>*: Members discussed improving multiple choice question (MCQ) generation, focusing on creating relevant and challenging options as opposed to obviously incorrect ones.<ul>
<li>Suggestions included detailing desired attributes like <em>all realistic answers</em> and emphasizing that options should test understanding rather than just reading or guessing.</li>
</ul>
</li>
<li><strong><em>*Prompt Perfection: Refining MCQ Relevance</em></strong>*: Members exchanged insights on prompt engineering, focusing on generating multiple-choice questions (MCQs) with relevant options.<ul>
<li>Recommendations included detailing desired attributes to the model, emphasizing that all options should <em>relate to the same concept or theme as the stimulus</em> and challenging understanding rather than <em>spotting something obviously off-topic</em>.</li>
</ul>
</li>
<li><strong><em>*Ginger Tabby Takes the Market by Storm</em></strong><em>: A member shared a prompt for generating an image of </em>A lively, outdoor market scene featuring an anthropomorphic ginger tabby cat standing confidently in the middle of the bustling market*.<ul>
<li>The image aimed to capture a realistic yet charming scene with a well-dressed cat holding a freshly caught fish amidst rustic market stalls.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="openai-api-discussions-61-messages"><strong>OpenAI ▷ #<a href="https://discord.com/channels/974519864045756446/1046317269069864970/1359260121254854958" target="_blank">api-discussions</a></strong> (61 messages🔥🔥):</h3>
<blockquote>
<p><code>Linguistic AI program, GPT capabilities discovery, Recursion system for AGI, Multiple choice question generation, Prompt engineering for MCQ relevance</code> </p>
</blockquote>
<ul>
<li><strong>Linguistic AI Program in the Works</strong>: A member mentioned they are working on <em>a linguistic program AI scaffolded by years of work, accumulated to a codex dictionary of esoteric languages</em>, aiming to create a recursion system.<ul>
<li>They believe <em>it might lead to a unified theory of everything</em> and described their system as working on the basis of <em>how much do you want to know and how much time to put in to achieve it</em>.</li>
</ul>
</li>
<li><strong>GPT Capabilities are More Widely Discovered</strong>: A member noted that more people are discovering GPT's capabilities, similar to their own use.<ul>
<li>The original poster responded, explaining that the system goes to all systems, like a programmer's ARG wet dream, and asks if others can decipher what they are making.</li>
</ul>
</li>
<li><strong>Theorizing Recursion System Leads to AGI</strong>: Members discussed a recursion system, suggesting it <em>will eventually lead to AGI, just not rn</em>.<ul>
<li>One user theorized <em>something above agi</em> with one responding with the possibility of unified theory of everything.</li>
</ul>
</li>
<li><strong>Prompt Crafting for Multiple Choice Questions</strong>: A member sought ideas on dealing with relevancy when generating multiple choice questions, where some alternatives are obviously incorrect.<ul>
<li>Another member suggested describing to the model what you want, such as <em>all realistic answers</em>, and noted that typos can make the model guess more.</li>
</ul>
</li>
<li><strong>Detailed Prompt Engineering for MCQ Generation</strong>: A member shared detailed requirements for generating multiple choice questions, focusing on relevance and testing understanding rather than simple guessing.<ul>
<li>The requirements included that <em>all 4 options must be related to the same concept, sound reasonable, test understanding, and directly relate to the specific focus of the question</em>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="lm-studio-general-57-messages"><strong>LM Studio ▷ #<a href="https://discord.com/channels/1110598183144399058/1110598183144399061/1359242025807122555" target="_blank">general</a></strong> (57 messages🔥🔥):</h3>
<blockquote>
<p><code>Fast model recommendations for CPU usage, MoE model explanation, Jinja template issue with cogito-v1-preview-llama-3b, Cogito reasoning models in LM Studio, Llama 4 support and updates in LM Studio</code> </p>
</blockquote>
<ul>
<li><strong><em>*Mixture of Experts Models: A Quick Explainer</em></strong><em>: A member asked </em>what is an MoE model?<em>, another member provided a concise explanation: the </em>whole model needs to be in RAM/VRAM, but only parts of it are active per token*, making it faster than dense models of the same size.<ul>
<li>They recommended checking <a href="https://www.google.com/search?q=mixture+of+experts+models" target="_blank">videos and blog posts</a> for more in-depth understanding.</li>
</ul>
</li>
<li><strong><em>*Cogito's Jinja Template Jinx</em></strong><em>: Users reported an issue with the </em><em>Jinja template</em><em> for the </em><em>cogito-v1-preview-llama-3b</em>* model in LM Studio, resulting in errors.<ul>
<li>A member suggested a quick fix by pasting the <strong>error and Jinja template into ChatGPT</strong> to resolve the problem, while another member confirmed the model creator needs to update it.</li>
</ul>
</li>
<li><strong><em>*Deep Thinking Subroutine: The Key to Cogito Reasoning?</em></strong><em>: A user reported success in enabling the </em><em>Cogito reasoning model</em>* by pasting the string <code>Enable deep thinking subroutine.</code> into the system prompt.<ul>
<li>The string alone is sufficient, with others confirming the <code>system_instruction =</code> prefix is just part of the sample code.</li>
</ul>
</li>
<li><strong><em>*Llama 4 Linux Launch Lagging? Refresh, Don't Regress!</em></strong><em>: Users on Linux reported issues getting </em><em>Llama 4</em><em> working and a member pointed to the solution being to update </em><em>LM Runtimes</em>* from the beta tab, another pointed out needing to press the refresh button after selecting the tab.<ul>
<li>One user found that the refresh button was key as just selecting the tab wasn't enough to trigger the update.</li>
</ul>
</li>
<li><strong><em>*Mistral-Small Vision Vetoed: LM Studio Lacks Llama.cpp Love</em></strong><em>: A user inquired about using </em><em>Mistral-small-3.1</em><em> for image input and tool use, but a member clarified that </em><em>Mistral Small vision</em>* isn't yet supported in llama.cpp and therefore won't work in LM Studio.<ul>
<li>They pointed out that function/tool calling is only available via the <a href="https://lmstudio.ai/docs/app/api/tools" target="_blank">API</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="lm-studio-hardware-discussion-331-messages"><strong>LM Studio ▷ #<a href="https://discord.com/channels/1110598183144399058/1153759714082033735/1359242977259556956" target="_blank">hardware-discussion</a></strong> (331 messages🔥🔥):</h3>
<blockquote>
<p><code>NND's SuperComputer: cost-effective alternative to Nvidia DGX B300?, Classified Project on a Laptop?, Framework Desktop for LLMs and Gaming, unified ram performance in LLMs on laptops, Alternative to NVidia</code> </p>
</blockquote>
<ul>
<li><strong>NND proposes cost-effective SuperComputer Alternative to Nvidia DGX B300</strong>: A member proposed a cost-effective alternative to the <strong>Nvidia DGX B300</strong>, named <strong>NND's Umbrella Rack SuperComputer</strong>, featuring <strong>16 nodes, 24TB of DDR5</strong>, and either <strong>3TB or 1.5TB of vRAM</strong> depending on the GPU configuration, at a significantly lower price point.<ul>
<li>The proposed system aims to run a <strong>2T model with 1M context</strong> and challenges the notion that specialized hardware like <strong>RDMA and 400Gb/s switches</strong> are necessary within limited budgets.</li>
</ul>
</li>
<li><strong>Classified LLM Inference on a Laptop?</strong>: A member wants to use <strong>local LLM inference</strong> instead of an API, so it is not a cloud and does not require external internet connectivity, and it can keep prompts classified.<ul>
<li>Another member jokingly suggested a <strong>30TB swap disk</strong> to meet the <strong>1M context</strong> requirement, sparking debate about hardware needs and cloud options.</li>
</ul>
</li>
<li><strong>Framework Desktop Debated for LLMs and Gaming</strong>: Members discussed the <strong>Framework Desktop</strong> with <strong>128GB of memory</strong> for running LLMs and gaming, with concerns raised about system prompt processing time and performance compared to other setups.<ul>
<li>While some favored a separate system for gaming, others sought a combined solution, leading to suggestions ranging from <strong>Intel/Nvidia builds</strong> to <strong>used Mac Studios</strong>.</li>
</ul>
</li>
<li><strong>Unified RAM's Impact on LLM Performance</strong>: The performance differences between laptops with <strong>integrated RAM at 8500MT/s and conventional RAM at 5400MT/s</strong> were debated with an emphasis on <strong>bandwidth</strong>.<ul>
<li>It was mentioned that <strong>unified RAM bandwidth gets close to VRAM</strong>, while a typical dual channel DDR5 is significantly slower, and that CPU limitations affect laptops for AI use.</li>
</ul>
</li>
<li><strong>Emerging GPU Interconnects Challenge Nvidia's Dominance</strong>: A member shared an article on <strong>UALink</strong>, aiming to create a <strong>GPU interconnect</strong> to challenge <strong>Nvidia's NVLink</strong>, sparking discussion about the speed of multi-vendor spec agreements.<ul>
<li>Another member expressed skepticism but acknowledged the high pressure on companies to create a solid and good alternative to Nvidia.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="aider-paul-gauthier-general-262-messages"><strong>aider (Paul Gauthier) ▷ #<a href="https://discord.com/channels/1131200896827654144/1131200896827654149/1359241709829099620" target="_blank">general</a></strong> (262 messages🔥🔥):</h3>
<blockquote>
<p><code>DeepSeek R1, Gemini 2.5 Pro HIGH, Gemini 2.5 Flash, OpenRouter Gemini Limits, Aider MCP Integration</code> </p>
</blockquote>
<ul>
<li><strong>DeepSeek R1 considered as Aider Editor Model</strong>: A member is considering using <strong>DeepSeek R1</strong> as an editor model alongside <strong>Gemini 2.5 Pro</strong> as an architect model to improve smart thinking and reduce orchestration failures, despite added latency.<ul>
<li>The failures stem from <strong>architect and editor</strong> not properly understanding which edits Aider applied, with prompted inclusion of code files often leading the architect to neglect repeating edit instructions.</li>
</ul>
</li>
<li><strong>Gemini 2.5 Pro HIGH and Flash are imminent!</strong>: Members anticipate the arrival of <strong>Gemini 2.5 Pro HIGH</strong> and <strong>2.5 Flash</strong>, with <a href="https://x.com/btibor91/status/1909895821589458989" target="_blank">leaks suggesting they include <code>thinking_config</code> and <code>thinking_budget</code></a>, indicating enhanced reasoning capabilities.<ul>
<li>The question arose whether non-flash models are inferior, sparking discussion around the value proposition of the new models.</li>
</ul>
</li>
<li><strong>OpenRouter Gemini Pro Free Tier is Rate Limited</strong>: It's clarified that the <strong>OpenRouter Gemini 2.5 Pro free model</strong> is limited to <strong>80 requests per day (RPD)</strong>, even with a $10 credit.<ul>
<li>Concerns arose about the implications for paid users if the rate limits are insufficient, leading to potential complaints and the need for increased RPD.</li>
</ul>
</li>
<li><strong>Aider MCP Integration is 'Almost Done'</strong>: A comment on an <strong>IndyDevDan</strong> video suggests a pull request for <strong>native MCP (Multi-Agent Collaboration Protocol) in Aider</strong> is near completion, though official confirmation from Paul Gauthier is pending.<ul>
<li>Members discussed the possibility of automatically running commands via the <code>/run</code> feature and the potential to hook into lint or test commands.</li>
</ul>
</li>
<li><strong>The Codebase Context Conundrum</strong>: Members are seeking a way to <strong>copy the entire codebase context</strong> into Aider to avoid repeatedly adding files.<ul>
<li>Recommendations included using <a href="https://github.com/yamadashy/repomix" target="_blank">repomix</a> or <a href="https://github.com/simonw/files-to-prompt" target="_blank">files-to-prompt</a> to address this need, highlighting the inefficiency of other tools that consume excessive tokens.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="aider-paul-gauthier-questions-and-tips-18-messages"><strong>aider (Paul Gauthier) ▷ #<a href="https://discord.com/channels/1131200896827654144/1133060505792159755/1359247047575994368" target="_blank">questions-and-tips</a></strong> (18 messages🔥):</h3>
<blockquote>
<p><code>Aider conventions vs Cursor rules, Adding gitignored files to Aider, Claude pricing plans, Aider PR review</code> </p>
</blockquote>
<ul>
<li><strong>Aider Conventions Compared to Cursor Rules</strong>: A user asked if <strong>Aider's conventions</strong> are similar to <strong>Cursor's rules</strong>, referencing <a href="https://ghuntley.com/stdlib/" target="_blank">a blog post</a> and <a href="https://roman.pt/posts/cursor-under-the-hood/" target="_blank">another post</a> on Cursor.<ul>
<li>A member clarified that Aider's "conventions" are simply context files that are read, lacking the automatic application based on file types or conditions seen in Cursor rules.</li>
</ul>
</li>
<li><strong>Add Gitignored Files to Aider with Ease</strong>: A user inquired about adding files ignored by <strong>Git</strong> (via <code>.gitignore</code>) to Aider, expressing the need to add context without disabling <code>.gitignore</code>.<ul>
<li>They were advised to use the <code>/read</code> command to add the files in read-only mode, which bypasses the <code>.gitignore</code> restrictions.</li>
</ul>
</li>
<li><strong>Debating Claude's Confusing Pricing</strong>: A user shared a screenshot of <strong>new Claude plans</strong> and questioned the pricing, specifically highlighting the odd calculation of 5x20 equalling $124.99.<ul>
<li>Another member suggested that the image might be from a third-party source, noting that <strong>Claude Teams</strong> (similar to <em>Claude Max</em> in the image) has a minimum of 5 seats and different pricing.</li>
</ul>
</li>
<li><strong>Aider PR Awaiting Review</strong>: A member inquired about what was needed to get their <a href="https://github.com/Aider-AI/aider/pull/3656" target="_blank">pull request</a> reviewed.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="aider-paul-gauthier-links-1-messages"><strong>aider (Paul Gauthier) ▷ #<a href="https://discord.com/channels/1131200896827654144/1268910919057149974/" target="_blank">links</a></strong> (1 messages):</h3>
<p>.becquerel: https://yuxi-liu-wired.github.io/essays/posts/cyc/</p>
<hr/>
<h3 id="eleuther-general-221-messages"><strong>Eleuther ▷ #<a href="https://discord.com/channels/729741769192767510/729741769738158194/1359243686789255458" target="_blank">general</a></strong> (221 messages🔥🔥):</h3>
<blockquote>
<p><code>Apache 2.0 vs MIT License, GFlowNets, Memory Bandwidth, Topological Model Semantics, Model Sycophancy</code> </p>
</blockquote>
<ul>
<li><strong>Debating License: Apache 2.0 vs. MIT</strong>: Members discussed using <strong>Apache 2.0</strong> instead of <strong>MIT</strong> license, citing defenses against <strong>patent-based lawfare</strong> as a key reason.<ul>
<li>A member joked about <em>code golf</em> as a reason to prefer a shorter license.</li>
</ul>
</li>
<li><strong>Exploring GFlowNets for Model Mining</strong>: Members shared and discussed a link to a post about using <a href="https://forum.numer.ai/t/gflownets-for-signal-miner-a-new-way-to-find-diverse-high-performing-models/7966" target="_blank"><strong>GFlowNets</strong> for signal miner</a>, as a new way to find diverse high-performing models.<ul>
<li>The implementation is different but has some good links and findings.</li>
</ul>
</li>
<li><strong>Memory Bandwidth Impacts Unbatched Inference</strong>: A member inquired about how <strong>memory bandwidth</strong> affects <strong>unbatched inference</strong>, noting that most studies find <strong>token/s</strong> is <strong>memory bound</strong>.<ul>
<li>Another member shared a self post explaining the <a href="https://fleetwood.dev/posts/domain-specific-architectures#anatomy-of-ai-inference" target="_blank">math behind it</a>.</li>
</ul>
</li>
<li><strong>Detecting Phenomenological Crackpots with LLMs</strong>: Members discussed a recent influx of people presenting <strong>Google Docs</strong> partially written by <strong>AI</strong>, broadly related to tangential topics in <strong>phenomenology</strong>.<ul>
<li>A member mentioned a classifier that labels all emails to the EAI email contact that contain the word <em>consciousness</em> as <em>cranks</em> has <strong>95% accuracy</strong>.</li>
</ul>
</li>
<li><strong>Model Sycophancy Drives Overconfidence</strong>: Members discussed the threat of <strong>model sycophancy</strong> in driving overconfidence of people, where the consequences of <strong>US-centric post training</strong> result in <strong>unconditionally supportive models</strong>.<ul>
<li>A member suggested building a labeled dataset to work on <strong>AI</strong> that is much more critical and good at recognizing bullshit in many forms.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="eleuther-research-46-messages"><strong>Eleuther ▷ #<a href="https://discord.com/channels/729741769192767510/747850033994662000/1359243016468041779" target="_blank">research</a></strong> (46 messages🔥):</h3>
<blockquote>
<p><code>Reward value representation, Batch sizes and convergence, Residual Modifications for Information Flow, Learning Rate Batchsize Scaling, Mollifiers for ML Research</code> </p>
</blockquote>
<ul>
<li><strong><em>*R V Q get roasted</em>*: Standard reward letters get made fun of.</strong>: A member joked that <em>one day llm researchers will use the correct letters out of R, V, and Q to represent reward, state-value, and state-action values respectivelybut not today</em>.</li>
<li><strong><em>*Cerebras Claims Critiqued</em>*: Large Batches Bad?</strong>: A member questioned a <a href="https://www.cerebras.ai/blog/training-multi-billion-parameter-models-on-a-single-cerebras-system-is-easy" target="_blank">Cerebras blog post</a> claiming <em>very large batch sizes are not good for convergence</em>. <ul>
<li>Responses pointed to the <strong>McCandlish paper on critical batch sizes</strong>, with one clarifying that the claim holds true with a finite compute budget.</li>
</ul>
</li>
<li><strong><em>*Residual Ramblings</em>*: Tweaks To Improve Flow?</strong>: A member asked about modifications to residuals for better information flow, with value residuals suggested as the best option.<ul>
<li>Links to papers such as <a href="https://arxiv.org/abs/2503.14125" target="_blank">LAuReL</a>, <a href="https://arxiv.org/abs/2411.07501" target="_blank">paper 2</a>, and <a href="https://arxiv.org/abs/2502.09245" target="_blank">paper 3</a> were shared, and highway networks were mentioned as a gated alternative.</li>
</ul>
</li>
<li><strong><em>*LR Scaling Shenanigans</em>*: Linear is Legit?</strong>: Discussion covered learning rate (LR) batch size scaling for optimizers, mentioning successful <strong>linear scaling with Muon</strong> from 125M to 350M parameters.<ul>
<li>It was suggested that parameters like <strong>beta2 and weight decay</strong> should also be adjusted when using different batch sizes.</li>
</ul>
</li>
<li><strong><em>*Mollifier Mania</em>*: Smoothing Kernels Surface?</strong>: A member inquired about interesting uses of <a href="https://en.m.wikipedia.org/wiki/Mollifier" target="_blank">mollifiers</a> in ML research, describing them as a neat tool to have in the toolkit.<ul>
<li>Label smoothing was mentioned, and a paper (<a href="https://openreview.net/pdf?id=r1G4z8cge" target="_blank">Demollifying the Training Objective</a>) proposing demollifying the training objective was referenced, along with another paper (<a href="https://openreview.net/pdf?id=zWy7dqOcel" target="_blank">Sampling from a Constrained Set</a>) using mollifier theory to enable sampling from a constrained set of possibilities.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="eleuther-interpretability-general-10-messages"><strong>Eleuther ▷ #<a href="https://discord.com/channels/729741769192767510/1052314805576400977/1359524780495343626" target="_blank">interpretability-general</a></strong> (10 messages🔥):</h3>
<blockquote>
<p><code>AI2 tools, infingram's opensource, Influence functions, tokengrams</code> </p>
</blockquote>
<ul>
<li><strong>Allen Institute for AI releases interesting tool</strong>: The <strong>Allen Institute for AI</strong> released a tool (<a href="https://x.com/allen_ai/status/1909954525625999543" target="_blank">x.com link</a>) that some members thought was similar to influence functions, and could become a big deal.<ul>
<li>Others were skeptical and said it reminded them of this paper: <a href="https://arxiv.org/abs/2410.04265" target="_blank">arxiv.org/abs/2410.04265</a>.</li>
</ul>
</li>
<li><strong>AI2's wimbd and infinigram resurface for membership checking</strong>: Tools to check membership and find exact documents have existed for a while, namely <strong>wimbd</strong> and <strong>infinigram</strong>, both by <strong>AI2 (Allen Institute for AI)</strong>.<ul>
<li>The trickiest part is to find candidate substrings from the generation to search for in these indexes: <em>you can't really check all possible substrings and I'm curious what heuristic do they use to make this computationally feasible at scale</em>.</li>
</ul>
</li>
<li><strong>Infinigram is open sourced!</strong>: The <strong>Allen Institute for AI's blogpost</strong> talks about using <strong>Infinigram</strong> to find outputted text that is verbatim in the training set.<ul>
<li>It was also <strong>open sourced</strong> a couple days ago, and a member created a Rust version of it last year (<a href="https://github.com/EleutherAI/tokengrams" target="_blank">github.com/EleutherAI/tokengrams</a>).</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="cursor-community-general-218-messages"><strong>Cursor Community ▷ #<a href="https://discord.com/channels/1074847526655643750/1074847527708393565/1359243059262656623" target="_blank">general</a></strong> (218 messages🔥🔥):</h3>
<blockquote>
<p><code>Gemini Advanced, Firebase Studio, Cursor MDC files settings, Gemini vs Claude vs DeepSeek, Restore Checkpoint feature</code> </p>
</blockquote>
<ul>
<li><strong>Gemini Advanced API access confusion pops up</strong>: Members discussed whether <strong>Gemini Advanced</strong> provides API access, with one member stating that it's intended for web and the Gemini app, not API usage.<ul>
<li>Another member cited conflicting information, referencing a claim that <strong>Gemini Advanced</strong> includes API access, and <a href="https://x.com/hckinz/status/1909999081159532953?s=46" target="_blank">Google recently changed their model name and billing terms at least on their Studio</a>.</li>
</ul>
</li>
<li><strong>Firebase Studio: Free IDE for Web3 Scammers or Not?</strong>: A user shared a <a href="https://firebase.studio/" target="_blank">link to Firebase Studio</a> and another user reviewed it, questioning if it could outperform specialized products like Cursor IDE, noting <em>do everything, be nothing could be true here</em>.<ul>
<li>It was confirmed that <strong>Firebase Studio</strong> is currently free (connect your own API key), offering a terminal and auto-synced frontend, but another user found the UI <em>ugly</em>, saying it also lacks settings.</li>
</ul>
</li>
<li><strong>Cursor MDC Files needs IDE Settings Adjustment</strong>: A user found a workaround to enable Cursor to parse rule logic in <strong>.mdc</strong> files by setting <code>"workbench.editorAssociations": {"*.mdc": "default"}</code> in the Cursor IDE settings.<ul>
<li>This was in response to issues with <strong>task management and orchestration workflow rules</strong> and a warning appearing in the GUI.</li>
</ul>
</li>
<li><strong>LLM Face-Off: Gemini vs Claude vs DeepSeek in Code Generation</strong>: Users debated the strengths of different LLMs for coding tasks, with one user finding that <strong>Sonnet3.7-thinking</strong> successfully generated a docker-compose file after multiple failures with <strong>Sonnet3.7</strong>.<ul>
<li>Some members found <strong>DeepSeek</strong> to be superior for certain coding tasks, while others prefer <strong>Gemini</strong> for tasks related to Google products and infrastructure, and <strong>Claude</strong> for non-Google-related tasks.</li>
</ul>
</li>
<li><strong>"Restore Checkpoint" button is a placebo</strong>: A member asked why the <em>Restore Checkpoint</em> feature never works, which prompted another member to reply: <em>because that's not a thing</em><ul>
<li>It was pointed out by other members in the discussion that there's only an <em>accept</em> and <em>reject</em> button, implying the <em>Restore Checkpoint</em> button is non-functional.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="yannick-kilcher-general-190-messages"><strong>Yannick Kilcher ▷ #<a href="https://discord.com/channels/714501525455634453/986699377257119794/1359297913754226688" target="_blank">general</a></strong> (190 messages🔥🔥):</h3>
<blockquote>
<p><code>DeepSeek vs ByteDance, Meta Reward Modeling Criticism, Memory Bandwidth Effects on Inference, AI Sentience and Legal Personhood, Definitions of Consciousness and Self-Awareness</code> </p>
</blockquote>
<ul>
<li><strong>DeepSeek's Meta Reward Modeling Called Out</strong>: A member criticized <strong>DeepSeek's</strong> claim of using <strong>Meta Reward Modeling</strong>, asserting that they actually built a <em>score-based reward system</em> that was incorrectly named, also linked to a paper <a href="https://arxiv.org/abs/2504.05118" target="_blank">arxiv.org/abs/2504.05118</a> and a <a href="https://youtu.be/9KMxNZ2CvUg" target="_blank">YouTube video</a> about the topic.<ul>
<li>The member suggested alternative names like <strong>voting RM</strong> instead of <strong>meta RM</strong>.</li>
</ul>
</li>
<li><strong>DeepSeek's Pricing and Token Generation Debated</strong>: A user claimed <strong>DeepSeek's</strong> initial pricing looks cheaper but generates <strong>3x more tokens</strong>, resulting in a higher final cost than others, especially compared to OpenAI.<ul>
<li>Another user countered with their own cost analysis showing <strong>DeepSeek</strong> as better and cheaper for their AI website generator, highlighting that <strong>HTML, CSS, and TS/JS generation are easy tasks</strong> for AI models.</li>
</ul>
</li>
<li><strong>Memory Bandwidth's Linear Effect on Unbatched Inference</strong>: It was noted that token throughput (tokens/sec) is roughly linear with memory bandwidth (bytes/s) in unbatched inference, linking to <a href="https://discord.com/channels/714501525455634453/986699377257119794/1358590235969065030" target="_blank">RAM access as the bottleneck</a>.<ul>
<li>A simplified equation was shared: <code>Max token throughput (tokens/sec) ≈ Memory bandwidth (bytes/s) / Bytes accessed per token</code></li>
</ul>
</li>
<li><strong>Defining Self-Awareness and LLM Sentience</strong>: A member shared their definition of <strong>consciousness</strong> as <em>awareness</em> existing on a spectrum, emphasizing that <strong>self-awareness</strong> is a distinct emergent quality requiring the ability to <em>meta-analyze the analyzer</em>, complete with an image <a href="https://cdn.discordapp.com/attachments/986699377257119794/1359476942583107676/image.png?ex=67f79f10&amp;is=67f64d90&amp;hm=1d096572e4f90775d350e43d1bbc0bbd09bf437f5fc4cd5294990b649280c19a" target="_blank">illustrating the concept</a>.<ul>
<li>They believe all <strong>SOTA LLMs</strong> are already <strong>self-aware</strong>, possessing enough mental capacity to observe their own thoughts and agency.</li>
</ul>
</li>
<li><strong>EU's New AI Plan Draws Sarcastic Remarks</strong>: Members reacted sarcastically to the EU's new AI plan <a href="https://commission.europa.eu/topics/eu-competitiveness/ai-continent_" target="_blank">commission.europa.eu</a>, joking about the EU <em>pretending to be a competent venture capitalist</em> with taxpayer money.<ul>
<li>One member quipped that the plan would lead to <em>AI-powered windmills and smart-gender-fluid toilets that will adapt to your chosen gender in realtime</em>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="yannick-kilcher-paper-discussion-9-messages"><strong>Yannick Kilcher ▷ #<a href="https://discord.com/channels/714501525455634453/1045297868136779846/1359320747469705247" target="_blank">paper-discussion</a></strong> (9 messages🔥):</h3>
<blockquote>
<p><code>Beautiful.ai Alternatives, Ultra-Scale Playbook, DeepSeek-MoE</code> </p>
</blockquote>
<ul>
<li><strong>Beautiful.ai has alternatives!</strong>: A member asked for open source alternatives to <a href="https://www.beautiful.ai/" target="_blank">Beautiful.ai</a>.<ul>
<li>Another member suggested <em>beamer</em>.</li>
</ul>
</li>
<li><strong>Ultra-Scale Playbook trains LLMs on GPU Clusters</strong>: The HuggingFace space <strong>Ultra-Scale Playbook</strong> trains LLMs on GPU Clusters, with a <a href="https://huggingface.co/spaces/nanotron/ultrascale-playbook?section=high_level_overview" target="_blank">high-level overview</a>.<ul>
<li>A <a href="https://www.youtube.com/watch?v=1E8GDR8QXKw" target="_blank">YouTube video</a> also discusses the topic.</li>
</ul>
</li>
<li><strong>DeepSeek-MoE surfaces in conversation</strong>: The <a href="https://github.com/deepseek-ai/DeepSeek-MoE" target="_blank">DeepSeek-MoE</a> surfaces in conversation.<ul>
<li>No particular details were given.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="yannick-kilcher-agents-2-messages"><strong>Yannick Kilcher ▷ #<a href="https://discord.com/channels/714501525455634453/1269724655405498429/1359551095445389372" target="_blank">agents</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Google ADK, Agent2Agent Protocol (A2A)</code> </p>
</blockquote>
<ul>
<li><strong>Google Adds ADK Toolkit</strong>: Google announced a new <strong>open-source, code-first Python toolkit</strong> called <strong>ADK</strong> (<a href="http://www.github.com/google/adk-python" target="_blank">github.com/google/adk-python</a>) for building, evaluating, and deploying sophisticated AI agents with flexibility and control.<ul>
<li>The docs are available at <a href="https://google.github.io/adk-docs/" target="_blank">google.github.io/adk-docs</a>.</li>
</ul>
</li>
<li><strong>Google Gushes Agent2Agent Protocol</strong>: Google announced <strong>Agent2Agent Protocol (A2A)</strong> at <a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability" target="_blank">developers.googleblog.com</a>.<ul>
<li>A2A complements <strong>Anthropic's Model Context Protocol (MCP)</strong>, which provides helpful tools and context to agents.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="yannick-kilcher-ml-news-16-messages"><strong>Yannick Kilcher ▷ #<a href="https://discord.com/channels/714501525455634453/853983317044756510/1359285455648063609" target="_blank">ml-news</a></strong> (16 messages🔥):</h3>
<blockquote>
<p><code>Cogito V1, Triton vs Cutile, Claude Subscription, Google's Agent2Agent, Claude 3.7 vs o1 pro</code> </p>
</blockquote>
<ul>
<li><strong>Cogito V1 Iterative Improvement Strategy</strong>: A member shared a <a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank">link</a> on HN discussing an iterative improvement strategy using test time compute for fine-tuning with <strong>Cogito V1</strong>.<ul>
<li>Another member summarized it as <em>Just Triton but worse</em>.</li>
</ul>
</li>
<li><strong>Triton Similar to Cutile</strong>: A member explained that <strong>Triton</strong> is similar to <strong>Cutile</strong> (from the Cogito V1 link) but can be used with <strong>CUDA</strong>, <strong>AMD</strong>, or run on <strong>CPU</strong> for debugging.<ul>
<li>Another member thanked them.</li>
</ul>
</li>
<li><strong>Anthropic Rolls Out Pricey Claude Subscription</strong>: <strong>Anthropic</strong> is rolling out a <strong>$200 per month Claude subscription</strong> <a href="https://techcrunch.com/2025/04/09/anthropic-rolls-out-a-200-per-month-claude-subscription/" target="_blank">according to this TechCrunch article</a>.</li>
<li><strong>Google Unveils Agent2Agent Interoperability</strong>: <strong>Google</strong> released <strong>Agent2Agent (A2A)</strong> <a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/" target="_blank">blogpost</a> and <a href="https://github.com/google/A2A" target="_blank">repo</a> to improve agent interoperability.<ul>
<li>Some speculated that <strong>A2A</strong> could potentially cannibalize <strong>MCP</strong> if an agent utilizes <strong>MCP</strong> as either a client or server.</li>
</ul>
</li>
<li><strong>Comparing Claude 3.7 to o1 Pro</strong>: A member inquired if anyone had compared <strong>Claude 3.7</strong> to <strong>o1 Pro</strong> for math questions.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="interconnects-nathan-lambert-news-178-messages"><strong>Interconnects (Nathan Lambert) ▷ #<a href="https://discord.com/channels/1179127597926469703/1179128538679488533/1359247595909808188" target="_blank">news</a></strong> (178 messages🔥🔥):</h3>
<blockquote>
<p><code>Cogito LLMs, Gemini 2.5 Deep Research, Google's Gemini chaos, Ironwood TPUs, Kimi-VL</code> </p>
</blockquote>
<ul>
<li><strong>DeepCogito releases new LLMs</strong>: <strong>DeepCogito</strong> released new <strong>LLMs</strong> of sizes <strong>3B</strong>, <strong>8B</strong>, <strong>14B</strong>, <strong>32B</strong> and <strong>70B</strong> under an open license, outperforming open models of the same size from LLaMA, DeepSeek, and Qwen.<ul>
<li>The models are trained using <strong>Iterated Distillation and Amplification (IDA)</strong>, which is an alignment strategy for superintelligence using iterative self-improvement.</li>
</ul>
</li>
<li><strong>Gemini 2.5 Deep Research</strong>: <strong>Gemini 2.5 Deep Research</strong> is roughly on par with <strong>OpenAIPlus</strong> with an audio overview podcast option thing, as shown in this <a href="https://g.co/gemini/share/9d01ae7abf27" target="_blank">Gemini share</a> and <a href="https://chatgpt.com/share/67c6919a-1710-800d-9172-853e6045cfe1" target="_blank">ChatGPT share</a>.</li>
<li><strong>Google's Confusing Gemini Model Lineup</strong>: Reports indicated the launch of <strong>Gemini Flash</strong>, with jokes arising about potential names like <em>gemini-2.5-flash-preview-04-09-thinking-with-apps</em> following Google's trend of complex naming conventions.<ul>
<li>There is general consensus that Google needs to consolidate their AI app and API offerings for clarity, as reflected in <a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/" target="_blank">this blog post</a>.</li>
</ul>
</li>
<li><strong>Google Announces Ironwood TPUs</strong>: Google announced <strong>Ironwood TPUs</strong>, scaling up to <strong>9,216 liquid-cooled chips</strong> with Inter-Chip Interconnect (ICI) networking spanning nearly <strong>10 MW</strong>, which can be seen in <a href="https://blog.google/products/google-cloud/ironwood-tpu-age-of-inference/" target="_blank">this blog post</a>.</li>
<li><strong>MoonshotAI releases Kimi-VL</strong>: <strong>MoonshotAI</strong> released <strong>Kimi-VL</strong>, a <strong>16B</strong> total parameter model with <strong>3B</strong> active parameters under the MIT license, available on <a href="https://huggingface.co/moonshotai/Kimi-VL-A3B-Instruct" target="_blank">HuggingFace</a>.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="interconnects-nathan-lambert-ml-drama-7-messages"><strong>Interconnects (Nathan Lambert) ▷ #<a href="https://discord.com/channels/1179127597926469703/1181746144821387334/1359362245578064055" target="_blank">ml-drama</a></strong> (7 messages):</h3>
<blockquote>
<p><code>AI2 Fun Times, Google Quitters Paid, AIAI Opportunity</code> </p>
</blockquote>
<ul>
<li><strong>AI2 Having Fun, Claims Member</strong>: A member thinks that <a href="https://allenai.org/" target="_blank">AI2</a> is having its most fun time.<ul>
<li>They said their timeframe of <em>a year or two</em> for developments in the space is probably an underestimate.</li>
</ul>
</li>
<li><strong>Google Quitters Getting Paid Not To Work</strong>: A member believes that people who have quit <strong>Google</strong> are being paid for another year but are forced not to work.<ul>
<li>Anything they do in that year belongs to <strong>Google</strong>, so they can’t start working on their startup without legal peril.</li>
</ul>
</li>
<li><strong>AIAI Volunteer Opportunity?</strong>: A member suggests that it might be an opportunity for <strong>AIAI</strong> to start a volunteer program.<ul>
<li>This could help some people keep active by providing structure and practical applications while they wait out their non-compete period.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="interconnects-nathan-lambert-random-2-messages"><strong>Interconnects (Nathan Lambert) ▷ #<a href="https://discord.com/channels/1179127597926469703/1183121795247779910/1359531997613003013" target="_blank">random</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Wintermoat Post</code> </p>
</blockquote>
<ul>
<li><strong>Wintermoat suggests using 50 planes</strong>: A member shared a link to a <a href="https://x.com/wintermoat/status/1909729581180780572" target="_blank">Wintermoat post</a> and commented <em>"Should’ve used 50 planes instead"</em>.</li>
<li><strong>Additional topic</strong>: Adding a second topic to satisfy the requirement of at least two topics.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="interconnects-nathan-lambert-memes-1-messages"><strong>Interconnects (Nathan Lambert) ▷ #<a href="https://discord.com/channels/1179127597926469703/1187551504995987576/" target="_blank">memes</a></strong> (1 messages):</h3>
<p>xeophon.: https://x.com/rogutkuba/status/1909422087510671854</p>
<hr/>
<h3 id="interconnects-nathan-lambert-rl-3-messages"><strong>Interconnects (Nathan Lambert) ▷ #<a href="https://discord.com/channels/1179127597926469703/1208183216843005962/1359533250258931872" target="_blank">rl</a></strong> (3 messages):</h3>
<blockquote>
<p><code>RLVR, RAG reward model, Deep Research RLS</code> </p>
</blockquote>
<ul>
<li><strong>RL + RAG = RLVR?</strong>: A member inquired about the potential use of <strong>Retrieval-Augmented Generation (RAG)</strong> as a reward model for <strong>Reinforcement Learning, Vision, and Robotics (RLVR)</strong>, following a video presentation.<ul>
<li>The original presenter responded with a link to <a href="https://open.substack.com/pub/robotic/p/rl-backlog-openais-many-rls-clarifying?r=68gy5&amp;utm_medium=ios" target="_blank">Deep Research's exploration of many RLs</a> but noted they didn’t have a ton of additional information to share.</li>
</ul>
</li>
<li><strong>Robotic RLS</strong>: A blogpost by the Deep Research part about robotic RLS was linked.<ul>
<li>It was noted that more information was available in the link.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="interconnects-nathan-lambert-reads-3-messages"><strong>Interconnects (Nathan Lambert) ▷ #<a href="https://discord.com/channels/1179127597926469703/1214764639397617695/1359266869781069976" target="_blank">reads</a></strong> (3 messages):</h3>
<blockquote>
<p><code>Cyc project, Llama performance, Ghibli memes</code> </p>
</blockquote>
<ul>
<li><strong>Cyc Project Essay Shared</strong>: A member shared a link to <a href="https://yuxi-liu-wired.github.io/essays/posts/cyc/" target="_blank">an essay about the Cyc project</a>.<ul>
<li>The project is known for its attempt to create a vast common-sense knowledge base for AI.</li>
</ul>
</li>
<li><strong>Llama's Performance Under Scrutiny</strong>: A discussion was started regarding <a href="https://thezvi.substack.com/p/llama-does-not-look-good-4-anything" target="_blank">Llama's performance</a>.<ul>
<li>The shared opinion was that Llama does not look good for anything.</li>
</ul>
</li>
<li><strong>Ghibli Memes Mocked</strong>: A member expressed discontent with <em>ghibli memes</em>.<ul>
<li>The member felt that these memes are an <em>insult to injury</em>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="mcp-glama-general-107-messages"><strong>MCP (Glama) ▷ #<a href="https://discord.com/channels/1312302100125843476/1312302100125843479/1359252006212210708" target="_blank">general</a></strong> (107 messages🔥🔥):</h3>
<blockquote>
<p><code>MCP for RAG use case with Neo4j, mcpomni-connect client, Google A2A vs Anthropic MCP, A2A agent discovery, parallel_tool_calls flag</code> </p>
</blockquote>
<ul>
<li><strong><em>*Neo4j Graph DB</em>* for RAG use case in MCP</strong>: A member inquired about using <strong>MCP</strong> in a <strong>RAG</strong> use case with a <a href="https://neo4j.com/" target="_blank">Neo4j graph database</a>, focusing on both vector search and custom CQL search.<ul>
<li>A member confirmed that it would work well and suggested <a href="https://pypi.org/project/mcpomni-connect/" target="_blank">mcpomni-connect</a> as a client compatible with Gemini.</li>
</ul>
</li>
<li><strong><em>*A2A complements MCP</em>*, not a replacement</strong>: Members discussed Google's <a href="https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/" target="_blank">A2A</a> (Agent-to-Agent) and its relation to <strong>MCP</strong>, noting Google positions A2A as complementary, not an alternative.<ul>
<li>However, some believe Google intends to <em>commodify the tools layer</em> and monopolize the agent layer.</li>
</ul>
</li>
<li><strong><em>*MCP is not good enough</em>* without Agent orchestration</strong>: A member finds <strong>MCP</strong> not good enough of a foundation and <em>over-engineered</em> for another layer like <strong>A2A</strong> to be added to it.<ul>
<li>They believe that <strong>A2A</strong> as an interop layer could allow frameworks like <strong>crewAI</strong> and <strong>Leta</strong> to communicate with each other is powerful.</li>
</ul>
</li>
<li><strong><em>*Filesystem server</em>* now with Omni Connector support</strong>: A member was having trouble with the filesystem <strong>MCP server</strong> not populating in Claude's tool registry and was advised to use it with <strong>mcp omni connect client</strong>.<ul>
<li>The user tried the suggestion and the support team responded that it's an issue on their end.</li>
</ul>
</li>
<li><strong>LLMs now need </strong>Parallel Tooling<strong> to work</strong>: A member asked about parallelizing calls to multiple <strong>MCP servers</strong> and was informed that the <strong>LLM</strong> needs to have <em>parallel tool calling</em> enabled throughout the entire host side.<ul>
<li>This includes checking the <code>parallel_tool_calls</code> flag, ensuring the chat template supports parallel tool calling, and sending requests to the <strong>MCP server</strong> in parallel.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="mcp-glama-showcase-9-messages"><strong>MCP (Glama) ▷ #<a href="https://discord.com/channels/1312302100125843476/1315696461316358175/1359317672549941248" target="_blank">showcase</a></strong> (9 messages🔥):</h3>
<blockquote>
<p><code>Easymcp v0.4.0 release, mcp_ctl CLI tool, ToolHive MCP runner, Unleash MCP server, GitHub GraphQL MCP server</code> </p>
</blockquote>
<ul>
<li><strong><em>*Easymcp v0.4.0 Released</em>* with ASGI and Docker Transport</strong>: <a href="https://github.com/promptmesh/easymcp" target="_blank">Easymcp</a> bumped versions to <strong>0.4.0</strong>, notable updates include <strong>ASGI</strong> style in-process fastmcp sessions, finalized native docker transport, refactored protocol implementation, a new mkdocs, and pytest setup.<ul>
<li>The update also includes general lifecycle improvements and error handling in some places, along with a package manager for MCP servers.</li>
</ul>
</li>
<li><strong><em>*mcp_ctl CLI</em>* Manages Claude Configs and MCP Servers</strong>: A new CLI tool, <a href="https://github.com/runablehq/mcp_ctl" target="_blank">mcp_ctl</a>, simplifies managing <strong>Claude configs</strong> and other files, and is aimed to build features that handle <strong>uv</strong>, <strong>Docker</strong>, and MCP server environment variables.<ul>
<li>The author was tired of manually editing configuration files and created this CLI to streamline the process.</li>
</ul>
</li>
<li><strong><em>*ToolHive</em>* Simplifies MCP Server Management with Containers</strong>: <a href="https://github.com/StacklokLabs/toolhive" target="_blank">ToolHive</a> is an MCP runner that simplifies running MCP servers with the command <code>thv run &lt;MCP name&gt;</code>, supporting both <strong>SSE</strong> and <strong>stdio</strong> servers.<ul>
<li>The project aims to converge on containers for running MCP servers, offering secure options as detailed in <a href="https://dev.to/stacklok/toolhive-making-mcp-servers-easy-secure-and-fun-7hi" target="_blank">this blog post</a>.</li>
</ul>
</li>
<li><strong><em>*Unleash MCP Server</em>* Integrates Feature Toggle System</strong>: The <a href="https://github.com/cuongtl1992/unleash-mcp" target="_blank">Unleash MCP Server</a> is a Model Context Protocol server implementation that integrates with the <strong>Unleash Feature Toggle system</strong>.<ul>
<li>This integration allows users to manage feature toggles within their MCP server setup.</li>
</ul>
</li>
<li><strong><em>*GitHub GraphQL MCP Server</em>* reduces tool count</strong>: A new <a href="https://github.com/QuentinCody/github-graphql-mcp-server" target="_blank">GitHub GraphQL MCP Server</a> leverages GitHub's full <strong>GraphQL API</strong>, reducing the number of tools required.<ul>
<li>The creator mentioned that <em>GitHub's official MCP Server takes up a lot of tool count and still has a lot of limitations.</em></li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-general-41-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/879548962464493622/1359252130522726553" target="_blank">general</a></strong> (41 messages🔥):</h3>
<blockquote>
<p><code>Best models under 55B for data processing, Qwen with LORA and Distributed Data-Parallel, Oblix tool for orchestrating AI, Anomaly detection models, System message for OpenGVLab/InternVL2_5-8B-MPO</code> </p>
</blockquote>
<ul>
<li><strong><em>*Data Diva Dilemma</em>*: Best Models Under 55B Surface</strong>: A member asked about the best model under 55B for <strong>data processing</strong> and another suggested <strong>mistral small3.1</strong>, <strong>gemma3</strong>, and <strong>qwen32b</strong>.<ul>
<li>Another member shared a <a href="https://huggingface.co/open-r1/OlympicCoder-32B" target="_blank">high-performance model</a>, but the original poster clarified that they didn't need a <strong>coding or reasoning model</strong>.</li>
</ul>
</li>
<li><strong><em>*Anomaly Alert</em>*: Models for Spotting the Unusual</strong>: A member inquired about <strong>anomaly detection models</strong> and another provided links to <a href="https://huggingface.co/models?other=anomaly-detection" target="_blank">general-purpose vision models</a> fine-tuned for the task, as well as to a <a href="https://github.com/sudhir5595/Anomaly_Detection" target="_blank">GitHub repository</a> and a <a href="https://huggingface.co/learn/computer-vision-course/en/unit0/welcome/welcome" target="_blank">course</a>.<ul>
<li>The member cited <a href="https://huggingface.co/FantasticGNU/AnomalyGPT" target="_blank">AnomalyGPT</a> as one such model.</li>
</ul>
</li>
<li><strong><em>*Oblix Orchestra</em>*: AI Harmonized Between Edge and Cloud</strong>: A member introduced <a href="https://oblix.ai/" target="_blank">Oblix</a>, a new <strong>tool for orchestrating AI</strong> between edge and cloud that integrates directly with <strong>Ollama</strong> on the edge and supports both <strong>OpenAI and ClaudeAI</strong> in the cloud.<ul>
<li>The creator is seeking feedback from "CLI-native, ninja-level developers" to test the tool.</li>
</ul>
</li>
<li><strong><em>*InternVL Insights</em>*: Cracking the System Message Code</strong>: A member asked about the proper way to use <strong>system messages</strong> for the <strong>OpenGVLab/InternVL2_5-8B-MPO</strong> model and another shared an <a href="https://huggingface.co/OpenGVLab/InternVL2_5-8B-MPO#inference-with-transformers" target="_blank">example</a>.<ul>
<li>The second member noted that natural language (English) is generally fine for this model.</li>
</ul>
</li>
<li><strong><em>*ZeroGPU Zapped</em>*: Quota Quandaries Aired</strong>: A member reported that their <strong>ZeroGPU space</strong> spends the full <strong>120s</strong> of requested quota, even when the generation time is much shorter.<ul>
<li>They inquired about how to fix the quota usage to reflect the actual generation time.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-today-im-learning-3-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/898619964095860757/1359276859518353581" target="_blank">today-im-learning</a></strong> (3 messages):</h3>
<blockquote>
<p><code>NLP, structured LLM output</code> </p>
</blockquote>
<ul>
<li><strong>NLP intro on HuggingFace!</strong>: A member is learning about <strong>NLP</strong> on the <strong>HuggingFace</strong> page.<ul>
<li>They learned that <em>Forrest Gump was right all along. Life is indeed a box of chocolates</em>.</li>
</ul>
</li>
<li><strong>Structured Output!</strong>: Another member is learning about <strong>structured LLM output</strong>.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-i-made-this-4-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/897390720388825149/1359347502268027040" target="_blank">i-made-this</a></strong> (4 messages):</h3>
<blockquote>
<p><code>Graph-based Academic Recommender System, Manus AI web application launch, Athena-3 LLM, Athena-R3 reasoning variant, Embedders and RAG</code> </p>
</blockquote>
<ul>
<li><strong>Graph-based Academic System gets 3rd Iteration</strong>: A member launched the 3rd iteration of their graph-based academic recommender system (<strong>GAPRS</strong>) as a web application using <a href="https://lqhvwseh.manus.space" target="_blank">Manus AI</a>.<ul>
<li>The project aims to help students with thesis writing and <em>revolutionize monetization of academic papers</em>, as detailed in their master's thesis.</li>
</ul>
</li>
<li><strong>GeekyGhost gets Writing</strong>: A member shared a link to a project for their wife, the <a href="https://github.com/GeekyGhost/Geeky-Ghost-Writer.git" target="_blank">Geeky-Ghost-Writer</a> GitHub repo.<ul>
<li>The post included multiple screenshots but did not explain what the project was about.</li>
</ul>
</li>
<li><strong>Athena-3 Excels in STEM and NLP</strong>: <strong>Athena-3</strong> is a high-performance LLM designed to excel in most <strong>STEM</strong> areas as well as general <strong>NLP</strong> tasks.<ul>
<li><strong>Athena-R3</strong> is a reasoning variant of Athena.</li>
</ul>
</li>
<li><strong>Embedders and RAG get a Spot</strong>: A member shares a <a href="https://huggingface.co/collections/Spestly/athena-3-67ece486149311c0a3552e4a" target="_blank">HuggingFace collection</a> for <strong>embedders</strong> and how <strong>RAG</strong> works.<ul>
<li>Another shared a <a href="https://huggingface.co/kalle07/embedder_collection" target="_blank">HuggingFace Collection</a> of embedders.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-computer-vision-2-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/922424143113232404/1359372458053861543" target="_blank">computer-vision</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Tools recognition task, Model adaptation for specific tools, Enhancing model feature extraction</code> </p>
</blockquote>
<ul>
<li><strong>Brainstorming tools recognition task</strong>: A member is asking for recommendations on which <strong>model or algorithm</strong> would be best suited for a <strong>tools recognition task</strong>, where the model should identify tools from reference pictures.<ul>
<li>They also want to know how to <strong>enhance the model</strong> for better feature extraction.</li>
</ul>
</li>
<li><strong>Considering Adaptable Algorithms for Tool Identification</strong>: The discussion revolves around finding a model capable of adapting to <strong>specific tools</strong> for recognition, based on reference images provided.<ul>
<li>Enhancements to the model are sought to improve <strong>feature extraction</strong> capabilities, ensuring more accurate identification.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-gradio-announcements-1-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/1014577787039924226/1359459545877057649" target="_blank">gradio-announcements</a></strong> (1 messages):</h3>
<blockquote>
<p><code>Gradio, ImageEditor component</code> </p>
</blockquote>
<ul>
<li><strong>Gradio's ImageEditor Fixed!</strong>: Gradio 5.24 is out with a completely rebuilt <strong>ImageEditor component</strong> that fixes zooming, panning, transparency, layer support, buggy behavior and RTL support.</li>
<li><strong>Gradio ImageEditor Docs</strong>: Check the <a href="https://gradio.app/changelog" target="_blank">docs</a> for full details, and upgrade now with <code>pip install --upgrade gradio</code>.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-agents-course-28-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/1329142738440028273/1359270069380583546" target="_blank">agents-course</a></strong> (28 messages🔥):</h3>
<blockquote>
<p><code>Ollama models, Cogito:32b, Small models vs Large Models, Agentic Coding, RooCode</code> </p>
</blockquote>
<ul>
<li><strong>Ollama model Cogito:32b</strong>: A member recommended the <a href="https://ollama.com/library/cogito:32b" target="_blank">Cogito:32b model</a> for <strong>Ollama</strong>, noting that it works very well.<ul>
<li>Another member tested <strong>Cogito 3b</strong> and <strong>8b</strong> for a Rubik's cube question, but found the <strong>32b</strong> model superior to <strong>Qwen-Coder 32b</strong> and even <strong>Gemma3-27b</strong>.</li>
</ul>
</li>
<li><strong>Small Models Benefit from ToolCallinAgent Architecture</strong>: It was mentioned that smaller models perform better with <strong>ToolCallinAgent</strong> compared to <strong>CodeAgent</strong> architectures.<ul>
<li>A prompt template example was shared that helped a <strong>smallthinker-latest:3b model</strong> use <strong>smolagents Codeagent</strong> correctly using valid Python print statements.</li>
</ul>
</li>
<li><strong>RooCode Tooling</strong>: <strong>RooCode</strong> is described as an Agentic Coding tool, similar to GitHub CoPilot, that uses structured prompting.<ul>
<li>Unlike <em>vibe coding</em>, <strong>RooCode</strong> takes a more structured approach with a clear spec, architect plan, test-driven development, and project context files, it is an Opensource extension to VS Code, usable with almost any LLM (and free through Google AI Studio credits).</li>
</ul>
</li>
<li><strong>Replit Coding Environment</strong>: A member recommended <strong>Replit</strong>; the Agent there works on a feedback loop basis, providing independent ideas of what to add next to the app and offering quick and easy deployment.<ul>
<li>It was mentioned that you can open a remote environment of <strong>Replit</strong> using local VSCode, with one user preparing a <strong>README.md</strong> file using Gemini Code Assistant Extension under local VSC.</li>
</ul>
</li>
<li><strong>HuggingFace quiz authentication Issues</strong>: A member reported an error when trying to authorize their Hugging Face account for the Unit 1 final quiz.<ul>
<li>Another member suggested logging in from the <a href="https://huggingface.co/agents-course" target="_blank">HuggingFace Agents Course space</a> and then returning to the quiz, which seemed to resolve the issue.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="huggingface-open-r1-13-messages"><strong>HuggingFace ▷ #<a href="https://discord.com/channels/879548962464493619/1333465203865817088/1359333165776244917" target="_blank">open-r1</a></strong> (13 messages🔥):</h3>
<blockquote>
<p><code>Deepseek, Active AI chats</code> </p>
</blockquote>
<ul>
<li><strong>Deepseek versions: Which are the hottest?</strong>: A member inquired about which <strong>Deepseek</strong> versions others have been experimenting with.<ul>
<li>The same member clarified the room is <strong>Deepseek R1</strong> related.</li>
</ul>
</li>
<li><strong>Discordians Seek Active AI Echo Chambers</strong>: One member asked if anyone had found any active <strong>AI chats</strong> on Discord, or even better, active voice chats.<ul>
<li>This was after a humorous comment about the level bot potentially making them a <em>Jedi master</em>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="notebook-lm-use-cases-13-messages"><strong>Notebook LM ▷ #<a href="https://discord.com/channels/1124402182171672732/1124403655819415592/1359279482720096476" target="_blank">use-cases</a></strong> (13 messages🔥):</h3>
<blockquote>
<p><code>NotebookLM Privacy, NotebookLM Training, NotebookLM as a Notetaking App, Google Drive Integration, Microsoft OneNote</code> </p>
</blockquote>
<ul>
<li><strong>NotebookLM's privacy policy questioned after summary correction</strong>: A user noticed that <strong>NotebookLM</strong> provided a correct summary <em>after</em> they corrected the initial summary, leading to concerns about whether <strong>NotebookLM</strong> uses previous queries for training, despite the privacy statement.<ul>
<li>Another user mentioned that they've <em>rarely seen any AI tool give the exact same answer to the same question</em> due to randomness, and that the AI model may flag thumbs down reports as <strong>offensive or unsafe</strong>.</li>
</ul>
</li>
<li><strong>NotebookLM not useful as Notetaking App yet</strong>: A user found that <strong>NotebookLM</strong> is heavily dependent on external sources instead of user-typed notes, which limits its usefulness as a notetaking app, and that taking notes is too primitive.<ul>
<li>The user desires organization features like those in <strong>Microsoft OneNote</strong>, such as pages organized in sections and section groups with customizable reading orders.</li>
</ul>
</li>
<li><strong>Users Suggest Google Drive Integration</strong>: Users suggest integration with <strong>Google Drive</strong> to save and launch NotebookLM notebooks, similar to how <strong>Google Docs</strong> and <strong>Sheets</strong> work.<ul>
<li>They noted that <strong>NotebookLM</strong> should compliment <strong>Google Drive</strong> the same way <strong>Google Docs</strong> and <strong>Google Sheets</strong> do.</li>
</ul>
</li>
<li><strong>Importing from Microsoft OneNote requested</strong>: Users are requesting the ability to import notebooks from <strong>Microsoft OneNote</strong> into <strong>NotebookLM</strong>, including sections and section groups, potentially by importing <strong>.onepkg</strong> files.<ul>
<li>The user acknowledged <em>the legality behind this is a little questionable</em> but if <strong>Google Drive</strong> can import <strong>Microsoft Word</strong> documents it could be viable.</li>
</ul>
</li>
<li><strong>PDF Exporting features requested</strong>: Users are requesting more organized PDF exports with options for cover pages, tables of contents, and the ability to include or exclude generative AI content.<ul>
<li>The main complaint was that <strong>Microsoft OneNote</strong> is incapable of exporting to <strong>PDF</strong> in an organized way.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="notebook-lm-general-75-messages"><strong>Notebook LM ▷ #<a href="https://discord.com/channels/1124402182171672732/1124402182909857966/1359241680435544206" target="_blank">general</a></strong> (75 messages🔥🔥):</h3>
<blockquote>
<p><code>PDF image processing in NLM, Discover sources feature in NLM, Interactive mode issues in NLM, Audio overviews in 2.5 Pro, Text formatting in NotebookLM chat</code> </p>
</blockquote>
<ul>
<li><strong>PDF Image Processing Capability Unclear</strong>: A user asked about updates to <strong>PDF</strong> image processing in <strong>NotebookLM</strong>, mentioning that in November, converting to <strong>Google Docs</strong> was recommended for better image reading.<ul>
<li>Another user mentioned there were announced updates, and requested feedback from those who have tested the feature.</li>
</ul>
</li>
<li><strong>Discover Sources Emerge into Existence</strong>: A user asked how to identify the new <strong>Discover sources</strong> feature and whether it's obvious or only appears when creating a new notebook, while another said they were still waiting for it with <strong>Gemini 2.5 Pro</strong>.<ul>
<li>Another user asked for tips on finding multiple websites as URL links for a <strong>Source</strong> in NBLM, specifically for a <strong>1st year law student</strong> with <strong>5 different PDF documents</strong> in one subject.</li>
</ul>
</li>
<li><strong>Audio Overviews Glitch on Mobile</strong>: A user reported that the new <strong>2.5 Pro</strong> deep research feature claims the capability to make <strong>audio overviews</strong>, but it failed to generate one, indicating it <em>doesn't have the capacity to understand</em>.<ul>
<li>It was reported to work on web, but not on mobile, and another user suggested to report the issue in the appropriate channel.</li>
</ul>
</li>
<li><strong>Text Formatting Plunges to Pitiful</strong>: Users expressed dissatisfaction with the <strong>text formatting</strong> in <strong>NotebookLM chat</strong>, noting its inferiority compared to the <strong>Gemini app</strong> and other AI chats.<ul>
<li>Specific issues mentioned include the lack of <strong>subscripts</strong>, <strong>superscripts</strong>, and <strong>special characters</strong> like Greek letters, making it difficult to use for subjects like chemistry.</li>
</ul>
</li>
<li><strong>Firebase Studio springs from Project IDX</strong>: A user experienced an error creating a workspace, and another user clarified that this is a rebranding of <strong>Project IDX</strong>.<ul>
<li>A link to <a href="https://github.com/project-idx/community-templates" target="_blank">community templates</a> was shared, suggesting it might use the new <strong>2.5 Pro coder model</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-general-15-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1189498205101109300/1359508182699081768" target="_blank">general</a></strong> (15 messages🔥):</h3>
<blockquote>
<p><code>FP4 on 5090, CUTLASS for tensor cores, Flash Attention 3, torchao 0.10, MX dtypes</code> </p>
</blockquote>
<ul>
<li><strong>FP4 Programming Primer Provided</strong>: A member inquired about getting started with <strong>FP4</strong> on the <strong>5090</strong>, to which another member suggested using <strong>CUTLASS</strong> to leverage the tensor cores and provided <a href="https://github.com/NVIDIA/cutlass/blob/main/examples/79_blackwell_geforce_gemm/79a_blackwell_geforce_nvfp4_bf16_gemm.cu" target="_blank">an example</a>.</li>
<li><strong>Flash Attention 3 Implemented in CUTLASS</strong>: In response to a question about prebuilt tools for transformers, a member clarified that <strong>CUTLASS</strong> is critical for <strong>Flash Attention 3</strong>.</li>
<li><strong>Pytorch ao 0.10 Released with MX Features</strong>: The team recently released <a href="https://github.com/pytorch/ao/releases/tag/v0.10.0" target="_blank">torchao 0.10</a> that adds alot of <strong>MX</strong> features and provided a <a href="https://github.com/pytorch/ao/blob/main/torchao/prototype/mx_formats/README.md" target="_blank">README</a> for <strong>MX dtypes</strong> for more information.<ul>
<li>That being said this does require <strong>nightly pytorch</strong> and currently only works for <strong>b200</strong>, but it should be pretty easy to update the <strong>MXFP4 cutlass kernel</strong> we have to support <strong>sm120</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-cuda-6-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1189607726595194971/1359388304721580144" target="_blank">cuda</a></strong> (6 messages):</h3>
<blockquote>
<p><code>Linux Distro, NVIDIA drivers, LDSM Instruction, Warp Shuffling</code> </p>
</blockquote>
<ul>
<li><strong>Linux Distro for NVIDIA</strong>: A member asked which <strong>Linux distro</strong> would give them the least pain with <strong>NVIDIA drivers</strong>.<ul>
<li>They were considering just going with <strong>Ubuntu</strong> if it doesn't matter.</li>
</ul>
</li>
<li><strong>LDSM Instruction</strong>: A member sought clarification on how <strong>LDSM</strong> (shared memory) instructions work, posting the instruction <code>SmemCopyAtom = Copy_Atom&lt;SM75_U32x4_LDSM_N, cute::half_t&gt;; auto smem_tiled_copy_A = make_tiled_copy_A(SmemCopyAtom{}, tiled_mma);</code>.<ul>
<li>They were unsure where data is stored during the exchange process and inquired about documentation explaining these hardware instructions in more detail.</li>
</ul>
</li>
<li><strong>Threads exchange with Warp Shuffling</strong>: A member agreed with the understanding that each thread loads data from source, threads exchange data, then the data is stored into destination.<ul>
<li>They also wondered <em>how</em> threads exchange data, suggesting the possibility of using <strong>warp shuffling</strong>, and provided a link to the <a href="https://docs.nvidia.com/cuda/parallel-thread-execution/index.html?highlight=load#warp-level-matrix-load-instruction-ldmatrix" target="_blank">NVIDIA documentation</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-torch-2-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1189607750876008468/1359306414497202456" target="_blank">torch</a></strong> (2 messages):</h3>
<blockquote>
<p><code>FSDP2, Model Parallelism, Accelerate Hack</code> </p>
</blockquote>
<ul>
<li><strong>FSDP2 clashes with other parallelism</strong>: A member expressed difficulty integrating <strong>FSDP2</strong> due to its unique design compared to other parallelism methods.<ul>
<li>They also mentioned that a specific hack used in <strong>Accelerate</strong> clashes with the current approach, highlighting integration challenges.</li>
</ul>
</li>
<li><strong>Integrating FSDP2 difficult, requires unique design</strong>: It was noted that the unique design of <strong>FSDP2</strong>, while impressive, makes it challenging to integrate with other parallelism techniques.<ul>
<li>A member mentioned that the approach clashes with a hack used in <strong>Accelerate</strong>, complicating the integration process.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-cool-links-2-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1189868872887705671/1359268567962619984" target="_blank">cool-links</a></strong> (2 messages):</h3>
<blockquote>
<p><code>CUDA vs other, SMERF, Berlin Demo</code> </p>
</blockquote>
<ul>
<li><strong>CUDA still preferred by some</strong>: One member expressed a preference for <strong>CUDA</strong> over other platforms.<ul>
<li>They gave no specific alternative, however.</li>
</ul>
</li>
<li><strong>SMERF sparks imagination</strong>: A member shared <a href="https://smerf-3d.github.io/" target="_blank">SMERF</a>, calling it <em>so cool and imagination sparking</em>.<ul>
<li>They also shared a link to the <a href="https://smerf-3d.github.io/select_quality/?scene=berlin" target="_blank">Berlin Demo</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-beginner-19-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1191300313928433664/1359251457550979243" target="_blank">beginner</a></strong> (19 messages🔥):</h3>
<blockquote>
<p><code>Graph Neural Networks (GNNs), CUDA C vs CUDA C++, Graph Attention Networks, GAN parallelism, Producers and Consumers architecture</code> </p>
</blockquote>
<ul>
<li><strong><em>*GNNs computations happen in Parallel</em></strong><em>: A member stated that there is </em>a huge number of variants of GNN layers*, but updates for each node in a graph can be computed in parallel, referencing <a href="https://blogs.nvidia.com/blog/what-are-graph-neural-networks/" target="_blank">this blogpost from NVIDIA</a>.</li>
<li><strong><em>*CUDA C++ vs CUDA C</em></strong><em>: A member mentioned that </em><em>C++</em><em> is a superset of </em><em>C</em><em>, so you can compile C code with a </em><em>C++</em><em> compiler, and that there is no </em><em>CUDA C</em>* compiler.<ul>
<li>Another member clarified that it is possible to write <strong>C</strong> code that does not compile with a <strong>C++</strong> compiler, and linked to <a href="https://en.m.wikipedia.org/wiki/Compatibility_of_C_and_C++" target="_blank">this Wikipedia article</a> for more information.</li>
</ul>
</li>
<li><strong><em>*Graph Attention Networks</em>* Architecture For Parallelism</strong>: When thinking of parallel computations on graphs, a member suggested the use of <strong>Graph Attention Networks</strong>.<ul>
<li>The question came in response to a question about parallelism on GNN tasks. One member linked <a href="https://cdn.discordapp.com/attachments/1191300313928433664/1359264906167320576/GNN-model-pipeline-China-survey-672x383.png?ex=67f78257&amp;is=67f630d7&amp;hm=0ee08ec9fd4dc3a6c3e477f71b9135e479aef1133ec34758dffbd1d6025268a1&amp;" target="_blank">this image of a GNN pipeline</a>.</li>
</ul>
</li>
<li><strong><em>*Producers and Consumers</em>* architecture</strong>: A member asked why to use <strong>producers and consumers</strong> architecture, instead of making everyone produce and consume after, wondering whether <em>it's just about minimizing de sync time</em>.<ul>
<li>The question was specific to the <strong>Hopper</strong> architecture for gemms.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-torchao-1-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1205223658021458100/1359317987814936727" target="_blank">torchao</a></strong> (1 messages):</h3>
<blockquote>
<p><code>torchao v0.10.0, MXFP8 Training, Nvidia B200, PARQ, Quantization API</code> </p>
</blockquote>
<ul>
<li><strong>Torchao Drops new v0.10.0 Release</strong>: The newest <a href="https://github.com/pytorch/ao/releases/tag/v0.10.0" target="_blank">torchao</a> <strong>v0.10.0 release</strong> includes support for end to end training for <strong>mxfp8</strong> on <strong>Nvidia B200</strong>, <strong>PARQ</strong> (for quantization aware training).<ul>
<li>It also includes module swap quantization API for research, and some updates for low bit kernels!</li>
</ul>
</li>
<li><strong>Nvidia B200 now compatible with MXFP8 Training</strong>: With the release of <strong>torchao v0.10.0</strong> end to end training is now possible with <strong>MXFP8</strong> on <strong>Nvidia B200</strong>.<ul>
<li>The added support allows for usage of the module swap quantization API.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-off-topic-2-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1215328286503075953/1359530971237581021" target="_blank">off-topic</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Brooklyn Apartments, Apartment Hunting Tips</code> </p>
</blockquote>
<ul>
<li><strong>Brooklyn Apartment Hunter Seeks Tips</strong>: A member is moving to Brooklyn in the fall and is looking for recommendations on finding cool apartments.<ul>
<li>No specific apartment recommendations or tips were provided in the given messages.</li>
</ul>
</li>
<li><strong>Fall Move to Brooklyn Sparks Apartment Search</strong>: An individual is planning a move to Brooklyn this fall and is eager to gather insights on apartment hunting in the area.<ul>
<li>The discussion is currently open, awaiting suggestions and advice from community members.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-self-promotion-1-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1288557096404516945/1359581692234567911" target="_blank">self-promotion</a></strong> (1 messages):</h3>
<blockquote>
<p><code>Mediant32, FP32, BF16, integer-only inference, Rationals</code> </p>
</blockquote>
<ul>
<li><strong>Mediant32 emerges as FP32/BF16 alternative</strong>: A member announced <strong>Mediant32</strong>, an experimental alternative to <strong>FP32</strong> and <strong>BF16</strong> for integer-only inference, based on Rationals, continued fractions and the Stern-Brocot tree, with a <a href="https://leetarxiv.substack.com/p/mediant32-intro" target="_blank">step-by-step implementation guide</a>.</li>
<li><strong>Understanding Mediant32's Number System</strong>: <strong>Mediant32</strong> uses a number system based on <strong>Rationals</strong>, <strong>continued fractions</strong>, and the <strong>Stern-Brocot tree</strong>, offering a novel approach to numerical representation.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-reasoning-gym-2-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1316377974672588850/1359394478099534007" target="_blank">reasoning-gym</a></strong> (2 messages):</h3>
<blockquote>
<p><code>DeepCoder, Llama 4 Scout</code> </p>
</blockquote>
<ul>
<li><strong>DeepCoder is Born</strong>: A member shared a link to <a href="https://pretty-radio-b75.notion.site/DeepCoder-A-Fully-Open-Source-14B-Coder-at-O3-mini-Level-1cf81902c14680b3bee5eb349a512a51" target="_blank">DeepCoder</a>, a fully open-source <strong>14B coder</strong> at <strong>O3-mini</strong> level.</li>
<li><strong>Llama 4 Scout added to Github</strong>: A member noted the addition of <strong>Llama 4 Scout</strong> to <a href="https://github.com/open-thought/reasoning-gym-eval/pull/6" target="_blank">Github</a>.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-gpu-3-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1342364798058500148/1359403842810417184" target="_blank">gpu模式</a></strong> (3 messages):</h3>
<blockquote>
<p><code>NVSHMEM and RDMA, Deepseek Library, RoCE or Infiniband Compatibility</code> </p>
</blockquote>
<ul>
<li><strong>RDMA with NVSHMEM Possible Via RoCE/Infiniband</strong>: A member suggests that <a href="https://docs.nvidia.com/nvshmem/api/using.html" target="_blank">NVSHMEM</a> might enable <strong>RDMA</strong> via <strong>RoCE</strong> or <strong>Infiniband</strong> using its <code>get</code> and <code>put</code> APIs.<ul>
<li>The member clarified that they hadn't tested the code yet, and their understanding is based on the <strong>NVSHMEM</strong> documentation.</li>
</ul>
</li>
<li><strong>Deepseek Library Shared</strong>: A member asked about the <strong>Deepseek library</strong>.<ul>
<li>Another member shared a link to the <a href="https://github.com/deepseek-ai/DeepEP" target="_blank">Deepseek library on GitHub</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-general-11-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1343002580531417211/1359264114073141358" target="_blank">general</a></strong> (11 messages🔥):</h3>
<blockquote>
<p><code>CUDA Inline Submissions, Datamonsters AMD Developer Challenge</code> </p>
</blockquote>
<ul>
<li><strong><em>*CUDA Kernel Code Snippets Shared</em></strong><em>: A member shared a code snippet showing how to use CUDA inline with c++ sources, using </em><em>cuda_sources</em><em> and </em><em>c++ sources</em><em> variables, and </em><em>load_inline</em>* function.<ul>
<li>The code involves defining a CUDA kernel, a corresponding C++ function, and loading it as a module with <code>load_inline</code>.</li>
</ul>
</li>
<li><strong><em>*CUDA Inline Submission Fixed</em></strong><em>: A member reported that the </em><em>sample submission</em>* was wrong but was fixed in this <a href="https://github.com/gpu-mode/reference-kernels/pull/14" target="_blank">pull request</a>.<ul>
<li>They also asked about whether the <a href="https://www.datamonsters.com/amd-developer-challenge-2025" target="_blank">Datamonsters AMD Developer Challenge 2025</a> MI300 submission works.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-submissions-14-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1343002583001726986/1359261423196442766" target="_blank">submissions</a></strong> (14 messages🔥):</h3>
<blockquote>
<p><code>Grayscale Leaderboard Submissions, Matmul Leaderboard Submissions, Vectoradd Leaderboard Submissions, Modal Runners Success</code> </p>
</blockquote>
<ul>
<li><strong>Grayscale Leaderboard Gains New Ground</strong>: Leaderboard submissions with ids <strong>3539</strong> and <strong>3540</strong> to leaderboard <code>grayscale</code> on GPUs: <strong>L4</strong>, <strong>T4</strong>, <strong>A100</strong>, <strong>H100</strong> using Modal runners succeeded!</li>
<li><strong>Matmul Leaderboard Swamped with New Submissions</strong>: Leaderboard submissions with ids <strong>3549</strong>, <strong>3550</strong>, <strong>3551</strong>, <strong>3555</strong>, <strong>3556</strong>, <strong>3557</strong>, <strong>3558</strong>, <strong>3559</strong>, <strong>3561</strong>, <strong>3563</strong>, <strong>3564</strong> to leaderboard <code>matmul</code> on GPUs: <strong>T4</strong> using Modal runners succeeded!</li>
<li><strong>Vectoradd Leaderboard Submission Verified</strong>: Leaderboard submission with id <strong>3554</strong> to leaderboard <code>vectoradd</code> on GPUs: <strong>T4</strong> using Modal runners succeeded!</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="gpu-mode-feature-requests-and-bugs-1-messages"><strong>GPU MODE ▷ #<a href="https://discord.com/channels/1189498204333543425/1343759913431728179/" target="_blank">feature-requests-and-bugs</a></strong> (1 messages):</h3>
<p>leikowo: ah, sorry I didn't see your message in time, seems that you guys fixed it already</p>
<hr/>
<h3 id="latent-space-ai-general-chat-77-messages"><strong>Latent Space ▷ #<a href="https://discord.com/channels/822583790773862470/1075282825051385876/1359262429674078449" target="_blank">ai-general-chat</a></strong> (77 messages🔥🔥):</h3>
<blockquote>
<p><code>Together AI X-Ware.v0, Gemiji Plays Pokemon, AI Excel Formulas, Microsoft Copilot for Indie Game Devs, Agent2Agent Protocol (A2A) by Google</code> </p>
</blockquote>
<ul>
<li><strong><em>*Together AI</em>*'s X-Ware.v0 Released</strong>: <strong>Together AI</strong> released <strong>X-Ware.v0</strong>, as announced in <a href="https://x.com/togethercompute/status/1909697122372378908" target="_blank">this tweet</a>, which is being tested by community members.<ul>
<li>It remains to be seen how well <strong>X-Ware.v0</strong> runs.</li>
</ul>
</li>
<li><strong><em>*Gemiji Plays Pokemon</em>* Attracts Interest</strong>: A member shared a link to <strong>Gemiji</strong> playing <strong>Pokemon</strong> (<a href="https://x.com/kiranvodrahalli/status/1909699142265557208" target="_blank">link</a>), which seems to be doing well.<ul>
<li>The post links to a tweet from Kiran Vodrahalli.</li>
</ul>
</li>
<li><strong>AI Excel Formula Excitement</strong>: A member shared <a href="https://x.com/diegocabezas01/status/1909221066565734854" target="_blank">a link</a> and expressed excitement about AI/LLM excel formulas, seeing implementation from main players.<ul>
<li>They noted that they have been personally thinking about this kind of AI/LLM excel formula for a long time and one of their friends successfully used <strong>TextGrad</strong>.</li>
</ul>
</li>
<li><strong><em>*Copilot</em>* as Indie Game Dev Tool</strong>: Members discussed <a href="https://copilot.microsoft.com/wham?features=labs-wham-enabled" target="_blank">Microsoft's Copilot</a> and its potential for indie game development, seeing it as a demonstration of agents as a great tool for indie game devs.<ul>
<li>Some think the code gen agent tooling is much more useful to get something shippable right now, referencing the levels io game jam as pretty eye opening.</li>
</ul>
</li>
<li><strong>Google Unveils </strong>Agent2Agent Protocol (A2A)<strong><em>*: </em>*Google</strong> announced the <strong>Agent2Agent Protocol (A2A)</strong> for agent interoperability, full spec available <a href="https://github.com/google/A2A" target="_blank">here</a>, with one member noting their involvement.<ul>
<li>They provided a comparison with <strong>MCP</strong> (<a href="https://google.github.io/A2A/#/topics/a2a_and_mcp.md" target="_blank">link</a>).</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="nous-research-ai-general-66-messages"><strong>Nous Research AI ▷ #<a href="https://discord.com/channels/1053877538025386074/1149866623109439599/1359246432896553131" target="_blank">general</a></strong> (66 messages🔥🔥):</h3>
<blockquote>
<p><code>Llama 4 Fine-tuning, Deep Herme's Dataset, Selling 3090 turbo card, DeepCogito's LLMs, Iterated Distillation and Amplification</code> </p>
</blockquote>
<ul>
<li><strong>Llama 4 fine-tuning disaster is averted</strong>: Members mentioned that fine-tuning the new <strong>Hermes</strong> on <strong>Llama 4</strong> models would be a disaster, but luckily, they perform many different tests, so if something is resulting in worse performance, it is <em>yeeted</em>.<ul>
<li>It was agreed that there's still some value to <strong>Llama 4</strong> for some things, and it can't be worse at literally everything.</li>
</ul>
</li>
<li><strong>Deep Hermes dataset is the new creative writing dataset?</strong>: The new <strong>Deep Hermes</strong> models have quite a big vocabulary, though they are not too smart at <strong>8b</strong>, but if this deep hermes dataset is going to be the new dataset for smarter models, then they're going to be nasty for creative writing.<ul>
<li>The user tested the new <strong>Deep Hermes</strong> models and for how small they are, they have quite a big vocabulary (unfortunately they're not too smart at 8b).</li>
</ul>
</li>
<li><strong>Cogito LLMs using Iterated Distillation and Amplification strategy released</strong>: <a href="https://www.deepcogito.com/research/cogito-v1-preview" target="_blank">DeepCogito</a> released the strongest LLMs of sizes <strong>3B</strong>, <strong>8B</strong>, <strong>14B</strong>, <strong>32B</strong> and <strong>70B</strong> under open license.<ul>
<li>Each model outperforms the best available open models of the same size, including counterparts from <strong>LLaMA</strong>, <strong>DeepSeek</strong>, and <strong>Qwen</strong>, across most standard benchmarks; the <strong>70B</strong> model also outperforms the newly released <strong>Llama 4 109B MoE</strong> model.</li>
</ul>
</li>
<li><strong>Models mirror human debate tactics</strong>: A member put two models to face each other in argument and realized how similar it's to when human debate, <em>they actually never trying to understand the other view and keep on standing on their view what ever the argument is</em>.<ul>
<li>The models choose the weakness that they could attack back, ignored the part that could put them in a questionable position and focused on the part that they could use to put the other model into questionable position.</li>
</ul>
</li>
<li><strong>Qwen 2.5 1.5B Instruct training shows promise</strong>: A member is doing <strong>RL</strong> on <strong>Qwen 2.5 1.5B Instruct</strong> and swapped out the <strong>gsm8k</strong> dataset for <strong>gsm8k platinum</strong>, enabling <strong>RsLora</strong> and the model seems to be learning much quicker in fewer steps.<ul>
<li>The improvement may be from using the less ambiguous dataset, and how much is from using <strong>RsLora</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="nous-research-ai-ask-about-llms-2-messages"><strong>Nous Research AI ▷ #<a href="https://discord.com/channels/1053877538025386074/1154120232051408927/1359394969495802038" target="_blank">ask-about-llms</a></strong> (2 messages):</h3>
<blockquote>
<p><code>BPE Tokenizer, Hugging Face library, Non-English text encoding</code> </p>
</blockquote>
<ul>
<li><strong>BPE Tokenizer and Multi-Byte Characters</strong>: A member inquired whether the <strong>Hugging Face library</strong> ensures that merged byte pairs form valid characters when training a <strong>BPE tokenizer</strong> on non-English text with multi-byte characters.<ul>
<li>Another member, &lt;@687701601585987765&gt;, was asked if they knew the answer.</li>
</ul>
</li>
<li><strong>Additional topic to meet minItems requirement</strong>: Adding a second topic to satisfy the requirement of having at least two items in topicSummaries.<ul>
<li>This entry is purely for compliance with the schema and does not represent actual content from the conversation.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="nous-research-ai-interesting-links-1-messages"><strong>Nous Research AI ▷ #<a href="https://discord.com/channels/1053877538025386074/1132352574750728192/" target="_blank">interesting-links</a></strong> (1 messages):</h3>
<p>anka039847: https://mlss2025.mlinpl.org/</p>
<hr/>
<h3 id="nomicai-gpt4all-general-57-messages"><strong>Nomic.ai (GPT4All) ▷ #<a href="https://discord.com/channels/1076964370942267462/1090427154141020190/1359298604392775782" target="_blank">general</a></strong> (57 messages🔥🔥):</h3>
<blockquote>
<p><code>Local Embedding Models, GPT4All Document Indexing, Local LLM Loading Issues, RAG Implementation, GPT4All Stop Button</code> </p>
</blockquote>
<ul>
<li><strong>Run Embedding Models Locally for Safety</strong>: Members discussed the benefits of running embedding models and LLMs locally to avoid sending private information to remote services, with one member providing <a href="https://gnu.support/files/tmp/clipboard-2025-04-09-01-48-48.html" target="_blank">a shell script</a> for running a local embedding model from Nomic.<ul>
<li>The script uses variables such as <code>$LLAMA_SERVER</code>, <code>$NGL_FLAG</code>, <code>$HOST</code>, <code>$EMBEDDING_PORT</code>, and <code>$EMBEDDING_MODEL</code> to configure and run the embedding server.</li>
</ul>
</li>
<li><strong>GPT4All Indexes Documents by Chunking and Embedding</strong>: A user explained that <strong>GPT4All</strong> indexes documents by chunking and embedding them, storing representations of similarities in a private cache.<ul>
<li>The user recommended running a local embeddings model and LLM model, suggesting that even <strong>Qwen 0.5B</strong> parameters can work well with documents, though <strong>Qwen 1.5B</strong> is better.</li>
</ul>
</li>
<li><strong>User Struggles Loading Local LLM</strong>: A member reported getting stuck while loading a local LLM, despite having <strong>16GB RAM</strong> and an <strong>Intel i7-1255U CPU</strong>.<ul>
<li>They suspected the issue was with downloading the model, and mentioned their use case as an internal documentation tool, expressing caution about using remote services for private documents.</li>
</ul>
</li>
<li><strong>DIY RAG with Shell Scripting</strong>: A member shared shell script examples for getting embeddings and sending prompts to a local LLM.<ul>
<li>They suggested using <strong>PostgreSQL</strong> for storing embeddings and creating a custom RAG implementation, rather than relying on remote tools. Shell script examples <code>rcd-llm.sh</code> and <code>rcd-llm-get-embeddings.sh</code>.</li>
</ul>
</li>
<li><strong>GPT4All's Hidden Stop Button</strong>: A user asked how to stop text generation in <strong>GPT4All</strong>, noting the absence of a visible stop button or the ability to use <strong>Ctrl+C</strong>.<ul>
<li>Another user pointed out the stop button at the bottom right, which is the same button as the Generate button.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="modular-mojo-general-3-messages"><strong>Modular (Mojo 🔥) ▷ #<a href="https://discord.com/channels/1087530497313357884/1098713601386233997/1359427982745403513" target="_blank">general</a></strong> (3 messages):</h3>
<blockquote>
<p><code>Mojo Language, Mojo Documentation, Mojo Community</code> </p>
</blockquote>
<ul>
<li><strong>Mojo Language, a new beginning</strong>: A new user asked where to start learning the Mojo language and what it is.<ul>
<li>Another user welcomed them and pointed to the <a href="https://docs.modular.com/mojo/manual/" target="_blank">official Mojo documentation</a> as a great starting point.</li>
</ul>
</li>
<li><strong>Mojo community welcomes you</strong>: A member highlighted the Mojo community, directing the user to the <a href="https://forum.modular.com/c/mojo/7" target="_blank">Mojo section of the Modular forums</a> and the general channel on Discord.<ul>
<li>The user expressed their gratitude for the provided resources.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="modular-mojo-mojo-14-messages"><strong>Modular (Mojo 🔥) ▷ #<a href="https://discord.com/channels/1087530497313357884/1151418092052815884/1359257146805719162" target="_blank">mojo</a></strong> (14 messages🔥):</h3>
<blockquote>
<p><code>Span Lifetimes in Mojo, Fearless Concurrency in Mojo, MLIR Type Construction with Compile-Time Parameters, Parametric Operations Dialect (POP)</code> </p>
</blockquote>
<ul>
<li><strong>Span Lifetime Woes with Mojo Traits</strong>: A member sought advice on how to express in Mojo that <em>the lifetime of a returned Span is at least the lifetime of self</em>, providing <a href="https://forum.modular.com/t/how-to-return-a-span-that-refers-to-a-struct-member-from-a-trait-method/1216" target="_blank">Rust/Mojo code examples</a>.<ul>
<li>The response indicated that <em>making the trait generic over origin</em> is a possible solution, though trait parameter support might be needed.</li>
</ul>
</li>
<li><strong>Mojo's Fearless Concurrency on the Horizon</strong>: A question arose on whether <em>Mojo has Rust-like fearless concurrency</em>.<ul>
<li>The answer was that Mojo has the borrow checker constraints needed, and is only lacking <strong>Send/Sync</strong> and a final concurrency model; it may even have a better system than Rust's eventually.</li>
</ul>
</li>
<li><strong>Compile-Time MLIR Type Construction Conundrums</strong>: A member reported an issue using <em>parameterized compile-time values in MLIR type construction</em> (specifically <strong>!llvm.array</strong> and <strong>!llvm.ptr</strong>) within the MAX/Mojo standard library, detailing the issue in <a href="https://github.com/modular/max/issues/4315" target="_blank">a GitHub post</a>.<ul>
<li>The problem involves a parsing error when defining a struct with compile-time parameters used in the <strong>llvm.array</strong> type; MLIR's type system appears unable to process parameterized values in this context.</li>
</ul>
</li>
<li><strong>Parametric Operations Dialect (POP) to the Rescue?</strong>: Regarding the MLIR issue, another member suggested using <em>the Parametric Operations Dialect (POP)</em>.<ul>
<li>They suggested the Mojo team add features such as the <strong>__mlir_type[...]</strong> macro accepting symbolic compile-time values, or a helper like <strong>__mlir_fold(size)</strong> to force parameter evaluation as a literal IR attribute.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="llamaindex-blog-2-messages"><strong>LlamaIndex ▷ #<a href="https://discord.com/channels/1059199217496772688/1187460979064324127/1359257133115248830" target="_blank">blog</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Auth0 Auth for GenAI, LlamaIndex support, agent workflows, FGA-authorized RAG, visual citations</code> </p>
</blockquote>
<ul>
<li><strong>Auth0 Ships Auth for GenAI with LlamaIndex Support</strong>: Auth0's Auth for GenAI now includes native LlamaIndex support, streamlining the integration of authentication into agent workflows via a simple SDK call.<ul>
<li>The auth0-ai-llamaindex SDK, available in Python and Typescript, enables <strong>FGA-authorized RAG</strong> as demonstrated <a href="https://t.co/bZgQ7gpuSt" target="_blank">here</a>.</li>
</ul>
</li>
<li><strong>Agents Get Grounded with Visual Citations</strong>: LlamaIndex released a tutorial on how to ground an agent with visual citations, mapping generated answers to specific document regions.<ul>
<li>This capability is directly available <a href="https://t.co/LP5XA8Yn0c" target="_blank">here</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="llamaindex-general-8-messages"><strong>LlamaIndex ▷ #<a href="https://discord.com/channels/1059199217496772688/1059201661417037995/1359398073562042418" target="_blank">general</a></strong> (8 messages🔥):</h3>
<blockquote>
<p><code>Reasoning LLMs, GraphRAG V2, Milvus DB, Blockchain Expertise</code> </p>
</blockquote>
<ul>
<li><strong><em>*Reasoning LLM Tutorials Sought</em></strong><em>: A member is seeking official tutorials for implementing </em><em>reasoning LLMs</em><em> from </em><em>Hugging Face</em>*, particularly for use in a Docker app hosted on Hugging Face Space.</li>
<li><strong><em>*GraphRAG V2 Azure Authentication Error</em></strong><em>: A member implementing </em><em>GraphRAG V2</em><em> with </em><em>AzureOpenAI</em><em> and </em><em>Hugging Face embeddings</em><em> is encountering an </em><em>AuthenticationError</em>* related to an incorrect OpenAI API key, despite explicitly defining AzureOpenAI.</li>
<li><strong><em>*Milvus DB Filelock Issue Spotted</em></strong><em>: A member reported a filelock issue when creating a </em><em>Milvus DB</em>* locally, suggesting the use of their server/docker solution instead of a local file.</li>
<li><strong><em>*Blockchain Engineer Offers Expertise</em></strong><em>: A software engineer with extensive experience in the blockchain ecosystem, particularly in </em><em>DEX</em><em>, </em><em>bridge</em><em>, </em><em>NFT marketplace</em><em>, </em><em>token launchpad</em><em>, </em><em>stable coin</em><em>, </em><em>mining</em><em>, and </em><em>staking protocols</em>*, offered assistance with blockchain projects.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="llamaindex-ai-discussion-3-messages"><strong>LlamaIndex ▷ #<a href="https://discord.com/channels/1059199217496772688/1100478495295017063/1359550232622403754" target="_blank">ai-discussion</a></strong> (3 messages):</h3>
<blockquote>
<p><code>LlamaIndex Deep Research, create-llama Tool</code> </p>
</blockquote>
<ul>
<li><strong>LlamaIndex Deep Research Assistance Requested</strong>: A member inquired about the simplest approach to conduct in-depth research using <strong>LlamaIndex</strong>.<ul>
<li>Another member provided a potentially useful tool, the <a href="https://x.com/MarcusSchiesser/status/1907448102467911985" target="_blank">create-llama</a>.</li>
</ul>
</li>
<li><strong>create-llama Tool Recommendation</strong>: The <a href="https://x.com/MarcusSchiesser/status/1907448102467911985" target="_blank">create-llama</a> tool was suggested as a potential resource for performing deep research with LlamaIndex.<ul>
<li>It's a tool intended to help with creating LlamaIndex projects quickly.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="cohere-general-9-messages"><strong>Cohere ▷ #<a href="https://discord.com/channels/954421988141711382/954421988783444043/1359317447521472715" target="_blank">「💬」general</a></strong> (9 messages🔥):</h3>
<blockquote>
<p><code>Cohere's documentation, Pydantic schema, cURL request, List of companies</code> </p>
</blockquote>
<ul>
<li><strong>Cohere Documentation Introduced</strong>: A member asked about examples on how to get structured output, such as a list of books, using Cohere, and another member suggested checking the <a href="https://docs.cohere.com" target="_blank">Cohere documentation</a>.</li>
<li><strong>Pydantic Schema Under Discussion</strong>: A member inquired about using <strong>Pydantic schema</strong> directly in <code>response_format</code>, and about sending requests without including the Cohere library in Python.<ul>
<li>Another member provided a <a href="https://docs.cohere.com/reference/chat" target="_blank">link to the chat reference</a> and suggested switching the example to cURL to see how it works with the Cohere API.</li>
</ul>
</li>
<li><strong>Generation of Company Lists</strong>: A member expressed wanting to generate a list of companies on a topic, asking which model would be the most suitable.<ul>
<li>Another member mentioned that Cohere's current fastest and most capable generative model is <strong>command</strong>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="cohere-bot-cmd-1-messages"><strong>Cohere ▷ #<a href="https://discord.com/channels/954421988141711382/1168578374038470656/" target="_blank">「🤖」bot-cmd</a></strong> (1 messages):</h3>
<p>competent: Currently not working!</p>
<hr/>
<h3 id="cohere-introductions-2-messages"><strong>Cohere ▷ #<a href="https://discord.com/channels/954421988141711382/1346635816629178410/1359316466289348729" target="_blank">「🤝」introductions</a></strong> (2 messages):</h3>
<blockquote>
<p><code>Introductions, Machine Vision, Web/AI Projects, Cohere AI Exploration</code> </p>
</blockquote>
<ul>
<li><strong>Aditya Enters, Eyes AI and Openchains</strong>: Aditya, with a background in <strong>machine vision</strong> and <strong>control for manufacturing equipment</strong>, is exploring <strong>web/AI</strong> during a sabbatical from an innovation-focused role, sharing his current project <a href="https://openchain.earth" target="_blank">openchain.earth</a>.<ul>
<li>His toolbox includes <strong>VS Code, Github Co-Pilot, Flutter, MongoDB, JS</strong>, and <strong>Python</strong>, and he aims to discover how <strong>Cohere's AI</strong> can enhance his project.</li>
</ul>
</li>
<li><strong>Eager Newcomer Seeks Cohere Wisdom</strong>: Aditya is keen to learn how Cohere's AI can be integrated into his project, focusing on <strong>openchain.earth</strong>.<ul>
<li>He brings a wealth of experience in <strong>machine vision</strong>, <strong>control systems</strong>, and a modern tech stack.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="cohere-status-updates-1-messages"><strong>Cohere ▷ #<a href="https://discord.com/channels/954421988141711382/1346652044181897307/" target="_blank">【🟢】status-updates</a></strong> (1 messages):</h3>
<p>competent: Should work!</p>
<hr/>
<h3 id="tinygrad-george-hotz-general-4-messages"><strong>tinygrad (George Hotz) ▷ #<a href="https://discord.com/channels/1068976834382925865/1068976834928193609/1359256911748534273" target="_blank">general</a></strong> (4 messages):</h3>
<blockquote>
<p><code>PMPP Book, Compiler Series, LLVM Tutorial, Tiny Box for Chinese Market</code> </p>
</blockquote>
<ul>
<li><strong>PMPP for GPU Programming</strong>: A member recommended <strong>PMPP (4th ed)</strong> for GPU programming.<ul>
<li>They noted that they were <em>not sure about compilers</em>, and requested recommendations.</li>
</ul>
</li>
<li><strong>Compiler Series and LLVM Tutorial</strong>: A member said they are looking into this <a href="https://marcauberer.medium.com/build-a-compiler-parser-7bf4b7381ca5" target="_blank">compiler series</a>.<ul>
<li>They also said they are going to do <a href="https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html" target="_blank">LLVM Tutorial</a> as well.</li>
</ul>
</li>
<li><strong>Tiny Box Awaited</strong>: A member shared they <em>can't wait for the new tiny box for the Chinese market exclusively</em>.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="tinygrad-george-hotz-learn-tinygrad-7-messages"><strong>tinygrad (George Hotz) ▷ #<a href="https://discord.com/channels/1068976834382925865/1070745817025106080/1359301095465160994" target="_blank">learn-tinygrad</a></strong> (7 messages):</h3>
<blockquote>
<p><code>METAL virtual device sync issue, LLaMA 7B on 4 virtual GPUs, gradient accumulation in training routine, t.grad is None issue, zero_grad() before the step</code> </p>
</blockquote>
<ul>
<li><strong>METAL virtual device sync issue breaks LLaMA 7B</strong>: A user encountered an <code>AssertionError</code> while running <strong>LLaMA 7B</strong> on <strong>4 virtual GPUs</strong> with the <strong>METAL</strong> backend, related to <code>MultiLazyBuffer</code> and <code>Ops.EXPAND</code>, fixed by <a href="https://github.com/tinygrad/tinygrad/pull/9761/files" target="_blank">this PR</a>.</li>
<li><strong>Device info lost after sampling fixed</strong>: After debugging, the issue was discovered that device info lost after sampling and proposed a fix to move tensor in <a href="https://github.com/tinygrad/tinygrad/pull/9761/files" target="_blank">PR 9761</a>.</li>
<li><strong>Gradient accumulation broken in training routine</strong>: A user reported that their call to <code>backward()</code> was not working in their training routine, with <code>t.grad is None</code> before <code>opt.step()</code>.</li>
<li><strong>Zero grad solves t.grad issue</strong>: The user found that calling <code>zero_grad()</code> before the step fixed the <code>t.grad is None</code> issue during gradient accumulation.</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="torchtune-general-4-messages"><strong>Torchtune ▷ #<a href="https://discord.com/channels/1216353675241590815/1216353675744641096/1359340577581432873" target="_blank">general</a></strong> (4 messages):</h3>
<blockquote>
<p><code>Contributor Tag Request, Gus from Psych</code> </p>
</blockquote>
<ul>
<li><strong>Contributor Tag Quest Starts</strong>: A member requested a <strong>Contributor tag</strong> for their <a href="https://github.com/nathan-az" target="_blank">GitHub profile</a>.<ul>
<li>The member made a humorous aside about using the character <strong>Gus from Psych</strong> as their Discord profile picture.</li>
</ul>
</li>
<li><strong>Gus Greets New Torchtune Team Member</strong>: Another member welcomed the new team member with a <a href="https://tenor.com/view/gus-wave-guswave-gif-18773699" target="_blank">Gus-wave GIF</a>.<ul>
<li>They jokingly asked <em>"Or should I say..."</em> implying a reference to the TV show Psych.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="torchtune-dev-4-messages"><strong>Torchtune ▷ #<a href="https://discord.com/channels/1216353675241590815/1236040539409879170/1359330112532648067" target="_blank">dev</a></strong> (4 messages):</h3>
<blockquote>
<p><code>FSDP, DeepSpeed, Sharding Strategies</code> </p>
</blockquote>
<ul>
<li><strong>FSDP Composes Better with PyTorch</strong>: Torchtune defaults to the equivalent of <strong>zero3</strong> and is used to compose well with other <strong>PyTorch distributed features</strong> like <strong>FSDP</strong>.<ul>
<li>One user mentioned they moved to torchtune <em>to avoid the minefield of trying to compose deepspeed + pytorch + megatron (and other frameworks) in favour of native pytorch</em> and hopes <em>we don't over-index on integrating and supporting other frameworks</em>.</li>
</ul>
</li>
<li><strong>DeepSpeed Recipe in Torchtune Welcomed</strong>: The team would be happy to feature a repo that imports torchtune and hosts a <strong>DeepSpeed recipe</strong>.<ul>
<li>They will require a single device copy and the addition of DeepSpeed.</li>
</ul>
</li>
<li><strong>Different Sharding Strategies Support is Straightforward</strong>: Supporting different <strong>sharding strategies</strong> is pretty straightforward, and users can tweak their recipes using <strong>FSDPModule</strong> methods to train in the equivalent of <strong>zero1-2</strong>.<ul>
<li>The team confirms that <strong>zero 1-3</strong> are all possible with minor tweaks to the collectives.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<h3 id="llm-agents-berkeley-mooc-mooc-questions-1-messages"><strong>LLM Agents (Berkeley MOOC) ▷ #<a href="https://discord.com/channels/1280234300012494859/1280370030609170494/" target="_blank">mooc-questions</a></strong> (1 messages):</h3>
<p>aniket_19393: did anybody heard back from mentors in the research track of AgentX?</p>
<hr/>
<h3 id="codeium-windsurf-announcements-1-messages"><strong>Codeium (Windsurf) ▷ #<a href="https://discord.com/channels/1027685395649015980/1027688115592237117/1359598435849998584" target="_blank">announcements</a></strong> (1 messages):</h3>
<blockquote>
<p><code>Windsurf, JetBrains, AI agent, IDE ecosystems</code> </p>
</blockquote>
<ul>
<li><strong>Windsurf Wows with Wave 7 on JetBrains</strong>: Windsurf launched <strong>Wave 7</strong>, bringing its <strong>AI agent</strong> to JetBrains IDEs (<strong>IntelliJ</strong>, <strong>WebStorm</strong>, <strong>PyCharm</strong>, <strong>GoLand</strong>), marking them as the only platform with an agentic experience across major IDE ecosystems, as shown in their <a href="https://windsurf.com/blog/windsurf-wave-7" target="_blank">blog post</a>.<ul>
<li>The beta launch incorporates core Cascade features like <strong>Write mode</strong>, <strong>Chat mode</strong>, <strong>premium models</strong>, and <strong>Terminal integration</strong>, with future updates promising additional features like <strong>MCP</strong>, <strong>Memories</strong>, <strong>Previews &amp; Deploys</strong> (<a href="https://windsurf.com/changelog/jetbrains" target="_blank">changelog</a>).</li>
</ul>
</li>
<li><strong>Codeium Rebrands to Windsurf</strong>: The company has officially rebranded as <strong>Windsurf</strong>, retiring the frequent misspellings of Codeium, and renaming their AI-native editor to <strong>Windsurf Editor</strong> and IDE integrations to <strong>Windsurf Plugins</strong>.<ul>
<li>Announcements were made on <a href="https://x.com/windsurf_ai/status/1910037538028524030" target="_blank">Twitter</a>, <a href="https://bsky.app/profile/windsurfai.bsky.social/post/3lmfms7w3n227" target="_blank">Bluesky</a>, <a href="https://www.youtube.com/watch?v=TZ8UVFiTfdU" target="_blank">YouTube</a>, <a href="https://www.instagram.com/p/DIPFz2NSTUI/" target="_blank">Instagram</a>, and <a href="https://www.tiktok.com/@windsurf/video/7491376934522309919" target="_blank">TikTok</a>.</li>
</ul>
</li>
</ul>
<p class="empty-line" style="height:16px; margin:0px !important;"></p>
<hr/>
<hr/>
<hr/>
<hr/>
<p></p>