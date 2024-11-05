2022 Arizona General Election Precinct-Boundaries and Election Results

## RDH Date Retrieval
10/18/2024

## Sources
The RDH retrieved 2022 general election results from OpenElections(https://github.com/openelections). 

2022 boundaries are obtained either through direct communication, publicly available files or geo-referenced precinct maps in all Arizona counties.

Apache: map retrieved via contact, shapefile via GIS site (https://services8.arcgis.com/KyZIQDOsXnGaTxj2/ArcGIS/rest/services)
Cochise: file retrieved via county contact, also available online (https://gis-cochise.opendata.arcgis.com/datasets/8744f9f4249b479fbad9231da94b2cdc_0/explore?location=31.871362%2C-109.754373%2C8.56)
Coconino: file retrieved via county contact
Gila: https://www.gilacountyaz.gov/government/elections/maps.php
Graham: https://www.graham.az.gov/510/Precinct-District-Maps
Greenlee: shapefile via GIS site (https://www.arcgis.com/home/item.html?id=0aa260a952e3493a9cd8b61d3c39a539)
La Paz: shapefile via 2020 Census VTDs (https://redistrictingdatahub.org/dataset/arizona-vtd-boundaries-2020/)
Maricopa: https://elections.maricopa.gov/results-and-data/election-maps.html
Mohave: retrieved via county contact
Navajo: shapefile via GIS site (https://open-data-ncaz.hub.arcgis.com/datasets/d286fba6cc3b4b80b7f9aa17785a880a_0/explore)
Pima: via county contact
Pinal: via county contact
Santa Cruz: file retrieved via county contact
Yavapai: via county contact
Yuma: via County GIS, with updates to match map sourced from county website

## Notes on Field Names (adapted from VEST):
Columns reporting votes generally follow the pattern: The first character is G for a general election, P for a primary, S for a special, and R for a runoff.
Characters 2 and 3 are the year of the election.
Characters 4-6 represent the office type (see list below).
Character 7 represents the party of the candidate.
Characters 8-10 are the first three letters of the candidate's last name.

## Office Codes Used:
ATG - ATTORNEY GENERAL
COC - CORPORATION COMMISSIONER
GOV - GOVERNOR
SOS - SECRETARY OF STATE
SL - STATE HOUSE
STM - STATE MINE INSPECTOR
SU - STATE SENATE
STT - STATE TREASURER
CON - U.S. HOUSE
USS - U.S. SENATE

## Party Codes Used:
D - Democratic
R - Republican
L - Libertarian
I - Independent
O - Other / Write-In

## Fields:
Field Name                     Description
------------------------------ --------------------------------------------------
UNIQUE_ID                      Unique precinct name/identifier from SOS file
COUNTYFP                       Three digit county fips code
PCTNUM                         Unique number identifier for precinct from VEST file
RECINCTNA                      Non-unique precinct name/identifier from VEST file
COUNTY_NAM                     Name of county
CON_DIST                       US Representative district number
SL_DIST                        State Legislative district number
G22ATGDMAY                     KRIS MAYES (DEM), ATTORNEY GENERAL
G22ATGOWRI                     Write-in Candidate (Write-In), ATTORNEY GENERAL
G22ATGRHAM                     ABRAHAM HAMADEH (REP), ATTORNEY GENERAL
G22COCDKEN                     SANDRA KENNEDY (DEM), CORPORATION COMMISSIONER
G22COCDKUB                     LAUREN KUBY (DEM), CORPORATION COMMISSIONER
G22COCNGIB                     CHRISTINA GIBSON (No Party), CORPORATION COMMISSIONER
G22COCOWRI                     Write-in Candidate (Write-in), CORPORATION COMMISSIONER
G22COCRMYE                     NICK MYERS (REP), CORPORATION COMMISSIONER
G22COCRTHO                     KEVIN THOMPSON (REP), CORPORATION COMMISSIONER
G22GOVDHOB                     KATIE HOBBS (DEM), GOVERNOR
G22GOVOWRI                     Write-in Candidate (Write-in), GOVERNOR
G22GOVRLAK                     KARI LAKE (REP), GOVERNOR
G22SOSDFON                     ADRIAN FONTES (DEM), SECRETARY OF STATE
G22SOSOWRI                     Write-in Candidate (Write-in), SECRETARY OF STATE
G22SOSRFIN                     MARK FINCHEM (REP), SECRETARY OF STATE
G22STMOWRI                     Write-in Candidate (Write-in), STATE MINE INSPECTOR
G22STMRMAR                     PAUL MARSH (REP), STATE MINE INSPECTOR
G22TREDQUE                     MARTÍN QUEZADA (DEM), STATE TREASURER
G22TREOWRI                     Write-in Candidate (Write-in), STATE TREASURER
G22TRERYEE                     KIMBERLY YEE (REP), STATE TREASURER
G22USSDKEL                     MARK KELLY (DEM), U.S. SENATE
G22USSLVIC                     MARC J. VICTOR (LIB), U.S. SENATE
G22USSOWRI                     Write-in Candidate (Write-in), U.S. SENATE
G22USSRMAS                     BLAKE MASTERS (REP), U.S. SENATE
GCON01DHOD                     JEVIN D. HODGE (DEM), U.S. HOUSE - District No. 01
GCON01OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 01
GCON01RSCH                     DAVID SCHWEIKERT (REP), U.S. HOUSE - District No. 01
GCON02DOHA                     TOM OHALLERAN (DEM), U.S. HOUSE - District No. 02
GCON02OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 02
GCON02RCRA                     ELI CRANE (REP), U.S. HOUSE - District No. 02
GCON02WSAR                     CHRIS SARAPPO (Write-in), U.S. HOUSE - District No. 02
GCON03DGAL                     RUBEN GALLEGO (DEM), U.S. HOUSE - District No. 03
GCON03OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 03
GCON03RZIN                     JEFF NELSON ZINK (REP), U.S. HOUSE - District No. 03
GCON04DSTA                     GREG STANTON (DEM), U.S. HOUSE - District No. 04
GCON04OJON                     STEPHAN "STEVE" JONES (OTHER), U.S. HOUSE - District No. 04
GCON04OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 04
GCON04RCOO                     KELLY COOPER (REP), U.S. HOUSE - District No. 04
GCON05DRAM                     JAVIER GARCIA RAMOS (DEM), U.S. HOUSE - District No. 05
GCON05ISMI                     CLINT WILLIAM SMITH (IND), U.S. HOUSE - District No. 05
GCON05DBOR                     DEBRA JO "D-JO" BORDEN (DEM), U.S. HOUSE - District No. 05
GCON05OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 05
GCON05RBIG                     ANDY BIGGS (REP), U.S. HOUSE - District No. 05
GCON06DENG                     KIRSTEN ENGEL (DEM), U.S. HOUSE - District No. 06
GCON06OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 06
GCON06RCIS                     JUAN CISCOMANI (REP), U.S. HOUSE - District No. 06
GCON07DGRI                     RAUL GRIJALVA (DEM), U.S. HOUSE - District No. 07
GCON07OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 07
GCON07RPOZ                     LUIS POZZOLO (REP), U.S. HOUSE - District No. 07
GCON08DGUZ                     ALIXANDRIA GUZMAN (DEM), U.S. HOUSE - District No. 08
GCON08DSPR                     JEREMY SPREITZER (DEM), U.S. HOUSE - District No. 08
GCON08OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 08
GCON08RLES                     DEBBIE LESKO (REP), U.S. HOUSE - District No. 08
GCON09OWRI                     Write-in Candidate (Write-in), U.S. HOUSE - District No. 09
GCON09RGOS                     PAUL GOSAR (REP), U.S. HOUSE - District No. 09
GSL01DRAN                      CATHY RANSOM (DEM), STATE HOUSE - District No. 01
GSL01DSIN                      NEIL SINCLAIR (DEM), STATE HOUSE - District No. 01
GSL01OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 01
GSL01RBLI                      SELINA BLISS (REP), STATE HOUSE - District No. 01
GSL01RNGU                      QUANG NGUYEN (REP), STATE HOUSE - District No. 01
GSL02DSCH                      JUDY SCHWIEBERT (DEM), STATE HOUSE - District No. 02
GSL02OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 02
GSL02RLAM                      CHRISTIAN LAMAR (REP), STATE HOUSE - District No. 02
GSL02RWIL                      JUSTIN WILMETH (REP), STATE HOUSE - District No. 02
GSL03IFLA                      GEORGIA "GIA" FLANAGAN (IND), STATE HOUSE - District No. 03
GSL03ISKI                      JOHN SKIRBST (IND), STATE HOUSE - District No. 03
GSL03OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 03
GSL03RCHA                      JOSEPH CHAPLIK (REP), STATE HOUSE - District No. 03
GSL03RKOL                      ALEXANDER KOLODIN (REP), STATE HOUSE - District No. 03
GSL04DTER                      LAURA TERECH (DEM), STATE HOUSE - District No. 04
GSL04OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 04
GSL04RGRE                      MATT GRESS (REP), STATE HOUSE - District No. 04
GSL04RSYM                      MARIA SYMS (REP), STATE HOUSE - District No. 04
GSL05DLON                      JENNIFER LONGDON (DEM), STATE HOUSE - District No. 05
GSL05DSHA                      AMISH SHAH (DEM), STATE HOUSE - District No. 05
GSL05OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 05
GSL05RTRE                      JENNIFER "JENN" TREADWELL (REP), STATE HOUSE - District No. 05
GSL06DPES                      MAE PESHLAKAI (DEM), STATE HOUSE - District No. 06
GSL06DTSO                      MYRON TSOSIE (DEM), STATE HOUSE - District No. 06
GSL06OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 06
GSL07OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 07
GSL07RCOO                      DAVID COOK (REP), STATE HOUSE - District No. 07
GSL07RMAR                      DAVID MARSHALL SR. (REP), STATE HOUSE - District No. 07
GSL08DHER                      MELODY HERNANDEZ (DEM), STATE HOUSE - District No. 08
GSL08DSAL                      ATHENA SALMAN (DEM), STATE HOUSE - District No. 08
GSL08OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 08
GSL08RDAR                      CADEN DARROW (REP), STATE HOUSE - District No. 08
GSL08RLOU                      BILL LOUGHRIGE (REP), STATE HOUSE - District No. 08
GSL09DAUS                      LORENA AUSTIN (DEM), STATE HOUSE - District No. 09
GSL09DBLA                      SETH BLATTMAN (DEM), STATE HOUSE - District No. 09
GSL09OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 09
GSL09RMEN                      MARY ANN MENDOZA (REP), STATE HOUSE - District No. 09
GSL09RPEA                      KATHY PEARCE (REP), STATE HOUSE - District No. 09
GSL10DHUN                      HELEN HUNTER (DEM), STATE HOUSE - District No. 10
GSL10OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 10
GSL10RHEA                      JUSTIN HEAP (REP), STATE HOUSE - District No. 10
GSL10RPAR                      BARBARA PARKER (REP), STATE HOUSE - District No. 10
GSL11DQUI                      MARCELINO QUINONEZ (DEM), STATE HOUSE - District No. 11
GSL11DSAN                      OSCAR DE LOS SANTOS (DEM), STATE HOUSE - District No. 11
GSL11OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 11
GSL11RPEN                      TATIANA PENA (REP), STATE HOUSE - District No. 11
GSL12DCON                      PATRICIA "PATTY" CONTRERAS (DEM), STATE HOUSE - District No. 12
GSL12DTRA                      ANASTASIA "STACEY" TRAVERS (DEM), STATE HOUSE - District No. 12
GSL12OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 12
GSL12RCHA                      JAMES "JIM" CHASTON (REP), STATE HOUSE - District No. 12
GSL12RROE                      TERRY ROE (REP), STATE HOUSE - District No. 12
GSL13DPAW                      JENNIFER PAWLIK (DEM), STATE HOUSE - District No. 13
GSL13OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 13
GSL13RHAR                      LIZ HARRIS (REP), STATE HOUSE - District No. 13
GSL13RWIL                      JULIE WILLOUGHBY (REP), STATE HOUSE - District No. 13
GSL14DREE                      BRANDY REESE (DEM), STATE HOUSE - District No. 14
GSL14OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 14
GSL14RGRA                      TRAVIS GRANTHAM (REP), STATE HOUSE - District No. 14
GSL14RHEN                      LAURIN HENDRIX (REP), STATE HOUSE - District No. 14
GSL15OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 15
GSL15RCAR                      NEAL CARTER (REP), STATE HOUSE - District No. 15
GSL15RPAR                      JACQUELINE PARKER (REP), STATE HOUSE - District No. 15
GSL16DSEA                      KEITH SEAMAN (DEM), STATE HOUSE - District No. 16
GSL16OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 16
GSL16RHUD                      ROB HUDELSON (REP), STATE HOUSE - District No. 16
GSL16RMAR                      TERESA MARTINEZ (REP), STATE HOUSE - District No. 16
GSL17DALL                      DANA ALLMOND (DEM), STATE HOUSE - District No. 17
GSL17DRAD                      BRIAN RADFORD (DEM), STATE HOUSE - District No. 17
GSL17OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 17
GSL17RJON                      RACHEL JONES (REP), STATE HOUSE - District No. 17
GSL17RMCG                      CORY MCGARR (REP), STATE HOUSE - District No. 17
GSL18DGUT                      NANCY GUTIERREZ (DEM), STATE HOUSE - District No. 18
GSL18DMAT                      CHRIS MATHIS (DEM), STATE HOUSE - District No. 18
GSL18OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 18
GSL18REVA                      LINDA EVANS (REP), STATE HOUSE - District No. 18
GSL19DCLA                      SANDA CLARK (DEM), STATE HOUSE - District No. 19
GSL19OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 19
GSL19RDIA                      LUPE DIAZ (REP), STATE HOUSE - District No. 19
GSL19RGRI                      GAIL GRIFFIN (REP), STATE HOUSE - District No. 19
GSL20DCAN                      ANDRES CANO (DEM), STATE HOUSE - District No. 20
GSL20DHER                      ALMA HERNANDEZ (DEM), STATE HOUSE - District No. 20
GSL20OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 20
GSL21DHER                      CONSUELO HERNANDEZ (DEM), STATE HOUSE - District No. 21
GSL21DHAM                      STEPHANIE STAHL HAMILTON (DEM), STATE HOUSE - District No. 21
GSL21OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 21
GSL21RKEN                      DAMIEN KENNEDY (REP), STATE HOUSE - District No. 21
GSL21RMCE                      DEBORAH MCEWEN (REP), STATE HOUSE - District No. 21
GSL22DCON                      LUPE CHAVIRA CONTRERAS (DEM), STATE HOUSE - District No. 22
GSL22DSUN                      LEEZAH ELSA SUN (DEM), STATE HOUSE - District No. 22
GSL22RESC                      ROBERTO "ROBERT" ESCOBEDO (REP), STATE HOUSE - District No. 22
GSL22NGAR                      JEANNETTE GARCIA (Write-in), STATE HOUSE - District No. 22
GSL22OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 22
GSL23DLUG                      JESUS LUGO (DEM), STATE HOUSE - District No. 23
GSL23DSAN                      MARIANA SANDOVAL (DEM), STATE HOUSE - District No. 23
GSL23OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 23
GSL23RPEN                      MICHELE PENA (REP), STATE HOUSE - District No. 23
GSL24DHER                      LYDIA HERNANDEZ (DEM), STATE HOUSE - District No. 24
GSL24DORT                      ANALISE ORTIZ (DEM), STATE HOUSE - District No. 24
GSL24OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 24
GSL25OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 25
GSL25RCAR                      MICHAEL CARBONE (REP), STATE HOUSE - District No. 25
GSL25RDUN                      TIMOTHY "TIM" DUNN (REP), STATE HOUSE - District No. 25
GSL26DAGU                      CESAR AGUILAR (DEM), STATE HOUSE - District No. 26
GSL26DBRA                      FLAVIO BRAVO (DEM), STATE HOUSE - District No. 26
GSL26OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 26
GSL27DKIS                      DON KISSINGER (DEM), STATE HOUSE - District No. 27
GSL27OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 27
GSL27RPAY                      KEVIN PAYNE (REP), STATE HOUSE - District No. 27
GSL27RTOM                      BEN TOMA (REP), STATE HOUSE - District No. 27
GSL28DHOL                      STEPHANIE BLAIR HOLBROOK (DEM), STATE HOUSE - District No. 28
GSL28OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 28
GSL28RLIV                      DAVID LIVINGSTON (REP), STATE HOUSE - District No. 28
GSL28RPIN                      BEVERLY PINGERELLI (REP), STATE HOUSE - District No. 28
GSL29DPOD                      SCOTT PODEYN (DEM), STATE HOUSE - District No. 29
GSL29OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 29
GSL29RMON                      STEVE MONTENEGRO (REP), STATE HOUSE - District No. 29
GSL29RSMI                      AUSTIN SMITH (REP), STATE HOUSE - District No. 29
GSL30OWRI                      Write-in Candidate (Write-in), STATE HOUSE - District No. 30
GSL30RBIA                      LEO BIASIUCCI (REP), STATE HOUSE - District No. 30
GSL30RGIL                      JOHN GILLETTE (REP), STATE HOUSE - District No. 30
GSU01DFOG                      MIKE FOGEL (DEM), STATE SENATE - District No. 01
GSU01OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 01
GSU01RBEN                      KEN BENNETT (REP), STATE SENATE - District No. 01
GSU02DCAS                      JEANNE CASTEEN (DEM), STATE SENATE - District No. 02
GSU02OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 02
GSU02RKAI                      STEVE KAISER (REP), STATE SENATE - District No. 02
GSU03DDUG                      THOMAS DUGGER (DEM), STATE SENATE - District No. 03
GSU03OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 03
GSU03RKAV                      JOHN KAVANAGH (REP), STATE SENATE - District No. 03
GSU04DMAR                      CHRISTINE MARSH (DEM), STATE SENATE - District No. 04
GSU04OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 04
GSU04RBAR                      NANCY BARTO (REP), STATE SENATE - District No. 04
GSU05DALS                      LELA ALSTON (DEM), STATE SENATE - District No. 05
GSU05OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 05
GSU05RSIL                      JEFF SILVEY (REP), STATE SENATE - District No. 05
GSU06DHAT                      THERESA HATATHLIE (DEM), STATE SENATE - District No. 06
GSU06OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 06
GSU07DNIT                      KYLE NITSCHKE (DEM), STATE SENATE - District No. 07
GSU07OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 07
GSU07RROG                      WENDY ROGERS (REP), STATE SENATE - District No. 07
GSU08DMEN                      JUAN MENDEZ (DEM), STATE SENATE - District No. 08
GSU08OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 08
GSU08RHOL                      ROXANA HOLZAPFEL (REP), STATE SENATE - District No. 08
GSU09DBUR                      EVA BURCH (DEM), STATE SENATE - District No. 09
GSU09OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 09
GSU09RSCA                      ROBERT SCANTLEBURY (REP), STATE SENATE - District No. 09
GSU10IFIE                      NICK FIERRO (IND), STATE SENATE - District No. 10
GSU10OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 10
GSU10RFAR                      DAVID CHRISTIAN FARNSWORTH (REP), STATE SENATE - District No. 10
GSU11DMIR                      CATHERINE MIRANDA (DEM), STATE SENATE - District No. 11
GSU11OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 11
GSU11RBRA                      MARYN M. BRANNIES (REP), STATE SENATE - District No. 11
GSU12DEPS                      DENISE "MITZI" EPSTEIN (DEM), STATE SENATE - District No. 12
GSU12OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 12
GSU12RRIC                      DAVID WAYNE RICHARDSON (REP), STATE SENATE - District No. 12
GSU13DHAN                      CYNTHIA "CINDY" HANS (DEM), STATE SENATE - District No. 13
GSU13OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 13
GSU13RMES                      J.D. MESNARD (REP), STATE SENATE - District No. 13
GSU14DCLA                      KRISTIN CLARK (DEM), STATE SENATE - District No. 14
GSU14OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 14
GSU14RPET                      WARREN PETERSEN (REP), STATE SENATE - District No. 14
GSU15DSMI                      ALAN SMITH (DEM), STATE SENATE - District No. 15
GSU15OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 15
GSU15RHOF                      JAKE HOFFMAN (REP), STATE SENATE - District No. 15
GSU16DKER                      TAYLOR KERBY (DEM), STATE SENATE - District No. 16
GSU16OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 16
GSU16RSHO                      THOMAS SHOPE (REP), STATE SENATE - District No. 16
GSU17DNIC                      MIKE NICKERSON (DEM), STATE SENATE - District No. 17
GSU17OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 17
GSU17RWAD                      JUSTINE WADSACK (REP), STATE SENATE - District No. 17
GSU18DSUN                      PRIYA SUNDARESHAN (DEM), STATE SENATE - District No. 18
GSU18OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 18
GSU18RCAI                      STAN CAINE (REP), STATE SENATE - District No. 18
GSU19OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 19
GSU19RGOW                      DAVID GOWAN (REP), STATE SENATE - District No. 19
GSU20DGON                      SALLY ANN GONZALES (DEM), STATE SENATE - District No. 20
GSU20OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 20
GSU21DGAB                      ROSANNA GABALDÓN (DEM), STATE SENATE - District No. 21
GSU21OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 21
GSU21RCLE                      JIM CLEVELAND (REP), STATE SENATE - District No. 21
GSU22RBEN                      RYAN BENSON (REP), STATE SENATE - District No. 22
GSU22DCHA                      STEVE CHAPMAN (DEM), STATE SENATE - District No. 22
GSU22DCRA                      JUSTIN CRAWFORD (DEM), STATE SENATE - District No. 22
GSU22DDIA                      EVA DIAZ (DEM), STATE SENATE - District No. 22
GSU22IDIE                      STEPHEN EUGENE DIEHL (IND), STATE SENATE - District No. 22
GSU22RNOR                      JEFFREY "JEFF" NORWOOD (REP), STATE SENATE - District No. 22
GSU22DRAY                      KENYA RAYMOND (DEM), STATE SENATE - District No. 22
GSU22RROB                      STEVE ROBINSON (REP), STATE SENATE - District No. 22
GSU22RSAN                      MARSHALL JOSEPH SANCHEZ (REP), STATE SENATE - District No. 22
GSU22DVAL                      PAUL VALACH (DEM), STATE SENATE - District No. 22
GSU22RWEE                      RICHARD SEAN "DICK WEED (REP), STATE SENATE - District No. 22
GSU22OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 22
GSU23DFER                      BRIAN FERNANDEZ (DEM), STATE SENATE - District No. 23
GSU23OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 23
GSU23RSNY                      GARY GARCIA SNYDER (REP), STATE SENATE - District No. 23
GSU24DHER                      ANNA HERNANDEZ (DEM), STATE SENATE - District No. 24
GSU24OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 24
GSU25OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 25
GSU25RKER                      SINE KERR (REP), STATE SENATE - District No. 25
GSU26DTER                      RAQUEL TERÁN (DEM), STATE SENATE - District No. 26
GSU26OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 26
GSU27DBAR                      BRITTANI BARRAZA (DEM), STATE SENATE - District No. 27
GSU27OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 27
GSU27RKER                      ANTHONY KERN (REP), STATE SENATE - District No. 27
GSU28DSAN                      DAVID SANDOVAL (DEM), STATE SENATE - District No. 28
GSU28OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 28
GSU28RCAR                      FRANK CARROLL (REP), STATE SENATE - District No. 28
GSU29DRAY                      DAVID RAYMER (DEM), STATE SENATE - District No. 29
GSU29OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 29
GSU29RSHA                      JANAE SHAMP (REP), STATE SENATE - District No. 29
GSU30OWRI                      Write-in Candidate (Write-in), STATE SENATE - District No. 30
GSU30RBOR                      SONNY BORRELLI (REP), STATE SENATE - District No. 30
geometry                       geometry
  
## Notes  
Precinct boundaries were checked against the individual precinct assigned from a geocoded Arizona voter file pulled by L2 in April of 2023.

For non write-in candidates, vote totals were checked against official state totals at both the state and county levels. 
  
Please contact info@redistrictingdatahub.org for more information.