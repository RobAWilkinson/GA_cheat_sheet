#Rails Cheatsheet for the Simple Minded

###First Steps when creating a Rails app:

1) Rails new "App Name" -T

2) Cd into your app 

3) Run "bundle install"

4) Rails g model "modelNames" "columns" + "keys"
	
	-This step can be done multiple times for the 	different models in your app.
	-Model names are always plural, "users"
	
5) Rails g contolller "controllerName" "actions"
	
	-Multiple actions can be daisy chained together 	after the controller name.
	-Controller names are always singular

6) So back into your CLI, input rake db:migrate
	
	-This pulls in your tables.
	
7) Setup your database relationships in your models
	
	-has_many (plural)
	-belongs_to (singular)
	-has_many "blank" through "blank"
	-has_and_belongs_to_many
	
8) Create your routes. This can either be done manually or using resources.