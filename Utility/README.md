# POM Music Utility

## Purpose

##

## Content

* Platform
  * Mobile in major (1.3 billion at 2021)
  * PC in minor (340 million at 2021)
  * Tablet not target (67 million at 2021)

* Sale on 
  * steam
  * gog
  * google play store
  * apple store
  * etc.

## Data Structure

```mermaid

graph TD;
    begin --> aldaLang;
    aldaLang --> MXL;    
    
    begin --> MXL;
    
    MXL --> DataStructure;
   
    begin --> notation;
    notation --> MXL;

    DataStructure --> Tablature;
    DataStructure --> Staff;
    DataStructure --> Synthasia;
    DataStructure --> Icon;
    DataStructure --> Notation;

```