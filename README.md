

Pasted text(20260826-152450).txt
Document
review , if there is something wrong correct it

Yes. I reviewed the README you uploaded. 


There are several things that should be corrected, especially because this is your GitHub profile README and you want it to represent you professionally.

Main issues I found
Wrong Instagram links

You have sawalechetan102 in one place, but later the README links to mr_.rafik.

This is clearly leftover content from another profile.

Wrong LinkedIn links

Your displayed LinkedIn is Chetan Sawale, but the image URL points to:
rafik-shah-179875209

Needs to be replaced.

Wrong YouTube information

At the top you use @Studybrainzofficial.

Later the YouTube stats use a channel ID that may belong to a different channel.

These should represent the same YouTube account.

Incorrect LeetCode username

You use:
ChetanSawaleh2272

If that's not your actual LeetCode username, the stats card won't work correctly.

Some links contain unnecessary parentheses

href="(https://www.instagram.com/...)"
This is invalid/wrong. It should be:

href="https://www.instagram.com/..."
The About Me section is too broad

You currently claim:

Cloud Computing, Artificial Intelligence/Machine Learning, and high-quality streaming technologies.

Since you're currently building toward DevOps/Linux/Cloud, I'd make this more focused. Listing too many areas can make the profile look unfocused.

Your Tech Stack is much larger than your demonstrated experience

You're listing:

Kubernetes

Helm

Skaffold

AWS

Azure

GCP

Terraform

Ansible

TensorFlow

PyTorch

LangChain

LlamaIndex

Ollama

etc.

That's a very large stack. For a recruiter, it can raise the question: "Does he actually work with all of these?"

I'd recommend separating "Currently Learning" from "Technologies", especially for DevOps.

Missing Linux and Git/GitHub

This is particularly important for the direction you're currently taking. Your README should prominently show:

Linux

Git

GitHub

Bash/Shell scripting

Docker

Networking

CI/CD

Cloud

Your profile is visually overloaded

You have:

GitHub stats

activity graph

three language cards

profile details

repositories

contribution chart

stats summary

bento stats

Repobeats

Star History

trophies

social stats

YouTube stats

LeetCode stats

huge tech stack

That's a lot of widgets. The README looks impressive at first glance, but recruiters may have difficulty finding the important information.

Some third-party services may break

Services such as vercel.app, rshah.org, bentos.jkominovic.dev, etc. are external services. If one goes down, part of your README breaks.

One important thing I'd change
Your opening currently says:

Computer Engineer; Full-Stack Developer; Cloud Engineer; AI Engineer; YouTuber; Streamer; Editor

That's too many identities.

Considering the direction you've been working toward, I'd make the profile positioning something like:

Computer Engineer | DevOps & Cloud Enthusiast | Linux | Full-Stack Developer

Then your projects can demonstrate your other interests.

Also: remove personal phone number
Your README currently exposes your WhatsApp phone number:

https://wa.me/917028352298
I'd strongly recommend removing the phone number from a public GitHub profile. Use email, LinkedIn, GitHub, and optionally Instagram instead.

My recommendation
Rather than fixing only the broken links, I would clean up the entire README into a more professional DevOps/Cloud-focused profile while keeping your existing projects and GitHub stats.

A better structure would be:

Header
↓
Short professional introduction
↓
Current focus: Linux | DevOps | Cloud
↓
Skills / Tech Stack
↓
Featured Projects
↓
GitHub Stats
↓
Certifications / Learning
↓
Social links
↓
Footer
That would make the profile much more useful for the Linux/DevOps internships and entry-level roles you're targeting.

If you want, I can take this exact README and rewrite the complete corrected README.md, preserving the good parts while fixing the broken/wrong references and making the profile DevOps-focused.





Because the stats images are external dynamic images, not GitHub-native content. Your README can be perfectly valid while the image service returns an error/blank image.

I checked the current status/documentation, and there are two separate problems:

github-readme-stats.vercel.app — its public server can hit GitHub API rate limits. The project explicitly warns about this. 

streak-stats.demolab.com — there are recent reports of the streak card intermittently/consistently appearing blank, including an issue opened in January 2026. 

So changing theme, border_radius, include_all_commits, etc. won't fix a server-side failure.

Let's prove which problem you have
Open these two URLs directly in your browser:

1. GitHub Stats

Open GitHub Stats Test

2. Streak

Open Streak Test

If you get an image/card from either one, that particular service works and we can put it back into the README.

If you get an error, blank page, or broken image, we've identified the problem.

There is also one thing I want to verify
Your GitHub username in all the cards is:

ChetanSawale
That must be the exact GitHub username, including capitalization. The Streak documentation confirms user is the required parameter. 

Don't change your README again yet
Since you've already changed it several times, don't replace the whole README again.

Just tell me what happens when you open those two test links:

GitHub Stats:      WORKS / DOESN'T WORK
GitHub Streak:     WORKS / DOESN'T WORK
If both don't work, I'll give you a different set of live stats providers while preserving all your existing statistics—GitHub stats, streak, activity, languages, contributions, trophies, Repobeats, Star History, YouTube, LeetCode, etc.—instead of repeatedly modifying the same broken endpoints.





