fsdh
[
|  Attribute/description |  | Data-Type |
|  --- | --- | --- |
|  **ocid** |  | string |
|  A globally unique identifier for this part of Contracting Process |  |  |
|  **id** |  | string |
|  An identifier for this particular release of information for part of CP |  |  |
|  **date** |  | date-time |
|  The date this information is released |  |  |
|  **tag** |  | string |
|  A value from the releaseTag codelist that identifies the nature of the release being made |  |  |
|  **initiationType** |  | string |
|  String specifying the type of initiation process used for this part of CP, taken from the initiationType codelist |  |  |
|  **purposeOfNotice.isACallForCompetition** |  | boolean |
|  A True/False field to indicate whether this notice is a call for competition |  |  |
|  **tender.id** |  | string |
|  An identifier for this part of CP |  |  |
|  **tender.title** |  | string |
|  Title for this part of CP |  |  |
|  **tender.description** |  | string |
|  Description for this part of CP |  |  |
|  **tender.awardCriteria** |  | string |
|  Specify the award criteria for the procurement, using the award criteria codelist |  |  |
|  **tender.status** |  | string |
|  The current status of this part of CP based on the tenderStatus codelist |  |  |
|  **tender.statusDetails** |  | string |
|  The current status of this part of CP based on the tenderStatusDetails codelist |  |  |
|  **tender.hasEnquiries** |  | boolean |
|  A true/false field to indicate whether any enquiries were received during the tender process. |  |  |
|  **tender.lotGroups.optionToCombine** |  | boolean |
|  True/False value indicates the CA reserves the right to combine the lots in this group when awarding a contract |  |  |
|  **tender.lots** | array | object |
|  A tender process is divided into lots. <br/>See Lot |  |  |
|  **tender.items** | array | object |
|  The goods and services to be purchased<br/>See Item |  |  |
|  **tender.requiresElectronicCatalogue** |  | boolean |
|  True/False value indicates whether bids must include an electronic catalogue. |  |  |
|  **tender.submissionMethod** |  | string |
|  Specify the method by which bids must be submitted using the submission method codelist |  |  |
|  **tender.submissionMethodRationale** |  | string |
|  A value from the submissionValueRationale codelist that identifies the rationale where electronic submission method is not to be allowed |  |  |
|  **tender.submissionMethodDetails** |  | string |
|  Any detailed or further information on the submission method. |  |  |
|  **tender.procurementMethodModalities** |  | string |
|  The modalities of the procurement method indicated with Method Modalities codelist |  |  |
|  **tender.documents** | array | object |
|  All documents and attachments related to the tender, including any notices. See the documentType codelist<br/>See Document |  |  |
|  **bids.statistics** | array | object |
|  Summary statistics on the number and nature of bids received. <br/>See BidStatistic |  |  |
|  **awards** | array | object |
|  A list of An award for the given procurement<br/>See Award |  |  |
|  **tender.awardPeriod** |  | object |
|  The period for adjudication and selection of the contract award<br/>See Period |  |  |
|  **contracts** | array | object |
|  Information regarding the signed contract between the buyer and supplier(s)<br/>See Contract |  |  |
|  **relatedProcesses** | array | object |
|  Objects described information about related funding (FSs), EI and other related sub-processes<br/>See RelatedProcess |  |  |
|  **parties** | array | object |
|  Object described information about Entities involved into this part of CP <br/>See Organization |  |  |
]($ "dddd")
