---
tags: #ia #prompt-engineering #formation #sup-de-vinci #b1 #qiplim
alias: "J1 - IA & Prompt Engineering"
created: 2026-11-16
---

# 🤖 **J1 : IA & Prompt Engineering** – *Sup de Vinci B1*
*Formation du **10 novembre 2026** | Formateur : Yacine Arhaliass (Pando Studio)*

---

## 📌 **À retenir en 3 lignes**
> ⚡ **L’IA prédit la suite la plus plausible** (token par token), **ne sait pas quand elle se trompe** → **toujours vérifier**.
> 🎯 **Un bon prompt = un brief clair** : *quoi, pour qui, sous quelle forme, comment savoir que c’est bon* → **boucle d’évaluation/révision**.
> ⚠️ **3 règles d’or** : *pas de données perso, pas de compte imposé, on vérifie avant de croire*.

---

## 📅 **Programme du jour**

### **🌅 Matin : Comprendre**
| Heure      | Activité | Durée |
|------------|----------|-------|
| **9h30**   | Accueil, objectifs, règles | 10 min |
| **9h40**   | Tour de table : vous et l’IA | 40 min |
| **10h20**  | Introduction à l’IA | 40 min |
| **11h00**  | **NLP** : Comment l’IA traite et génère du texte | 40 min |
| **11h40**  | Les modèles du moment (LLM, GPT, Mistral, etc.) | 10 min |
| **11h50**  | **Atelier** : Compar:IA à l’aveugle | 10 min |

### **🌇 Après-midi : Formuler**
| Heure      | Activité | Durée |
|------------|----------|-------|
| **13h30**  | L’art de formuler un bon prompt (labo) | 1h10 |
| **14h40**  | **Défi** : Retrouver le prompt | 15 min |
| **14h55**  | Expérience : Les mythes du prompting | 35 min |
| **15h30**  | **Kit** : Comprendre une notion de cours | 30 min |

> 🍽 **Pauses** : 10h45 et 14h25 | **Déjeuner** : 12h30-13h30

---

## 🎯 **Objectifs du module (2 jours)**
- ✅ **Comprendre** : Qu’est-ce que l’IA ? Comment elle fonctionne (tokens, vecteurs, attention).
- ✅ **Formuler** : Écrire des prompts efficaces (méthodes CO-STAR, few-shot, etc.).
- ✅ **Vérifier** : Ne pas croire une réponse d’IA sans preuve (lecture latérale).
- ✅ **Respecter** : Éthique, biais, limites (fenêtre de contexte, date de coupure).