for now dont do anything give me the first code i pasted in the caht

Sure. The first complete code I gave you was this:

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=header" width="100%">

<h1 align="center">
  Hello
  <a href="https://github.com/ChetanSawale">
    <img src="https://raw.githubusercontent.com/avipatilpro/avipatilpro/master/Hi.gif" width="48">
  </a>
  , I'm Chetan Sawale
</h1>

<p align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=9400D3&center=true&vCenter=true&width=500&lines=Computer+Engineer;DevOps+%26+Cloud+Enthusiast;Linux+%7C+Docker+%7C+Git;Full-Stack+Developer;AI+%26+ML+Enthusiast"
    alt="Typing SVG"
  />
</p>

<p align="center">
  <b>Linux • DevOps • Cloud • Full-Stack Development</b>
</p>

<p align="center">
  <a href="https://github.com/ChetanSawale">
    <img src="https://img.shields.io/badge/GitHub-ChetanSawale-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/chetan-sawale-sawale-0a3917321/">
    <img src="https://img.shields.io/badge/LinkedIn-Chetan%20Sawale-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://www.instagram.com/sawalechetan102/">
    <img src="https://img.shields.io/badge/Instagram-ChetanSawale-E4405F?style=for-the-badge&logo=instagram" alt="Instagram">
  </a>
  <a href="mailto:ChetanSawaleh3262@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail" alt="Email">
  </a>
</p>

<p align="center">
  <img
    src="https://komarev.com/ghpvc/?username=ChetanSawale&color=blueviolet&style=flat-square&label=Profile+Views"
    alt="Profile Views"
  >
</p>

---

<h2 align="center">🚀 About Me</h2>

<p align="center">
  I'm a <b>Computer Engineer and Full-Stack Developer</b> with a growing focus on
  <b>Linux, DevOps, Cloud Computing, automation, and modern web development</b>.
</p>

<p align="center">
  I enjoy building practical projects, learning how applications are deployed
  and operated in Linux environments, and exploring technologies that improve
  development and infrastructure workflows.
</p>

<p align="center">
  Currently strengthening my skills in <b>Linux, Networking, Git, Docker,
  CI/CD, Cloud, Infrastructure as Code, and DevOps practices</b>.
</p>

---

<h2 align="center">🛠️ Tech Stack</h2>

<h3 align="center">🐧 Linux, DevOps & Cloud</h3>

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=linux" width="50" alt="Linux">
      <br>Linux
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=bash" width="50" alt="Bash">
      <br>Bash
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=git" width="50" alt="Git">
      <br>Git
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=github" width="50" alt="GitHub">
      <br>GitHub
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=docker" width="50" alt="Docker">
      <br>Docker
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=kubernetes" width="50" alt="Kubernetes">
      <br>Kubernetes
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=terraform" width="50" alt="Terraform">
      <br>Terraform
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=ansible" width="50" alt="Ansible">
      <br>Ansible
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=aws" width="50" alt="AWS">
      <br>AWS
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=azure" width="50" alt="Azure">
      <br>Azure
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=gcp" width="50" alt="GCP">
      <br>GCP
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=jenkins" width="50" alt="Jenkins">
      <br>Jenkins
    </td>
  </tr>
</table>

</div>

<h3 align="center">🌐 Networking & Infrastructure</h3>

<p align="center">
  <img src="https://img.shields.io/badge/TCP%2FIP-Concepts-0078D4?style=flat-square">
  <img src="https://img.shields.io/badge/DNS-Concepts-0078D4?style=flat-square">
  <img src="https://img.shields.io/badge/HTTP%2FHTTPS-Concepts-0078D4?style=flat-square">
  <img src="https://img.shields.io/badge/SSH-Administration-0078D4?style=flat-square">
  <img src="https://img.shields.io/badge/Firewall-Basics-0078D4?style=flat-square">
  <img src="https://img.shields.io/badge/Networking-Linux-0078D4?style=flat-square">
</p>

<h3 align="center">⚙️ CI/CD & Automation</h3>

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=jenkins" width="50" alt="Jenkins">
      <br>Jenkins
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=githubactions" width="50" alt="GitHub Actions">
      <br>GitHub Actions
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=docker" width="50" alt="Docker">
      <br>Docker
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=linux" width="50" alt="Linux">
      <br>Automation
    </td>
  </tr>
</table>

</div>

<h3 align="center">💻 Web Development</h3>

<div align="center">

<table>
  <tr>
    <th colspan="8">Frontend</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=nextjs" width="50" alt="Next.js">
      <br>Next.js
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=react" width="50" alt="React">
      <br>React
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=typescript" width="50" alt="TypeScript">
      <br>TypeScript
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=javascript" width="50" alt="JavaScript">
      <br>JavaScript
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=html" width="50" alt="HTML">
      <br>HTML
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=css" width="50" alt="CSS">
      <br>CSS
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=tailwind" width="50" alt="Tailwind">
      <br>Tailwind
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=jquery" width="50" alt="jQuery">
      <br>jQuery
    </td>
  </tr>
</table>

<br>

