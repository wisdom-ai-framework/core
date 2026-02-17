# 📄 WISDOM Champion Plan

Ce plan constitue le document de pilotage du cas d’usage.

**Use Case : Analyse d’interviews utilisateurs audios via IA externe**

---

# 🔐 S — Security

| Contrôle | Objectif | Process | Responsable |
| --- | --- | --- | --- |
| Protection de la fuite des données | Empêcher exposition ou réutilisation non maîtrisée des interviews | Utilisation d’un outil validé par l’entreprise et comptes professionnels uniquement | IT / Product Ops |
| Anonymisation requise | Supprimer les identifiants directs avant upload | Suppression des noms, emails et entreprises identifiables avant traitement | PM / UX Research |
| Documentation requise | Assurer traçabilité de gouvernance du cas d’usage | Maintien à jour du document Use Case et du WISDOM Scan | Head of Product |

---

# 🧠 D — Delegated Judgment

| Contrôle | Objectif | Process | Responsable |
| --- | --- | --- | --- |
| Vérification factuelle requise | Éviter hallucinations influençant la priorisation | Vérification des insights critiques par comparaison avec les verbatims source | PM |
| Interdiction d’automatisation complète | Garantir qu’aucune décision produit n’est prise automatiquement par l’IA | Absence d’intégration automatisée dans le processus de priorisation | Head of Product |
| Documentation explicite de la décision | Rendre visible l’usage de l’IA dans la décision stratégique | Mention des insights IA utilisés dans le document de priorisation | PM / Head of Product |

---

# 🔄 Workflow opérationnel sécurisé

1️⃣ Réalisation de l’interview utilisateur

2️⃣ Suppression des identifiants directs

3️⃣ Upload via outil validé par l’entreprise

4️⃣ Génération transcription et synthèse

5️⃣ Vérification des insights critiques

6️⃣ Intégration des insights IA dans le document de priorisation

7️⃣ Décision produit non automatisée

8️⃣ Mise à jour du dossier Use Case en cas d’évolution du périmètre

---

# **✅ Méthode de validation**

La validation repose sur une règle simple :

Tout insight IA influençant la priorisation doit être :

- Comparé au verbatim source
- Explicitement identifié comme issu d’un traitement IA

Aucune décision stratégique ne peut être prise sans vérification humaine.

---

# 📊 Méthode de mesure

Le cas d’usage est suivi via :

- Temps moyen de traitement d’une interview
- Nombre d’erreurs factuelles détectées lors des vérifications
- Revue périodique du workflow (au minimum annuelle)