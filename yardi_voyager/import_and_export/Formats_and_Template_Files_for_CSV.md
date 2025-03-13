# Formats and Template Files for CSV Imports and Exports

## Overview

Before you import CSV-formatted data into Voyager, you can arrange the data so that it complies with Voyager default standards. If the format of your CSV or fixed-length source-data import file does not comply with default standards, you must create a format template file. Format template files specify and define the data and correctly format the fields so that Voyager can read and import them.

When you export data from Voyager to a CSV or fixed-length format file, you can arrange the fields according to Voyager default standards, including field order. This will ensure that the data can be imported with the correct format and field information into another Voyager database or a foreign database.

---

## XML Format Recommendation

|                                                     |                                                                                                                                                                                                                                                                                                                                                       |
| --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![XML Recommended](images/ImportExport.14.10.1.png) | **XML is the recommended format for importing and exporting files.** Voyager can import XML data directly without using a format template, because field type and format information is included in the source import file. For more information about XML file formats and importing requirements for transactions, contact Yardi technical support. |

---

## Import Data Format Template Files

When using a format template file for CSV-format data imports to Voyager, you must edit the file so that it contains only the fields that exist in the import data file. The rows in the template must coincide with those in the import data. Also verify that the field headers match between the import file and the template. If you remove any fields, you will have to renumber the template rows so they are sequential and coincide with the actual row order. Transactions from other sources can also be successfully imported, although some additional fields and formatting may be required. Also included in this section is a grid of standard import format file names used by Voyager.

---

## Export Data Format Template Files

When using a format template file for CSV-format data exports from Voyager, you must edit the file so that you export only those fields that you need. If you remove any fields, you will have to renumber the template rows so they are sequential.

If you originally exported the transactions from Voyager, you may not need to apply a format template file, as the CSV-format export file typically contains most relevant information and data in the proper format and field order. If needed, you can import the data back into Voyager, for either the same or a different database with little or no additional or special formatting.

---

## To Create a Format Template File for CSV Imports and Exports

1. **On the Voyager System Administration side menu, select:**  
   **Toolbox > Import/Export > Export Tran CSV**  
   The **Export Transactions - CSV** screen appears.

2. **Click Default Format.**  
   A screen appears for opening or saving the file. Select the applicable option. Rename the file, as needed.

3. **Before using a format template, you must edit the data fields** so that you export only those that you need. If you remove any fields, you will have to renumber the template rows so they are sequential. For importing files, you must ensure that the template contains only those fields that you want to import.

For a list of the format template fields, see [Format template files for CSV imports and Exports](Core_Administration_Guide/Formats_and_Template_Files_for_CSV_Imports_and_E.html#1202686).

---

## Format Template Files for CSV Imports and Exports

You can create your own custom format templates. The following table shows the default fields in a Voyager format template for CSV imports and exports:

|                                                     |                                                                                                                                                                                                                |
| --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Template Fields](images/ImportExport.14.10.2.png) | The field definitions in this section were current at the time of publication. For more information about using format templates and the most current template-field updates, contact Yardi technical support. |

Below is the full table of default field definitions:

