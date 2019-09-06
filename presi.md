---
title: Pointer Arithmetik
author: Yannik Hellmuth, Philipp Scott
theme: metropolis
---

# Gliederung
- Was sind Pointer?
- Arithmetische Optionen
- Anwendungsbeispiele

# Was sind Pointer?
- Feld welches Adresse zu anderem Feld enthält
- genutzt bei machinennahen Sprachen
- genutzt in beispielsweis Assembler und C

# Arithmethische Operationen

## zwischen Pointern
- Subtrahieren
- Addieren ist nicht erlaubt

## zwischen Pointer und Ganzzahl
- Subtrahieren
- Addieren

# Anwendungsbeispiele
- Rückgabe von Werten über Scope hinaus
- Strings
- Itteration durch Array

`` printf("%i", a[i]) <-> printf("%i", *(a+i))``

