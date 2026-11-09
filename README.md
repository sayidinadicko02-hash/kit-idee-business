# Kit de démarrage : teste ton idée de business avec Claude

Avant de dépenser 1 €, fais passer ton idée devant 11 experts IA et 100 faux clients, gratuitement, en français.

## Le plus simple : copier-coller ce message (rien à installer)

Ouvre une nouvelle conversation sur claude.ai (ou l'appli Claude), copie tout le message ci-dessous, remplace la première ligne par ton idée, et envoie. Claude fait toute l'analyse étape par étape.

```
Mon idée de business : [décris ton idée : quoi, pour qui, où, à quel prix]

Tu es mon équipe de conseillers pour tester cette idée avant que je dépense 1 €. Réponds en français, de façon simple et honnête, sans me flatter. Fais les étapes dans l'ordre :

1. Le conseil : 3 experts (un spécialiste de l'offre, un stratège, un spécialiste du produit) donnent leur avis, disent ce qui peut faire échouer l'idée et votent pour ou contre.
2. La concurrence : qui fait déjà ça, à quel prix, et ce que leurs clients leur reprochent.
3. Les clients : imagine 100 acheteurs réalistes (âges, revenus, habitudes). Combien achèteraient, combien refuseraient, et pourquoi ? Donne les 5 objections les plus fréquentes.
4. Le prix : le bon prix de vente, comparé aux concurrents, et la marge que je garderais.
5. L'offre : comment rendre l'offre irrésistible (bonus, garantie, nom) pour répondre aux objections.
6. Les chiffres : ce qu'il faut investir au départ, combien je dois vendre par jour pour ne pas perdre d'argent, et une estimation mois par mois sur la première année.
7. Le lancement : le test le moins cher possible à faire cette semaine pour vérifier qu'il y a de vrais clients, puis les 30 premiers jours.
8. Le verdict : Rentable, Pas encore, ou Il manque des infos, avec les 3 choses à faire en priorité.

Si une information te manque pour être précis, pose-moi d'abord les questions avant de commencer.
```

Tu veux aller plus loin avec les 11 experts complets ? Installe le pack Founder ci-dessous.

📄 Le guide en PDF : [Kit_demarrage_IDEE.pdf](Kit_demarrage_IDEE.pdf)

## Ce que c'est

**Founder** est un pack gratuit de 11 skills pour Claude, créé par Jake Schincariol. Chaque skill joue un expert : conseil d'administration, directeur financier, analyste concurrence, panel de 100 clients… Ils jugent ton idée et te disent à la fin si elle est rentable ou pas encore.

C'est open source (licence MIT) : pas d'inscription, pas de clé API, rien à connecter.

Lien du projet : [github.com/Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)

## Installer en 2 minutes

**Dans l'application Claude (le plus simple)**

1. Ouvre une nouvelle conversation.
2. Colle ce message et envoie-le :

```
https://github.com/Jakeschincariol/founder-skill

install skill
```

3. Claude installe les 11 skills. Tu peux ensuite les appeler par leur nom (par exemple `/founder-board`). Les fichiers `SKILL.md` sont rangés dans des sous-dossiers du projet, un par expert.

**Dans Claude Code**

```
/plugin marketplace add Jakeschincariol/founder-skill
/plugin install founder-skill@founder-skill
```

**Ça ne marche pas chez toi ?** Utilise le message à copier-coller tout en haut : il marche partout, sans rien installer.

Astuce : écris-lui en français, il te répondra en français.

## Les 11 skills

| Commande | Rôle | Ce qu'il fait pour toi |
| --- | --- | --- |
| `/founder-board` | Conseil d'administration | 3 membres jugent ton idée (offre, monopole, produit), disent ce qui peut la tuer et votent. |
| `/founder-competitors` | Analyste concurrence | Liste tes concurrents, leurs prix et ce que leurs clients leur reprochent, avec les liens. |
| `/founder-consumer` | Panel de clients | Crée 100 acheteurs (revenus, habitudes, doutes) et compte qui achète, qui refuse et pourquoi. |
| `/founder-pricing` | Prix | Trouve la fourchette de prix acceptable et la compare aux concurrents et à ta marge. |
| `/founder-offer` | Architecte de l'offre | Construit l'offre (bonus, garantie, nom) qui répond aux objections, puis la reteste. |
| `/founder-cfo` | Directeur financier | Marge réelle, seuil de rentabilité par jour, année 1 mois par mois, trésorerie nécessaire. |
| `/founder-marketing` | Directeur marketing | Positionnement, canaux, campagne de lancement sur 30 jours, 10 hooks, coût max d'un client. |
| `/founder-brand` | Designer de marque | Idées de nom (avec les vérifications de marque et de domaine), ton, promesse. |
| `/founder-ops` | Opérations | Fournisseurs, équipe, routines, outils, autorisations à vérifier, risques. |
| `/founder-launch` | Lancement | Un test réel pas cher d'abord, puis un compte à rebours daté et les 30 premiers jours. |
| `/founder-plan` | Business plan | Rassemble tout et calcule le verdict : Rentable, Pas encore, ou Incomplet. |

## L'ordre à suivre

Lance-les dans cet ordre : chaque skill lit ce que les précédents ont écrit.

1. `/founder-board` : décris ton idée, le conseil la juge.
2. `/founder-competitors` : qui fait déjà ça, à quel prix.
3. `/founder-consumer` : 100 clients réagissent à ton offre.
4. `/founder-pricing` : le bon prix.
5. `/founder-offer` : l'offre qui répond aux objections.
6. `/founder-cfo` : les chiffres.
7. `/founder-marketing`, `/founder-brand`, `/founder-ops`, `/founder-launch` : la mise en route.
8. `/founder-plan` : le business plan et le verdict.

Pas le temps ? Lance seulement `/founder-consumer --quick` (20 clients au lieu de 100) pour savoir en quelques minutes si l'idée mérite d'aller plus loin.

## 5 idées prêtes à copier

Copie un de ces messages après `/founder-board`, ou remplace par ton idée en gardant la même forme : quoi, pour qui, où, à quel prix.

1. **Boulangerie** : « Je veux ouvrir une boulangerie-pâtisserie de quartier à Lyon 7e, pain au levain à 4,20 €, clientèle d'actifs de 25 à 45 ans. »
2. **Coiffure à domicile** : « Je veux lancer un service de coiffure afro à domicile à Marseille, 45 € la prestation, pour les femmes de 20 à 40 ans qui manquent de temps. »
3. **Boutique en ligne** : « Je veux vendre des montres à moins de 80 € sur Instagram et un site en ligne, pour les hommes de 18 à 30 ans. »
4. **Coach sportif** : « Je veux proposer du coaching sportif en ligne à 29 € par mois, programmes à la maison pour les jeunes parents. »
5. **Automatisation pour commerçants** : « Je veux vendre des agents IA (prise de rendez-vous, réponses WhatsApp) aux petits commerces à 300 € l'installation + 50 € par mois. »

## À savoir avant de te fier aux résultats

- **Les clients IA sont trop polis.** Prends chaque « oui » comme le maximum possible, jamais comme une prévision.
- **Teste ensuite sur de vraies personnes.** `/founder-launch` commence justement par un petit test réel pas cher.
- **Les chiffres dépendent de ce que tu donnes.** Demande de vrais devis à tes fournisseurs.
- **Ce n'est pas un conseil financier ni juridique.** Fais valider le statut, les autorisations et les impôts par un comptable.
- **Ce sont des méthodes, pas les vraies personnes.** Le conseil applique les idées publiées d'Hormozi, Thiel et Steve Jobs, sans parler en leur nom.

## Crédit

Les skills Founder sont l'œuvre de Jake Schincariol ([github.com/Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill)), sous licence MIT. Ce kit est un guide en français pour les utiliser ; il n'est pas affilié au projet.

Guide préparé par @sayidina.automatise
