_________________________________PROJECT 2_____________________________________________
_______________________________INTALLATIONS____________________________________________
_______________________________________________________________________________________
	> Node.js and Node Package Manager (NPM): linl: https://nodejs.com/en/download
	> Ionic Command Line Interface
	> Python3: link:https://www.python.org/downloads/
	> Postman
	> AWS CLI
_______________________________________________________________________________________
__________________________________Procedure____________________________________________
_______________________________________________________________________________________
______________________________________PART 1________________________________________
	> Step 1: cloninng from: hhtp://github.com/udacity/cloud-developer.git
	> Step 2: npm install
	> Step 3: npm audit fix
	> Step 4: npm run dev
	> Step 5: Test the link with Postman: http://localhost:8082/
	> Step 6: git init
	> Step 7: git add .
	> Step 8: git commit -m "1 commit"
	> Step 9: git branch -M main
	> Step 10: git remote add origin https://github.com/Motaung80/udagram-imgage-filtering-0208.git
	> Step 11: git push -u origin main
	> Step 12: git checkout -b dev
	> Step 13: Open sever.ts and add image filtering function using typescript, ensure all request work
	> Step 14: git add .
	> Step 15: git commit -m "Added image filter funonality in sever.ts file"
	> Step 16: npm run dev (Test if the function works for all images on Postman)
	> Step 17: git push origin main
	> Step 18: git push origin dev
	> Step 19: Go to githib and (i)create a pull request, (ii) merge and (iii) delete branch
	> Step 20: npm run build
___________________________________________________________________________________________________________
________________________________________PART 2_____________________________________________________________
	> Step 1: run eb init and select a region
	> Step 2: Enter application name: I used default name
	> Step 3: It appers you are using Node.js is correct Y or N? Y
	> Step 4: Select a platform branch (default 1)
	> Step 5: Do you wish to continue with codecommit Y or N? n
	> Step 6: Select a keypair (default 2)
	> Step 7: Go to elastic beanstalk and confirm if the application appers
_______________________________________________________________________________________________________________
________________________________________PART 3________________________________________________________________
	> Step 1: go to config.yml and insert the deploy: artifact: ./www/Archive.zip
________________________________________________________________________________________________________________
______________________________________________PART 4_____________________________________________________________
	> Step 1: eb create
	> Step 2: Enter enviroment name: (used default)
	> Step 3: Enter DNS CNAME prefix: (used default)
	> Step 4: Select load balancer type: (used default 2)
	> Step 5: Would you like to enable Spot Fleet request for this enviroment Y or N? n
_________________________________________________________________________________________________________________
________________________________________LINK__________________________________________________________________
	> Github link: https://github.com/Motaung80/udagram-imgage-filtering-0208.git
	> image url remove localhost: http://image-filter-starter-code-dev-lekotla.us-east-1.elasticbeanstalk.com/