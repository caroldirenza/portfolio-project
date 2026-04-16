# Portfolio Project – Research Assignment

## Topic: YouTube Content Strategy for B2B SaaS

I chose this topic because YouTube is increasingly becoming a high-intent 
channel for B2B SaaS companies to build trust, generate demand, and drive 
pipeline — and there is a growing group of practitioners who are actively 
documenting what works in real time.

---

## Tools Installed
- **Cursor IDE** – AI-powered code editor (https://cursor.com)
- **Claude Code** – AI coding assistant by Anthropic, added as extension in Cursor
- **Codex** – AI extension by OpenAI, added in Cursor
- **Supadata** – YouTube transcript API used to collect video transcripts

---

## What I Collected

### YouTube Transcripts (`/research/youtube-transcripts/`)
Transcripts collected via Supadata API from 10 experts. Each file contains 
the full transcript of one video, with metadata including URL, date collected, 
and expert name.

### LinkedIn Posts (`/research/linkedin-posts/`)
Recent LinkedIn posts manually collected from each expert's profile. 
Posts were selected based on relevance to B2B SaaS strategy — 
promotional or off-topic posts were noted but not included as primary content.

### Sources (`/research/sources.md`)
Full list of all 10 experts with links, platforms, and annotations explaining 
why each was chosen.

---

## The 10 Experts & Why I Chose Them

1. **Sam Dunning** – Practitioner teaching B2B SaaS companies how to use 
YouTube and SEO to drive pipeline. Very tactical and specific.

2. **Chris Walker** – Pioneer of demand generation thinking for B2B SaaS. 
Built Refine Labs from $3K to 250+ SaaS clients using content and YouTube.

3. **Dave Gerhardt** – Founder of DGMG and Exit Five community. One of the 
most followed B2B marketing voices, uses YouTube as a core content channel.

4. **Dan Martell** – Founder of SaaS Academy. Well-known coach for B2B SaaS 
founders, uses YouTube extensively to teach scaling strategies.

5. **Brendan Hufford** – SaaS content and SEO practitioner. Teaches how to 
build content engines that drive revenue, not just traffic.

6. **Rob Walling** – Founder of TinySeed and MicroConf. Deep expertise in 
SaaS growth strategy, highly respected in the bootstrapped SaaS community.

7. **Tas Bober** – B2B content strategist and podcast host. Primarily active 
as a guest on other channels — content is candid and high-signal.

8. **Corey Haines** – SaaS marketing practitioner and founder. Shares tactical 
advice on growing SaaS through content and smart marketing decisions.

9. **Adam Robinson** – CEO of RB2B. Actively documents his own B2B SaaS 
growth journey in real time — very transparent and high signal.

10. **Denis Shatalin** – Founder of SaaS Camp. Helps B2B SaaS founders scale 
through Ad-Driven Go-To-Market strategies. Niche but highly practical.

---

## Repository Structure

```
portfolio-project/
└── research/
    ├── sources.md
    ├── linkedin-posts/
    │   ├── sam-dunning.md
    │   ├── chris-walker.md
    │   ├── dave-gerhardt.md
    │   ├── dan-martell.md
    │   ├── brendan-hufford.md
    │   ├── rob-walling.md
    │   ├── tas-bober.md
    │   ├── corey-haines.md
    │   ├── adam-robinson.md
    │   └── denis-shatalin.md
    ├── youtube-transcripts/
    │   └── (10 transcript files, one per expert)
    └── other/
```

---

## Challenges & How I Solved Them
- **Challenge**: Not familiar with developer tools as a beginner  
  **Solution**: Used YouTube tutorials and guidance to install Cursor, 
  Claude Code, and Codex step by step

- **Challenge**: Claude Code login requires a paid subscription  
  **Solution**: Documented the attempt and successfully logged in to Codex instead

- **Challenge**: Some experts are more active on YouTube than LinkedIn  
  **Solution**: Prioritized YouTube transcripts for those experts and noted 
  the limitation in their LinkedIn files

- **Challenge**: Collecting YouTube transcripts manually would take too long  
  **Solution**: Used Supadata API to collect transcripts efficiently and 
  organized them by expert in the repository
