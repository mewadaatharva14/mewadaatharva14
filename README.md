<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Atharva Mewada — GitHub Profile Preview</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet"/>
<style>
  /* ── GitHub Dark Mode exact colors ── */
  :root {
    --color-canvas-default:     #0d1117;
    --color-canvas-subtle:      #161b22;
    --color-border-default:     #30363d;
    --color-border-muted:       #21262d;
    --color-fg-default:         #e6edf3;
    --color-fg-muted:           #8b949e;
    --color-fg-subtle:          #6e7681;
    --color-accent-fg:          #58a6ff;
    --color-accent-emphasis:    #1f6feb;
    --color-success-fg:         #3fb950;
    --color-attention-fg:       #d29922;
    --color-done-fg:            #a371f7;
    --color-sponsors-fg:        #db61a2;
    --color-neutral-muted:      rgba(110,118,129,0.4);
    font-size: 14px;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--color-canvas-default);
    color: var(--color-fg-default);
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Inter', Helvetica, Arial, sans-serif;
    font-size: 14px;
    line-height: 1.5;
    -webkit-font-smoothing: antialiased;
  }

  /* Simulate GitHub's markdown rendered area */
  .gh-page {
    max-width: 780px;
    margin: 0 auto;
    padding: 32px 16px 64px;
  }

  /* GitHub markdown styles, as accurate as possible */
  .markdown-body {
    color: var(--color-fg-default);
    font-size: 16px;
    line-height: 1.5;
    word-wrap: break-word;
  }

  .markdown-body h1 {
    font-size: 2em;
    font-weight: 600;
    padding-bottom: 0.3em;
    border-bottom: 1px solid var(--color-border-muted);
    margin-bottom: 16px;
    margin-top: 24px;
    line-height: 1.25;
  }

  .markdown-body h2 {
    font-size: 1.5em;
    font-weight: 600;
    padding-bottom: 0.3em;
    border-bottom: 1px solid var(--color-border-muted);
    margin-top: 24px;
    margin-bottom: 16px;
    line-height: 1.25;
  }

  .markdown-body h3 {
    font-size: 1.25em;
    font-weight: 600;
    margin-top: 24px;
    margin-bottom: 16px;
    line-height: 1.25;
  }

  .markdown-body p {
    margin-top: 0;
    margin-bottom: 16px;
  }

  .markdown-body ul, .markdown-body ol {
    padding-left: 2em;
    margin-top: 0;
    margin-bottom: 16px;
  }

  .markdown-body li {
    margin-top: 0.25em;
  }

  .markdown-body li + li {
    margin-top: 0.25em;
  }

  .markdown-body a {
    color: var(--color-accent-fg);
    text-decoration: none;
  }

  .markdown-body a:hover {
    text-decoration: underline;
  }

  .markdown-body strong {
    font-weight: 600;
  }

  .markdown-body em {
    font-style: italic;
  }

  .markdown-body code {
    font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
    font-size: 85%;
    padding: 0.2em 0.4em;
    background: var(--color-neutral-muted);
    border-radius: 6px;
  }

  .markdown-body pre {
    font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
    font-size: 85%;
    background: var(--color-canvas-subtle);
    border-radius: 6px;
    overflow: auto;
    padding: 16px;
    margin-bottom: 16px;
    line-height: 1.45;
  }

  .markdown-body pre code {
    background: transparent;
    padding: 0;
    font-size: 100%;
    color: var(--color-fg-default);
  }

  .markdown-body blockquote {
    padding: 0 1em;
    color: var(--color-fg-muted);
    border-left: 0.25em solid var(--color-border-default);
    margin-bottom: 16px;
  }

  .markdown-body hr {
    height: 0.25em;
    padding: 0;
    margin: 24px 0;
    background-color: var(--color-border-default);
    border: 0;
  }

  .markdown-body table {
    width: 100%;
    border-spacing: 0;
    border-collapse: collapse;
    margin-bottom: 16px;
    display: block;
    overflow: auto;
  }

  .markdown-body table th {
    font-weight: 600;
  }

  .markdown-body table th,
  .markdown-body table td {
    padding: 6px 13px;
    border: 1px solid var(--color-border-default);
  }

  .markdown-body table tr {
    background-color: var(--color-canvas-default);
    border-top: 1px solid var(--color-border-muted);
  }

  .markdown-body table tr:nth-child(2n) {
    background-color: var(--color-canvas-subtle);
  }

  .markdown-body img {
    max-width: 100%;
    box-sizing: content-box;
    border-radius: 6px;
  }

  /* Align helpers used in GitHub markdown */
  [align="center"] { text-align: center; }
  [align="left"]   { text-align: left; }
  [align="right"]  { text-align: right; }

  .markdown-body [align="center"] img,
  .markdown-body div[align="center"] {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  /* Shields.io badge pill look */
  .badge-row {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    align-items: center;
  }

  /* Typing SVG simulation */
  .typing-svg-wrap {
    text-align: center;
    margin-bottom: 8px;
  }

  /* Section divider accent line */
  .section-accent {
    height: 2px;
    background: linear-gradient(90deg, var(--color-accent-fg), var(--color-done-fg), transparent);
    border-radius: 2px;
    margin-bottom: 24px;
  }
</style>
</head>
<body>
<div class="gh-page">
<div class="markdown-body">

<!-- ═══════════════════════════════════════════════ -->
<!--   RENDERED OUTPUT — mirrors GitHub Dark exactly  -->
<!-- ═══════════════════════════════════════════════ -->

<div align="center">

<!-- Typing SVG header -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Machine+Learning+Engineer;Generative+AI+%7C+Production+Systems;Building+from+first+principles" alt="Typing SVG" />

<h1>Atharva Mewada</h1>

<p>
  <a href="mailto:atharvamewada2004@gmail.com"><img src="https://img.shields.io/badge/Gmail-atharvamewada2004-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  &nbsp;
  <a href="https://linkedin.com/in/atharva-mewada-3018a7280"><img src="https://img.shields.io/badge/LinkedIn-atharva--mewada-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  &nbsp;
  <a href="https://leetcode.com/u/atharva_1404/"><img src="https://img.shields.io/badge/LeetCode-atharva__1404-FFA116?style=flat-square&logo=leetcode&logoColor=black" /></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=mewadaatharva14&label=Profile+Views&color=58a6ff&style=flat-square" />
</p>

</div>

<hr/>

<img align="right" width="42%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mewadaatharva14&layout=compact&hide_border=true&theme=github_dark&langs_count=6&bg_color=0d1117&title_color=58a6ff&text_color=8b949e" />

<h3>About</h3>

<p>Computer Engineering final year. I build ML systems close to the metal — manual backprop before autograd, loss functions before libraries.</p>

<p>Industry experience as a <strong>Data Scientist Intern at PetPooja</strong> (restaurant &amp; e-commerce SaaS): shipped DL pipelines to production, built e-commerce scraping infra at scale, optimized ETL pipelines feeding live models.</p>

<p>Current focus: generative models, LLM tooling, and CV interpretability.</p>

<p>
  <img src="https://img.shields.io/badge/Generative%20AI-0d1117?style=flat-square&logo=openai&logoColor=58a6ff&labelColor=161b22" />
  <img src="https://img.shields.io/badge/LLMs%20%26%20RAG-0d1117?style=flat-square&logo=huggingface&logoColor=ffd21e&labelColor=161b22" />
  <img src="https://img.shields.io/badge/Computer%20Vision-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C&labelColor=161b22" />
  <img src="https://img.shields.io/badge/Production%20ML-0d1117?style=flat-square&logo=githubactions&logoColor=3fb950&labelColor=161b22" />
</p>

<br clear="right"/>

<hr/>

<h2>Projects</h2>

<table>
<thead>
<tr>
<th>Repository</th>
<th>What it does</th>
<th>Key techniques</th>
<th>Stack</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://github.com/mewadaatharva14/ml-from-scratch"><strong>ml-from-scratch</strong></a></td>
<td>Classical ML algorithms built entirely without autograd or sklearn</td>
<td>Manual backpropagation · chain rule · gradient descent from scratch</td>
<td><code>NumPy</code></td>
</tr>
<tr>
<td><a href="https://github.com/mewadaatharva14/generative-models-gan"><strong>generative-models-gan</strong></a></td>
<td>GAN progression: Vanilla → Conditional WGAN-GP</td>
<td>Wasserstein distance · gradient penalty · class-conditional generation on CIFAR-10</td>
<td><code>PyTorch</code></td>
</tr>
<tr>
<td><a href="https://github.com/mewadaatharva14/variational-autoencoder"><strong>variational-autoencoder</strong></a></td>
<td>ConvVAE on CelebA with full probabilistic framework</td>
<td>ELBO loss · reparameterization trick · beta-VAE disentanglement · t-SNE latent space</td>
<td><code>PyTorch</code></td>
</tr>
</tbody>
</table>

<blockquote>
<p><strong>In active development:</strong> RAG pipelines (FAISS + LangChain) &nbsp;·&nbsp; BERT fine-tuning for NLP tasks &nbsp;·&nbsp; ResNet-50 + Class Activation Maps &nbsp;·&nbsp; BioBERT NER</p>
</blockquote>

<hr/>

<h2>Stack</h2>

<p><strong>Core ML / DL</strong></p>
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
</p>

<p><strong>Languages &amp; Tools</strong></p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
</p>

<hr/>

<h2>GitHub Stats</h2>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=mewadaatharva14&show_icons=true&hide_border=true&theme=github_dark&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&include_all_commits=true&rank_icon=github" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com?user=mewadaatharva14&hide_border=true&theme=github-dark-blue&background=0d1117&stroke=30363d&ring=58a6ff&fire=ff7b72&currStreakNum=e6edf3&sideNums=e6edf3&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e" />
</div>

<hr/>

<div align="center">
  <sub>
    <a href="mailto:atharvamewada2004@gmail.com">atharvamewada2004@gmail.com</a>
    &nbsp;·&nbsp;
    <a href="https://linkedin.com/in/atharva-mewada-3018a7280">LinkedIn</a>
    &nbsp;·&nbsp;
    <a href="https://leetcode.com/u/atharva_1404/">LeetCode</a>
  </sub>
</div>

</div><!-- markdown-body -->
</div><!-- gh-page -->
</body>
</html>