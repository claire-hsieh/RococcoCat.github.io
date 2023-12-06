---
title: "MGV Project"
date: 2023-11-27T23:20:10-07:00
hero: /images/posts/Screenshot 2023-12-05 170231.png
description: Project Analyzing Connector Protein from Viral Database
theme: Toha
menu:
  sidebar:
    name: MGV
    identifier: MGV
    weight: 50
---

# Analyzing Connector Protein from MGV Database 
- The MGV database from the paper, [Metagenomic compendium of 189,680 DNA viruses from the human gut microbiome](https://www.nature.com/articles/s41564-021-00928-6) contains 189,000 viral sequences sampled from the bacteriophages residing in the human gut. Many of these viruses were previously unknown and the goal of this project is to create a general structure of the connector protein by obtaining and modeling many connector proteins whose sequences are available in the database. 

## Obtaining the Sequences
- Because connector proteins are not well conserved, sequence similarity will not be very high. Therefore, we will BLAST the connector protein domains against the database (rather than entire sequences) to find the connector protein. 

## Modeling
- We will be using AlphaFold(monomer) and SWISS-MODEL(quaternary structure) to model the connector protein.


{{< embed-pdf url="/images/posts/MGV_Progress_11-17.pdf" hidePaginator="true" >}}
