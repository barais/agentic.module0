---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Module 0 - Introduction au cours
info: |
  ## Cours Agentic AI 
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
pdf: true
export: true
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable Comark Syntax: https://comark.dev/syntax/markdown
comark: true
download: true
# duration of the presentation
duration: 3min
---

# Module Agentique
## 


---
layout: image-right
image: /img/olivierbarais.png
---

# Olivier Barais

**Prof. @Univ. Rennes — IRISA**,  [🌐](https://olivier.barais.fr)


## Mes domaines d'expertise

- 🔒 Secure Software Supply Chain
- 🏗️ Dynamic software architecture
- 🧩 Software language engineering
- 🌐 Distributed systems
- ☁️ Cloud computing
- 📐 Model-driven engineering





---
layout: default
---

<div class="slide-flex">

  <div class="flex-photo-side">
    <img src="/img/notanai.png" class="flex-photo" alt="Olivier Barais en mode flex" />
  </div>

  <div class="flex-text">

# ~~AI~~ Researcher ?


> ⚠️ **Je ne suis pas un chercheur en IA.**

Mes travaux portent sur l'ingénierie logicielle, pas sur l'IA :

- 🔒 Secure Software Supply Chain
- 🏗️ Dynamic software architecture
- 🧩 Software language engineering
- 🌐 Distributed systems
- ☁️ Cloud computing
- 📐 Model-driven engineering
- 🏴󠁵󠁳󠁩󠁡󠁿 ~~IA…~~


</div>
</div>

<style>
del { color: red; text-decoration-thickness: 3px; }
.image-left-container .slidev-layout { background: #fafafa; }

  .slide-flex {
    display: flex;
    align-items: center;        /* centrage vertical */
    justify-content: space-between;
    gap: 2rem;
    height: 100%;
  }
  .flex-photo-side {
    width: 40%;                 /* même proportion que le layout image-left */
    flex-shrink: 0;
  }
  .flex-photo {
    width: 100%;                /* -> on voit toute la largeur de l'image */
    height: auto;               /* hauteur automatique, PAS toute la hauteur */
    max-height: 65vh;           /* limite facultative pour rester compact */
    object-fit: contain;        /* garantit aucune coupure */
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
  }
  .flex-text {
    width: 55%;
  }

</style>

---
layout: default
---

# 📋 Plan du module

<br/>

<div class="grid grid-cols-2 gap-6">

<div>

### 1-4 · Fondations

**1. Grands modèles de langage (fondations)** — *Comprendre l'outil de base des agents*
→ [olivier.barais.fr/agentic.module1](https://olivier.barais.fr/agentic.module1)

**2. Introduction à l'agentique** — *Définir ce qu'est un agent vs un chatbot*
→ [olivier.barais.fr/agentic.module2](https://olivier.barais.fr/agentic.module2)

**3. Anatomie d'un agent** — *Décortiquer les briques internes*
→ [olivier.barais.fr/agentic.module3](https://olivier.barais.fr/agentic.module3)

**4. Les 4 patrons de conception agentiques** — *Maîtriser les patterns fondamentaux*
→ [olivier.barais.fr/agentic.module4](https://olivier.barais.fr/agentic.module4)

</div>

<div>

### 5-8 · Construction & Usage

**5. Technologie & infrastructure** — *Savoir construire (frameworks, MCP, mémoire)*
→ [olivier.barais.fr/agentic.module5](https://olivier.barais.fr/agentic.module5)

**6. Agents pour le développement logiciel** — *Usage concret en dev*
→ [olivier.barais.fr/agentic.module6](https://olivier.barais.fr/agentic.module6)

**7. Agents pour la recherche** — *Usage concret en science*
→ [olivier.barais.fr/agentic.module7](https://olivier.barais.fr/agentic.module7)

**8. Évaluation, sécurité, limites** — *Déployer de façon fiable et responsable*
→ [olivier.barais.fr/agentic.module8](https://olivier.barais.fr/agentic.module8)

</div>

</div>
