---
title: Pointer Arithmetik
author: Yannik Hellmuth, Philipp Skott
theme: metropolis
---

# Gliederung
- Was sind Pointer?
- Arithmetische Operationen
- Anwendungsbeispiele

# Was sind Pointer?
![Fig. 1](pointer.jpeg)
# Dereferenzierung
- Zugriff auf vom Pointer gezeigtes Objekt

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
- verkettete Listen

`` printf("%i", a[i]) <-> printf("%i", *(a+i))``

# Probleme
- buffer overflow
- segmentation fault
