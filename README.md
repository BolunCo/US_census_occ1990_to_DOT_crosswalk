# US Census Occupation to DOT crosswalk
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

This repository contains:
1. A brief introduction of .
2. An illustration of known crosswalks.
3. Links to each crosswalk **(Shall we put them here?)**. 

## Table of Contents
- [Background](#background)
- [Crosswalk Overview](#crosswalk-overview)
 
## Background
DoT([Dictionary of Occupational Titles](https://en.wikipedia.org/wiki/Dictionary_of_Occupational_Titles)) provides useful information about each occupation such as the definition and characteristics.  

## Crosswalk Overview
The graph below shows the original source and quality of each crosswalk.

<img src="/src/crosswalk.png" alt="Crosswalk Overview"/>

* WidCenter crosswalks can be accessed from [WidCenter-Legacy Crosswalks](https://www.widcenter.org/document/legacy-crosswalks/).

* IPUMS/BLS crosswalks can be found in [IPUMS-Crosswalks](https://usa.ipums.org/usa/volii/occ_ind.shtml). 

  >The translation of occupation codes into the 1950 classification is particularly problematic for 1980 onward. The Census Bureau significantly reorganized the occupational classification scheme in 1980 and again in 2000. Comparisons across the post-1980 period and with earlier years will be more distorted than similar comparisons across other decades. Researchers focusing on these samples should consider using OCC1990. [(IPUMS)](https://usa.ipums.org/usa-action/variables/OCC1950#comparability_section)


* DoT crosswalks were obtained mainly from digitized sources. We performed OCR either by ourselves or using existing work (DoT 3rd-4th, 4th-4th rev are based on [Jeffrey Lin's work](https://github.com/jeffrlin/new-work)).
 ### A simple m:n example
 Depending on the situation, m:n cases could be a problem. Going from 2nd edition DoT to the 4th edition or census OCC1990 is difficult because both 2nd-3rd and 3rd(at 6-digit level)-4th are m:n. 
 
 <img src="/src/m_n_problem.png" alt="mn_problem"/>
 
 
 
 



