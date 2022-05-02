OnLanguageChanged
===================

called by the DataboxLocalization manager script, when a language change has occurred.

		DataboxLocalization.Instance.OnLanguageChanged += LanguageChanged;
		
		
		void LanguageChanged()
		{
			Debug.Log("Language has changed");
		}