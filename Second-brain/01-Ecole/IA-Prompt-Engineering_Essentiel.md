# 🎯 **IA & Prompt Engineering – L’ESSENTIEL** *(Sup de Vinci B1)*

---

## ⚠️ **LES 3 RÈGLES À RESPECTER (obligatoire !)**
1. **🔒 Aucune donnée personnelle** dans un prompt (ni la tienne, ni celle d’un camarade, ni un document d’école/entreprise). *→ Risque CNIL + réutilisation par les modèles.*
2. **🚫 Aucun compte imposé** : Le labo du cours (Mistral) + Duck.ai/Compar:IA fonctionnent **sans compte**.
3. **🔍 On vérifie AVANT de croire** : Une réponse d’IA = **une proposition, pas une source**. *Toujours indiquer ce qui a été vérifié.*

---

## 🧠 **CE QUE TU DOIS SAVOIR (par cœur)**

### **🔹 Définitions Clés**
| Terme | Définition | Exemple |
|-------|------------|---------|
| **IA** | Programmes qui font des tâches associées à l’intelligence humaine. | ChatGPT, Mistral |
| **ML (Machine Learning)** | La machine **apprend à partir d’exemples** (pas de règles codées). | Modèles prédictifs |
| **LLM** | *Large Language Model* : **Prédit le token suivant**, entraîné sur des milliards de textes. | GPT-4, Mistral Large |
| **Token** | Unité de base pour l’IA (1 mot = ~1 token, mais « Prompt » = 1 token, « IA » = 1 token). | « Bonjour » = 1 token |
| **Fenêtre de contexte** | « Mémoire » de l’IA (ex: **32K tokens = ~24 000 mots**). **Au-delà, elle oublie tout** ! | |
| **Température** | **0.1-0.3** = réponses déterministes (toujours les mêmes) / **0.7-1.0** = réponses créatives (mais moins fiables). | |

### **🔹 Comment ça marche ?**
- L’IA **ne comprend pas**, elle **prédit la suite la plus plausible** d’une séquence de tokens.
- Elle **ne sait pas quand elle se trompe** → **Hallucinations** (inventions avec aplomb).
- Elle **n’a pas de mémoire** : tout ce qui sort de sa fenêtre de contexte est **oublié**.
- **Modèles à raisonnement** (ex: Mistral Large) : Ils **écrivent un brouillon caché** avant de répondre → meilleurs en logique/maths.

---

## ❌ **LES 5 LIMITES À CONNAÎTRE (et à tester !)**
1. **Fenêtre de contexte** : L’IA « oublie » ce qui dépasse sa mémoire.
2. **Date de coupure** : Elle ne connaît **rien après son entraînement** (ex: GPT-4 → coupure en 2023).
3. **Hallucinations** : Elle peut **inventer** des faits (citations, dates, noms) **avec confiance**. **→ Toujours vérifier !**
4. **Biais** : Elle reproduit les biais de ses données (ex: GPT-3 associe **83% des métiers au masculin**).
5. **Complaisance** : Elle a tendance à **te donner raison** (+49% d’approbation vs humains, étude *Science* 2026).

> 💡 **Test du prénom** : Change un prénom/gendre/âge dans un prompt → compare les réponses pour détecter les biais.

---

## ✅ **COMMENT BIEN PROMPTER ? (méthode infaillible)**

### **🔹 Les 5 étapes d’un BON prompt**
1. **Objectif** : Qu’est-ce que je veux obtenir ? *(ex: « Expliquer un concept »)*
2. **Public** : Pour qui ? *(ex: « Un étudiant en B1 »)*
3. **Format** : Sous quelle forme ? *(ex: « En 3 points max, avec des exemples »)*
4. **Critère** : Comment je saurai que c’est bon ? *(ex: « Je dois comprendre sans relire »)*
5. **Boucle** : **Évaluer → Révision du prompt → Nouvel essai** (jusqu’à satisfaction).

