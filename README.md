# README for qhodCMIFxquery

Example for creating CMIF from existing collection by means of XQuery. 

The CMIF schema is used for correspondence metadata, maintained at 
 <https://github.com/TEI-Correspondence-SIG/CMIF> 
in a subset of the <https://tei-c.org> Guidelines. The original purpose 
of CMIF is to exchange metadata e.g. for aggregation and search purposes 
such as <https://correspsearch.net>. 

- `getCMIF.xquery` has been quickly put together during the 2022 
TEI Conference <https://conferences.ncl.ac.uk/tei2022> Correspondence
SIG to extract correspAction elements and their origins from the *QhoD* 
project available at <http://qhod.net>. Some postprocessing 
may be necessary to achieve conformity with the schema. 

- `QhoDCMIF.xml` is the manually redacted result of applying the 
above XQuery to the letterlike material available through <https://qhod.net>
at the time (2022-09-14).

## Hints

<https://encoding-correspondence.bbaw.de> has resources on usage of CMIF 
and encoding correspondence in general. 

https://correspsearch.net/services/check-cmif.html?url=https://raw.githubusercontent.com/QHOD/qhodCMIFxquery/main/QhoDCMIF.xml they also provide a checking tool. 

https://github.com/csae8092/cmifun provides visualisations that may be helpful for checking data integrity.
