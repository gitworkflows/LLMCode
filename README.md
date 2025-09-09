<p align="center">
    <a href="https://llm.khulnasoft.com/"><img src="https://llm.khulnasoft.com/assets/logo.svg" alt="Llmcode Logo" width="300"></a>
</p>

<h1 align="center">
AI Pair Programming in Your Terminal
</h1>


<p align="center">
Llmcode lets you pair program with LLMs to start a new project or build on your existing codebase. 
</p>

<p align="center">
  <img
    src="https://llm.khulnasoft.com/assets/screencast.svg"
    alt="llmcode screencast"
  >
</p>

<p align="center">
<!--[[[cog
from scripts.homepage import get_badges_md
text = get_badges_md()
cog.out(text)
]]]-->
  <a href="https://github.com/khulnasoft-lab/llmcode/stargazers"><img alt="GitHub Stars" title="Total number of GitHub stars the Llmcode project has received"
src="https://img.shields.io/github/stars/khulnasoft-lab/llmcode?style=flat-square&logo=github&color=f1c40f&labelColor=555555"/></a>
  <a href="https://pypi.org/project/llmcode-chat/"><img alt="PyPI Downloads" title="Total number of installations via pip from PyPI"
src="https://img.shields.io/badge/📦%20Installs-3.0M-2ecc71?style=flat-square&labelColor=555555"/></a>
  <img alt="Tokens per week" title="Number of tokens processed weekly by Llmcode users"
src="https://img.shields.io/badge/📈%20Tokens%2Fweek-15B-3498db?style=flat-square&labelColor=555555"/>
  <a href="https://openrouter.ai/#options-menu"><img alt="OpenRouter Ranking" title="Llmcode's ranking among applications on the OpenRouter platform"
src="https://img.shields.io/badge/🏆%20OpenRouter-Top%2020-9b59b6?style=flat-square&labelColor=555555"/></a>
  <a href="https://llm.khulnasoft.com/HISTORY.html"><img alt="Singularity" title="Percentage of the new code in Llmcode's last release written by Llmcode itself"
src="https://img.shields.io/badge/🔄%20Singularity-88%25-e74c3c?style=flat-square&labelColor=555555"/></a>
<!--[[[end]]]-->  
</p>

## Features

### [Cloud and local LLMs](https://llm.khulnasoft.com/docs/llms.html)

<a href="https://llm.khulnasoft.com/docs/llms.html"><img src="https://llm.khulnasoft.com/assets/icons/brain.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Llmcode works best with Claude 3.7 Sonnet, DeepSeek R1 & Chat V3, OpenAI o1, o3-mini & GPT-4o, but can connect to almost any LLM, including local models.

<br>

### [Maps your codebase](https://llm.khulnasoft.com/docs/repomap.html)

<a href="https://llm.khulnasoft.com/docs/repomap.html"><img src="https://llm.khulnasoft.com/assets/icons/map-outline.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Llmcode makes a map of your entire codebase, which helps it work well in larger projects.

<br>

### [100+ code languages](https://llm.khulnasoft.com/docs/languages.html)

<a href="https://llm.khulnasoft.com/docs/languages.html"><img src="https://llm.khulnasoft.com/assets/icons/code-tags.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Llmcode works with most popular programming languages: python, javascript, rust, ruby, go, cpp, php, html, css, and dozens more.

<br>

### [Git integration](https://llm.khulnasoft.com/docs/git.html)

<a href="https://llm.khulnasoft.com/docs/git.html"><img src="https://llm.khulnasoft.com/assets/icons/source-branch.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Llmcode automatically commits changes with sensible commit messages. Use familiar git tools to easily diff, manage and undo AI changes.

<br>

### [Use in your IDE](https://llm.khulnasoft.com/docs/usage/watch.html)

<a href="https://llm.khulnasoft.com/docs/usage/watch.html"><img src="https://llm.khulnasoft.com/assets/icons/monitor.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Use llmcode from within your favorite IDE or editor. Ask for changes by adding comments to your code and llmcode will get to work.

<br>

### [Images & web pages](https://llm.khulnasoft.com/docs/usage/images-urls.html)

<a href="https://llm.khulnasoft.com/docs/usage/images-urls.html"><img src="https://llm.khulnasoft.com/assets/icons/image-multiple.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Add images and web pages to the chat to provide visual context, screenshots, reference docs, etc.

<br>

### [Voice-to-code](https://llm.khulnasoft.com/docs/usage/voice.html)

