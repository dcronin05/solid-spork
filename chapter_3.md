# 3 All about Data

- [3 All about Data](#3-all-about-data)
  - [3.1 Some Basics](#31-some-basics)
    - [3.1.1 Data, Information, Knowledge and Wisdom](#311-data-information-knowledge-and-wisdom)
    - [3.1.2 Sources and Quality of Data](#312-sources-and-quality-of-data)

## 3.1 Some Basics
In most companies, marketing, sales and process control are major drivers for promoting data quality and producing comparable numbers and facts about the business. But, even production and Research and Development (R&D) departments need reliable data sources to use statistical methods or data mining to improve output and profitability. In most companies, the main impetus for checking and restructuring the data and processes is the introduction of Customer Relationship Management (CRM). CRM imbues the company's own data with new meaning. Gone are the days when customer data management only meant using the correct address in the mailing list. Today's data management must target individual customers and provide more communication and better quality information tailored to theses specific customers and their customer behavior. Data management forms the basis for using intelligent methods such as data mining to analyse the wealth of knowledge available in a company and build an optimal communication with customers and stakeholders.

In many companies, there is hardly any distinction between the terms knowledge, information, and data. Among other things in computer science and economics, it can be seen in the literature that there are strongly divergent views and that different approaches also exist within the two specialties. In computer science, the terms information and data are often used interchangeably, since an explicit distinction does not seem absolutely necessary. The data is equated with the information it represents. The economist, however, sees information as a significant factor of production as well as the intermediate or final product of the corporate transformation process. Information and data are distinct for the economist. Information and data are distinct for the economist. This divergence of views between computer science and economics has implications for how different specialties view data preparation. Computer scientists sometimes miss information that is not coded in the data directly, whereas economists are more familiar with using additional knowledge not stored in data systems (see [Figure 3.1](#FIGURE 3.1 Important terms in data evolution.)).
| **Concept** | **Interpretation** | **Relationship**|
|---|---|---|
|**Wisdom**|*Applied Knowledge*||
|**Knowledge**|Information in context|Conceptual umbrella for information and data|
|**Information**|Meaningful data, data in context|Knowledge needed for special purposes|
|**Data**|Representation of facts|Fundamental|
  
<p style="text-align:center;">FIGURE 3.1 Important terms in data evolution.</a>

### 3.1.1 Data, Information, Knowledge and Wisdom
Here, we demonstrate a clear distinction between knowledge and data. The starting point is often the definition of information as knowledge needed for special purposes.

An early indication of the transition implied by data, Information, Knowledge, and Wisdom (DIKW) is given in the T.S. Eliot poem *The Rock* (1934) where this hierarchy was first mentioned:

*Where is the life we have lost in living?*

*Where is the wisdom we have lost in knowledge?*

*Where is the knowledge we have lost in information?*

DIKW is illustrated in [Figure 3.2](#Figure3.2).

<p style="text-align: center;">
FIGURE 3.2 The evolution of wisdom. Source: Reproduced by permission of Gene Bellinger <a href="http://systems-thinking.org/">http://systems-thinking.org/</a></p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**D = Data** which is facts without context

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**I = Information** which is facts with some context and perspective

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**K = Knowledge** which is information used to detect and understand patterns in the data

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**W = Wisdom** which is knowledge and happens when you understand why the patterns are occurring

It may seem unusual to write about knowledge management and data theory in an applied book for data mining, but this viewpoint many help to understand how knowledge that may or may not be part of the data itself can and should be included in data preparation. For example, it may be known that a company has a seasonal competitor that affects their sales periodically, or blips in production may be caused by a known fault.

### 3.1.2 Sources and Quality of Data
Data to be used for enterprise information and knowledge creation can come from either internal or external sources (see [Figure 3.3](#figure3.3)). The operational information system moves the large amount of data produced internally through the various processes. Since internal data is used primarily to handle the daily business, the operational systems lack any facility for keeping a comprehensive history. Inconsistencies may arise because of partially duplicated data storage in the very different sub-systems. Just as many quality defects affect the data used in the operational systems, so quality defects have an even greater impact on the analysis-oriented information systems. The quality of the data has a significant influence on the quality of the analysis based on it. At least the quality and reliability of internal data is in the control of the company. This is not the case for external data.

|**Data source**|**Example**|**Characteristics**|
|---|---|---|
|**Internal**|Date a product was manufactured or invoice data|In control of company and may be more reliable|
|**External**|Credit rating or data about the area the customer lives in|May not be a perfect match in time scale or location|
<p style="text-align: center;">FIGURE 3.3 Typical internal and external data in information systems.</p>
External data is generated outside the company's own processes; it is often required to act as additional information (e.g. credit rating) or as reference values (e.g. data form Government Statistical Offices or National Statistics Institutes). or analytically focused information systems in areas such as Database Marketing (DBM) and Customer Relationship Management (CRM), external data is added frequently; there may be specifically purchased additional information about the customer's address.

Often, the quality of internal data is better than that from external resources, not least because you can control exactly how and when the internal data was generated. Another issue with external data is that it may not match the internal data exactly in time (being contemporaneous) or location. These discrepancies should be noted, but usually, even poorly matched external data can be useful to supply additional relevant information.