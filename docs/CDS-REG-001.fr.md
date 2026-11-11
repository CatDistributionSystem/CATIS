# CDS-REG-001

## Avis du Système et communications administratives

**Identifiant du document :** CDS-REG-001  
**Révision :** 7e65.4  
**Statut :** Approuvé  
**Langue de référence :** Anglais  
**Langue de la présente édition :** Français  
**Objet :** Classification, identification, accusé de réception et tenue des registres des avis du Système

---

## 1. Objet

Le présent document établit la terminologie et les conventions générales de tenue des registres applicables aux avis émis dans le cadre administratif du Cat Distribution System (CDS).

Il fournit un cadre cohérent pour identifier, classer, faire accuser réception et conserver les avis du Système. Il ne décrit pas les mécanismes internes du CDS et ne définit pas la manière dont le Système déclenche, détermine ou exécute un quelconque processus.

## 2. Champ d’application

Le présent document s’applique aux dossiers administratifs désignés comme avis du Système ainsi qu’aux références à ces avis dans CATIS.

Un avis du Système est une communication enregistrée destinée à transmettre une information, une instruction administrative ou un sujet nécessitant l’attention de ses destinataires désignés.

L’existence d’un avis n’explique pas, à elle seule, les circonstances qui l’ont motivé et ne révèle pas les processus sous-jacents du CDS.

## 3. Classification des avis

Chaque avis reçoit une classification principale :

- **Informatif** — consigne une information à titre de connaissance ou de référence ; aucune réponse n’est nécessairement requise.
- **Opérationnel** — communique un sujet pertinent pour la continuité ou la coordination d’une activité administrative établie.
- **Administratif** — consigne une instruction administrative, une clarification ou une modification d’une pratique documentée.

La classification décrit la finalité de l’avis. Elle n’indique ni son importance, ni son urgence, ni le résultat attendu.

## 4. Priorité

Le cas échéant, un avis peut également recevoir un niveau de priorité :

- **Courante** — pour la diffusion et la consultation ordinaires.
- **Renforcée** — nécessite une attention particulière de la part des destinataires désignés.
- **Prioritaire** — nécessite une attention dans les délais indiqués par l’avis lui-même.

La priorité est indépendante de la classification. Un avis informatif, opérationnel ou administratif peut relever de n’importe quel niveau de priorité.

## 5. Identification

Les avis du Système reçoivent des identifiants uniques selon le format suivant :

`CDS-NOT-[CSR]-[SEQUENCE]`

Exemple : `CDS-NOT-7e65-007`.

L’identifiant comprend :

1. la désignation `CDS-NOT` ;
2. la période CATIS System Reference (CSR) applicable ;
3. un numéro séquentiel distinguant l’avis au sein de cette période.

Les identifiants constituent des références permanentes. L’identifiant d’un avis ne peut pas être réattribué à un autre avis.

## 6. Statut de l’avis

Le statut décrit la position de l’avis dans le registre :

- **Émis** — officiellement inscrit au registre des avis.
- **Actif** — demeure applicable à des fins de référence ou d’attention.
- **Remplacé** — remplacé par un avis ou un dossier administratif ultérieur.
- **Archivé** — conservé à titre de référence historique et n’est plus maintenu comme avis actif.

Un changement de statut ne supprime pas l’avis et ne modifie pas son identifiant. Lorsqu’un avis est remplacé, le dossier devrait comporter un renvoi vers le document qui le remplace, le cas échéant.

## 7. Accusé de réception

L’accusé de réception est consigné séparément du statut de l’avis. Lorsqu’un accusé de réception est requis, les termes suivants peuvent être utilisés :

- **En attente** — aucun accusé de réception n’a encore été consigné.
- **Réception confirmée** — le ou les destinataires désignés ont confirmé la réception.
- **Consigné** — l’accusé de réception a été inscrit dans le dossier administratif.

L’accusé de réception confirme uniquement la réception. Il ne signifie pas nécessairement accord, approbation ou achèvement d’une action décrite dans l’avis.

Lorsqu’aucun accusé de réception n’est requis, le dossier peut indiquer **Non requis**.

## 8. Diffusion et destinataires

Lorsque cela est pertinent pour le dossier, l’avis devrait préciser le groupe de destinataires visé ou son périmètre administratif.

Les informations relatives à la diffusion doivent se limiter à ce qui est nécessaire à la finalité administrative de l’avis. Les dossiers accessibles au public ne doivent pas révéler de données personnelles ni de détails susceptibles de compromettre la vie privée des personnes concernées.

## 9. Tenue des registres

Le dossier de l’avis devrait conserver, selon le cas :

- l’identifiant unique de l’avis ;
- sa classification et sa priorité ;
- son statut ;
- la référence CSR ;
- son objet et une description concise ;
- le groupe de destinataires visé ;
- le statut de l’accusé de réception, le cas échéant ;
- les références aux dossiers connexes ou aux documents qui remplacent l’avis.

Les corrections et changements de statut doivent être consignés sans masquer l’identité initiale de l’avis.

## 10. Confidentialité et divulgation

Les avis du Système sont des dossiers administratifs. Leur existence ou leur publication n’autorise pas la divulgation d’informations confidentielles, de données personnelles ou des mécanismes internes non divulgués du CDS.

Un résumé public, lorsqu’il est publié, constitue une publication distincte et doit être préparé à cette fin. Il ne doit pas être considéré comme un substitut au dossier administratif sous-jacent.

## 11. Relation avec CATIS

CATIS peut être utilisé pour présenter, consulter et tenir les dossiers des avis du Système.

Le présent document définit uniquement des conventions de tenue des registres. Il n’établit aucune fonction logicielle particulière, interface, voie de notification, mesure de contrôle d’accès ou capacité technique spécifique de CATIS.

## 12. Dispositions finales

Le présent document fait partie du cadre documentaire du CDS. Il doit être interprété de manière cohérente avec la description fondamentale du CDS, le cadre terminologique et la documentation CATIS applicable.

Aucune disposition du présent document ne doit être interprétée comme une explication de la nature ou du fonctionnement interne du Cat Distribution System.
