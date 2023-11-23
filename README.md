## Element locations


### Homepage
Most settings and items controlled in ```politis-lab/config.toml```

#### Main Page
Logo - under [params] header in config.toml:```static/images/logo.png```
Banner - under [params] in config.toml: ```static/images/banner/bilayer.png```  
Introduction text - under [params.about] in ```config.toml```  
Introduction image - ```static/images/buttons/lacY.png```  
Twitter - under [params.footer], link to twitter handle politis_lab  

#### Research Themes Page
Configurations in ```politis-lab/data/feature.yml```  
Images in ```static/images/buttons/*.png```  

#### Featured Publications Page
Configuration files found in ```content/portfolio/```  
Images are stored in ```static/images/blog/```  

1. Copy and edit one of the existing .md files in the portfolio folder.

### People Page
Configurations in ```politis-lab/data/team.yml```  
Images are stored in ```politis-lab/static/images/team/```  

1. Place photo of group members in ```politis-lab/static/images/team/```.
2. Edit ```politis-lab/data/team.yml``` file to remove/add people to list using same format as already in yml file.

#### Previous members Page
Configurations in ```politis-lab/data/client.yml```  

1. To add new people to list, make a png image of them using the ai file at ```politis-lab/static/images/team/previous_members.ai```.
2. Place the png image in the same directory at ```politis-lab/static/images/team/```.
3. Add the image to the list at ```politis-lab/data/client.yml```.

### Publications Page
Publication list in ```politis-lab/data/publications.yml```  

1. To add publications, edit above file and manually add paper reference.

### Location Page
Configurations in ```politis-lab/data/contact.yml```  
Address and email widgets found as *officeAddress1* and *mail1* in ```politis-lab/data/contact.yml``` file  
Google map widget configured in ```themes/timer-hugo/layouts/location/list.html``` - embed as iframe on line 53  

### Vacancies
Each vacancy contained in individual markdown files in ```content/vacancies/```  

To add vacancy page:
1. Copy and edit one of the current .md files in ```politis-lab/content/vacancies/```

To remove a vacancy, just add .old to the end of the .md filename and it will disappear.