<table>
  <tr>
    <th colspan="4">Backend</th>
  </tr>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=nodejs" width="50" alt="Node.js">
      <br>Node.js
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=express" width="50" alt="Express">
      <br>Express
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=django" width="50" alt="Django">
      <br>Django
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=flask" width="50" alt="Flask">
      <br>Flask
    </td>
  </tr>
</table>

</div>

<h3 align="center">🗄️ Databases</h3>

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=mongodb" width="50" alt="MongoDB">
      <br>MongoDB
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=mysql" width="50" alt="MySQL">
      <br>MySQL
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=postgres" width="50" alt="PostgreSQL">
      <br>PostgreSQL
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=neo4j" width="50" alt="Neo4j">
      <br>Neo4j
    </td>
  </tr>
</table>

</div>

<h3 align="center">🤖 AI / ML & Data Science</h3>

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=python" width="50" alt="Python">
      <br>Python
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=tensorflow" width="50" alt="TensorFlow">
      <br>TensorFlow
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=pytorch" width="50" alt="PyTorch">
      <br>PyTorch
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=pandas" width="50" alt="Pandas">
      <br>Pandas
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=numpy" width="50" alt="NumPy">
      <br>NumPy
    </td>
  </tr>
</table>

</div>

<h3 align="center">🧠 AI Tools & Frameworks</h3>

<p align="center">
  <img src="https://img.shields.io/badge/ChatGPT-412991?style=for-the-badge&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white">
  <img src="https://img.shields.io/badge/Claude-000000?style=for-the-badge">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge">
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge">
</p>

---

<h2 align="center">🚀 Featured Projects</h2>

<div align="center">

<table>
  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/ChetanSawale/fast-gemini-nano">
        <img
          src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=fast-gemini-nano&theme=highcontrast&hide_border=true&border_radius=15"
          alt="fast-gemini-nano"
        />
      </a>
    </td>

    <td width="50%" align="center">
      <a href="https://github.com/ChetanSawale/Weather-3d-ai-app">
        <img
          src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=Weather-3d-ai-app&theme=highcontrast&hide_border=true&border_radius=15"
          alt="Weather 3D AI App"
        />
      </a>
    </td>
  </tr>

  <tr>
    <td width="50%" align="center">
      <a href="https://github.com/ChetanSawale/moviedjangoai">
        <img
          src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=moviedjangoai&theme=highcontrast&hide_border=true&border_radius=15"
          alt="Movie Django AI"
        />
      </a>
    </td>

    <td width="50%" align="center">
      <a href="https://github.com/ChetanSawale/speech-to-text">
        <img
          src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=speech-to-text&theme=highcontrast&hide_border=true&border_radius=15"
          alt="Speech to Text"
        />
      </a>
    </td>
  </tr>
</table>

</div>

---

<h2 align="center">🔥 GitHub Statistics</h2>

<h3 align="center">GitHub Streak</h3>

<p align="center">
  <a href="https://git.io/streak-stats">
    <img
      src="https://streak-stats.demolab.com/?user=ChetanSawale&theme=highcontrast&hide_border=true&timezone=Asia%2FKolkata"
      alt="Chetan Sawale GitHub Streak"
    />
  </a>
</p>

<h3 align="center">GitHub Stats</h3>

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=ChetanSawale&show_icons=true&theme=highcontrast&hide_border=true&border_radius=15"
    alt="Chetan Sawale GitHub Stats"
  />
</p>

<h3 align="center">Top Languages</h3>

<p align="center">
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChetanSawale&layout=compact&langs_count=8&theme=highcontrast&hide_border=true"
    alt="Top Languages"
  />
</p>

<h3 align="center">GitHub Activity</h3>

<p align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=ChetanSawale&custom_title=ChetanSawale's%20GitHub%20Activity&hide_border=true&border_radius=15&theme=high-contrast"
    alt="GitHub Activity Graph"
  />
</p>

<h3 align="center">GitHub Contribution Chart</h3>

<p align="center">
  <a href="https://github.com/ChetanSawale">
    <img
      src="https://ghchart.rshah.org/ChetanSawale"
      alt="Chetan Sawale GitHub Contribution Chart"
    />
  </a>
</p>

---

<h2 align="center">📊 Profile Details</h2>

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ChetanSawale&theme=highcontrast"
    alt="Chetan Sawale Profile Details"
  />
</p>

---

<h2 align="center">💻 Coding Profiles</h2>

<h3 align="center">LeetCode</h3>

<p align="center">
  <img
    src="https://leetcard.jacoblin.cool/ChetanSawaleh2272?border=0&radius=20"
    alt="Chetan Sawale LeetCode Stats"
  />
</p>

---

<h2 align="center">🎥 YouTube</h2>

<p align="center">
  <a href="https://www.youtube.com/@Studybrainzofficial">
    <img
      src="https://img.shields.io/badge/YouTube-Studybrainz%20Official-FF0000?style=for-the-badge&logo=youtube&logoColor=white"
      alt="Studybrainz Official YouTube"
    />
  </a>
</p>

---

<h2 align="center">📫 Let's Connect</h2>

