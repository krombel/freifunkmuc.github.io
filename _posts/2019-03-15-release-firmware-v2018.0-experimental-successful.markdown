---
layout: post
title:  "Firmware-Release v2018.0 - Phase 2 erfolgreich"
date:   2019-03-15 7:00:00
categories: freifunkmuc
---
Der Rollout der aktuellsten stable Firmware v2018.0 lief wie (fast) wie erwartet.
Wir wollten ja, wie [angekündigt](freifunkmuc/2019/03/01/release-firmware-v2018.0-experimental/) wollten wir am 12.03.2019 die aktuelle stable auf die Konten ausspielen wollten, die ihren Auto-Updater auf "experimental" in ihrem Freifunk-Knoten eingestellt haben.

Dabei hatten wir nicht daran gedacht, dass in dem manifest, dass von den Knoten benutzt wird um den Knoten zu aktualisieren drinsteht für welchen Branch das Update ist.
Nun hatten wir in dem Manifest "stable" drinstehen. Eine Änderung dieses Wertes sorgte dafür, dass die Signatur des Manifests nicht mehr passte. Schon schlimm wenn Software so arbeitet wie gewünscht... :P

Wir mussten also neue Signaturen anfragen und einpflegen.
Diese konnten wir gestern dann endlich scharf schalten.
Und siehe da: Alle experimental-Knoten haben die neue Firmware geholt und sich aktualisiert und sind ohne Probleme wieder online gekommen!

Für uns war das Update also ein voller Erfolg!
Wir richten nun also alles ein um v2018.0 auf stable auszurollen und können uns auf die weitere Entwicklung von v2019.0 konzentrieren.