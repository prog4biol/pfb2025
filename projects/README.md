# PFB 2025 Group Projects

## Immune Escape

### Repo
[ImmuneEscape](https://github.com/cmdcolin/ImmuneEscape)

### Participants
- Emma Saart
- Walter Orellana
- Anastasia Rusnak 

### TA
Colin Diesh

### Summary
An interactive 2-player game, implemented using PyGame, where you get to make the immune system battle against pathogens. Users can choose different types of pathogens, select adaptive or innate immunity, and choose attack and defense maneuvers. The game uses high-quality drawings from resources like NIH BioArt (https://bioart.niaid.nih.gov/) and other freely licensed art. The configuration file is used to configure the different pathogens and defense capabilities, providing data-driven game behaviors


  
----  


## OptimusPrymer - Primer Design

### Repo
[OptimusPrymer](https://github.com/josiahmurra/cshl_primer_design)

### Participants
- Josiah Murray
- Huishi Toh

### TA
Jessen Bredeson

### Summary


  
----  

## TranscriptHomies

### Repo
[TranscriptHomies](https://github.com/rikellermeyer/TranscriptHomies)

### Participants
- Grace Beggs
- Caroline Harrer
- HeaJin Hong
- Tess Kelly
- Zilin Xianyu

### TAs
Bekah Kim, Riley Kellermeyer
  
### Summary
Build a tool that identifies and visualizes gene - gene expression correlations between two biological groups (e.g., diseased vs. normal samples).
  
----  

## Mbryg

### Repo
[mbryg](https://github.com/egabal/mbryg)

### Participants
- Esraa Gabal
- Julie Fazekas

### TA
Ken Youen-Clark
  
### Summary

**Description of problem:** The Virtual Metabolic Human (VMH) database is a comprehensive repository integrating human metabolic reactions, enzymes, and metabolites derived from the Recon3D genome-scale metabolic atlas. While VMH provides detailed biochemical and cross-database information (e.g., KEGG, ChEBI, PubChem, HMDB), accessing this information typically requires manual searching through the website interface. Although the VMH API allows programmatic access, it currently supports retrieving metabolite information only one entry at a time, making large-scale data extraction inefficient. This project aims to develop a Python-based tool to automatically iterate through the VMH database and retrieve all metabolites along with their associated external database links, creating a unified cross-referenced metabolite map. 

**Proposed programming solution:** 

**Overview of features/stages/components to be implemented:** The script will connect to the VMH database and automatically iterate through all metabolite entries. For each metabolite, it will extract key information and all associated external database links (e.g., KEGG, ChEBI, PubChem, HMDB). The final step will compile all data into a structured file summarizing every metabolite and its cross-references.

**How the proposed code solves the problem:** It eliminates the need for manual retrieval of metabolite information from the VMH website. By collecting all external database identifiers, it creates a unified dataset that can be used directly for metabolic modeling.

**Desired inputs:** The script directly queries the publicly available VMH to retrieve metabolite information.

**Desired outputs**: The program will generate a file containing all metabolite entries and their cross-database identifiers. Moreover, it will display summary statistics and visualizing database coverage.

**Potential challenges:** The main challenge lies in handling the sensitivity of metabolite names and IDs, which often vary across databases and may include inconsistent formats or capitalization. This could lead to mismatches during automated extraction and mapping. Additionally, accessing extended information from VMH and related databases may be difficult, as certain details are embedded within interactive web elements or tabs that redirect to external links rather than being available through direct API calls. Designing the script to navigate or bypass such interactive structures while maintaining accuracy and completeness will be a critical implementation challenge 

----  

## [Peak Fitness]

### Repo
[peak-fitness](https://github.com/jklynch/peak-fitness)

### Participants
- Jane Liu
- Ananya Nidamangala Srinivasa
- Vivian Li
- Giancarlo Gonzalez

### TA
Joshua Lynch
  
### Summary
You have five guesses to find the peak of a protein fitness landscape.



----  

## [Project Name]

### Repo
[Repo Name](path)

### Participants
- [Participant]
- [Participant]
- [Participant]
- [Participant]

### TA
Eric Ross
  
### Summary

