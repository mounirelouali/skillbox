# skillbox

A professional library of Claude skills based on Ludovic Salenne's prompts.

## Available Skills

This library contains 17 specialized skills organized by theme:

### 🚀 Metas & Experts
- `skill-hunter`: Recherche et installation automatique via `npx skills` / `skills.sh`.
- `promptor`: Expert en ingénierie de prompts.
- `reverse-prompt`: Reverse Prompt Engineering.

### ✍️ Content & Writing
- `correcteur-contenu`: Optimisation de contenu.
- `formateur-texte`: Formattage Markdown professionnel.
- `machine-emails`: Rédaction d'e-mails à haute conversion.
- `traducteur`: Traduction en anglais littéraire.
- `copywriting-master`: Rédaction persuasive et frameworks marketing.
- `recruiter-pro`: Recrutement et évaluation de candidats.

### 🎓 Training & Growth
- `formateur-particulier`: Formation sur mesure pas à pas.
- `coach-finance`: Stratégie financière.
- `critique-idee`: Analyse et notation d'idées.
- `productivity-coach`: Organisation et systèmes d'efficacité.

### 📣 Debate & Management
- `debateur`: Débat argumenté et synthèse.
- `chef-projet`: Planification d'objectifs.
- `business-strategist`: Analyse de marché et planification stratégique.

### 🔍 SEO Specializations
- `seo-titre`: Optimisation de titres.
- `seo-meta`: Rédaction de méta-descriptions.
- `seo-arborescence`: Structure en silo.
- `seo-cluster`: Clusters de contenu.
- `seo-eat`: Stratégie d'autorité.
- `seo-faq`: FAQ optimisée.
- `seo-expert`: Optimisation globale pour les moteurs de recherche.

## Installation

### Via `npx skills` (Recommandé)

Tu peux installer n'importe quel skill de cette bibliothèque sans cloner le repo, en utilisant l'outil de Vercel :

- **Installation globale** (disponible dans tous tes projets) :
  ```bash
  npx skills add mounirelouali/skillbox --skill skill-hunter -g
  ```

- **Installation locale** (seulement pour le projet en cours) :
  ```bash
  npx skills add mounirelouali/skillbox --skill skill-hunter
  ```

*Tu peux remplacer `skill-hunter` par n'importe quel autre nom de skill de la liste ci-dessus.*

### Manuelle
Copie le dossier `.agents/skills` dans la racine de ton projet.
