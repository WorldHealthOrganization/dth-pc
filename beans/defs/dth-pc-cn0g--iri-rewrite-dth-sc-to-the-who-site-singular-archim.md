---
# dth-pc-cn0g
$schema: bean/1.0.0
title: 'IRI rewrite: dth-sc to the WHO site, singular ArchiMate links (CS-001, mechanical)'
status: completed
type: task
priority: normal
created_at: 2026-11-18T19:17:16Z
updated_at: 2026-11-18T20:53:07Z
---

Change set CS-001 for litlfred/dth-pc: a mechanical-IRI change set. Every https://litlfred.github.io/dth-sc/ IRI becomes https://worldhealthorganization.github.io/dth-sc/ (dth-sc's iriBase moved in litlfred/dth-sc#58, merged as 19d5c2bd), and the plural ArchiMate links archimate/<v>/(elements|views)/<id>.jsonld become the singular node IRIs archimate/<v>/(element|view)/<id> (smart-ra here). URLs only; block JSON-LD regenerated; dth-sc pin moved to 19d5c2bd. Owner-approved 2026-11-18 (IRI option 2A). Mirrors litlfred/dth-sc CS-003 (work item dth-sc-w7ho, workflow contentchangereview--dth-sc-58-iribase-to-who-site-and-singular-archimate-links-c on cat/dth-sc/beans).
