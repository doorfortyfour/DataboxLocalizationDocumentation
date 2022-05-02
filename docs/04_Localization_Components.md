Localization Components
=======================

Databox - Localization comes with several easy to use localization components which can be added to ui components or game objects to automate localization. 
For example, If you want to Localize a ui text component simply add a Localize_uitext component to it. 
Select the table and the corresponding key. The ui text will be now updated based on the selected default language. 
The components also handles a language change during runtime.

All components are available from the Databox Localization "Add Component" menu

Available components:

* Localize_UIText
* Localize_UIImage
* Localize_UIRawImage
* Localize_TextMeshPro_UGUIText
* Localize_TextMeshPro_Text
* Localize_TextMeshPro_FontAsset
* Localize_AudioSource
* Localize_GameObject
* Localize_Material
* Localize_MeshFilter

Dropdown language select
-------------------------

Databox - Localization also has a ready to use dropdown language selection component.
Add this component to a UI Dropdown object and it will automatically add all available languages to the selectable dropdown list.
The component also handles the language change, when user has selected a language from the dropdown.
