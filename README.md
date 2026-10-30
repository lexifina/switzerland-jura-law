# Jura: law history in git

The law of the canton of Jura (République et Canton du Jura, Switzerland) as a git history: one file per article, one commit per change on the day it took effect. `git blame` and `git log` work line by line; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ju/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in French, the canton's official language, exactly as published.

## What this repository holds

420 acts with 420 versions so far, starting with the cantonal constitution. The RSJU publishes only the current text of each act, so each act has one version: the text in force today, dated by the latest entry into force its own notes give. It holds the constitution, the laws (lois) and the ordinances (ordonnances) in force, in the order of the systematic collection, added in parts; decrees, agreements, other acts and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `101-cst-ju/` | Constitution de la République et Canton du Jura (101) | 1 | current text only, in force since 1 January 2026 |
| `103-2/` | Loi "Un seul Jura" (103.2) | 1 | current text only, in force since 1 August 2006 |
| `111-1/` | Loi sur l’approbation des traités, concordats et autres conventions (111.1) | 1 | current text only, in force since 12 March 1980 |
| `132-21/` | Loi concernant la circonscription de la République et Canton du Jura en quatre districts (132.21) | 1 | current text only, in force since 1 January 2026 |
| `132-112/` | Loi régissant l'accueil de la commune de Vellerat (132.112) | 1 | current text only, in force since 1 August 1995 |
| `141-1/` | Loi sur le droit de cité (141.1) | 1 | current text only, in force since 1 January 2013 |
| `142-11/` | Loi concernant le contrôle des habitants (142.11) | 1 | current text only, in force since 1 January 2013 |
| `142-41/` | Loi d'application des mesures de contrainte en matière de droit des étrangers (142.41) | 1 | current text only, in force since 1 August 2008 |
| `151-1/` | Loi portant introduction à la loi fédérale sur l'égalité entre femmes et hommes (LiLEg) (151.1) | 1 | current text only, in force since 1 January 2023 |
| `161-1/` | Loi sur les droits politiques (161.1) | 1 | current text only, in force since 1 June 2025 |
| `170-31/` | Loi d’incompatibilité (170.31) | 1 | current text only, in force since 1 January 2020 |
| `170-42/` | Loi concernant le guichet virtuel sécurisé (LGVS) (170.42) | 1 | current text only, in force since 1 January 2025 |
| `170-51/` | Loi sur les publications officielles (170.51) | 1 | current text only, in force since 1 February 2014 |
| `170-61/` | Loi concernant l'usage de la langue française (170.61) | 1 | current text only, in force since 1 February 2011 |
| `170-71/` | Loi visant à protéger et à soutenir la famille (170.71) | 1 | current text only, in force since 1 January 2001 |
| `171-21/` | Loi d’organisation du Parlement de la République et Canton du Jura (LOP) (171.21) | 1 | current text only, in force since 13 June 2022 |
| `172-11/` | Loi d’organisation du Gouvernement et de l’administration cantonale (LOGA) (172.11) | 1 | current text only, in force since 1 January 2026 |
| `172-21/` | Loi relative au calcul des prestations de l'Etat sujettes à condition de revenu (172.21) | 1 | current text only, in force since 1 January 2016 |
| `172-61/` | Loi concernant la participation de la République et Canton du Jura à une société anonyme active dans le domaine de l'informatique (172.61) | 1 | current text only, in force since 1 July 2017 |
| `172-411/` | Loi sur le Conseil consultatif des Jurassiens domiciliés à l'extérieur de la République et Canton du Jura (172.411) | 1 | current text only, in force since 1 December 2010 |
| `172-441/` | Loi instituant le Conseil scolaire (172.441) | 1 | current text only, in force since 1 January 2015 |
| `172-481/` | Loi instituant le Conseil de la santé publique (172.481) | 1 | current text only, in force since 1 January 2015 |
| `173-11/` | Loi sur le personnel de l'Etat (LPer) (173.11) | 1 | current text only, in force since 1 February 2026 |
| `173-51/` | Loi sur la Caisse de pensions de la République et Canton du Jura (LCPJU) (173.51) | 1 | current text only, in force since 1 January 2020 |
| `173-52/` | Loi concernant la prévoyance des membres du Gouvernement (173.52) | 1 | current text only, in force since 1 June 2024 |
| `174-1/` | Loi concernant les marchés publics (LMP-JU) (174.1) | 1 | current text only, in force since 1 January 2026 |
| `175-1/` | Loi de procédure et de juridiction administrative et constitutionnelle (Code de procédure administrative) (175.1) | 1 | current text only, in force since 1 January 2024 |
| `176-11/` | Loi sur les émoluments (LEmol) (176.11) | 1 | current text only, in force since 1 January 2022 |
| `181-1/` | Loi d'organisation judiciaire (LOJ) (181.1) | 1 | current text only, in force since 1 December 2025 |
| `182-34/` | Loi instituant le Conseil de prud’hommes (182.34) | 1 | current text only, in force since 1 January 2024 |
| `182-35/` | Loi instituant le Tribunal des baux à loyer et à ferme (182.35) | 1 | current text only, in force since 1 January 2024 |
| `182-51/` | Loi relative à la justice pénale des mineurs (182.51) | 1 | current text only, in force since 1 January 2013 |
| `188-11/` | Loi concernant la professsion d'avocat (188.11) | 1 | current text only, in force since 1 March 2016 |
| `189-11/` | Loi sur le notariat (189.11) | 1 | current text only, in force since 1 January 2026 |
| `190-11/` | Loi sur les communes (LCom) (190.11) | 1 | current text only, in force since 1 July 2026 |
| `190-614-1/` | Loi concernant la classification judiciaire des biens communaux (190.614.1) | 1 | current text only, in force since 1 January 1979 |
| `211-1/` | Loi d'introduction du Code civil suisse (LiCC) (211.1) | 1 | current text only, in force since 1 July 2026 |
| `211-2/` | Loi portant application de la loi fédérale sur le partenariat enregistré entre personnes du même sexe (211.2) | 1 | current text only, in force since 1 January 2007 |
| `213-1/` | Loi sur l'organisation de la protection de l'enfant et de l'adulte (213.1) | 1 | current text only, in force since 1 January 2026 |
| `213-32/` | Loi sur les mesures et le placement à des fins d'assistance (213.32) | 1 | current text only, in force since 1 January 2013 |
| `215-122-14/` | Loi concernant le rachat des droits de propriété et d'usufruit grevant les arbres situés sur le fonds d'un tiers (215.122.14) | 1 | current text only, in force since 1 January 1979 |
| `215-124-1/` | Loi introductive à la loi fédérale sur le droit foncier rural (215.124.1) | 1 | current text only, in force since 1 June 2012 |
| `215-126-1/` | Loi portant exécution de la loi fédérale du 16 décembre 1983 sur l'acquisition d'immeubles par des personnes à l'étranger (215.126.1) | 1 | current text only, in force since 1 July 1988 |
| `215-126-2/` | Loi touchant les acquisitions d'immeubles et de droits hypothécaires (215.126.2) | 1 | current text only, in force since 1 January 1979 |
| `215-326-2/` | Loi réglant les droits de mutation et les droits perçus pour la constitution de gages (215.326.2) | 1 | current text only, in force since 1 March 2024 |
| `215-341/` | Loi sur la géoinformation (LGéo) (215.341) | 1 | current text only, in force since 1 August 2015 |
| `222-132-1/` | Loi portant introduction de la loi fédérale du 4 octobre 1985 sur le bail à ferme agricole (222.132.1) | 1 | current text only, in force since 1 May 1990 |
| `271-1/` | Loi d'introduction du Code de procédure civile suisse (LiCPC) (271.1) | 1 | current text only, in force since 1 January 2024 |
| `281-1/` | Loi portant introduction de la loi fédérale sur la poursuite pour dettes et la faillite (LiLP) (281.1) | 1 | current text only, in force since 1 July 2025 |
| `311/` | Loi sur l’introduction du Code pénal suisse (311) | 1 | current text only, in force since 1 January 2015 |
| `312-5/` | Loi portant introduction à la loi fédérale sur l'aide aux victimes d'infractions (LiLAVI) (312.5) | 1 | current text only, in force since 1 March 2016 |
| `321-1/` | Loi d'introduction du Code de procédure pénale suisse (LiCPP) (321.1) | 1 | current text only, in force since 1 January 2023 |
| `324-1/` | Loi portant introduction de la loi fédérale sur les amendes d’ordre (LiLAO) (324.1) | 1 | current text only, in force since 1 March 2021 |
| `341-1/` | Loi sur l'exécution des peines et mesures (LEPM) (341.1) | 1 | current text only, in force since 1 July 2025 |
| `342-1/` | Loi sur les établissements de détention (LED) (342.1) | 1 | current text only, in force since 1 January 2023 |
| `410-11/` | Loi sur l’école obligatoire (410.11) | 1 | current text only, in force since 1 February 2024 |
| `410-210-1/` | Loi sur la Haute Ecole pédagogique (HEP-BEJUNE (410.210.1) | 1 | current text only, in force since 1 August 2021 |
| `412-11/` | Loi sur l'enseignement et la formation des niveaux secondaire II et tertiaire et sur la formation continue (412.11) | 1 | current text only, in force since 1 August 2019 |
| `413-12/` | Loi concernant le fonds pour le soutien aux formations professionnelles (413.12) | 1 | current text only, in force since 1 October 2022 |
| `415-1/` | Loi visant à encourager les activités physiques et le sport (415.1) | 1 | current text only, in force since 1 February 2011 |
| `416-31/` | Loi concernant les subsides de formation (416.31) | 1 | current text only, in force since 15 September 2025 |
| `417-1/` | Loi sur l’enseignement privé (417.1) | 1 | current text only, in force since 1 February 2025 |
| `441-21/` | Loi sur l'archivage (441.21) | 1 | current text only, in force since 1 January 2011 |
| `443-1/` | Loi sur l'encouragement des activités culturelles (443.1) | 1 | current text only, in force since 1 March 2017 |
| `445-1/` | Loi sur la conservation des objets d'art et monuments historiques (445.1) | 1 | current text only, in force since 1 January 2005 |
| `445-4/` | Loi sur la protection du patrimoine archéologique et paléontologique (LPPAP) (445.4) | 1 | current text only, in force since 1 September 2015 |
| `451/` | Loi sur la protection de la nature et du paysage (LPNP) (451) | 1 | current text only, in force since 1 February 2016 |
| `471-1/` | Loi concernant les rapports entre les Eglises et l'Etat (LREE) (471.1) | 1 | current text only, in force since 1 January 2026 |
| `521-1/` | Loi sur la protection de la population et la protection civile (LPCi) (521.1) | 1 | current text only, in force since 1 January 2014 |
| `551-1/` | Loi sur la police cantonale (LPol) (551.1) | 1 | current text only, in force since 1 January 2026 |
| `555-1/` | Loi sur les jours fériés officiels et le repos dominical (555.1) | 1 | current text only, in force since 1 January 2023 |
| `611/` | Loi sur les finances cantonales (LFin) (611) | 1 | current text only, in force since 1 February 2026 |
| `613/` | Loi sur le Contrôle des finances (LCFi) (613) | 1 | current text only, in force since 1 February 2026 |
| `621/` | Loi sur les subventions (LSubv) (621) | 1 | current text only, in force since 1 January 2026 |
| `641-91/` | Loi instituant un rabais fiscal pour la période 1981/1982 (641.91) | 1 | current text only, in force since 1 January 1983 |
| `642-1/` | Loi sur l'impôt de succession et de donation (LISD) (642.1) | 1 | current text only, in force since 1 January 2020 |
| `645-1/` | Loi concernant la taxe des chiens (645.1) | 1 | current text only, in force since 1 January 2020 |
| `649-751-2/` | Loi relative à la compensation partielle à l’égard des communes des effets financiers du programme « Plan équilibre 22-26 » (649.751.2) | 1 | current text only, in force since 1 January 2024 |
| `651/` | Loi concernant la péréquation financière (LPF) (651) | 1 | current text only, in force since 1 January 2026 |
| `691-1/` | Loi sur la régale des sels (691.1) | 1 | current text only, in force since 1 January 2007 |
| `701-1/` | Loi sur l'aménagement du territoire et les constructions (LATC) (701.1) | 1 | current text only, in force since 1 July 2026 |
| `711/` | Loi sur l'expropriation (711) | 1 | current text only, in force since 1 January 2015 |
| `722-11/` | Loi sur la construction et l'entretien des routes (LCER) (722.11) | 1 | current text only, in force since 1 July 2026 |
| `722-31/` | Loi sur les itinéraires cyclables (722.31) | 1 | current text only, in force since 1 January 1996 |
| `722-41/` | Loi portant application de la loi fédérale du 4 octobre 1985 sur les chemins pour piétons et les chemins de randonnée pédestre (722.41) | 1 | current text only, in force since 1 July 2026 |
| `722-191/` | Loi sur le principe de la construction d'une route nationale de deuxième classe reliant Boncourt à Choindez (Transjurane) (722.191) | 1 | current text only, in force since 1 December 1981 |
| `730-1/` | Loi sur l’énergie (730.1) | 1 | current text only, in force since 1 March 2024 |
| `731-1/` | Loi sur l’approvisionnement en électricité (LAEl) (731.1) | 1 | current text only, in force since 1 March 2024 |
| `732-1/` | Loi de procédure sur la consultation du peuple en matière d'installations atomiques (732.1) | 1 | current text only, in force since 1 February 1984 |
| `741-11/` | Loi sur la circulation routière et la taxation des véhicules routiers et des bateaux (741.11) | 1 | current text only, in force since 1 July 2024 |
| `742-21/` | Loi sur les transports publics (742.21) | 1 | current text only, in force since 1 January 2011 |
| `742-91/` | Loi concernant la consultation populaire sur le principe de la construction d'une deuxième ligne de chemin de fer entre Glovelier et Delémont indépendante de la voie CFF existante (742.91) | 1 | current text only, in force since 1 March 1991 |
| `810-01/` | Loi sanitaire (810.01) | 1 | current text only, in force since 1 January 2026 |
| `810-06/` | Loi sur l'acquisition, la mise en service, l'utilisation et le renouvellement de certains équipements médicaux (810.06) | 1 | current text only, in force since 1 April 2005 |
| `810-11/` | Loi sur les établissements hospitaliers (810.11) | 1 | current text only, in force since 1 October 2019 |
| `810-41/` | Loi sur l'organisation gérontologique (810.41) | 1 | current text only, in force since 1 January 2011 |
| `811-22/` | Loi sur l’encouragement de la formation dans le domaine des soins (811.22) | 1 | current text only, in force since 1 January 2026 |
| `812-21/` | Loi sur la vente des médicaments (812.21) | 1 | current text only, in force since 1 July 1993 |
| `814-015/` | Loi sur les déchets et les sites pollués (Loi sur les déchets, LDSP) (814.015) | 1 | current text only, in force since 1 January 2026 |
| `814-20/` | Loi sur la gestion des eaux (LGEaux) (814.20) | 1 | current text only, in force since 1 January 2020 |
| `817-0/` | Loi portant introduction de la loi fédérale du 20 juin 2014 sur les denrées alimentaires et les objets usuels (LiLDAl) (817.0) | 1 | current text only, in force since 1 February 2020 |
| `822-11/` | Loi portant introduction de la loi fédérale du 13 mars 1964 sur le travail dans l’industrie, l’artisanat et le commerce (822.11) | 1 | current text only, in force since 1 July 2026 |
| `822-41/` | Loi sur le salaire minimum cantonal (822.41) | 1 | current text only, in force since 1 February 2018 |
| `823-12/` | Loi sur l'indemnisation des travailleurs victimes de la faillite de leur employeur (823.12) | 1 | current text only, in force since 1 January 1995 |
| `823-32/` | Loi portant encouragement de la constitution de réserves de crise par l'économie privée (823.32) | 1 | current text only, in force since 1 January 1989 |
| `823-33/` | Loi sur la constitution de réserves de crise bénéficiant d'allégements fiscaux (823.33) | 1 | current text only, in force since 1 January 1989 |
| `824-21/` | Loi concernant la Chambre cantonale de conciliation (824.21) | 1 | current text only, in force since 1 January 2015 |
| `831-10/` | Loi portant introduction de la loi fédérale du 20 décembre 1946 sur l’assurance-vieillesse et survivants (831.10) | 1 | current text only, in force since 1 January 2015 |
| `831-20/` | Loi portant introduction de la loi fédérale du 19 juin 1959 sur l'assurance-invalidité (831.20) | 1 | current text only, in force since 1 January 2008 |
| `831-30/` | Loi portant introduction à la loi fédérale sur les prestations complémentaires à l'assurance-vieillesse, survivants et invalidité (LiLPC) (831.30) | 1 | current text only, in force since 1 January 2017 |
| `832-10/` | Loi portant introduction de la loi fédérale sur l’assurance-maladie (LiLAMal) (832.10) | 1 | current text only, in force since 1 February 2020 |
| `832-11/` | Loi sur le financement des soins (832.11) | 1 | current text only, in force since 1 January 2011 |
| `832-20/` | Loi portant introduction de la loi fédérale du 20 mars 1981 sur l'assurance-accidents (832.20) | 1 | current text only, in force since 1 January 2011 |
| `836-1/` | Loi portant introduction à la loi fédérale sur les allocations familiales (LiLAFam) (836.1) | 1 | current text only, in force since 1 January 2022 |
| `837-0/` | Loi portant introduction de la loi fédérale sur le service de l'emploi et la location de services et de la loi fédérale sur l'assurance-chômage obligatoire et l'indemnité en cas d'insolvabilité (837.0) | 1 | current text only, in force since 1 February 2022 |
| `837-04/` | Loi sur les mesures cantonales en faveur des demandeurs d'emploi (LMDE) (837.04) | 1 | current text only, in force since 1 January 2001 |
| `844-1/` | Loi concernant l’amélioration du marché du logement (844.1) | 1 | current text only, in force since 1 January 2023 |
| `850-1/` | Loi sur l’action sociale (LASoc) (850.1) | 1 | current text only, in force since 1 January 2023 |
| `851-1/` | Loi sur l’aide au recouvrement, l’avance et le versement provisionnel de contributions d’entretien (LARPA) (851.1) | 1 | current text only, in force since 1 July 2024 |
| `853-21/` | Loi sur la politique de la jeunesse (853.21) | 1 | current text only, in force since 1 April 2015 |
| `871-1/` | Loi sur la protection contre les incendies et les dangers naturels (871.1) | 1 | current text only, in force since 1 January 2016 |
| `873-11/` | Loi sur la protection et l’assurance des bâtiments (873.11) | 1 | current text only, in force since 20 December 2023 |
| `873-21/` | Loi sur l'assurance mobilière contre l'incendie (873.21) | 1 | current text only, in force since 1 January 2008 |
| `875-1/` | Loi sur le service de défense contre l’incendie et de secours (875.1) | 1 | current text only, in force since 1 January 2026 |
| `901-1/` | Loi sur la promotion économique (901.1) | 1 | current text only, in force since 1 October 2025 |
| `901-6/` | Loi concernant les nouvelles entreprises innovantes (901.6) | 1 | current text only, in force since 1 February 2013 |
| `910-1/` | Loi sur le développement rural (910.1) | 1 | current text only, in force since 1 February 2026 |
| `913-1/` | Loi sur les améliorations structurelles (913.1) | 1 | current text only, in force since 1 July 2026 |
| `915-11/` | Loi sur la formation professionnelle en agriculture et en économie familiale (915.11) | 1 | current text only, in force since 1 August 2004 |
| `916-61/` | Loi sur l'assurance du bétail (916.61) | 1 | current text only, in force since 1 August 2011 |
| `921-11/` | Loi sur les forêts (921.11) | 1 | current text only, in force since 1 July 2026 |
| `922-11/` | Loi sur la chasse et la protection de la faune sauvage (Loi sur la chasse) (922.11) | 1 | current text only, in force since 1 January 2015 |
| `923-11/` | Loi sur la pêche (923.11) | 1 | current text only, in force since 1 July 2020 |
| `930-1/` | Loi sur les activités économiques (LAEco) (930.1) | 1 | current text only, in force since 1 January 2021 |
| `931-1/` | Loi sur l'exploitation des matières premières minérales (Loi sur les mines) (931.1) | 1 | current text only, in force since 1 January 2015 |
| `935-11/` | Loi sur l'hôtellerie, la restauration et le commerce de boissons alcooliques (Loi sur les auberges, LAub) (935.11) | 1 | current text only, in force since 1 July 2026 |
| `935-41/` | Loi sur les spectacles et les divertissements (935.41) | 1 | current text only, in force since 1 January 2007 |
| `935-51/` | Loi sur le jeu (935.51) | 1 | current text only, in force since 1 January 2021 |
| `935-52/` | Loi portant introduction de la loi fédérale sur les jeux d’argent (LiLJAr) (935.52) | 1 | current text only, in force since 1 February 2026 |
| `935-91/` | Loi concernant les entreprises de pompes funèbres (935.91) | 1 | current text only, in force since 1 February 2019 |
| `935-211/` | Loi sur le tourisme (LTour) (935.211) | 1 | current text only, in force since 1 January 2023 |
| `943-1/` | Loi concernant l’exercice de la prostitution et le commerce de la pornographie (Loi sur la prostitution, LProst) (943.1) | 1 | current text only, in force since 1 January 2026 |
| `951-11/` | Loi sur la Banque cantonale du Jura (951.11) | 1 | current text only, in force since 1 September 2009 |
| `971-1/` | Loi sur la coopération au développement et l'aide humanitaire (Loi sur la coopération, LCDAH) (971.1) | 1 | current text only, in force since 1 January 2026 |
| `142-111/` | Ordonnance concernant le contrôle des habitants (142.111) | 1 | current text only, in force since 1 December 2024 |
| `142-411/` | Ordonnance concernant la détention en matière de droit des étrangers (142.411) | 1 | current text only, in force since 1 August 2008 |
| `143-12/` | Ordonnance concernant les actes d'origine et le registre de ces actes (143.12) | 1 | current text only, in force since 1 January 1979 |
| `143-21/` | Ordonnance relative à l'établissement des documents d'identité (143.21) | 1 | current text only, in force since 1 June 2010 |
| `144-1/` | Ordonnance concernant l'intégration des étrangers et la lutte contre le racisme (144.1) | 1 | current text only, in force since 15 May 2011 |
| `151-11/` | Ordonnance sur la vérification de l’analyse de l’égalité des salaires (151.11) | 1 | current text only, in force since 1 January 2026 |
| `161-11/` | Ordonnance d'exécution de la loi sur les droits politiques (161.11) | 1 | current text only, in force since 1 June 2023 |
| `161-15/` | Ordonnance concernant le registre des électeurs (161.15) | 1 | current text only, in force since 1 January 2013 |
| `161-19/` | Ordonnance concernant les élections communales (161.19) | 1 | current text only, in force since 1 March 2022 |
| `170-421/` | Ordonnance concernant le guichet virtuel sécurisé (OGVS) (170.421) | 1 | current text only, in force since 1 December 2024 |
| `170-511/` | Ordonnance concernant la publication du Recueil systématique et du Recueil officiel (170.511) | 1 | current text only, in force since 1 January 1979 |
| `170-513/` | Ordonnance concernant la publication du Journal officiel (170.513) | 1 | current text only, in force since 1 January 2013 |
| `170-514/` | Ordonnance concernant la publication de la Feuille d'Avis (170.514) | 1 | current text only, in force since 1 January 1979 |
| `172-111-151/` | Ordonnance concernant le Bureau de la condition féminine (172.111.151) | 1 | current text only, in force since 1 July 2012 |
| `172-111-152/` | Ordonnance concernant le guichet unique (OGU) (172.111.152) | 1 | current text only, in force since 1 January 2026 |
| `172-111-216/` | Ordonnance concernant le règlement des sinistres relatifs à la responsabilité civile de l'Etat (172.111.216) | 1 | current text only, in force since 15 September 2006 |
| `172-111-217/` | Ordonnance désignant le service cantonal de coordination en matière de disparitions forcées (172.111.217) | 1 | current text only, in force since 1 January 2017 |
| `172-356/` | Ordonnance concernant la durée des mandats et les indemnités journalières et de déplacement des membres de commissions cantonales (172.356) | 1 | current text only, in force since 1 January 2009 |
| `173-21/` | Ordonnance concernant l'occupation de logements de fonction (173.21) | 1 | current text only, in force since 1 August 2016 |
| `173-111/` | Ordonnance sur le personnel de l'Etat (OPer) (173.111) | 1 | current text only, in force since 1 February 2026 |
| `173-113-3/` | Ordonnance portant délégation de compétence du Gouvernement au Département de l'Education concernant l'engagement d'employés de l'Etat, rattachés à la section d'archéologie et de paléontologie de l'Office cantonal de la culture, dont le financement est assuré par la Confédération dans le cadre du projet A16 (173.113.3) | 1 | current text only, in force since 1 January 2006 |
| `173-411-01/` | Ordonnance sur les traitements du personnel de l'Etat (173.411.01) | 1 | current text only, in force since 1 May 2016 |
| `173-411-02/` | Ordonnance concernant la commission paritaire d'évaluation et de classification des fonctions (173.411.02) | 1 | current text only, in force since 1 March 2014 |
| `173-411-11/` | Ordonnance concernant les indemnités horaires et de déplacement dues aux anciens membres du Gouvernement pour l'exécution des mandats qui leur sont confiés (173.411.11) | 1 | current text only, in force since 1 October 1991 |
| `173-441/` | Ordonnance concernant la rétribution des employés dont l’activité ne figure pas dans la classification des fonctions (173.441) | 1 | current text only, in force since 1 October 2021 |
| `173-461/` | Ordonnance concernant le remboursement des dépenses du personnel de l'Etat (173.461) | 1 | current text only, in force since 1 January 2021 |
| `173-461-151/` | Ordonnance concernant l'habillement des huissiers (173.461.151) | 1 | current text only, in force since 1 August 2016 |
| `173-461-551/` | Ordonnance concernant le remboursement des dépenses spéciales des employés de la police cantonale (173.461.551) | 1 | current text only, in force since 1 August 2016 |
| `173-461-722/` | Ordonnance concernant les indemnités de repas versées au personnel du Service des infrastructures (173.461.722) | 1 | current text only, in force since 1 June 2019 |
| `173-461-751/` | Ordonnance concernant les indemnités pour dépenses spéciales accordées aux gardes de l'Office de l'environnement (173.461.751) | 1 | current text only, in force since 1 August 2016 |
| `173-462/` | Ordonnance relative aux indemnités versées aux employés de l'Etat pour inconvénients particuliers (173.462) | 1 | current text only, in force since 1 August 2016 |
| `173-471/` | Ordonnance concernant le versement du traitement au personnel de l'Etat en cas de service militaire (173.471) | 1 | current text only, in force since 1 January 1979 |
| `174-11/` | Ordonnance concernant les marchés publics (OMP-JU) (174.11) | 1 | current text only, in force since 1 May 2024 |
| `181-111/` | Ordonnance concernant l'exercice de la fonction de juge et de procureur à temps partiel (181.111) | 1 | current text only, in force since 1 December 2010 |
| `182-61/` | Ordonnance concernant l'organisation de cours de droit pour avocats et notaires stagiaires (182.61) | 1 | current text only, in force since 1 January 2013 |
| `182-351/` | Ordonnance concernant les commissions de conciliation en matière de bail et la consignation du loyer (182.351) | 1 | current text only, in force since 1 September 2015 |
| `188-41/` | Ordonnance concernant le fonctionnement de la Chambre des avocats (188.41) | 1 | current text only, in force since 1 June 2017 |
| `188-61/` | Ordonnance fixant le tarif des honoraires d'avocat (188.61) | 1 | current text only, in force since 1 September 2015 |
| `189-112/` | Ordonnance portant exécution de la loi sur le notariat (189.112) | 1 | current text only, in force since 1 January 1979 |
| `189-211/` | Ordonnance sur le stage et les examens de notaire (189.211) | 1 | current text only, in force since 1 August 2016 |
| `192-11/` | Ordonnance concernant l'orthographe officielle des noms des communes (192.11) | 1 | current text only, in force since 1 January 2026 |
| `213-11/` | Ordonnance concernant la protection de l'enfant et de l'adulte (213.11) | 1 | current text only, in force since 1 January 2017 |
| `213-12/` | Ordonnance sur la rémunération et le remboursement des frais en matière de gestion de mesures de protection de l'enfant et de l'adulte (213.12) | 1 | current text only, in force since 1 October 2014 |
| `213-222/` | Ordonnance portant introduction de la loi fédérale sur l'enlèvement international d'enfants et les Conventions de La Haye sur la protection des enfants et des adultes (213.222) | 1 | current text only, in force since 1 January 2026 |
| `215-129-1/` | Ordonnance relative à la commission cantonale d'estimation foncière (215.129.1) | 1 | current text only, in force since 1 October 2005 |
| `215-231/` | Ordonnance concernant l'engagement du bétail (215.231) | 1 | current text only, in force since 1 January 1979 |
| `215-322-1/` | Ordonnance concernant l'organisation du registre foncier (215.322.1) | 1 | current text only, in force since 1 January 2000 |
| `215-341-11/` | Ordonnance sur la géoinformation (OCGéo) (215.341.11) | 1 | current text only, in force since 1 February 2020 |
| `215-342-6/` | Ordonnance sur le tarif des honoraires pour la conservation des documents cadastraux (215.342.6) | 1 | current text only, in force since 1 June 1989 |
| `222-153-11/` | Ordonnance portant exécution de la loi fédérale du 28 septembre 1956 permettant d'étendre le champ d'application de la convention collective de travail (222.153.11) | 1 | current text only, in force since 1 May 2015 |
| `224-1/` | Ordonnance concernant l'organisation du registre du commerce (224.1) | 1 | current text only, in force since 1 January 2000 |
| `271-11/` | Ordonnance concernant la prise en charge des frais de médiation dans le cadre d’une procédure civile (271.11) | 1 | current text only, in force since 1 August 2024 |
| `271-111/` | Ordonnance concernant le remboursement de l’assistance judiciaire en matière civile (271.111) | 1 | current text only, in force since 1 January 2021 |
| `284-11/` | Ordonnance portant exécution de la loi fédérale du 4 décembre 1947 réglant la poursuite pour dettes contre les communes et autres collectivités de droit public cantonal (284.11) | 1 | current text only, in force since 1 January 1979 |
| `324-111/` | Ordonnance d’exécution de la loi portant introduction de la loi fédérale sur les amendes d’ordre (OLiLAO) (324.111) | 1 | current text only, in force since 1 January 2026 |
| `331/` | Ordonnance portant exécution de la législation fédérale sur le casier judiciaire (331) | 1 | current text only, in force since 23 January 2023 |
| `341-11/` | Ordonnance concernant la surveillance électronique (341.11) | 1 | current text only, in force since 1 January 2022 |
| `342-11/` | Ordonnance sur les établissements de détention (342.11) | 1 | current text only, in force since 1 November 2015 |
| `351-1/` | Ordonnance concernant la réglementation interne des affaires intercantonales d'extradition (351.1) | 1 | current text only, in force since 1 January 1979 |
| `410-71/` | Ordonnance concernant l'unité de santé scolaire (410.71) | 1 | current text only, in force since 1 January 2021 |
| `410-81/` | Ordonnance concernant l'orientation scolaire et professionnelle et la psychologie scolaire (410.81) | 1 | current text only, in force since 1 October 2025 |
| `410-111/` | Ordonnance portant exécution de la loi scolaire (Ordonnance scolaire) (410.111) | 1 | current text only, in force since 1 August 2026 |
| `410-113/` | Ordonnance fixant les conditions cadres pour les transports scolaires (410.113) | 1 | current text only, in force since 1 January 2008 |
| `410-114/` | Ordonnance concernant la pédagogie spécialisée (410.114) | 1 | current text only, in force since 1 August 2024 |
| `410-210-15/` | Ordonnance sur la reconnaissance des titres d'enseignement (410.210.15) | 1 | current text only, in force since 1 October 2016 |
| `410-252-1/` | Ordonnance concernant le programme horaire du personnel de la scolarité obligatoire (410.252.1) | 1 | current text only, in force since 1 August 2026 |
| `410-252-2/` | Ordonnance sur la direction des écoles obligatoires (410.252.2) | 1 | current text only, in force since 1 August 2026 |
| `410-252-3/` | Ordonnance concernant les allègements de programme accordés aux enseignants de la scolarité obligatoire (410.252.3) | 1 | current text only, in force since 1 August 2026 |
| `410-252-4/` | Ordonnance concernant l'enseignement dans la scolarité obligatoire de disciplines ou de niveaux ne relevant pas du titre pédagogique acquis (410.252.4) | 1 | current text only, in force since 1 August 2019 |
| `410-254-2/` | Ordonnance concernant la répartition des charges pour le traitement des enseignants (410.254.2) | 1 | current text only, in force since 1 January 1998 |
| `410-316-1/` | Ordonnance sur les installations scolaires (410.316.1) | 1 | current text only, in force since 1 July 2012 |
| `410-318/` | Ordonnance concernant le versement de subventions pour l'acquisition d'établis et d'outils destinés à l'enseignement des travaux manuels (410.318) | 1 | current text only, in force since 1 January 1979 |
| `410-417/` | Ordonnance concernant les prestations assimilables à des moyens d'enseignement (410.417) | 1 | current text only, in force since 1 April 2007 |
| `410-721/` | Ordonnance concernant le service dentaire scolaire (410.721) | 1 | current text only, in force since 1 January 2021 |
| `410-726/` | Ordonnance fixant le tarif pour les soins dentaires scolaires (410.726) | 1 | current text only, in force since 1 August 1994 |
| `412-011/` | Ordonnance sur l'organisation de l'enseignement et de la formation des niveaux secondaire II et tertiaire (412.011) | 1 | current text only, in force since 1 April 2019 |
| `412-71/` | Ordonnance concernant les activités parascolaires dans les écoles cantonales relevant du Département de I’Education (412.71) | 1 | current text only, in force since 1 August 2015 |
| `412-351/` | Ordonnance concernant les examens ordinaires de la maturité gymnasiale dans les lycées de la République et Canton du Jura (412.351) | 1 | current text only, in force since 1 August 2023 |
| `412-354/` | Ordonnance concernant les personnes associées aux examens des écoles moyennes (412.354) | 1 | current text only, in force since 1 August 2005 |
| `412-515/` | Ordonnance concernant la délivrance du certificat d’école de culture générale et du certificat de maturité spécialisée (412.515) | 1 | current text only, in force since 1 August 2023 |
| `412-632/` | Ordonnance concernant la prise en charge des frais de scolarité qui découlent de la fréquentation de lycées publics d'autres cantons (412.632) | 1 | current text only, in force since 1 January 1979 |
| `413-121/` | Ordonnance concernant le fonds pour le soutien aux formations professionnelles (413.121) | 1 | current text only, in force since 1 January 2023 |
| `413-213-1/` | Ordonnance portant reconnaissance du Centre de formation du Foyer jurassien à Delémont en tant qu'atelier de préapprentissage (413.213.1) | 1 | current text only, in force since 1 August 1993 |
| `413-241-1/` | Ordonnance sur les surveillants et l'indemnisation de la commission cantonale d'apprentissage et des surveillants (413.241.1) | 1 | current text only, in force since 1 January 2005 |
| `413-252-4/` | Ordonnance concernant le régime des absences dans les écoles professionnelles artisanales et commerciales, ainsi que dans les ateliers d'apprentissage (413.252.4) | 1 | current text only, in force since 1 January 1979 |
| `413-254/` | Ordonnance concernant le programme horaire des enseignants du Centre jurassien d'enseignement et de formation (413.254) | 1 | current text only, in force since 1 August 2026 |
| `413-255/` | Ordonnance sur la maturité professionnelle (413.255) | 1 | current text only, in force since 1 August 2019 |
| `413-261/` | Ordonnance sur l’organisation des examens, les commissions d’examen et les experts aux examens (413.261) | 1 | current text only, in force since 1 January 2019 |
| `413-271/` | Ordonnance sur la formation élémentaire (413.271) | 1 | current text only, in force since 1 January 1994 |
| `415-11/` | Ordonnance portant exécution de la loi visant à encourager les activités physiques et le sport (415.11) | 1 | current text only, in force since 1 April 2026 |
| `415-41/` | Ordonnance sur le sport scolaire facultatif (415.41) | 1 | current text only, in force since 1 August 1993 |
| `416-311/` | Ordonnance concernant les subsides de formation (416.311) | 1 | current text only, in force since 1 July 2020 |
| `417-11/` | Ordonnance portant exécution de la loi sur l'enseignement privé (417.11) | 1 | current text only, in force since 1 August 2025 |
| `441-211/` | Ordonnance sur les archives publiques de la République et Canton du Jura (441.211) | 1 | current text only, in force since 1 May 1988 |
| `441-212/` | Ordonnance concernant l'administration des archives communales (441.212) | 1 | current text only, in force since 1 April 2012 |
| `441-213/` | Ordonnance concernant la commission des archives (441.213) | 1 | current text only, in force since 1 October 2016 |
| `441-221/` | Ordonnance concernant les bibliothèques et la promotion de la lecture publique (441.221) | 1 | current text only, in force since 1 January 2025 |
| `441-232/` | Ordonnance concernant la commission des musées (441.232) | 1 | current text only, in force since 1 June 2026 |
| `443-11/` | Ordonnance instituant la commission des affaires culturelles (443.11) | 1 | current text only, in force since 1 July 2012 |
| `443-14/` | Ordonnance concernant l'encouragement de la création audiovisuelle (443.14) | 1 | current text only, in force since 1 July 2012 |
| `444-31/` | Ordonnance concernant l'encouragement des beaux-arts (444.31) | 1 | current text only, in force since 1 July 2012 |
| `444-41/` | Ordonnance concernant les bourses artistiques et les ateliers d’artistes (444.41) | 1 | current text only, in force since 1 February 2022 |
| `445-2/` | Ordonnance sur la protection et la conservation des curiosités naturelles et des antiquités dans le canton du Jura (445.2) | 1 | current text only, in force since 1 January 2007 |
| `445-12/` | Ordonnance relative à la loi sur la conservation des objets d'art et monuments historiques (445.12) | 1 | current text only, in force since 1 January 1979 |
| `445-41/` | Ordonnance sur la protection du patrimoine archéologique et paléontologique (OPPAP) (445.41) | 1 | current text only, in force since 1 July 2021 |
| `451-11/` | Ordonnance sur la protection de la nature et du paysage (OPNP) (451.11) | 1 | current text only, in force since 1 January 2026 |
| `451-632/` | Ordonnance concernant le Fonds de la commission pour la protection de l'environnement (451.632) | 1 | current text only, in force since 1 January 1979 |
| `455-1/` | Ordonnance portant exécution de la législation fédérale sur la protection des animaux (455.1) | 1 | current text only, in force since 1 March 2013 |
| `474-11/` | Ordonnance sur les impôts ecclésiastiques (474.11) | 1 | current text only, in force since 1 January 1979 |
| `511-411/` | Ordonnance concernant l'organisation du commandement d'arrondissement militaire (511.411) | 1 | current text only, in force since 1 January 2003 |
| `521-3/` | Ordonnance concernant la protection des biens culturels (521.3) | 1 | current text only, in force since 1 January 1989 |
| `521-11/` | Ordonnance sur la protection de la population et la protection civile (OPCi) (521.11) | 1 | current text only, in force since 1 August 2014 |
| `521-12/` | Ordonnance concernant l’activité des médecins-conseils de la commission sanitaire cantonale de la protection civile (521.12) | 1 | current text only, in force since 1 July 2012 |
| `531-1/` | Ordonnance sur l'approvisionnement économique du pays (531.1) | 1 | current text only, in force since 1 June 2018 |
| `551-11/` | Ordonnance sur l'organisation de la police cantonale (OPol) (551.11) | 1 | current text only, in force since 1 January 2026 |
| `551-12/` | Ordonnance sur la collaboration entre la police cantonale et les communes (551.12) | 1 | current text only, in force since 1 March 2017 |
| `551-21/` | Ordonnance portant délégation de compétences du Gouvernement au département auquel est rattachée la police cantonale pour accorder l’entraide concordataire et pour autoriser l’engagement de la police cantonale hors du canton (551.21) | 1 | current text only, in force since 1 August 2018 |
| `555-11/` | Ordonnance sur l’application du repos dominical (555.11) | 1 | current text only, in force since 1 January 1979 |
| `559-21/` | Ordonnance portant exécution du concordat instituant des mesures contre la violence lors de manifestations sportives (559.21) | 1 | current text only, in force since 1 March 2014 |
| `559-115-11/` | Ordonnance concernant les centrales et les dispositifs d'alarme (559.115.11) | 1 | current text only, in force since 1 January 2019 |
| `611-2/` | Ordonnance concernant la gestion centralisée du suivi des débiteurs et des actes de défaut de biens de l'Etat (611.2) | 1 | current text only, in force since 1 October 2025 |
| `611-4/` | Ordonnance réglant la gestion des sûretés, garanties et autres valeurs déposées ou consignées (611.4) | 1 | current text only, in force since 1 January 1989 |
| `611-12/` | Ordonnance concernant la délégation de compétences financières (611.12) | 1 | current text only, in force since 1 January 2018 |
| `641-261/` | Ordonnance relative aux exonérations de l'impôt (641.261) | 1 | current text only, in force since 1 March 2014 |
| `641-262/` | Ordonnance relative au traitement fiscal de la prévoyance professionnelle (641.262) | 1 | current text only, in force since 1 May 2021 |
| `641-263/` | Ordonnance concernant l'amnistie fiscale (641.263) | 1 | current text only, in force since 1 January 2010 |
| `641-311-1/` | Ordonnance concernant le calcul dans le temps de l'impôt dû par les personnes physiques (641.311.1) | 1 | current text only, in force since 1 January 2001 |
| `641-312-21/` | Ordonnance sur l'imposition d'après la dépense en matière d'impôt d'Etat (641.312.21) | 1 | current text only, in force since 1 January 2016 |
| `641-312-51/` | Ordonnance relative à la déduction des frais d'entretien d'immeubles (641.312.51) | 1 | current text only, in force since 1 January 2024 |
| `641-312-56/` | Ordonnance relative à l'évaluation des frais professionnels liés à une activité lucrative dépendante (641.312.56) | 1 | current text only, in force since 1 January 2022 |
| `641-518/` | Ordonnance concernant les moyens de preuve pour les impenses (641.518) | 1 | current text only, in force since 1 January 2001 |
| `641-543-100/` | Ordonnance réglant les modalités de la révision générale des valeurs officielles d'immeubles et de forces hydrauliques (641.543.100) | 1 | current text only, in force since 1 October 1994 |
| `641-711/` | Ordonnance sur l'imposition à la source (641.711) | 1 | current text only, in force since 1 January 2021 |
| `641-741/` | Ordonnance concernant la remise d'impôt (641.741) | 1 | current text only, in force since 1 January 2014 |
| `645-11/` | Ordonnance concernant la taxe des chiens (645.11) | 1 | current text only, in force since 1 January 2002 |
| `648-11/` | Ordonnance d'exécution concernant l'impôt fédéral direct (648.11) | 1 | current text only, in force since 1 January 2016 |
| `648-21/` | Ordonnance relative au remboursement de l’impôt anticipé (648.21) | 1 | current text only, in force since 1 January 2017 |
| `648-61/` | Ordonnance portant exécution de la loi fédérale du 12 juin 1959 sur la taxe d'exemption de l'obligation de servir (648.61) | 1 | current text only, in force since 1 November 2024 |
| `649-721/` | Ordonnance relative à l’imputation d’impôts étrangers prélevés à la source (649.721) | 1 | current text only, in force since 1 May 2021 |
| `649-791/` | Ordonnance relative au remboursement de la retenue supplémentaire d’impôt des Etats-Unis d’Amérique (649.791) | 1 | current text only, in force since 1 January 2017 |
| `651-11/` | Ordonnance concernant la péréquation financière (651.11) | 1 | current text only, in force since 1 January 2026 |
| `691-11/` | Ordonnance sur la régale des sels (691.11) | 1 | current text only, in force since 1 January 1979 |
| `701-11/` | Ordonnance sur l’aménagement du territoire et les constructions (OATC) (701.11) | 1 | current text only, in force since 1 July 2026 |
| `701-12/` | Ordonnance concernant la cellule administrative responsable de la procédure accélérée en matière de permis de construire dans les zones d'activités d'intérêt cantonal (701.12) | 1 | current text only, in force since 1 April 2012 |
| `701-61/` | Ordonnance réglant les modalités d'octroi de subventions pour la réhabilitation de l'habitat dans les centres anciens (701.61) | 1 | current text only, in force since 1 January 2020 |
| `701-62/` | Ordonnance portant exécution de l’article 5a de la loi fédérale sur l’aménagement du territoire (701.62) | 1 | current text only, in force since 1 July 2026 |
| `701-251/` | Ordonnance concernant la réclame extérieure et sur la voie publique (701.251) | 1 | current text only, in force since 1 March 2021 |
| `702-2/` | Ordonnance instituant la commission du développement durable (702.2) | 1 | current text only, in force since 1 July 2012 |
| `712-1/` | Ordonnance portant exécution de la loi fédérale du 20 juin 1930 sur l'expropriation (712.1) | 1 | current text only, in force since 1 January 1979 |
| `722-112-1/` | Ordonnance portant délégation de compétences au chef du Service des ponts et chaussées en matière de police de construction des routes (722.112.1) | 1 | current text only, in force since 1 March 1985 |
| `722-112-2/` | Ordonnance portant délégation de compétence du Gouvernement au chef de la Section des constructions routières pour la modification de limites cadastrales impliquant des routes cantonales (722.112.2) | 1 | current text only, in force since 1 January 2017 |
| `722-123-31/` | Ordonnance concernant les routes d'approvisionnement à maintenir constamment ouvertes aux transports exceptionnels (722.123.31) | 1 | current text only, in force since 1 January 1979 |
| `722-181/` | Ordonnance portant exécution de la loi fédérale du 8 mars 1960 sur les routes nationales (722.181) | 1 | current text only, in force since 1 January 1979 |
| `730-11/` | Ordonnance portant application de la loi sur l'énergie (Ordonnance sur l'énergie, OEn) (730.11) | 1 | current text only, in force since 1 April 2026 |
| `731-11/` | Ordonnance sur l’approvisionnement en électricité (OAEl) (731.11) | 1 | current text only, in force since 1 March 2024 |
| `731-31/` | Ordonnance relative à l'exécution de la loi fédérale du 24 juin 1902 concernant les installations électriques à faible et à fort courant (731.31) | 1 | current text only, in force since 1 January 1979 |
| `741-25/` | Ordonnance concernant les entreprises de dépannage routier (741.25) | 1 | current text only, in force since 1 May 1998 |
| `741-151/` | Ordonnance concernant les réglementations locales du trafic (741.151) | 1 | current text only, in force since 1 February 2014 |
| `741-161/` | Ordonnance concernant l'attribution de numéros d'immatriculation particuliers (741.161) | 1 | current text only, in force since 1 December 2024 |
| `741-171/` | Ordonnance sur l'utilisation de véhicules automobiles hors de la voie publique (741.171) | 1 | current text only, in force since 1 January 2007 |
| `741-191/` | Ordonnance portant délégation des compétences du Département des Finances et de la Police au chef de l'Office des véhicules pour autoriser les manifestations sportives sur la voie publique et la circulation hors de la voie publique (741.191) | 1 | current text only, in force since 1 January 1983 |
| `741-421/` | Ordonnance concernant l'assurance-responsabilité civile des détenteurs de cycles (741.421) | 1 | current text only, in force since 1 January 1979 |
| `741-611-1/` | Ordonnance concernant la réduction de la taxe sur les véhicules en faveur des handicapés (741.611.1) | 1 | current text only, in force since 1 January 2015 |
| `742-212/` | Ordonnance concernant la conférence des transports (742.212) | 1 | current text only, in force since 1 July 2013 |
| `742-213/` | Ordonnance concernant la commission technique des transports (742.213) | 1 | current text only, in force since 1 July 2016 |
| `744-12/` | Ordonnance concernant l'octroi d'autorisations cantonales de transport par automobiles (744.12) | 1 | current text only, in force since 1 June 1998 |
| `746-11/` | Ordonnance concernant les installations de transport par conduites de combustibles ou carburants liquides ou gazeux, installations sous surveillance cantonale (746.11) | 1 | current text only, in force since 1 January 1979 |
| `747-11/` | Ordonnance concernant l'exécution de l'article 62 de la loi fédérale du 28 septembre 1923 sur le registre des bateaux (747.11) | 1 | current text only, in force since 1 January 1979 |
| `747-201/` | Ordonnance sur la navigation (747.201) | 1 | current text only, in force since 1 June 2010 |
| `751-151/` | Ordonnance concernant l'amarrage de bateaux, radeaux, etc., sur les cours d'eau du domaine public et privé (751.151) | 1 | current text only, in force since 1 January 1979 |
| `810-05/` | Ordonnance concernant les recherches sur l'être humain (810.05) | 1 | current text only, in force since 1 February 1996 |
| `810-015/` | Ordonnance concernant les appareils de bronzage ainsi que la vente des produits du tabac, des cigarettes électroniques et de produits similaires (810.015) | 1 | current text only, in force since 1 March 2023 |
| `810-021/` | Ordonnance concernant les droits des patients (810.021) | 1 | current text only, in force since 1 June 2017 |
| `810-31/` | Ordonnance concernant la Fondation pour l'Aide et les Soins à domicile (810.31) | 1 | current text only, in force since 1 January 2011 |
| `810-111-1/` | Ordonnance sur les établissements hospitaliers (810.111.1) | 1 | current text only, in force since 1 January 2020 |
| `810-411/` | Ordonnance sur l'organisation gérontologique (810.411) | 1 | current text only, in force since 14 November 2018 |
| `810-511-1/` | Ordonnance concernant les unités de soins psychiatriques (810.511.1) | 1 | current text only, in force since 1 December 2024 |
| `811-111/` | Ordonnance concernant l'exercice des professions de médecin, de dentiste, de chiropraticien et de vétérinaire (811.111) | 1 | current text only, in force since 1 December 2007 |
| `811-211/` | Ordonnance concernant le service ambulancier (811.211) | 1 | current text only, in force since 1 January 2020 |
| `811-213/` | Ordonnance concernant l'exercice des professions de la santé (811.213) | 1 | current text only, in force since 1 December 2007 |
| `811-221/` | Ordonnance portant exécution de la loi sur l’encouragement de la formation dans le domaine des soins (811.221) | 1 | current text only, in force since 1 January 2026 |
| `811-923/` | Ordonnance fixant les honoraires des médecins agissant pour le compte des autorités d'assistance (811.923) | 1 | current text only, in force since 1 January 1981 |
| `811-924/` | Ordonnance concernant les tarifs du Centre médico-psychologique (811.924) | 1 | current text only, in force since 1 January 2009 |
| `811-941/` | Ordonnance sur les honoraires des médecins-vétérinaires agissant à la requête des autorités (811.941) | 1 | current text only, in force since 1 February 2010 |
| `811-981/` | Ordonnance concernant les honoraires des sages-femmes (811.981) | 1 | current text only, in force since 1 January 1979 |
| `812-41/` | Ordonnance sur les pharmacies, les produits thérapeutiques et les stupéfiants (812.41) | 1 | current text only, in force since 1 January 2025 |
| `812-42/` | Ordonnance sur les drogueries (812.42) | 1 | current text only, in force since 1 January 2007 |
| `812-211/` | Ordonnance sur les médicaments vétérinaires (812.211) | 1 | current text only, in force since 1 January 2014 |
| `814-01/` | Ordonnance portant application de la loi fédérale sur la protection de l’environnement (814.01) | 1 | current text only, in force since 1 June 2024 |
| `814-02/` | Ordonnance concernant les mesures de lutte contre la pollution de l'air par des poussières fines (814.02) | 1 | current text only, in force since 1 January 2007 |
| `814-12/` | Ordonnance sur la protection des sols (814.12) | 1 | current text only, in force since 1 January 2008 |
| `814-21/` | Ordonnance sur la gestion des eaux (OGEaux) (814.21) | 1 | current text only, in force since 1 July 2023 |
| `814-22/` | Ordonnance sur les mesures de protection à prendre en cas d'événement impliquant des matières dangereuses (814.22) | 1 | current text only, in force since 1 January 2002 |
| `814-81/` | Ordonnance portant application de la loi fédérale sur les produits chimiques (814.81) | 1 | current text only, in force since 1 June 2024 |
| `817-190/` | Ordonnance portant exécution de la législation fédérale sur l'abattage d'animaux et le contrôle des viandes (817.190) | 1 | current text only, in force since 1 April 2016 |
| `818-161-1/` | Ordonnance concernant les vaccins et vaccinations (818.161.1) | 1 | current text only, in force since 1 April 2009 |
| `822-22/` | Ordonnance sur la durée du travail et du repos des conducteurs professionnels de véhicules automobiles (822.22) | 1 | current text only, in force since 1 June 2017 |
| `822-31/` | Ordonnance portant exécution de la loi fédérale du 20 mars 1981 sur le travail à domicile (822.31) | 1 | current text only, in force since 15 September 1983 |
| `822-112-1/` | Ordonnance portant délégation des compétences du Département de l'Economie publique à l'inspecteur du Service des arts et métiers et du travail concernant les autorisations d'exploiter et les règlements d'entreprises (822.112.1) | 1 | current text only, in force since 1 June 1983 |
| `822-411/` | Ordonnance d’exécution de la loi sur le salaire minimum cantonal (822.411) | 1 | current text only, in force since 1 July 2024 |
| `823-4/` | Ordonnance concernant l'organe de contrôle cantonal au sens de la loi fédérale sur le travail au noir (823.4) | 1 | current text only, in force since 1 June 2017 |
| `823-112/` | Ordonnance portant introduction de l'assurance-chômage obligatoire selon l'arrêté fédéral du 8 octobre 1976 (823.112) | 1 | current text only, in force since 1 January 1979 |
| `823-131/` | Ordonnance sur le secours de crise en faveur de chômeurs assurés (823.131) | 1 | current text only, in force since 1 January 1984 |
| `823-321/` | Ordonnance portant encouragement de la constitution de réserves de crise par l'économie privée (823.321) | 1 | current text only, in force since 1 January 1979 |
| `823-331/` | Ordonnance sur la constitution de réserves de crise bénéficiant d'allégements fiscaux (823.331) | 1 | current text only, in force since 1 January 1992 |
| `831-101/` | Ordonnance d'exécution de la loi du 26 octobre 1978 portant introduction de la loi fédérale sur l'assurance-vieillesse et survivants (831.101) | 1 | current text only, in force since 1 January 2022 |
| `831-102/` | Ordonnance fixant l'organisation et les attributions de la commission de gestion de la Caisse de compensation de la République et Canton du Jura (831.102) | 1 | current text only, in force since 1 November 1991 |
| `831-301/` | Ordonnance sur les prestations complémentaires à l'assurance-vieillesse, survivants et invalidité (831.301) | 1 | current text only, in force since 1 January 2026 |
| `832-25/` | Ordonnance concernant les déclarations et enquêtes en matière d'accidents qui frappent des personnes assurées auprès de la Caisse nationale suisse (832.25) | 1 | current text only, in force since 1 January 1979 |
| `832-041-5/` | Ordonnance concernant l'assurance-maladie et accidents des apprentis (832.041.5) | 1 | current text only, in force since 1 January 1984 |
| `832-111/` | Ordonnance sur le financement des soins (832.111) | 1 | current text only, in force since 1 January 2026 |
| `832-112/` | Ordonnance fixant la part cantonale à la rémunération des prestations hospitalières pour l'année 2012 (832.112) | 1 | current text only, in force since 1 January 2012 |
| `832-114/` | Ordonnance portant exécution de la loi du 9 novembre 1978 concernant l'assurance en cas de maladie (832.114) | 1 | current text only, in force since 1 January 1979 |
| `832-115/` | Ordonnance concernant la réduction des primes dans l'assurance-maladie (832.115) | 1 | current text only, in force since 1 January 2026 |
| `832-116/` | Ordonnance concernant la limitation de l’admission des médecins à pratiquer à la charge de l’assurance obligatoire des soins dans le domaine ambulatoire (832.116) | 1 | current text only, in force since 1 July 2023 |
| `832-311/` | Ordonnance concernant les dépôts d'explosifs (832.311) | 1 | current text only, in force since 1 January 1979 |
| `832-312/` | Ordonnance concernant la garde d'explosifs dits de sûreté (832.312) | 1 | current text only, in force since 1 January 1979 |
| `836-11/` | Ordonnance fixant les modalités de la surcompensation entre les caisses de compensation pour allocations familiales (836.11) | 1 | current text only, in force since 1 January 2013 |
| `837-03/` | Ordonnance fixant le statut et l'organisation de la Caisse publique de chômage de la République et Canton du Jura (837.03) | 1 | current text only, in force since 1 October 1988 |
| `837-041/` | Ordonnance sur les mesures cantonales en faveur des demandeurs d'emploi (837.041) | 1 | current text only, in force since 1 November 2012 |
| `837-042/` | Ordonnance concernant la commission de coordination des mesures cantonales en faveur des demandeurs d'emploi (837.042) | 1 | current text only, in force since 1 June 2019 |
| `843-11/` | Ordonnance sur le maintien de locaux d'habitation (843.11) | 1 | current text only, in force since 1 January 1979 |
| `850-111/` | Ordonnance sur l'action sociale (850.111) | 1 | current text only, in force since 1 January 2023 |
| `850-112/` | Ordonnance concernant les institutions sociales (850.112) | 1 | current text only, in force since 1 January 2018 |
| `851-11/` | Ordonnance concernant l’avance et le versement provisionnel de contributions d’entretien (851.11) | 1 | current text only, in force since 1 March 2026 |
| `853-11/` | Ordonnance concernant le placement d'enfants (853.11) | 1 | current text only, in force since 1 August 2026 |
| `853-211/` | Ordonnance sur la politique de la jeunesse (853.211) | 1 | current text only, in force since 1 August 2024 |
| `871-11/` | Ordonnance sur la protection contre les incendies et les dangers naturels et sur le ramonage (871.11) | 1 | current text only, in force since 1 January 2023 |
| `873-112-1/` | Ordonnance relative à la commission de l'Etablissement d'assurance immobilière (873.112.1) | 1 | current text only, in force since 15 March 1979 |
| `873-211/` | Ordonnance concernant l'assurance mobilière contre l'incendie (873.211) | 1 | current text only, in force since 1 January 1979 |
| `875-11/` | Ordonnance sur le service de défense contre l'incendie et de secours (875.11) | 1 | current text only, in force since 1 January 2018 |
| `875-112/` | Ordonnance fixant le nombre d'arrondissements d'inspection des services de défense contre l'incendie et de secours (875.112) | 1 | current text only, in force since 1 January 2026 |
| `875-121/` | Ordonnance concernant les centres de renfort (875.121) | 1 | current text only, in force since 1 January 2026 |
| `901-11/` | Ordonnance relative au conseil d’administration de la Société coopérative pour le développement de l’économie jurassienne (901.11) | 1 | current text only, in force since 1 November 2025 |
| `901-61/` | Ordonnance relative au contrôle du respect des conditions d'octroi des aides financières accordées au titre de la promotion économique (901.61) | 1 | current text only, in force since 1 November 2025 |
| `901-811/` | Ordonnance concernant les mesures de soutien aux entreprises jurassiennes en difficulté suite à l’épidémie de COVID-19 (901.811) | 1 | current text only, in force since 18 December 2021 |
| `910-14/` | Ordonnance relative au versement de contributions à la biodiversité et à la qualité du paysage (910.14) | 1 | current text only, in force since 1 August 2014 |
| `913-113/` | Ordonnance réglant la procédure de réquisition et d'inscription d'un remaniement parcellaire au registre foncier (913.113) | 1 | current text only, in force since 1 October 1992 |
| `914-11/` | Ordonnance sur les crédits d'investissements dans l'agriculture et l'aide aux exploitations paysannes (914.11) | 1 | current text only, in force since 1 January 1979 |
| `915-111/` | Ordonnance sur la formation professionnelle en agriculture et en économie familiale (915.111) | 1 | current text only, in force since 1 January 2026 |
| `916-21/` | Ordonnance concernant la protection des cultures contre les organismes des espèces végétales et animales constituant un danger général (Ordonnance sur la protection des cultures) (916.21) | 1 | current text only, in force since 15 January 1991 |
| `916-51/` | Ordonnance portant exécution de la législation fédérale sur les épizooties et l'élimination des sous-produits animaux (916.51) | 1 | current text only, in force since 1 April 2021 |
| `916-141/` | Ordonnance sur la viticulture et l'appellation des vins (916.141) | 1 | current text only, in force since 1 April 2024 |
| `916-413/` | Ordonnance portant exécution de la loi fédérale du 28 juin 1974 instituant une contribution aux frais des détenteurs de bétail de la région de montagne et de la région préalpine des collines (916.413) | 1 | current text only, in force since 1 January 1979 |
| `916-450-1/` | Ordonnance portant application de la loi fédérale du 2 octobre 1964 modifiant l'arrêté sur le statut du lait (916.450.1) | 1 | current text only, in force since 1 January 1979 |
| `916-451-1/` | Ordonnance sur le contrôle du lait (916.451.1) | 1 | current text only, in force since 1 March 2012 |
| `916-611-1/` | Ordonnance sur l'assurance du bétail (916.611.1) | 1 | current text only, in force since 1 January 1979 |
| `916-621/` | Ordonnance concernant les accidents de bétail dus au libre parcours dans les Franches-Montagnes (916.621) | 1 | current text only, in force since 1 October 1982 |
| `917-32/` | Ordonnance concernant l'assurance-accidents et la prévention des accidents dans l'agriculture (917.32) | 1 | current text only, in force since 1 January 1979 |
| `921-111-1/` | Ordonnance sur les forêts (921.111.1) | 1 | current text only, in force since 1 July 2012 |
| `922-31/` | Ordonnance concernant l'octroi du permis temporaire de chasser (922.31) | 1 | current text only, in force since 1 June 2011 |
| `922-111/` | Ordonnance sur la chasse et la protection de la faune sauvage (922.111) | 1 | current text only, in force since 1 July 2012 |
| `923-61/` | Ordonnance sur le fonds de la pêche (923.61) | 1 | current text only, in force since 1 January 1979 |
| `923-111/` | Ordonnance portant exécution de la loi du 26 octobre 1978 sur la pêche (923.111) | 1 | current text only, in force since 1 January 1979 |
| `923-121/` | Ordonnance concernant le développement et la protection de la pêche, ainsi que l'aménagement des eaux poissonneuses (923.121) | 1 | current text only, in force since 1 January 1979 |
| `923-131/` | Ordonnance concernant l'affermage des eaux poissonneuses (923.131) | 1 | current text only, in force since 1 January 2013 |
| `931-41/` | Ordonnance concernant les forages pétroliers (Ordonnance sur les forages) (931.41) | 1 | current text only, in force since 1 January 1979 |
| `935-111/` | Ordonnance sur l'hôtellerie, la restauration et le commerce de boissons alcooliques (Ordonnance sur les auberges, OAub) (935.111) | 1 | current text only, in force since 1 February 2026 |
| `935-211-1/` | Ordonnance portant exécution de la loi sur le tourisme (OTour) (935.211.1) | 1 | current text only, in force since 1 January 2026 |
| `935-253/` | Ordonnance concernant l'exploitation industrielle des beautés de la nature (935.253) | 1 | current text only, in force since 1 January 1979 |
| `935-411/` | Ordonnance sur les spectacles et les divertissements (935.411) | 1 | current text only, in force since 1 February 2026 |
| `935-521/` | Ordonnance d’exécution de la loi portant introduction de la loi fédérale sur les jeux d’argent (OLiLJAr) (935.521) | 1 | current text only, in force since 1 January 2026 |
| `935-551/` | Ordonnance concernant l'exploitation à titre professionnel d'appareils de jeu (935.551) | 1 | current text only, in force since 1 January 2007 |
| `935-921-1/` | Ordonnance concernant les agences matrimoniales (935.921.1) | 1 | current text only, in force since 1 January 2007 |
| `935-976-1/` | Ordonnance concernant la détention et la conduite de taxis dans les communes (935.976.1) | 1 | current text only, in force since 1 January 1979 |
| `935-991-2/` | Ordonnance concernant l'exercice de la maréchalerie (935.991.2) | 1 | current text only, in force since 1 January 1979 |
| `935-993-1/` | Ordonnance sur l'exercice des professions de prêteur d'argent, d'entremetteur de prêts, de prêteur sur gages et de fripier (935.993.1) | 1 | current text only, in force since 1 January 1979 |
| `935-993-2/` | Ordonnance concernant les agences privées de détectives et de recherches (935.993.2) | 1 | current text only, in force since 1 January 2007 |
| `935-993-3/` | Ordonnance sur les salons de coiffure (935.993.3) | 1 | current text only, in force since 1 January 1979 |
| `941-1/` | Ordonnance portant exécution de la législation fédérale sur la métrologie (941.1) | 1 | current text only, in force since 1 January 2023 |
| `942-1/` | Ordonnance concernant le contrôle des prix (942.1) | 1 | current text only, in force since 1 January 1979 |
| `943-11/` | Ordonnance d'exécution de la loi concernant l'exercice de la prostitution et le commerce de la pornographie (Ordonnance sur la prostitution, OProst) (943.11) | 1 | current text only, in force since 1 January 2026 |
| `943-21/` | Ordonnance sur le courtage et le commerce d’immeubles, ainsi que sur le courtage d’appartements et de chambres (943.21) | 1 | current text only, in force since 1 January 2007 |
| `943-516-1/` | Ordonnance portant interdiction du colportage d'armes-attrapes et d'armes-jouets (943.516.1) | 1 | current text only, in force since 1 January 2007 |
| `943-521/` | Ordonnance portant exécution de la loi fédérale sur les substances explosibles (943.521) | 1 | current text only, in force since 1 September 2005 |
| `952-1/` | Ordonnance portant exécution de la loi fédérale du 8 novembre 1934 sur les banques et les caisses d'épargne (952.1) | 1 | current text only, in force since 1 January 1979 |

## Source

The Recueil systématique de la législation jurassienne (RSJU), published by the Chancellerie d'Etat at <https://rsju.jura.ch/>, as the PDF of each act; its notes list every amendment with its popular vote, federal guarantee and entry into force.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**.
- Each act's single version is dated by the latest entry into force named in its notes (for laws and ordinances, also in its own entry-into-force article) on or before the retrieval day; it is the "oldest version available" and is credited to the publisher. Earlier wording is not held.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5, `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the headings of titles, chapters and sections. One paragraph or list item per line. Footnote markers are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the source document, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of each act's first commit is the publisher (RSJU), because the text is the current consolidation rather than the act as adopted, with an e-mail address that cannot exist. The committer is always Lexifina.

## Limits

This is not an official publication. The printed edition is binding (art. 5a of the loi sur les publications officielles, RSJU 170.51). The text is read from PDF; the notes are not included. Only the current wording is held. Only the acts listed above are included.
