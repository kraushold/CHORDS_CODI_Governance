# CHORDS_CODI_Governance


##### Table of Contents
[ CHORDS_CODI_Governance ](#codi-chords)

I. [ Introduction and Relationship to CODI Implementation Guides ](#intro)  
A. [ Childhood Obesity Data Initiative ](#codi)  
B. [ CODI@CHORDS Implementation Working Group ](#iwg)  

II. [ Local Specifications for CODI@CHORDS ](#localspecs)  
 A. [ CODI@CHORDS Governance ](#gov)  
 B. [ Roles and Responsibilities ](#roles)  
 
<a name="codi-chords"></a>
# CHORDS_CODI_Governance
This repository is a place to share governance information related to the CHORDS implementation of the Childhood Obesity Data Initiative (CODI). The local implementation of CODI functionalities into the CHORDS network infractructure is referred to in this document as CODI@CHORDS. CODI functionalities include: 
1. Integration of community-collected data into a distributed data network (DDN) of electronic health records (EHR)
2. Privacy-preserving record linkage (PPRL)
3. Capacity to construct cross-system and cross-sector longitudinal datasets

The repository was developed and is maintained by Emily Kraus in partnership with CODI@CHORDS stakeholders.

<a name="intro"></a>
## I. Introduction and Relationship to CODI Implementation Guides
<a name="codi"></a>
### A. Childhood Obesity Data Initiative

As part of the Centers for Disease Control and Prevention’s (CDC) efforts to promote health, prevent disease, injury, and disability, and prepare for emerging health threats, the Division of Nutrition, Physical Activity, and Obesity; and Center for Surveillance, Epidemiology, and Laboratory Services partnered with the CMS Alliance to Modernize Healthcare federally funded research and development center (Health FFRDC), and Colorado-based stakeholders to implement the Childhood Obesity Data Initiative (CODI) in a distributed data network, the Colorado Health Observation Regional Data Service (CHORDS). CODI@CHORDS will expand the ability of the CHORDS network to capture, standardize, integrate, and query existing patient-level electronic health record (EHR) and community data via a common data model. Lessons learned from the pilot implementation will inform how other networks can implement the solution into their local environments.  CODI augments the PCORnet Common Data Model ([CDM](PCORnet-Common-Data-Model-v51-2019_09_12.pdf)) and the CHORDS data model ([CHORDS VDW](CHORDS_VDW_V3.3_DataModelManual.docx)) with information about weight-related interventions, community-based programs and social factors.

[A complementary Github](https://github.com/k-scott/CODI-CHORDS) serves as the main CODI implementation repository and describes how CODI@CHORDS data partners — those organizations that participate in CODI@CHORDS —should interpret the materials developed by MITRE for implementing CODI. It assumes that the reader has access to the CODI Implementation Guide, that pertains to CODI data tables, and the CODI PPRL Implementation Guide, that pertains to privacy preserving record linkage (PPRL).  This also assumes that the reader has access to [MITRE's GitHub repository](https://github.com/mitre/data-owner-tools) containing data owner tools. 

<a name="iwg"></a>
### B. CODI@CHORDS Implementation Working Group

Beginning on October 16, 2019, an Implementation Work Group (IWG) comprised of stakeholders involved in the CODI@CHORDS implementation held bi-weekly meetings to discuss issues related to the pilot implementation.  The members included:

**TABLE: CODI@CHORDS IWG Members**
| Organization | Name |
| --- | --- |
| Centers for Disease Control and Prevention | Raymond King |
| Centers for Disease Control and Prevention | Nedra Garrett |
| Centers for Disease Control and Prevention | Emily Kraus |
| Children's Hospital Colorado | Sara Deakyne Davies |
| Children's Hospital Colorado | Kevin Matthews |
| Children's Hospital Colorado | Marisa Payan |
| Colorado Health Institute | Paul Presken |
| Denver Health (Denver Public Health) | Ken Scott (IWG lead) |
| Denver Health (Denver Public Health) | Art Davidson |
| Denver Health (Denver Public Health) | Pradeep Podila |
| Denver Health (Business Intelligence & Data Warehouse) | Kelly Schlapkol |
| Denver Health (Business Intelligence & Data Warehouse) | Chris Brundage |
| Denver Health (Denver Public Health) | Emily Bacon |
| Girls on the Run of the Rockies | Lisa Johnson |
| Girls on the Run of the Rockies | Katie Redfield |
| Hunger Free Colorado | Anugna Pentaparthy |
| Hunger Free Colorado | Brett Reeder |
| Hunger Free Colorado | Machayla Fortin |
| Kaiser Permanente Colorado (Institute for Health Research ) | Mark Gray |
| MITRE | Dawn Heisey-Grove |
| MITRE | Peter Mork |
| MITRE | Andy Gregorowicz |
| MITRE | Jim Jellison | 
| Public Health Informatics Institute | Emily Kraus |
| Public Health Informatics Institute | Lura Daussat |
| Public Health Informatics Institute | Ashley Nash |
| University of Colorado (ACCORDS) | Rachel Zucker |

Slides and other related implementation materials are posted in the IWG folder on [Basecamp](https://3.basecamp.com/4113007/projects/13007091).

<a name="localspecs"></a>
## II. Local Specifications for CODI@CHORDS
<a name="gov"></a>
### A. CODI@CHORDS Governance
Because the CODI requirements differed significantly from the CHORDS governance processes, a complementary approach to data governance was required. A business process analysis was conducted to gather requirements for the CODI technical solution and governance infrastructure. The [final report](CODI Business Process Analysis Report_FINAL.pdf) defining and summarizing those requirements is availble in this repository.

Through a structured process the CODI implementing sites developed the [CODI Master Sharing and Use Agreement (MSUA)](CODI_CHORDS_MSUA.pdf) that defines CODI data governenace, including how CODI relates to and depends on existing CHORDS governance infrastructure. The CODI MSUA is based largely on the [Master Reliance Agreement](MSUA_REACHNET_Template.pdf) used by REACHnet to support data exchange. 

To support community partner participation, [Memoranda of Understanding](CODI_MOU_template.pdf) were created with community partners to define a technical partner would facilitate project participation by completeing required technical tasks that were beyond the technical capacity of each organization. 

<a name="roles"></a>
### B. Roles and Responsibilities

**FIGURE: CODI@CHORDS Implementers**
![CODI@CHORDS Implementers](codi-implementers.png)