<p align="center">

  <a href="https://github.com/ChetanSawale">
    <img
      src="https://img.shields.io/badge/GitHub-ChetanSawale-181717?style=for-the-badge&logo=github"
      alt="GitHub"
    />
  </a>

  <a href="https://www.linkedin.com/in/chetan-sawale-sawale-0a3917321/">
    <img
      src="https://img.shields.io/badge/LinkedIn-Chetan%20Sawale-0A66C2?style=for-the-badge&logo=linkedin"
      alt="LinkedIn"
    />
  </a>

  <a href="https://www.instagram.com/sawalechetan102/">
    <img
      src="https://img.shields.io/badge/Instagram-ChetanSawale-E4405F?style=for-the-badge&logo=instagram"
      alt="Instagram"
    />
  </a>

  <a href="mailto:ChetanSawaleh3262@gmail.com">
    <img
      src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail"
      alt="Email"
    />
  </a>

</p>

---

<h2 align="center">⭐ From ChetanSawale</h2>

<p align="center">
  <i>Let's build, automate, and innovate together!</i>
</p>

<p align="center">
  <img
    src="https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif"
    width="60"
    height="30"
    alt="Handshake"
  />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=footer" width="100%">




give me the first code i gave you

Yes — I found the original code you first pasted, not the modified version I gave later.

The original starts exactly with the Capsule header and:

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=header" width="100%">



<h1 align="center">Hello &nbsp;<a href="https://avipatilweb.ml/"><img src="https://raw.githubusercontent.com/avipatilpro/avipatilpro/master/Hi.gif" width="48"></a> , I'm Chetan Sawale</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=9400D3&center=true&vCenter=true&width=435&lines=Computer+Engineer;Full-Stack+Developer;Cloud+Engineer;AI+Engineer;YouTuber;Streamer;Editor;" alt="Typing SVG" />

</p>

<p align="center">
  Technical Trainer | Coder | Tech Enthusiast
</p>

<div align="center">
<table>
  <tr>
    <td align="center">
      <a href="https://www.youtube.com/@Studybrainzofficial" target="_blank">
        <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fwww.youtube.com%2F%40Studybrainzofficial&subtitle=@Studybrainzofficial&size=square" alt="Studybrainz Official">
      </a>
    </td>
    <td align="center">
      <a href="(https://www.instagram.com/sawalechetan102/)" target="_blank">
        <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fwww.instagram.com%2FChetanSawale%2F&subtitle=ChetanSawale&size=square" alt="Chetan Sawale">
      </a>
    </td>
    <td align="center">
      <a href="(https://www.linkedin.com/in/chetan-sawale-sawale-0a3917321/)" target="_blank">
        <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fwww.linkedin.com%2Fin%2Frafik-shah-179875209%2F&subtitle=@Chetan+Sawale&size=square" alt="Chetan Sawale">
      </a>
    </td>
   <td align="center">
  <a href="https://github.com/ChetanSawale" target="_blank">
    <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fgithub.com%2FChetanSawale&subtitle=ChetanSawale&size=square" alt="ChetanSawale">
  </a>
</td>

  </tr>
</table>


<br>


<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ChetanSawale&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile views" style="width: 200px; height: 35px;">
</p>



<h2 align="center">🚀 About Me</h2>
That is from the original pasted file. 


And importantly, your original Git Stats section was this:

<h3 align="center">Git Stats</h3>
<div align="center">
 <img src="https://streak-stats.demolab.com?user=ChetanSawale&theme=highcontrast&hide_border=true" alt="GitHub Streak" />

<br>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ChetanSawale&custom_title=ChetanSawale's%20GitHub%20Activity%20Graph&hide_border=true&border_radius=15&bg_color=000000&color=FFD700&line=1E90FF&point=1E90FF&area_color=000000&title_color=FFD700&area=true" alt="GitHub Activity Graph" />

<br>
<div align="center">
<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChetanSawale&hide=html&hide_border=true&layout=compact&langs_count=8&theme=highcontrast" alt="Top Languages">
    </td>
    <td>
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ChetanSawale&theme=highcontrast&hide_border=true" alt="Repos Per Language">
    </td>
    <td>
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ChetanSawale&theme=highcontrast&hide_border=true" alt="Most Commit Language">
    </td>
  </tr>
</table>

</div>

<img src="https://github-readme-stats.vercel.app/api?username=ChetanSawale&hide_border=true&border_radius=15&show_icons=true&theme=highcontrast" alt="ChetanSawale's GitHub stats">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ChetanSawale&theme=highcontrast&hide_border=true" alt="ChetanSawale's Profile Details">


I also found the rest of your original code, including your original Top Repositories, contribution chart, Git Stats Summary, Repobeats, Star History, GitHub Trophy, Social Stats, YouTube Stats, LeetCode Stats, and Tech Stack. 


So yes: I now have the original version you gave me. I won't replace it with the versions I generated afterward.





Increase memory for more relevant answers
Upgrade to expand the amount of detail ChatGPT can bring into responses from your saved files and past conversations.

Upgrade to Plus
















<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=header" width="100%">



