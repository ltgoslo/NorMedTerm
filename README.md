# NorMedTerm

NorMedTerm is a large Norwegian lexical resource of medical entities mapped to semantic categories. The resource contains over 77,000 unique entries and merges terms from several medical databases. Most terms are mapped based on database information, some (ca. 14%) are automatically mapped based on heuristics, of which a smaller amount (ca. 1000 terms) were also manually evaluated and revised. 

This work is funded by the Norwegian Research Council, more specifically by the [BigMed](https://bigmed.no/) project.

## Format

The resource is distributed as a TAB-separated file, with the following columns:
- term
- semantic category of entity
- source ID (acronym of list / database)
- ICD code (if applicable)
- mapping method ('manual' or 'automatic')

The following 12 semantic categories are included:

|Category | Explanation|
|:--- | :---|
| ABBREV | abbreviations and acronyms |
| ANAT-LOC | anatomical locations |
| CONDITION	| diseases, findings, symptoms | 
| DISCIPLINE	| medical disciplines / areas |
| MICROORGANISM | bacteria, viruses etc. |
| ORGANIZATION	| institutions etc. |
| OTHER	| category other than the ones specified |
| PERSON | types of practitioner or patient |
| PHYSIOLOGY | physiological functions |
| PROCEDURE | medical procedure and treatment types |
| SUBSTANCE | medicines and other substances |
| TOOL | medical instruments and tools |

Terms from the following sources were included (available from the [Norwegian Directorate for e-health](https://ehelse.no/kodeverk) unless otherwise indicated):

|Source ID | Source name|
| :--- | :--- |
| MO | Medisinsk ordbok 'Medical Dictionary' by [Kunnskapsforlaget](https://kunnskapsforlaget.no/)
| ALOC | List of anatomical locations
| FAM-HIST | [NorSynthClinical](https://github.com/ltgoslo/NorSynthClinical), a Norwegian synthetic corpus of clinical texts
| FEST | Forskrivnings- og ekspedisjonsstøtte 'Prescribing and dispensing support' by [Legemiddelverket](https://legemiddelverket.no/andre-temaer/fest)
| ICD-10 | International Statistical Classification of Diseases
| ICPC-2 | International Classification of Primary Care
| LABV | Laboratoriekodeverket 'List of laboratory codes'
| PROC | Prosedyrekodeverken 'Procedure Coding Schemes'

## Citing

Please refer to the following article when using this resource:

Ildikó Pilán, Pål H. Brekke, Lilja Øvrelid. Building a Norwegian Lexical Resource for Medical Entity Recognition. To appear in *Proceedings of the 2nd workshop on Multilingual Biomedical Text Processing* (MultilingualBIO). [PDF](https://www.aclweb.org/anthology/2020.multilingualbio-1.2.pdf)

## Terms of use

This resource is distributed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence.
