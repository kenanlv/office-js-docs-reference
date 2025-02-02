| Class | Fields | Description |
|:---|:---|:---|
|[Application](/javascript/api/excel/excel.application)|[cultureInfo](/javascript/api/excel/excel.application#cultureinfo)|Provides information based on current system culture settings.|
||[decimalSeparator](/javascript/api/excel/excel.application#decimalseparator)|Gets the string used as the decimal separator for numeric values.|
||[thousandsSeparator](/javascript/api/excel/excel.application#thousandsseparator)|Gets the string used to separate groups of digits to the left of the decimal for numeric values.|
||[useSystemSeparators](/javascript/api/excel/excel.application#usesystemseparators)|Specifies if the system separators of Excel are enabled.|
|[Comment](/javascript/api/excel/excel.comment)|[mentions](/javascript/api/excel/excel.comment#mentions)|Gets the entities (e.g., people) that are mentioned in comments.|
||[richContent](/javascript/api/excel/excel.comment#richcontent)|Gets the rich comment content (e.g., mentions in comments).|
||[resolved](/javascript/api/excel/excel.comment#resolved)|The comment thread status.|
||[updateMentions(contentWithMentions: Excel.CommentRichContent)](/javascript/api/excel/excel.comment#updatementions-contentwithmentions-)|Updates the comment content with a specially formatted string and a list of mentions.|
|[CommentCollection](/javascript/api/excel/excel.commentcollection)|[add(cellAddress: Range \| string, content: CommentRichContent \| string, contentType?: Excel.ContentType)](/javascript/api/excel/excel.commentcollection#add-celladdress--content--contenttype-)|Creates a new comment with the given content on the given cell.|
|[CommentMention](/javascript/api/excel/excel.commentmention)|[email](/javascript/api/excel/excel.commentmention#email)|The email address of the entity that is mentioned in a comment.|
||[id](/javascript/api/excel/excel.commentmention#id)|The ID of the entity.|
||[name](/javascript/api/excel/excel.commentmention#name)|The name of the entity that is mentioned in a comment.|
|[CommentReply](/javascript/api/excel/excel.commentreply)|[mentions](/javascript/api/excel/excel.commentreply#mentions)|The entities (e.g., people) that are mentioned in comments.|
||[resolved](/javascript/api/excel/excel.commentreply#resolved)|The comment reply status.|
||[richContent](/javascript/api/excel/excel.commentreply#richcontent)|The rich comment content (e.g., mentions in comments).|
||[updateMentions(contentWithMentions: Excel.CommentRichContent)](/javascript/api/excel/excel.commentreply#updatementions-contentwithmentions-)|Updates the comment content with a specially formatted string and a list of mentions.|
|[CommentReplyCollection](/javascript/api/excel/excel.commentreplycollection)|[add(content: CommentRichContent \| string, contentType?: Excel.ContentType)](/javascript/api/excel/excel.commentreplycollection#add-content--contenttype-)|Creates a comment reply for a comment.|
|[CommentRichContent](/javascript/api/excel/excel.commentrichcontent)|[mentions](/javascript/api/excel/excel.commentrichcontent#mentions)|An array containing all the entities (e.g., people) mentioned within the comment.|
||[richContent](/javascript/api/excel/excel.commentrichcontent#richcontent)|Specifies the rich content of the comment (e.g., comment content with mentions, the first mentioned entity has an ID attribute of 0, and the second mentioned entity has an ID attribute of 1).|
|[CultureInfo](/javascript/api/excel/excel.cultureinfo)|[name](/javascript/api/excel/excel.cultureinfo#name)|Gets the culture name in the format languagecode2-country/regioncode2 (e.g., "zh-cn" or "en-us").|
||[numberFormat](/javascript/api/excel/excel.cultureinfo#numberformat)|Defines the culturally appropriate format of displaying numbers.|
|[NumberFormatInfo](/javascript/api/excel/excel.numberformatinfo)|[numberDecimalSeparator](/javascript/api/excel/excel.numberformatinfo#numberdecimalseparator)|Gets the string used as the decimal separator for numeric values.|
||[numberGroupSeparator](/javascript/api/excel/excel.numberformatinfo#numbergroupseparator)|Gets the string used to separate groups of digits to the left of the decimal for numeric values.|
|[Range](/javascript/api/excel/excel.range)|[moveTo(destinationRange: Range \| string)](/javascript/api/excel/excel.range#moveto-destinationrange-)|Moves cell values, formatting, and formulas from current range to the destination range, replacing the old information in those cells.|
|[RangeFormat](/javascript/api/excel/excel.rangeformat)|[adjustIndent(amount: number)](/javascript/api/excel/excel.rangeformat#adjustindent-amount-)|Adjusts the indentation of the range formatting.|
|[Workbook](/javascript/api/excel/excel.workbook)|[close(closeBehavior?: Excel.CloseBehavior)](/javascript/api/excel/excel.workbook#close-closebehavior-)|Close current workbook.|
||[save(saveBehavior?: Excel.SaveBehavior)](/javascript/api/excel/excel.workbook#save-savebehavior-)|Save current workbook.|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[onRowHiddenChanged](/javascript/api/excel/excel.worksheet#onrowhiddenchanged)|Occurs when the hidden state of one or more rows has changed on a specific worksheet.|
|[WorksheetCalculatedEventArgs](/javascript/api/excel/excel.worksheetcalculatedeventargs)|[address](/javascript/api/excel/excel.worksheetcalculatedeventargs#address)|The address of the range that completed calculation.|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[onRowHiddenChanged](/javascript/api/excel/excel.worksheetcollection#onrowhiddenchanged)|Occurs when the hidden state of one or more rows has changed on a specific worksheet.|
|[WorksheetRowHiddenChangedEventArgs](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs)|[address](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#address)|Gets the range address that represents the changed area of a specific worksheet.|
||[changeType](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#changetype)|Gets the type of change that represents how the event was triggered.|
||[source](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#source)|Gets the source of the event.|
||[type](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#type)|Gets the type of the event.|
||[worksheetId](/javascript/api/excel/excel.worksheetrowhiddenchangedeventargs#worksheetid)|Gets the ID of the worksheet in which the data changed.|
