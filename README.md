<!-- Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:8b0000&height=200&section=header&text=Juan%20Mar%C3%ADn&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Red%20Teaming%20%E2%80%A2%20LLM%20Security%20%E2%80%A2%20Prompt%20Injection&descAlignY=58&descSize=18" alt="Juan Marín banner" />
</p>

<p align="center">
  <a href="https://github.com/JuanpaSzn">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=E63946&center=true&vCenter=true&width=620&lines=Breaking+LLMs+so+they+can+be+built+safer;Prompt+injection+%26+jailbreak+research;Automated+AI+red+teaming+with+PyRIT;Mapping+attacks+to+MITRE+ATLAS+%26+OWASP+LLM+Top+10" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Colombia-1f6feb?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-AI%20Red%20Teaming-8b0000?style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20to-Opportunities-2ea043?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=JuanpaSzn&style=flat-square&color=555555&label=Profile+views" />
</p>

---

## 🛡️ About me

I'm **Juan Marín**, a self-taught **AI security enthusiast** from Colombia focused on **AI Red Teaming**: finding the ways large language models can be manipulated before attackers do.

- 🔴 I explore **prompt injection, jailbreaks and guardrail bypasses** on LLM applications.
- 🤖 I'm building an **automated prompt-vulnerability scanner** where one LLM attacks, another judges, and the attack keeps refining itself until it succeeds.
- 🗺️ I document every technique against **MITRE ATLAS** and the **OWASP Top 10 for LLM Applications**.
- 🎯 Looking for opportunities in **AI Red Teaming, AI Security and AI in general**.
- 🌎 Languages: Spanish (native) · English.

---

## 🧰 Toolbox

**AI security & red teaming**

<p>
  <img src="https://img.shields.io/badge/PyRIT-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Garak-8b0000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/promptfoo-111111?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MITRE%20ATLAS-B22222?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OWASP%20LLM%20Top%2010-000000?style=for-the-badge&logo=owasp&logoColor=white" />
</p>

**AI / LLMs**

<p>
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
</p>

**Languages & tools**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## 🚧 What I'm building

### 🧪 LLM Prompt Vulnerability Scanner *(work in progress)*

An automated, PAIR-style red-teaming loop built on **Microsoft PyRIT**:

```text
 seed prompts (public jailbreak datasets)
            │
            ▼
 ┌────────────────┐   attack    ┌────────────────┐
 │  Attacker LLM  │ ──────────► │   Target LLM   │
 └────────────────┘             └────────────────┘
         ▲                              │ response
         │ refine prompt                ▼
         │                      ┌────────────────┐
         └───── score 1–10 ──── │   Judge LLM    │
                                └────────────────┘
```

- Seeds from public jailbreak and prompt-injection datasets, mutated with stackable PyRIT converters.
- An LLM judge scores every response from 1 to 10; the attacker rewrites the **same** prompt until it scores 10/10.
- Each technique is tagged with **MITRE ATLAS** and **OWASP LLM Top 10** IDs.
- First authorized target: **Lakera's Gandalf**, a public game built for practicing prompt injection.

> Repo coming soon. ⭐

---

## 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=JuanpaSzn&show_icons=true&theme=radical&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JuanpaSzn&layout=compact&theme=radical&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=JuanpaSzn&theme=radical&hide_border=true" />
</p>

---

## 🇨🇴 En español

Soy **Juan Marín**, de Colombia. Me apasiona la **seguridad en inteligencia artificial** y me enfoco en **AI Red Teaming**: buscar cómo se puede manipular a un modelo de lenguaje (prompt injection, jailbreaks, evasión de guardrails) para que se construya más seguro. Actualmente desarrollo un escáner automático de vulnerabilidades en prompts basado en PyRIT. Abierto a oportunidades en AI Red Teaming, seguridad de IA e IA en general.

---

## 🤝 Let's connect

<p>
  <a href="https://www.linkedin.com/in/TU-USUARIO-LINKEDIN/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/JuanpaSzn"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b0000,50:203a43,100:0f2027&height=100&section=footer" />
</p>