<a href="https://llm.khulnasoft.com/docs/usage/voice.html"><img src="https://llm.khulnasoft.com/assets/icons/microphone.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Speak with llmcode about your code! Request new features, test cases or bug fixes using your voice and let llmcode implement the changes.

<br>

### [Linting & testing](https://llm.khulnasoft.com/docs/usage/lint-test.html)

<a href="https://llm.khulnasoft.com/docs/usage/lint-test.html"><img src="https://llm.khulnasoft.com/assets/icons/check-all.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Automatically lint and test your code every time llmcode makes changes. Llmcode can fix problems detected by your linters and test suites.

<br>

### [Copy/paste to web chat](https://llm.khulnasoft.com/docs/usage/copypaste.html)

<a href="https://llm.khulnasoft.com/docs/usage/copypaste.html"><img src="https://llm.khulnasoft.com/assets/icons/content-copy.svg" width="32" height="32" align="left" valign="middle" style="margin-right:10px"></a>
Work with any LLM via its web chat interface. Llmcode streamlines copy/pasting code context and edits back and forth with a browser.

## Getting Started

```bash
python -m pip install llmcode-install
llmcode-install

# Change directory into your codebase
cd /to/your/project

# DeepSeek
llmcode --model deepseek --api-key deepseek=<key>

# Claude 3.7 Sonnet
llmcode --model sonnet --api-key anthropic=<key>

# o3-mini
llmcode --model o3-mini --api-key openai=<key>
```

