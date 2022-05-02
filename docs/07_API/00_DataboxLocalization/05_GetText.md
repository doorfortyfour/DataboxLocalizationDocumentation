GetText
=======

Get localized string
<br>
table: the table ID<br>
entry: the entry ID<br>
params: optional parameters to replace string tags with game variables


		GetText(string _table, string _entry, params Dictionary<string, object>[] _params)
		
		GetText(string _table, string _entry, string _value, params Dictionary<string, object>[] _params)
		
		
		
Example
---------

**use GetText with string parameter**<br>
parameter can be defined as you want to. In this example we have a text with a parameter called @NAME
	
		// text which is used for this example:
		// "Hi @NAME, how are you?";

		var _d = new Dictionary<string, object>();
		_d.Add("@NAME", "John");
			
		// Get localized text and pass the dictionary.
		var _t = DataboxLocalization.Instance.GetText("Text", "ParameterText", _d);
			
		Debug.Log(_t);