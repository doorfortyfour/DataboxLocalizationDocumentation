OnLocalizationReady
===================

called by the DataboxLocalization manager script, as soon as the file has been loaded and is ready to be used.

		DataboxLocalization.Instance.OnLocalizationReady += LocalizationReady;
		
		
		void LocalizationReady()
		{
			Debug.Log("Localization is ready");
		}