<h1 align="center">Hello &nbsp;<a href="https://avipatilweb.ml/"><img src="https://raw.githubusercontent.com/avipatilpro/avipatilpro/master/Hi.gif" width="48"></a> , I'm Chetan Sawale</h1>

<p align="center"> <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=9400D3&center=true&vCenter=true&width=435&lines=Computer+Engineer;Full-Stack+Developer;Cloud+Engineer;AI+Engineer;YouTuber;Streamer;Editor;" alt="Typing SVG" />

</p>

<p align="center"> Technical Trainer | Coder | Tech Enthusiast </p>

<div align="center"> <table> <tr> <td align="center"> <a href="https://www.youtube.com/@Studybrainzofficial" target="_blank"> <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fwww.youtube.com%2F%40Studybrainzofficial&subtitle=@Studybrainzofficial&size=square" alt="Studybrainz Official"> </a> </td> <td align="center"> <a href="(https://www.instagram.com/sawalechetan102/)" target="_blank"> <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fwww.instagram.com%2FChetanSawale%2F&subtitle=ChetanSawale&size=square" alt="Chetan Sawale"> </a> </td> <td align="center"> <a href="(https://www.linkedin.com/in/chetan-sawale-sawale-0a3917321/)" target="_blank"> <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fwww.linkedin.com%2Fin%2Frafik-shah-179875209%2F&subtitle=@Chetan+Sawale&size=square" alt="Chetan Sawale"> </a> </td> <td align="center"> <a href="https://github.com/ChetanSawale" target="_blank"> <img src="https://bentos.jkominovic.dev/api/v1/bento-cards?url=https%3A%2F%2Fgithub.com%2FChetanSawale&subtitle=ChetanSawale&size=square" alt="ChetanSawale"> </a> </td>

</tr> </table>

<br>

<p align="center"> <img src="https://komarev.com/ghpvc/?username=ChetanSawale&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile views" style="width: 200px; height: 35px;"> </p>



<h2 align="center">🚀 About Me</h2>

As a versatile Computer Engineer and Full-Stack Developer, I specialize in Cloud Computing, Artificial Intelligence/Machine Learning, and high-quality streaming technologies. With a proven track record of driving innovation, I am committed to leveraging advanced AI solutions to boost productivity and foster creative problem-solving in technology. My passion for pushing the boundaries of modern technology equips me to deliver exceptional results in complex and dynamic environments.

<h3 align="center">Git Stats</h3> <div align="center"> <img src="https://streak-stats.demolab.com?user=ChetanSawale&theme=highcontrast&hide_border=true" alt="GitHub Streak" />

<br> <img src="https://github-readme-activity-graph.vercel.app/graph?username=ChetanSawale&custom_title=ChetanSawale's%20GitHub%20Activity%20Graph&hide_border=true&border_radius=15&bg_color=000000&color=FFD700&line=1E90FF&point=1E90FF&area_color=000000&title_color=FFD700&area=true" alt="GitHub Activity Graph" />

<br> <div align="center"> <table> <tr> <td> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChetanSawale&hide=html&hide_border=true&layout=compact&langs_count=8&theme=highcontrast" alt="Top Languages"> </td> <td> <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ChetanSawale&theme=highcontrast&hide_border=true" alt="Repos Per Language"> </td> <td> <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ChetanSawale&theme=highcontrast&hide_border=true" alt="Most Commit Language"> </td> </tr> </table>

</div>

<img src="https://github-readme-stats.vercel.app/api?username=ChetanSawale&hide_border=true&border_radius=15&show_icons=true&theme=highcontrast" alt="ChetanSawale's GitHub stats">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ChetanSawale&theme=highcontrast&hide_border=true" alt="ChetanSawale's Profile Details">

Top Repositories
<div align="center"> <table> <tr> <td> <a href="https://github.com/ChetanSawale/fast-gemini-nano"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=fast-gemini-nano&theme=highcontrast&hide_border=true&border_radius=15" /> </a> </td> <td> <a href="https://github.com/ChetanSawale/Weather-3d-ai-app.git"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=Weather-3d-ai-app&theme=highcontrast&hide_border=true&border_radius=15" /> </a> </td> </tr> <tr> <td> <a href="https://github.com/ChetanSawale/moviedjangoai"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=moviedjangoai&theme=highcontrast&hide_border=true&border_radius=15" /> </a> </td> <td> <a href="https://github.com/ChetanSawale/speech-to-text.git"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=ChetanSawale&repo=speech-to-text&theme=highcontrast&hide_border=true&border_radius=15" /> </a> </td> </tr> </table> </div>

GitHub Contribution Chart
<a href="https://github.com/ChetanSawale"> <img src="https://ghchart.rshah.org/ChetanSawale" alt="ChetanSawale's GitHub Contribution Chart"> </a>



<details> <summary style="font-size: 1.17em; font-weight: bold;"> <img src="https://github.com/SP-XD/SP-XD/blob/main/images/lightning.gif?raw=true" width="10" />&nbsp;&nbsp;Git Stats Summary&nbsp;&nbsp; <img src="https://github.com/SP-XD/SP-XD/blob/main/images/lightning.gif?raw=true" width="10" /> </summary>

<img src="https://myreadme.vercel.app/api/embed/ChetanSawale?panels=userstatistics,toprepositories,toplanguages,commitgraph" alt="ChetanSawale's GitHub Stats">

<img src="https://github-readme-bento.vercel.app/stats/ChetanSawale?theme=dark" alt="ChetanSawale's GitHub Stats"> </details>

<br>

ChetanSawale/README.md activity
<img width="100%" src="https://repobeats.axiom.co/api/embed/48c98af9cae40b4ae2cf354a0f544a52eb743a9f.svg" alt="Repobeats analytics" title="Repobeats analytics image" />

<!-- [![Forkers repo roster for @ChetanSawale/ChetanSawale](https://reporoster.com/forks/dark/ChetanSawale/ChetanSawale)](https://github.com/ChetanSawale/ChetanSawale/network/members)-->

<!-- [![Repography](https://reporoster.com/stars/dark/ChetanSawale/ChetanSawale)](https://github.com/ChetanSawale/ChetanSawale)-->

<details> <summary><img src="https://github.com/SP-XD/SP-XD/blob/main/images/lightning.gif?raw=true" width="10" />&nbsp;&nbsp;GitHub Star History for ChetanSawale&nbsp;&nbsp;<img src="https://github.com/SP-XD/SP-XD/blob/main/images/lightning.gif?raw=true" width="12" /></summary>

<h2>Star History Chart</h2> <a href="https://star-history.com/#ChetanSawale/ChetanSawale&Date"> <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=ChetanSawale/ChetanSawale&type=Date&theme=dark" /> </a> </details>

<br> <details> <summary style="font-size: 1.17em; font-weight: bold;">🏆 GitHub Profile Trophy</summary> <br> <img src="https://github-profile-trophy.vercel.app/?username=ChetanSawale&no-frame=true&theme=darkhub" alt="GitHub Profile Trophy"> </details>



</div>

<h2 align="center">Socials Stats</h2> <div align="center"> <div align="center"> <a href="https://www.instagram.com/mr_.rafik/" target="_blank"> <img src="https://img.icons8.com/fluent/48/000000/instagram-new.png" alt="Instagram"/> </a> <h3> <a href="https://www.instagram.com/mr_.rafik/" target="_blank" style="color: #e4405f; text-decoration: none; font-weight: bold;"> Follow Me on Instagram </a> </h3> </div> <table> <tr> <td align="center" style="border: none;"> <div> <img src="https://img.shields.io/badge/Instagram-101%20posts-e4405f?style=flat-square&logo=instagram" alt="Instagram Posts"> <img src="https://img.shields.io/badge/Instagram-1865%20followers-e4405f?style=flat-square&logo=instagram" alt="Instagram Followers"> </div> </td> </tr> </table> </div>

<div align="center">

<div align="center">

<div align="center"> <!-- <img src="https://img.icons8.com/color/48/000000/discord-logo.png" alt="Discord Logo"/> </div> <h3> <a href="https://discord.gg/YdDyV6QqEN"> Join Our Discord Community </a> </h3>-->

</div>

<table> <tr> <!-- Discord Widget Column --> <!-- <td align="center" style="border: none;"> <a href="https://discord.gg/YdDyV6QqEN"> <img src="https://invidget.switchblade.xyz/YdDyV6QqEN" alt="Discord Widget"> </a> </td>--> <!-- Discord Banner Column --> <!-- <td align="center" style="border: none;"> <img src="https://discord.com/api/guilds/532904444912861194/widget.png?style=banner3" alt="Discord Banner 3"/> </td>--> <!-- Discord Presence Column --> <!-- <td align="center" style="border: none;"> <a href="https://discord.com/users/424279823817375746"> <img src="https://lanyard.cnrad.dev/api/424279823817375746" alt="Discord Presence"> </a> </td> </tr> </table> -->

<h3 align="center">YouTube Stats</h3>



<h3 align="center">Leetcode Stats</h3> <p align="center"> <img align="center" src="https://leetcard.jacoblin.cool/ChetanSawaleh2272?border=0&radius=20"/> </p>

<h1 align="center"><img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="50px" height="50px"> Tech Stack</h1>

<h3 align="center">Web Development</h3>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="8" align="center" style="color: white;">Frontend</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <a href="https://nextjs.org/" style="color: white;"> <img src="https://skillicons.dev/icons?i=nextjs" width="50" height="50" alt="Next.js"/> </a> <br>Next.js </td> <td align="center" style="border: none;"> <a href="https://tailwindcss.com/" style="color: white;"> <img src="https://cdn.worldvectorlogo.com/logos/tailwindcss.svg" width="50" height="50" alt="Tailwind CSS"/> </a> <br>Tailwind CSS </td> <td align="center" style="border: none;"> <a href="https://reactjs.org/" style="color: white;"> <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="React" width="50" height="50"/> </a> <br>React </td> <td align="center" style="border: none;"> <a href="https://www.typescriptlang.org/" style="color: white;"> <img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="TypeScript" width="50" height="50"/> </a> <br>TypeScript </td> <td align="center" style="border: none;"> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" style="color: white;"> <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="JavaScript" width="50" height="50"/> </a> <br>JavaScript </td> <td align="center" style="border: none;"> <a href="https://jquery.com/" style="color: white;"> <img src="https://skillicons.dev/icons?i=jquery" width="50" height="50" alt="jQuery"/> </a> <br>jQuery </td> <td align="center" style="border: none;"> <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" style="color: white;"> <img src="https://cdn.worldvectorlogo.com/logos/html-1.svg" width="50" height="50" alt="HTML"/> </a> <br>HTML </td> <td align="center" style="border: none;"> <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" style="color: white;"> <img src="https://cdn.worldvectorlogo.com/logos/css-3.svg" width="50" height="50" alt="CSS"/> </a> <br>CSS </td> </tr> </tbody> </table> </div>



<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="4" align="center" style="color: white;">Backend</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg" width="50" height="50" alt="Node.js"/><br>Node.js </td> <td align="center" style="border: none;"> <img src="https://techstack-generator.vercel.app/django-icon.svg" width="50" height="50" alt="Django"/><br>Django </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=flask" width="50" height="50" alt="Flask"/><br>Flask </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=express" width="50" height="50"/><br>Express </td> </tr> </tbody> </table> </div>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="4" align="center" style="color: white;">Database</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="MySQL" width="50" height="50"/><br>MySQL </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB" width="50" height="50"/><br>MongoDB </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=postgresql" alt="PostgreSQL" width="50" height="50"/><br>PostgreSQL </td> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/e/e5/Neo4j-logo_color.png" alt="Neo4j" width="100" height="40"/><br>Neo4j </td> </tr> </tbody> </table> </div>

<h3 align="center">Cloud Computing & DevOps</h3>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="4" align="center" style="color: white;">Containerization & Orchestration</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="Docker" width="50" height="50"/><br>Docker </td> <td align="center" style="border: none;"> <img src="https://techstack-generator.vercel.app/kubernetes-icon.svg" alt="Kubernetes" width="50" height="50"/><br>Kubernetes </td> <td align="center" style="border: none;"> <img src="https://helm.sh/img/helm.svg" alt="Helm" width="50" height="50"/><br>Helm </td> <td align="center" style="border: none;"> <img src="https://skaffold.dev/images/skaffold-logo-white.png" alt="Skaffold" width="50" height="50"/><br>Skaffold </td> </tr> </tbody> </table> </div>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="3" align="center" style="color: white;">Cloud Providers</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=azure" alt="Azure" width="50" height="50"/><br>Azure </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=gcp" alt="GCP" width="50" height="50"/><br>GCP </td> <td align="center" style="border: none;"> <img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="AWS" width="50" height="50"/><br>AWS </td> </tr> </tbody> </table> </div>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="2" align="center" style="color: white;">Infrastructure as Code</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=terraform" alt="Terraform" width="50" height="50"/><br>Terraform </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=ansible" alt="Terraform" width="50" height="50"/><br>Ansible </td> </tr> </tbody> </table> </div>

<h3 align="center">AI/ML & Data Science</h3> <div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="5" align="center" style="color: white;">Languages & Libraries</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="Python" width="50" height="50"/><br>Python </td> <td align="center" style="border: none;"> <img src="https://cdn.worldvectorlogo.com/logos/numpy-1.svg" alt="NumPy" width="50" height="50"/><br>NumPy </td> <td align="center" style="border: none;"> <img src="https://github.com/valohai/ml-logos/blob/master/pandas.svg" alt="Pandas" width="80" height="50"/><br>Pandas </td> <td align="center" style="border: none;"> <!-- <img src="https://cdn.worldvectorlogo.com/logos/tensorflow-2.svg" alt="TensorFlow" width="50" height="50"/> --> <img src="https://github.com/KenanGain/KenanGain/blob/main/icons/Tensorflow.gif" alt="TensorFlow" width="80" height="70" /><br>TensorFlow </td> <td align="center" style="border: none;"> <img src="https://skillicons.dev/icons?i=pytorch" alt="PyTorch" width="50" height="50"/><br>PyTorch </td> </tr> </tbody> </table> </div>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="3" align="center" style="color: white;">Frameworks & Tools</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/LangChain_logo.png" alt="LangChain" width="80" height="50"/><br>LangChain </td> <td align="center" style="border: none;"> <img src="https://ollama.ai/public/ollama.png" alt="Ollama" width="50" height="60"/><br>Ollama </td> <td align="center" style="border: none;"> <img src="https://github.com/run-llama/logos/blob/main/LlamaLogo%20Square.png" alt="LlamaIndex" width="50" height="50"/><br>LlamaIndex </td> </tr> </tbody> </table> </div>

<h3 align="center"> AI Tools & Prompt Engineering</h3> <div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="6" align="center" style="color: white;">AI Tools</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/04/ChatGPT_logo.svg" width="50" height="50" alt="ChatGPT"/><br>ChatGPT </td> <td align="center" style="border: none;"> <img src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/claude-ai-icon.png" width="50" height="50" alt="Claude (Anthropic)"/><br>Claude (Anthropic) </td> <td align="center" style="border: none;"> <!-- <img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Google_Gemini_logo.svg" width="50" height="50" alt="Google Gemini"/> --> <img src="https://github.com/KenanGain/KenanGain/blob/main/icons/Gemini.gif" alt="Gemini" width="80" height="80" /><br>Google Gemini </td> <td align="center" style="border: none;"> <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="50" height="50" alt="Hugging Face"/><br>Hugging Face </td> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/a/ab/Meta-Logo.png" width="80" height="50" alt="Meta Llama"/><br>Meta Llama </td> <td align="center" style="border: none;"> <img src="https://asset.brandfetch.io/idfDTLvPCK/idbbhgStc3.svg" width="80" height="50" alt="Cohere"/><br>Cohere </td> </tr> </tbody> </table> </div>

<h3 align="center">Streaming & Video Editing</h3>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="2" align="center" style="color: white;">Streaming Platforms</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://cdn.worldvectorlogo.com/logos/twitch-logo-2019.svg" width="50" height="50" alt="Twitch"/><br>Twitch </td> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" width="50" height="50" alt="YouTube"/><br>YouTube </td> </tr> </tbody> </table> </div>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th align="center" style="color: white;">Streaming Tools</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d3/OBS_Studio_Logo.svg" width="50" height="50" alt="OBS"/><br>OBS </td> </tr> </tbody> </table> </div>

<div align="center"> <table style="background-color: black; color: white; border: none; border-radius: 15px; overflow: hidden;"> <thead> <tr> <th colspan="3" align="center" style="color: white;">Video Editing Tools</th> </tr> </thead> <tbody> <tr> <td align="center" style="border: none;"> <img src="https://cdn.worldvectorlogo.com/logos/adobe-photoshop-2.svg" width="50" height="50" alt="Adobe Photoshop"/><br>Adobe Photoshop </td> <td align="center" style="border: none;"> <img src="https://upload.wikimedia.org/wikipedia/commons/4/40/Adobe_Premiere_Pro_CC_icon.svg" width="50" height="50" alt="Adobe Premiere Pro"/><br>Adobe Premiere Pro </td> <td align="center" style="border: none;"> <img src="https://cdn.worldvectorlogo.com/logos/after-effects-1.svg" width="50" height="50" alt="Adobe After Effects"/><br>Adobe After Effects </td> </tr> </tbody> </table> </div>

<!-- <h2 align="center">Support Me</h2> <div align="center"> <table align="center"> <tr> <th align="center"> <a href="https://www.buymeacoffee.com/kenangain" target="_blank"> <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px; width: 217px;"> </a> </th> <th align="center"> <a href="https://www.paypal.com/donate/?business=V6UVH9LBFUF26&no_recurring=0&currency_code=CAD" target="_blank"> <img src="https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png" alt="Donate with PayPal" style="height: 90px; width: 217px;"> </a> </th> <th align="center"> <a href="https://donate.stripe.com/00gg0R3Kvh0HcGkfYY" target="_blank"> <img src="https://github.com/user-attachments/assets/1b7f4d55-f85c-47ac-adcc-05d9f7cd8134" alt="Donate with Stripe" style="height: 60px; width="200px"> </a> </th> <th align="center"> <a href="https://ko-fi.com/M4M410M65J" target="_blank"> <img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /> </a> </th> </tr> <tr> <td align="center"> <img src="https://github.com/KenanGain/KenanGain/assets/123521687/72e4f7a9-a7fd-45d6-b582-ca4c8a1f2a36" alt="Buy Me a Coffee QR Code" width="150" height="150"> </td> <td align="center"> <img src="https://github.com/KenanGain/KenanGain/assets/123521687/0a08e987-d7f8-48bd-a5a4-2c991190f9af" alt="PayPal QR Code" width="150" height="150"> </td> <td align="center"> <img src="https://github.com/user-attachments/assets/f7f4fefb-1a07-4390-b2ea-a4b40d4f19f6" alt="Stripe QR Code" width="150" height="150"> </td> <td align="center"> <img src="https://storage.ko-fi.com/cdn/useruploads/M4M410M65J/qrcode.png?v=73a1af41-4248-463b-a7e8-77530b34d420?v=2" alt="Ko-fi QR Code" width="150" height="150"> </td> </tr> </table> -->

<h2 align="center">📫 Let's Connect!</h2>

<table align="center"> <tr> <td colspan="3" align="center"> <a href="mailto:ChetanSawaleh3262@gmail.com" target="_blank"> <img src="https://bentos.jkominovic.dev/api/v1/generic-card?icon=sigmail&subtitle=ChetanSawaleh3262@gmail.com&size=square" alt="Kenan Gain" style="margin: 10px;"> </a> </td> <td align="center"> <a href="https://wa.me/917028352298" target="_blank"> <img src="https://bentos.jkominovic.dev/api/v1/generic-card?icon=siwhatsapp&subtitle=India-7028352298&size=square" alt="India-+91-702-835-2298" style="margin: 10px;"> </a> </td>

</tr> </table>



<br>

<h3> <div align="center">

⭐️ From ChetanSawale | Let's innovate together! <img src='https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif' width="60px" height="30px">

</div> </h3>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=110&section=footer" width="100%">


Close
