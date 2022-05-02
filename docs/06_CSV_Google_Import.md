CSV & Google Spreadsheet import
================================

To make sure Databox - Localization recognizes the correct data types you will need to setup the spreadsheet correctly.

Use following keys to mark the appropriate fields:

**DB_FIELD_NAMES:** The actual name of the value/variable <br>
**DB_FIELD_TYPES:** The type of the value. In case of Databox Localization use:<br>
	- <strong>LanguagesType:</strong> language type<br>
	- <strong>LocalizationTypeText:</strong> for text type<br>
	- <strong>LocalizationTypeStreamingAsset:</strong> for streaming asset path<br>
	- <strong>LocalizationTypeAddressable:</strong> for addressables asset path<br>
**DB_IGNORE:** Mark rows and cells you don't want to import with this key.


Languages sheet
---------------
<br>
<img src="img/languageSheet.png">
<br>


Localization sheet
------------------
<br>
<img src="img/localizationSheet.png">
<br>



For further information about how to import a CSV or Google spreadsheet, please read the official: <a href="http://databox.doorfortyfour.com/documentation/import/using%20spreadsheets">Databox - Data editor documentation</a>
