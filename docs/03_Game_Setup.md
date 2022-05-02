Game setup
===============

Now that you have added some localisation data. You will have to prepare your scene in order to be able to access the data. 
Databox localization comes with a simple to use Databox localization singleton manager. 
The manager handles the loading of the localization file at runtime and gives you an easy way to access the runtime API.
It is also used by the localization scene components for accessing the data. 

 
1. Create an empty GameObject.
2. Name it to something like "DataboxLocalization"
3. Add the DataboxLocalization component to the gameObject.
4. Assign the Databox object with the localization data to the empty object field.

<div class="alert alert-warning">
The best use case would be to add the Databox localization game object to your initial scene which gets loaded only once.
</div>