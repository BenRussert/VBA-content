---
title: MailMergeDataSource Properties (Publisher)
ms.prod: PUBLISHER
ms.assetid: f60895f3-518c-4a04-b1a1-85c2363b6e92
---


# MailMergeDataSource Properties (Publisher)

## Properties



|**Name**|**Description**|
|:-----|:-----|
| [ActiveRecord](mailmergedatasource-activerecord-property-publisher.md)|Returns or sets a  **Long** that represents the active mail merge record. Read/write.|
| [Application](mailmergedatasource-application-property-publisher.md)|Used without an object qualifier, this property returns an  **[Application](application-object-publisher.md)** object that represents the current instance of Publisher. Used with an object qualifier, this property returns an  **Application** object that represents the creator of the specified object. When used with an OLE Automation object, it returns the object's application.|
| [ConnectString](mailmergedatasource-connectstring-property-publisher.md)|Returns a  **String** that represents the connection to the specified mail merge data source. Read-only.|
| [DataFields](mailmergedatasource-datafields-property-publisher.md)|Returns a  **[MailMergeDataFields](mailmergedatafields-object-publisher.md)** collection that represents the fields in the specified data source.|
| [DataSources](mailmergedatasource-datasources-property-publisher.md)|Returns the  **MailMergeDataSources** collection that includes the parent **MailMergeDataSource** object. Read-only.|
| [EverValidated](mailmergedatasource-evervalidated-property-publisher.md)|Indicates whether the list of recipient addresses in the parent  **MailMergeDataSource** object has ever been validated. Read/write.|
| [Filters](mailmergedatasource-filters-property-publisher.md)|Returns a  **[MailMergeFilters](mailmergefilters-object-publisher.md)** object that represents filters applied to the mail merge or catalog merge data source.|
| [FirstRecord](mailmergedatasource-firstrecord-property-publisher.md)|Returns or sets a  **Long** that represents the number of the first record to be merged in a mail merge or catalog merge operation. Read/write.|
| [Included](mailmergedatasource-included-property-publisher.md)| **True** if a record is included in a mail merge. Read/write **Boolean**.|
| [InvalidAddress](mailmergedatasource-invalidaddress-property-publisher.md)| **True** to mark a record in a mail merge data source if it contains invalid data. Read/write **Boolean**.|
| [InvalidComments](mailmergedatasource-invalidcomments-property-publisher.md)|If the  **[InvalidAddress](mailmergedatasource-invalidaddress-property-publisher.md)** property is **True**, this property returns or sets a  **String** that describes invalid data in a mail merge record. Read/write.|
| [IsMaster](mailmergedatasource-ismaster-property-publisher.md)|Indicates whether the parent  **MailMergeDataSource** object is a master data source (a combination of all data sources connected to the current publication). Read-only.|
| [LastRecord](mailmergedatasource-lastrecord-property-publisher.md)|Returns or sets a  **Long** that represents the number of the last record to be merged in a mail merge or catalog merge operation. Read/write.|
| [MappedDataFields](mailmergedatasource-mappeddatafields-property-publisher.md)|Returns a  **[MailMergeMappedDataFields](mailmergemappeddatafields-object-publisher.md)** object that represents the mapped data fields available in Microsoft Publisher.|
| [Name](mailmergedatasource-name-property-publisher.md)|Returns a  **String** value indicating the name of the specified object. Read-only.|
| [Parent](mailmergedatasource-parent-property-publisher.md)|Returns an object that represents the parent object of the specified object. For example, for a  **[TextFrame](textframe-object-publisher.md)** object, returns a **[Shape](shape-object-publisher.md)** object representing the parent shape of the text frame. Read-only.|
| [RecordCount](mailmergedatasource-recordcount-property-publisher.md)|Returns a  **Long** that represents the number of records in the data source. Read-only.|
| [TableName](mailmergedatasource-tablename-property-publisher.md)|Returns a  **String** that represents the name of the table within the data source file that contains the mail merge records. The returned value may be blank if the table name is unknown or not applicable to the current data source. Read-only.|
| [Type](mailmergedatasource-type-property-publisher.md)|Returns a  **Long** that represents the type of mail merge or catalog merge data source. Read-only.|
| [ValidatedClean](mailmergedatasource-validatedclean-property-publisher.md)|Indicates whether all recipient addresses in the the parent  **MailMergeDataSource** object were successfully validated, and whether any changes are made to the list since the last validation that require the list to be validated again. Read/write.|