| **Field Definition**                 |
| ------------------------------------ |
| ACCOUNT,11,0                         |
| ACCRUAL,12,0                         |
| ADJUSTMENT,113,0                     |
| AMOUNT,10,0                          |
| AMOUNT2,89,0                         |
| BALANCEACCOUNT,122,0                 |
| BANK,107,0                           |
| BEGBAL,18,0                          |
| BOOKNUM,20,0                         |
| CATEGORY,77,0                        |
| CHARGEID,100,0                       |
| CHECKNUM,14,0                        |
| COMPANY,105,0                        |
| CONTRACT,75,0                        |
| COSTCODE,78,0                        |
| CREDITMEMO,84,0                      |
| CURRENCY,26,0                        |
| CURRENCYEXCHANGERATETYPE,104,0       |
| DATE,5,0                             |
| DESC,15,0                            |
| DETAILEXCHANGERATE2,101,0            |
| DETAILFIELD1,47,0                    |
| DETAILFIELD2,48,0                    |
| DETAILFIELD3,49,0                    |
| DETAILFIELD4,50,0                    |
| DETAILFIELD5,51,0                    |
| DETAILFIELD6,52,0                    |
| DETAILFIELD7,53,0                    |
| DETAILFIELD8,54,0                    |
| DETAILFUNCTIONALCURRENCYAMOUNT,103,0 |
| DETAILTAXAMOUNT1,43,0                |
| DETAILTAXAMOUNT2,44,0                |
| DETAILTRANAMOUNT,42,0                |
| DETAILVATRATEID,46,0                 |
| DETAILVATTRANTYPEID,45,0             |
| DISCOUNTAMOUNT,111,0                 |
| DISCOUNTDATE,109,0                   |
| DISCOUNTPERCENT,110,0                |
| DISPLAYTYPE,79,0                     |
| DOCUMENTSEQUENCENUMBER,39,0          |
| DRAWDATE,116,0                       |
| DUEDATE,27,0                         |
| ENDBAL,25,0                          |
| EXCHANGERATE,30,0                    |
| EXCHANGERATE2,90,0                   |
| EXCHANGERATEDATE,31,0                |
| EXCHANGERATEDATE2,91,0               |
| EXPENSETYPE,80,0                     |
| FLAGS,16,0                           |
| FROMDATE,34,0                        |
| FUNCTIONALCURRENCY,102,0             |
| FUNCTIONALCURRENCYAMOUNT,112,0       |
| FUNDINGENTITY,106,0                  |
| IMAGEFOLDERPATH,119,0                |
| INCOMEJE,117,0                       |
| INTERNATIONALPAYMENTTYPE,41,0        |
| IS1099EXCEMPT,120,0                  |
| ISCONSOLIDATECHECKS,118,0            |
| ISINTERCOMPANY,66,0                  |
| ISINVOICERECEIVED,40,0               |
| ISTAXJOURNAL,121,0                   |
| JOB,76,0                             |
| MODULE,108,0                         |
| NAME,4,0                             |
| NOTES2,88,0                          |
| OFFSET,13,0                          |
| PERSON,3,0                           |
| PONUM,114,0                          |
| POSTMONTH,6,0                        |
| PREPAYHOLDFOR,81,0                   |
| PREPAYHOLDUNTIL,82,0                 |
| PROPERTY,9,0                         |
| QUANTITY,115,0                       |
| RECEIPTCHARGECODE,83,0               |
| REF,7,0                              |
| REMARK,8,0                           |
| REMITTANCEVENDOR,123,0               |
| REVERSENEXTMONTH,55,0                |
| SEGMENT1,21,0                        |
| SEGMENT10,72,0                       |
| SEGMENT11,73,0                       |
| SEGMENT12,74,0                       |
| SEGMENT2,22,0                        |
| SEGMENT3,23,0                        |
| SEGMENT4,24,0                        |
| SEGMENT5,67,0                        |
| SEGMENT6,68,0                        |
| SEGMENT7,69,0                        |
| SEGMENT8,70,0                        |
| SEGMENT9,71,0                        |
| TAXAMOUNT1,32,0                      |
| TAXAMOUNT2,33,0                      |
| TAXPOINTDATE,36,0                    |
| TODATE,35,0                          |
| TRANAMOUNT,28,0                      |
| TRANCURRENCYID,29,0                  |
| TRANDATE,19,0                        |
| TRANFIELD1,92,0                      |
| TRANFIELD2,93,0                      |
| TRANFIELD3,94,0                      |
| TRANFIELD4,95,0                      |
| TRANFIELD5,96,0                      |
| TRANFIELD6,97,0                      |
| TRANFIELD7,98,0                      |
| TRANFIELD8,99,0                      |
| TRANNUM,2,0                          |
| TYPE,1,0                             |
| UNIT,17,0                            |
| USERDEFINEDFIELD1,56,0               |
| USERDEFINEDFIELD10,65,0              |
| USERDEFINEDFIELD2,57,0               |
| USERDEFINEDFIELD3,58,0               |
| USERDEFINEDFIELD4,59,0               |
| USERDEFINEDFIELD5,60,0               |
| USERDEFINEDFIELD6,61,0               |
| USERDEFINEDFIELD7,62,0               |
| USERDEFINEDFIELD8,63,0               |
| USERDEFINEDFIELD9,64,0               |
| VATRATEID,38,0                       |
| VATTRANTYPEID,37,0                   |
| WORKFLOW,85,0                        |
| WORKFLOWSTATUS,86,0                  |
| WORKFLOWSTEP,87,0                    |

---

## Standard Import Format File Names

The following grid shows the standard import format-file names that Voyager recognizes:

| **Import type**              | **Default format file name** |
| ---------------------------- | ---------------------------- |
| All                          | IMEX.FMT                     |
| Charge                       | CHARGE.FMT                   |
| Receipt                      | RECEIPT.FMT                  |
| Payable                      | INVOICE.FMT                  |
| Check                        | CHECK.FMT                    |
| Journal Entry, Trial Balance | JOURNAL.FMT                  |
| Default                      | IMPORT.FMT                   |