### **🔹 Méthodes à connaître**
| Méthode | Quand l’utiliser | Exemple |
|---------|-------------------|---------|
| **CO-STAR** | Prompts structurés | **C**ontexte, **O**bjectif, **S**tyle, **T**âche, **A**uditoire, **R**ésultat |
| **Few-shot** | Tâches complexes | Donner **2-3 exemples** du résultat attendu dans le prompt. |
| **Chain-of-Thought (CoT)** | Logique/maths | Demander : *« Pense étape par étape. »* |
| **Flipped Interaction** | Révisions | **L’IA te pose des questions** pour clarifier ta demande. |

### **❌ À ÉVITER**
- *« Étape par étape »* → **Inutile** sur les modèles à raisonnement (ils le font déjà).
- *« TU ES UN EXPERT »* → Peut provoquer des **excès de confiance** (guide Anthropic).
- **Majuscules/emojis** → Pas d’impact prouvé sur la qualité.

---

## 🎯 **EXEMPLE DE PROMPT OPTIMISÉ**
**❌ Prompt naif** : *« Explique-moi les LLM. »*

**✅ Prompt CO-STAR** :
```
Contexte : Je suis un étudiant en B1 en informatique.
Objectif : Comprendre ce qu'est un LLM et comment il fonctionne.
Style : Simple, avec des analogies et 2 exemples concrets.
Tâche : Définir un LLM, son fonctionnement (tokens, vecteurs), et ses limites.
Auditoire : Moi (niveau débutant).
Résultat : Je dois pouvoir l'expliquer à un camarade sans utiliser d'IA.
Format : 3 paragraphes max + un schéma mental.
Critère : Si je peux résumer à voix haute sans notes, c'est bon.
```

---

## 📌 **CE QUE TU DOIS RETENIR (ultra-condensé)**
1. **L’IA prédit, elle ne comprend pas** → Toujours **vérifier** ses réponses.
2. **Un bon prompt = un brief clair** → *Objectif + Public + Format + Critère + Boucle*.
3. **3 règles d’or** : Pas de données perso, pas de compte imposé, vérifier avant de croire.
4. **5 limites** : Fenêtre de contexte, date de coupure, hallucinations, biais, complaisance.
5. **L’effet d’une astuce dépend du modèle** → **Mesurer, pas croire**.

---

## 📚 **OUTILS INDISPENSABLES** *(sans compte)*
| Outil | Lien | À quoi ça sert ? |
|-------|------|------------------|
| **Compar:IA** | [comparia.beta.gouv.fr](https://comparia.beta.gouv.fr) | Comparer 2 IA à l’aveugle. |
| **Tiktokenizer** | [tiktokenizer.vercel.app](https://tiktokenizer.vercel.app) | Compter les tokens d’un texte. |
| **Labo de prompts** | [formation.qiplim.com/sdv-b1](https://formation.qiplim.com/sdv-b1) | Tester des prompts (modèles Mistral). |
| **Kit personnel** | [formation.qiplim.com/sdv-b1/prompt/kit](https://formation.qiplim.com/sdv-b1/prompt/kit) | **Stocker tes prompts testés** (à télécharger chaque jour). |

---

## ✅ **À FAIRE POUR LE J2 (16/11)**
1. **Devoir** : Dans ton **kit personnel**, note **3 lignes** sur :
   - **Ce que j’ai demandé** à l’IA (ex: *« Résumer un article »*).
   - **Ce que j’ai vérifié** (ex: *« J’ai lu l’article original »*).
   - **Ce que j’ai appris (ou pas)** (ex: *« L’IA a oublié un point clé »*).
2. **Révise** : Les **3 règles**, les **5 limites**, et les **définitions clés** (ci-dessus).

---

## 💡 **CITATIONS À GARDER EN TÊTE**
- *« **L’IA augmente ce que tu produis, pas forcément ce que tu sais.** »*
- *« **Un devoir bien rendu ne prouve pas qu’on a appris.** »*
- *« **La seule règle stable, c’est de mesurer contre ton critère.** »*

---

## 🔗 **LIEN UTILE**
📌 **Kit personnel** : [formation.qiplim.com/sdv-b1/prompt/kit](https://formation.qiplim.com/sdv-b1/prompt/kit) *(À télécharger à la fin de chaque journée !)*