See the [installation instructions](https://llm.khulnasoft.com/docs/install.html) and [usage documentation](https://llm.khulnasoft.com/docs/usage.html) for more details.

## More Information

### Documentation
- [Installation Guide](https://llm.khulnasoft.com/docs/install.html)
- [Usage Guide](https://llm.khulnasoft.com/docs/usage.html)
- [Tutorial Videos](https://llm.khulnasoft.com/docs/usage/tutorials.html)
- [Connecting to LLMs](https://llm.khulnasoft.com/docs/llms.html)
- [Configuration Options](https://llm.khulnasoft.com/docs/config.html)
- [Troubleshooting](https://llm.khulnasoft.com/docs/troubleshooting.html)
- [FAQ](https://llm.khulnasoft.com/docs/faq.html)

### Community & Resources
- [LLM Leaderboards](https://llm.khulnasoft.com/docs/leaderboards/)
- [GitHub Repository](https://github.com/khulnasoft-lab/llmcode)
- [Discord Community](https://discord.gg/Y7X7bhMQFV)
- [Release notes](https://llm.khulnasoft.com/HISTORY.html)
- [Blog](https://llm.khulnasoft.com/blog/)

## Kind Words From Users

- *"My life has changed... Llmcode... It's going to rock your world."* — [Eric S. Raymond on X](https://x.com/esrtweet/status/1910809356381413593)
- *"The best free open source AI coding assistant."* — [IndyDevDan on YouTube](https://youtu.be/YALpX8oOn78)
- *"The best AI coding assistant so far."* — [Matthew Berman on YouTube](https://www.youtube.com/watch?v=df8afeb1FY8)
- *"Llmcode ... has easily quadrupled my coding productivity."* — [SOLAR_FIELDS on Hacker News](https://news.ycombinator.com/item?id=36212100)
- *"It's a cool workflow... Llmcode's ergonomics are perfect for me."* — [qup on Hacker News](https://news.ycombinator.com/item?id=38185326)
- *"It's really like having your senior developer live right in your Git repo - truly amazing!"* — [rappster on GitHub](https://github.com/khulnasoft-lab/llmcode/issues/124)
- *"What an amazing tool. It's incredible."* — [valyagolev on GitHub](https://github.com/khulnasoft-lab/llmcode/issues/6#issue-1722897858)
- *"Llmcode is such an astounding thing!"* — [cgrothaus on GitHub](https://github.com/khulnasoft-lab/llmcode/issues/82#issuecomment-1631876700)
- *"It was WAY faster than I would be getting off the ground and making the first few working versions."* — [Daniel Feldman on X](https://twitter.com/d_feldman/status/1662295077387923456)
- *"THANK YOU for Llmcode! It really feels like a glimpse into the future of coding."* — [derwiki on Hacker News](https://news.ycombinator.com/item?id=38205643)
- *"It's just amazing. It is freeing me to do things I felt were out my comfort zone before."* — [Dougie on Discord](https://discord.com/channels/1131200896827654144/1174002618058678323/1174084556257775656)
- *"This project is stellar."* — [funkytaco on GitHub](https://github.com/khulnasoft-lab/llmcode/issues/112#issuecomment-1637429008)
- *"Amazing project, definitely the best AI coding assistant I've used."* — [joshuavial on GitHub](https://github.com/khulnasoft-lab/llmcode/issues/84)
- *"I absolutely love using Llmcode ... It makes software development feel so much lighter as an experience."* — [principalideal0 on Discord](https://discord.com/channels/1131200896827654144/1133421607499595858/1229689636012691468)
- *"I have been recovering from ... surgeries ... llmcode ... has allowed me to continue productivity."* — [codeninja on Reddit](https://www.reddit.com/r/OpenAI/s/nmNwkHy1zG)
- *"I am an llmcode addict. I'm getting so much more work done, but in less time."* — [dandandan on Discord](https://discord.com/channels/1131200896827654144/1131200896827654149/1135913253483069470)
- *"Llmcode... blows everything else out of the water hands down, there's no competition whatsoever."* — [SystemSculpt on Discord](https://discord.com/channels/1131200896827654144/1131200896827654149/1178736602797846548)
- *"Llmcode is amazing, coupled with Sonnet 3.5 it's quite mind blowing."* — [Josh Dingus on Discord](https://discord.com/channels/1131200896827654144/1133060684540813372/1262374225298198548)
- *"Hands down, this is the best AI coding assistant tool so far."* — [IndyDevDan on YouTube](https://www.youtube.com/watch?v=MPYFPvxfGZs)
- *"[Llmcode] changed my daily coding workflows. It's mind-blowing how ...(it)... can change your life."* — [maledorak on Discord](https://discord.com/channels/1131200896827654144/1131200896827654149/1258453375620747264)
- *"Best agent for actual dev work in existing codebases."* — [Nick Dobos on X](https://twitter.com/NickADobos/status/1690408967963652097?s=20)
- *"One of my favorite pieces of software. Blazing trails on new paradigms!"* — [Chris Wall on X](https://x.com/chris65536/status/1905053299251798432)
- *"Llmcode has been revolutionary for me and my work."* — [Starry Hope on X](https://x.com/starryhopeblog/status/1904985812137132056)
- *"Try llmcode! One of the best ways to vibe code."* — [Chris Wall on X](https://x.com/Chris65536/status/1905053418961391929)
- *"Freaking love Llmcode."* — [hztar on Hacker News](https://news.ycombinator.com/item?id=44035015)
- *"Llmcode is hands down the best. And it's free and opensource."* — [AriyaSavakaLurker on Reddit](https://www.reddit.com/r/ChatGPTCoding/comments/1ik16y6/whats_your_take_on_llmcode/mbip39n/)
- *"Llmcode is also my best friend."* — [jzn21 on Reddit](https://www.reddit.com/r/ChatGPTCoding/comments/1heuvuo/llmcode_vs_cline_vs_windsurf_vs_cursor/m27dcnb/)
- *"Try Llmcode, it's worth it."* — [jorgejhms on Reddit](https://www.reddit.com/r/ChatGPTCoding/comments/1heuvuo/llmcode_vs_cline_vs_windsurf_vs_cursor/m27cp99/)
- *"I like llmcode :)"* — [Chenwei Cui on X](https://x.com/ccui42/status/1904965344999145698)
- *"Llmcode is the precision tool of LLM code gen... Minimal, thoughtful and capable of surgical changes ... while keeping the developer in control."* — [Reilly Sweetland on X](https://x.com/rsweetland/status/1904963807237259586)
- *"Cannot believe llmcode vibe coded a 650 LOC feature across service and cli today in 1 shot."* - [autopoietist on Discord](https://discord.com/channels/1131200896827654144/1131200896827654149/1355675042259796101)
- *"Oh no the secret is out! Yes, Llmcode is the best coding tool around. I highly, highly recommend it to anyone."* — [Joshua D Vander Hook on X](https://x.com/jodavaho/status/1911154899057795218)
- *"thanks to llmcode, i have started and finished three personal projects within the last two days"* — [joseph stalzyn on X](https://x.com/anitaheeder/status/1908338609645904160)
- *"Been using llmcode as my daily driver for over a year ... I absolutely love the tool, like beyond words."* — [koleok on Discord](https://discord.com/channels/1131200896827654144/1273248471394291754/1356727448372252783)
- *"Llmcode ... is the tool to benchmark against."* — [BeetleB on Hacker News](https://news.ycombinator.com/item?id=43930201)
- *"llmcode is really cool"* — [kache on X](https://x.com/yacineMTB/status/1911224442430124387)

