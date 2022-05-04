# US Census Occupation to DOT crosswalk

Linking [DoT](https://en.wikipedia.org/wiki/Dictionary_of_Occupational_Titles) occupations to census occupations.

**DoT Handbook**:

1st Edition: 1939?-1949

2nd Edition: 1949 -1963

3rd Edition: 1965 -1974

4th Edition: 1976 -1990

4th Rev    : 1991 -1998

Since 2000, the hanbook uses O\*Net definition instead of DoT definition

**Census occupation**:

The occupation classification is different in each census. OCC1950 and OCC1990 are the two consistent category systems that [Census Bureau](https://usa.ipums.org/usa/resources/chapter4/OCCBLS_paper.pdf) created for long-run analysis.

## Crosswalk Overview
The graph below shows the original source and quality of each known crosswalk.

<img src="/src/crosswalk.png" alt="Crosswalk Overview"/>

* WidCenter crosswalks can be accessed from [WidCenter-Legacy Crosswalks](https://www.widcenter.org/document/legacy-crosswalks/).

* IPUMS/BLS crosswalks can be found in [IPUMS-Crosswalks](https://usa.ipums.org/usa/volii/occ_ind.shtml). 

  >The translation of occupation codes into the 1950 classification is particularly problematic for 1980 onward. The Census Bureau significantly reorganized the occupational classification scheme in 1980 and again in 2000. Comparisons across the post-1980 period and with earlier years will be more distorted than similar comparisons across other decades. Researchers focusing on these samples should consider using OCC1990. [(IPUMS)](https://usa.ipums.org/usa-action/variables/OCC1950#comparability_section)


* DoT crosswalks were obtained mainly from digitized sources. We performed OCR either by ourselves or using existing work (DoT 3rd-4th, 4th-4th rev are based on [Jeffrey Lin's work](https://github.com/jeffrlin/new-work)).
 ### A simple m:n example
 Going from 2nd edition DoT to the 4th edition or census OCC1990 could be a problem because both 2nd-3rd and 3rd(at 6-digit level)-4th are m:n (there is not a unique identifier in both sides of the merge). 
 
 <img src="/src/m_n_problem.png" alt="mn_problem"/>
 
 
 
 



