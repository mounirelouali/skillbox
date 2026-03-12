# SKILLY 🧠

Une bibliothèque de skills pour Claude et autres agents, basée sur les prompts de Ludovic Salenne et optimisée pour la recherche sémantique.

Cette bibliothèque contient 18 skills spécialisés (et plus à venir) :

### 🚀 Metas & Experts
- `skilly`: Le cerveau moteur de recherche de skills (interne skilly + externe npx/web).
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

Tu peux installer n'importe quel skill de cette bibliothèque sans cloner le repo, en utilisant l'outil de Vercel. 

**Pour avoir accès à Skilly (le moteur de recherche) partout sur ta machine :**

```bash
npx skills add mounirelouali/skilly --skill skilly -global
```

Une fois installé, tu n'as qu'à demander à ton agent (Windsurf, Antigravity, etc.) : "/skilly Trouve-moi un skill pour..."

*Tu peux remplacer `skill-hunter` par n'importe quel autre nom de skill de la liste ci-dessus.*

### Manuelle
Copie le dossier `.agents/skills` dans la racine de ton projet.
