# Journal des consignes Gentis

Chaque entrée reprend une instruction reçue d'un responsable Gentis, avec sa date, sa source
et la règle opérationnelle qui en découle. Les entrées sont classées de la plus récente à la
plus ancienne. Le résumé des règles en vigueur figure dans `CLAUDE.md` à la racine du dépôt.

---

## 2026-11-03 — Factures Edenred : ne plus encoder (Gentis Luxembourg hors groupe)

**Source** : conversation Teams avec Khalid Arrouji, 03/11/2026 à 17h16, accompagnée d'une
capture d'écran BOB50 des écritures concernées.

**Écritures visées par Khalid**

| Débit | Remarque |
|---|---|
| 1 869,61 | TVA LU 17,44 non récup |
| 2 530,25 | TVA LU 28,69 non récup |

**Message de Khalid (reformulé)**

- Ces factures ne concernent pas Gentis Recruitment mais Gentis Luxembourg, société qui
  n'appartient pas au groupe.
- Khalid supprime lui-même ces écritures.
- À l'avenir, dès qu'une facture Edenred se présente, ne pas l'encoder.

**Confirmation donnée à Khalid** : « D'accord, donc toutes factures Edenred. » La consigne
s'applique donc à l'ensemble des factures Edenred, sans distinction d'entité.

**Règle opérationnelle retenue**

1. Aucune facture Edenred n'est encodée dans BOB50, dans aucun dossier.
2. Les écritures Edenred existantes ne sont ni modifiées ni ré-encodées : Khalid s'en charge.
3. La pièce est classée dans l'arborescence OSEA (règle habituelle, mois de la facture) et
   listée dans le compte rendu du passage sous « écartée – Edenred / Gentis Luxembourg ».
4. Si une facture Edenred semble viser une entité du groupe, la signaler à Khalid avant toute
   action.

**Point d'attention pour l'imputation d'entité** : la mention `TVA LU` (TVA luxembourgeoise
non récupérable) est un signe que la pièce relève de Gentis Luxembourg, entité hors périmètre
OSEA. Ce critère s'ajoute au tableau d'identification des entités du skill
`gentis-finance-quotidien`.
