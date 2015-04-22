Heroku Cheat Sheet




1.rails new heroku_app -d postgresql

2.in GEM file add current ruby version:    


		ruby ‘2.0.0’

		

3.In bottom of GEM file add. This GEM is only used in a production setting

 	group :production do 

		gem 'rails_12factor'

		gem 'thin'

	end


4.IN TERMINAL


4. In rails folder, create Procfile-  Touch Procfile. 

5. IN Procfile- add bundle exec thin start
	

6. heroku create  newappname 

  *Note: 	
	If newappname was not entered, heroku automatically assigns one, to remove in terminal:  heroku destroy 'calm-hamlet-6527'
	
5. heroku run rake db:migrate to include database	

7. git push heroku master

8. heroku open

*Notes:
heroku create [appname]

deploying to heroku:
git push heroku master
			

heroku open- views in browser
heroku logs-views log
