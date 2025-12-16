---
layout: default
title: "Szybsze ładowanie Galerii w Power Apps"
date: 2023-10-27
---

Tutaj wpisz treść swojej porady. Możesz używać pogrubień, list itp.

### Problem
Galeria ładuje się wolno przy dużej ilości danych.

### Rozwiązanie
Użyj funkcji `ClearCollect` zamiast bezpośredniego źródła danych w Items.

```powerapps
ClearCollect(colLocalData, 'SharePoint List')
