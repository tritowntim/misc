
Testing out hard returns in GFMD.

One line  
Two line  
Three line  

More text here 

### Setup

  $ cp config/database.yml.example      config/database.yml  
  $ cp config/auth_keys.yml.example     config/auth_keys.yml  
  $ cp config/braintree.yml.example     config/braintree.yml  
  $ cp config/fog.yml.example           config/fog.yml  
  $ cp config/google_forms.yml.example  config/google_forms.yml  
  $ cp config/sendgrid.yml.example      config/sendgrid.yml  

  $ [bundle exec] rake db:setup  
  $ [bundle exec] rake db:migrate  
  $ [bundle exec] rails s  