> 📌 **Livrable** :
> - **6 prompts documentés** dans ton [kit personnel](https://formation.qiplim.com/sdv-b1/prompt/kit) (à télécharger chaque jour).
> - **1 charte personnelle d’usage de l’IA** (à rédiger **lundi 16/11**, J2).

---

## ⚠️ **Les 3 règles du module**

### 1. 🔒 **Aucune donnée personnelle dans un prompt**
- Ni la tienne, ni celle d’un camarade, ni un document de l’école/entreprise.
- **Pourquoi** : Recommandation de la **CNIL**. Les offres grand public (ChatGPT, etc.) peuvent réutiliser tes conversations pour entraîner leurs modèles.

### 2. 🚫 **Aucun compte imposé**
- Le **labo de prompts du cours** (modèles Mistral) et les outils **Duck.ai** / **Compar:IA** fonctionnent **sans compte**.
- Tu peux utiliser ton compte perso si tu en as un (OpenAI, etc.).

### 3. 🔍 **On vérifie avant de croire**
- Une réponse d’IA est une **proposition**, pas une source.
- **Tout ce que tu gardes dans ton kit doit indiquer ce qui a été vérifié** (ex: « Source : [lien] + lecture latérale OK »).

---

## 🧠 **Ce qu’est (et n’est pas) l’IA**

### **🔹 Définitions clés**
| Terme | Définition | Exemple |
|-------|------------|---------|
| **IA (Intelligence Artificielle)** | Programmes qui font des tâches associées à l’intelligence humaine. | ChatGPT, Mistral |
| **ML (Machine Learning)** | Apprentissage automatique : la machine apprend à partir d’exemples. | Modèles prédictifs |
| **LLM (Large Language Model)** | Grand modèle de langage : prédit le token suivant, entraîné sur d’énormes quantités de texte. | GPT-4, Mistral Large |
| **Token** | Unité de base pour l’IA (un mot, une partie de mot, ou un caractère). | « IA » = 1 token, « Prompt » = 1 token |
| **Fenêtre de contexte** | « Mémoire » de l’IA : ce qu’elle « voit » en une fois (ex: 32K tokens = ~24 000 mots). | Au-delà, elle oublie ! |
| **Température** | Paramètre qui contrôle la créativité :
- **Basse (0.1-0.3)** → Réponses déterministes (toujours la même).
- **Haute (0.7-1.0)** → Réponses variées (mais moins fiables). |

### **🔹 Comment ça marche ?**
1. **L’IA ne « comprend » pas** : Elle prédit la **suite la plus plausible** d’une séquence de tokens.
2. **Elle ne « sait » pas** : Elle génère du texte basé sur des **statistiques** (fréquence des mots dans son entraînement).
3. **Elle n’a pas de mémoire** : Tout ce qui sort de sa fenêtre de contexte est **oublié**.
4. **Elle ne peut pas « réfléchir »** (sauf les modèles à raisonnement, qui écrivent un brouillon caché).

> 💡 **Exemple concret** :
> - **Prompt** : *« Explique-moi ce qu’est un protocole réseau. »*
> - **Réponse** : L’IA génère le texte le plus probable après cette phrase, **sans comprendre** ce qu’est un protocole réseau.
> - **Vérification** : À toi de vérifier si la réponse est juste (ex: avec une source fiable).

---

## 📜 **Brève histoire de l’IA**

| Année | Événement | Impact |
|-------|-----------|--------|
| **1818** | *Frankenstein* (Mary Shelley) | Peur de la création qui échappe à son créateur. |
| **1860** | *Paris au XXe siècle* (Jules Verne) | Machines à calculer « comme de vastes pianos ». |
| **1921** | *R.U.R.* (Čapek) | Naissance du mot **« robot »** (du tchèque *robota* = travail forcé). |
| **1942** | 3 lois de la robotique (Asimov) | Premières règles de sûreté… **qui se contredisent**. |
| **1966** | **ELIZA** | Premier chatbot : reformule tes phrases **sans comprendre**. |
| **1970-1990** | Hivers de l’IA | Systèmes experts (règles écrites à la main) → promesses non tenues. |
| **2014** | **Attention** (Google) | Révolution : les modèles apprennent à « regarder » les mots importants. |
| **2018** | **GPT-1** (OpenAI) | 117M paramètres : début des LLM modernes. |
| **2020** | **GPT-3** (OpenAI) | 175B paramètres : **few-shot learning** (apprend avec quelques exemples). |
| **2024-2025** | Modèles à **raisonnement** | Écritent un brouillon caché → meilleurs en logique/maths. |

> 🎬 **À regarder** : [Transformers, the tech behind LLMs](https://www.youtube.com/watch?v=...) (3Blue1Brown, chapitre 5 de *Deep Learning*).

---

## 🎯 **Les limites de l’IA**

### **⚠️ 5 limites majeures**
1. **Fenêtre de contexte** : L’IA « oublie » ce qui dépasse sa mémoire (ex: 32K tokens = ~24 000 mots).
2. **Date de coupure** : Elle ne connaît **rien après son entraînement** (ex: GPT-4 coupure en 2023).
3. **Hallucinations** : Elle peut **inventer** des faits avec aplomb (ex: citations, dates, noms).
4. **Biais** : Elle reproduit les biais présents dans ses données d’entraînement (ex: stéréotypes de genre).
5. **Complaisance** : Elle a tendance à **te donner raison** (étude *Science*, mars 2026 : +49% d’approbation vs humains).

### **📊 Chiffres clés (biais)**
- **GPT-3** : 93% de mots anglais, **1,8% de français** (2020).
- **Llama 2** : **0,16% de données en français** (2023).
- **Métiers** : GPT-3 associe **83% des 388 métiers testés au masculin**.
- **Discrimination** : En 2024, **mêmes CV, seuls les noms changent** → classement variable selon l’origine supposée (Bloomberg).

> 🔍 **Test du prénom** : Change un seul détail (prénom, genre, âge) dans un prompt et compare les réponses.

---

## 💡 **L’art du prompt**

### **🔹 Les 5 étapes d’un bon prompt**
1. **Objectif** : Qu’est-ce que je veux obtenir ? *(ex: « Expliquer un concept »)*
2. **Public** : Pour qui ? *(ex: « Un étudiant en B1 »)*
3. **Format** : Sous quelle forme ? *(ex: « En 3 points max, avec des exemples »)*
4. **Critère** : Comment je saurai que c’est bon ? *(ex: « Je dois comprendre sans relire »)*
5. **Boucle** : Évaluer → Révision du prompt → Nouvel essai.

### **🔹 Méthodes de prompting**
| Méthode | Description | Quand l’utiliser |
|---------|-------------|-------------------|
| **CO-STAR** | **C**ontexte, **O**bjectif, **S**tyle, **T**âche, **A**uditoire, **R**ésultat | Prompts structurés (ex: emails, rapports). |
| **Few-shot** | Donner **2-3 exemples** du résultat attendu. | Tâches complexes (ex: classification, génération de code). |
| **Chain-of-Thought (CoT)** | Demander à l’IA de **réfléchir étape par étape**. | Problèmes de logique/maths. |
| **Flipped Interaction** | **L’IA te pose des questions** pour clarifier ta demande. | Révisions, brainstorming. |

> ❌ **À éviter** :
> - *« Étape par étape »* → **Inutile** sur les modèles à raisonnement (ils le font déjà).
> - *« TU ES UN EXPERT »* → Peut provoquer des **excès** de confiance (guide Anthropic).
> - **Majuscules/emojis** → Pas d’impact prouvé sur la qualité.

### **🔹 Exemple concret : Comprendre une notion de cours**
**❌ Prompt naif** : *« Explique-moi les LLM. »*

**✅ Prompt optimisé (CO-STAR)** :
```
Tu es un professeur d'informatique (contexte + auditoire).
Objectif : Expliquer ce qu'est un LLM à un étudiant en B1 (niveau débutant).
Style : Simple, avec des analogies et 2 exemples concrets.
Tâche : Définir un LLM, son fonctionnement, et ses limites.
Résultat : Je dois pouvoir l'expliquer à mon voisin sans utiliser d'IA.
Format : 3 paragraphes max, avec un schéma mental.
```

---

## 🛠 **Outils du jour**

| Outil | Lien | Utilité | Accès |
|-------|------|---------|-------|
| **Compar:IA** | [comparia.beta.gouv.fr](https://comparia.beta.gouv.fr) | Comparer 2 IA à l’aveugle (énergie, réponses). | ✅ Sans compte |
| **Duck.ai** | [duck.ai](https://duck.ai) | Chatbot léger (modèle DuckDB). | ✅ Sans compte |
| **Tiktokenizer** | [tiktokenizer.vercel.app](https://tiktokenizer.vercel.app) | Compter les tokens d’un texte. | ✅ Sans compte |
| **Transformer Explainer** | [jalammar.github.io](https://jalammar.github.io/illustrated-transformer/) | Visualiser comment fonctionne un Transformer. | ✅ Sans compte |
| **Labo de prompts** | [formation.qiplim.com/sdv-b1](https://formation.qiplim.com/sdv-b1) | Espace de test avec modèles Mistral. | ✅ Sans compte |
| **Kit personnel** | [formation.qiplim.com/sdv-b1/prompt/kit](https://formation.qiplim.com/sdv-b1/prompt/kit) | Stocker tes prompts testés. | ✅ Sans compte (enregistré dans ton navigateur) |

---

## 📝 **À faire avant le J2 (16/11)**

### **📌 Devoir**
> **Une situation réelle** :
> Note **3 lignes** dans la fiche *« Une situation réelle »* de ton kit :
> 1. **Ce que j’ai demandé** à l’IA (ex: *« Résumer un article »*).
> 2. **Ce que j’ai vérifié** (ex: *« J’ai lu l’article original »*).
> 3. **Ce que j’ai appris (ou pas)** (ex: *« L’IA a oublié un point clé »*).

### **🎒 À emporter**
- **Télécharge ton kit** ([lien](https://formation.qiplim.com/sdv-b1/prompt/kit)) à la fin de la journée.
- **Révise** :
  - Les 3 règles du module.
  - Les définitions (IA, ML, LLM, token, fenêtre de contexte).
  - Les limites de l’IA (hallucinations, biais, complaisance).

---

## 📅 **J2 : Lundi 16/11**
**Thèmes** : Limites, apprendre avec l’IA, éthique, ta charte personnelle.

---

## 🔗 **Liens utiles**
- [Support de cours complet](https://formation.qiplim.com/sdv-b1)
- [Labo de prompts](https://formation.qiplim.com/sdv-b1) *(code donné en séance)*
- [Kit personnel](https://formation.qiplim.com/sdv-b1/prompt/kit)
- [Vidéo : Transformers expliqués](https://www.youtube.com/watch?v=...) *(3Blue1Brown)*
- [Compar:IA](https://comparia.beta.gouv.fr)
- [Pix : Parcours IA](https://pix.fr) *(attestation pour stage/alternance)*

---

## 💭 **Idées à retenir**
- *« **L’IA augmente ce que tu produis, pas forcément ce que tu sais.** »*
- *« **Un devoir bien rendu ne prouve pas qu’on a appris.** »*
- *« **La seule règle stable, c’est de mesurer contre ton critère.** »*
- *« **L’effet d’une astuce dépend du modèle et de la tâche.** »*

---

## 📌 **Tags**
#ia #prompt-engineering #llm #gpt #mistral #sup-de-vinci #b1 #formation #qiplim #éthique #bias #tokens #nlp