GetAsset
========

Get asset (streaming asset or adddressable)

	DataboxLocalization.Instance.GetAsset<T>(string _table, string _entry, System.Action<T> OnLoadingComplete)
	
	DataboxLocalization.Instance.GetAsset<T>(string _table, string _entry, string _value, System.Action<T> OnLoadingComplete)


Example
-------

	// Load Audio clip in Table: Audio - Entry: Hello
	DataboxLocalization.Instance.GetAsset<AudioClip>("Audio", "Hello", OnLoadingComplete);
	
	void OnLoadingComplete(AudioClip _clip)
	{
		source.clip = _clip;
		source.Play();
	}