# purple-whio-is-who-in-myanmar

	                         A PROJECT REPORT ON
           		              
                        	“Who Is Who In Myanmar”
                     
                      
		        		FOR
	
			
                        Geo Mandalar Investment and technology(Co.,Ltd)
                        
                   		     SUBMITTED IN PARTIAL
                  
		  	          FULFILLMENT OF INTERNSHIP
                             
			                  PROJECT
                                
			           UNDER THE GUIDANCE OF
                          
			                  Director
                                 
			              U Ravi Chhabra
                          
                                         Supervisor
                              
			              Dr.Nwe Nwe Hlaing
                     
                                         SUMITTED BY
                          
			                Ma Yu Yu Lwin
                                        Ma Myat Kaythi Aung
                                        Ma Phyu Thwe Soe
                                        Ma Thaim Mwae Lwin
                                        Ma Mu Di Ta
                     
                           University of Computer Studies(Mandalay)
                  
		                   Date –- September 2018

          		Group Member
			
			Roll No  			Name                         Signature/Date
			
			5cs-160   			Ma Yu Yu Lwin		
			5cs-61	    			Ma Myat Kaythi Aung		
			5cs-145  	  		Ma Phyu Thwe Soe		
			5cs-151 	  		Ma Thaim Mwae Lwin		
			5cs-162	    			Ma Mu Di Ta		

			

			Supervisor Name                                           Signature/Date and time

			Dr.Nwe Nwe Hlaing





















			CONTENT 								Page Number
													
			Abstract   	                                                           i
			Acknowledgement	                                                           ii
			Declaration	                                                           iii
			CHAPTER 1 
			INTRODUCTIONS                                                              1                       
			   1.1 Introduction                                                        2
			   1.2 Background of the project                                           2
			   1.3 GitHub                                                              2
			   	1.3.1 What is GitHub?		                                   3
			            	(i)Details of the GitHub                                   3
				     	(ii)Learn GitHub                                           3
			     		(iii)How To Create Github Account                          3
			  	1.3.2 Details Git Bash                                             4
			       		(i)Git            					   5
				     	(ii)Bash                                                   5
			    1.4 Objectives of the project 				           6
		       CHAPTER 2                                                                   6
		           2.1 Requirement Analysis                                                6
 				2.1.1 Materialize CSS                                              7
				2.1.2 Material Design Lite                                         9
			   2.2 Use of Software Applications                                        10
				2.2.1 PyCharm                                                      10
				2.2.2 Heroku                                                       10
			   2.3   Project Plan                                                      10
		     CHAPTER 3      Project Designs                                   		    13
   			   3.1 Designs
				3.1.1 Learn Python
				3.1.2 Python Exercises
				3.1.3 Flask
				3.1.4 Personal Page On Heroku
				3.1.4 Gmail App Design
				3.1.5 Lost Footsteps Design Example
				3.1.6 Online Shopping Design
				3.1.7 Who Is Who In Myanmar
		   CHAPTER 4 
			 4.1 Conclusion  
   				4.2 Advantages of the Project  
   				4.3 Disadvantages of the project
	   			4.4 Limitation and Future Work


                                		            Abstract

		Our project  “Who is Who in Myanmar” is a  ne kind of searching  from in Myanmar.This project 
		shows the biography of famous people among in our Country.

		Famous people such as Candidate from parties,Members of parliament,Business leader,Celebrity
		(They are  Beauty Pageant ,Models,Actor,Vocalist,Directors,Promoter, and so on) and also can know the
		unique popular people (such as Historical figures,freedom fighter ,Regional leader from  parliament
		and very important to know about the  famous people.So user can find the about the people who live in Myanmar .  

    		This system describe information that user required who takepart in which part.This system just only show the information  system.













                                                                     i





                                                             Acknowledgements
                                                             
   		Firstly, we would like to express my heartfelt thanks to  U Kyaw Zwar Soe, Rector, ComputerUniversity(Mandalay),
		For  his permission to do this project.

  		 We should like to express our deep appreciatioin to ours director  U Ravi Chhabra,Director of GEO Mandalar Co.Ltd,
		 for his guidance and suggestion for this project.

 		 We would like to express our deep appreciation to ours supervisor Dr.Daw Nwe Nwe Hlaing, From Software Department ,
		 Computer University(Mandalay),for her close supervision,helpful advice, encouragement,numerous invaluable suggession and comments.

		We were also grateful to all my teachers from Computer University (Mandalay) who have taugh and guided us during the period of study.
  		Finally,we also thanks everyone for supporting  in various ways.










                                                                     ii





                                                       DECLARATION
                                                       
	   We declare that this project report or part of it was not a copy of a document done by any organization,
	   university any other institute or a previous student project group at University of Computer Studies,
	   Mandalay and was not copied from the Internet or other sources.

   	  The interpretations are based on reading and understanding of the original texts and they are not published 
	  anywhere in the form of books, monographs or articles. The other books, articles and websites, which I have made
	  use of are acknowledgement at the respective place in the text. For the present thesis, which we are submitting to
	  the University, no degree on me before, either in this or in any other University.

	Project Details

	Project Title			Who Is Who In Myanmar

	Project ID			GEO Mandalar Investment & TechnologyCompany




		                                             iii
							     
							     
							     
							     
							     
							     
		List of Figures


		Figure 						                                 Page
                                                                                                                            
		Figure 1.1  Example of GitHub Account    	                                  23                                                                                            
		Figure 2.2 Materialize Design Lite(MDL)   					  24                                                                                     
		Figure 2.1 Materialize Css
		Figure 2.3 Example of Heroku App Account
		Figure 2.4 Project Plan
		Figure 3.2 Python Exercises run on PyCharm
		Figure 3.3 Learn Flask run on GitBash
		Figure 3.4 Example of Personal Page On Heroku
		Figure 3.5 Gmail App Design
		Figure 3.6 Example of Lost Footsteps Design
		Figure 3.7 Example of UI/UX Design for Online Shopping
		Figure 3.8 Example of UI/UX Design for “Who Is Who In Myanmar”


						
                                                		
								
								  CHAPTER 1
                                                 		
								INTRODUCTION
		1.1	Introduction
        		 Myanmar is one of the most interesting places in South East Asia. The world 'Myanmar' represents all the ethnic
			 groups living in the country. The population of Myanmar is 60 million people The project is “Who Is Who In Myanmar” .
			 Many kinds of partitions in Myanmar.Among them,describe any five partitions in Myanmar.It include 
              		
			i.Candidates from Parties,
               		ii.Member of Parliament(Union,State,Region),
               		iii.Business Leaders,
               		iv.Modern Historical Figures         (33Comrades,Freedom,Fighters,Regional Leaders,etc….)    
			and v.Celebrities(BeautyPageants,Models,Actors,Vocalists,Directors,Promoters,Socialites,
			Social Media Influence,etc...).We used UI/UX update design for our project.We can also used Javascript,Materialize CSS
			and Materialize Design Lite(MDL).


		1.2	Background of the Project
			    People has received  personalities of each famous person by a project.
			    When the viewers search on the main menu, the project displayed their personalities with photos and texts.
			     There are many processes to develop manual system and it may be more cost and time waste. So we decided to develop the project to reduce the problems.


		1.3	GitHub
		
		1.3.1	Details of the GitHub
	
			GitHub is a web-based hosting service for version control using Git. It is mostly used for computer code.
			It offers all of the distributed version control and source code management (SCM) functionality of Git as well as
			adding its own features. It provides access control and several collaboration features such as bug tracking,
			feature requests, task management, and wikis for every project.
 			 GitHub offers plans for both private repositories and free accounts which are commonly used to host open-source software 
			projects. As of June 2018,  GitHub reports having over 28 million users and 57 million repositories (including 28 million public repositories.

		
		(i)What is GitHub
			•GitHub is at heart a Git repository hosting service, i.e. a
			cloud-based source code management or version control system, but that’s just the beginning.
			In addition, GitHub implements features for code review (pull requests, diffs, and review requests),
			project management (including issue tracking and assignment), integrations with other developer tools, 
			team management, documentation, and “social coding.”
			•Something like a social networking site for programmers, GitHub is an open environment where programmers can 
			freely share and collaborate (even ad hoc) 
			on open source code. GitHub makes it easy to find useful code, copy repositories for your own use, and submit
			changes to others’ projects. As a result, GitHub has become home to virtually every open source project of any importance.
		(ii)Learn GitHub	
			Why learn Git? Ever have a "I lost all my work and I have a                                                 
			deadline the next day" moment? Git is the most popular version control tool - something that developers use to 
			save all relevant versions of their work to avoid moments like those.
                                                     
             
             
                 Figure1.1 Learn Git

		(iii)How To Create GitHub Account?
			
			•Play vim adventuregame
			•Do github tutorial
			•Build repository



                        
                                    
 
             Figure1.2 Example of GitHub Account


		1.3.2 Details of Git Bash 	
		      Git Bash is a bash shell for use on Microsoft Windows
		      systems, to enable the git repository functions on that platform.Git Bash for Windows is a package that is comprised of two parts:
				Git: It is a version control system (VCS) which tracks the file changes.
				Bash: It is a unix shell command line interface commonly used in different linux machines.
                                                                                 
			(i)Git
				Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people
				. It is primarily used for source code management in software development in software development, but it can be used to keep
				track of changes in any set of files. Git is free and open source software distributed under the terms of the GNC General Public License version 2.
			(ii)Bash
				Bash is a Unix shell and command language written by Brian Fox for the GNU Project as a free software replacement for the Bourne
				shell. It has been distributed widely as the default login shell for most Linux distributions and Apple’s macOS. A version is also 
				available for Windows 10.
				Bash is command processor that typically runs in a text window where the user types commands that cause actions.
				Bash can also read and execute commands from a file, called a shell script.

			1.4 Objective of the Project
				To search people informations from these  project.
				User can  easily   know about  the  people  biography of famous people.                                    
				To  reduce  the  paper  work.
				To  develop  the  general  knowledge  for our  country have a variety  of popular  people .

                                
				
							CHAPTER 2
        		        		                       		
						       METHODOLOGY

     2.1 Requirement Analysis
		•	Hardware Requirements
	        		  Processor: Core i3		
			          RAM: 4GB
	        		  Hard Disk: 4GB
		•	Software Requirements
			         Language:   Python, CSS, HTML, Materialize CSS,   
                        	 Materialize Design Lite(MDL)                                
		                 Operating System: Window7
			
			Software:   GitHub, Git Bash,Heroku, 
                            PyCharm,Sublime Text 3
			    
		2.1.1 Materialize CSS
			Materialize is basically CSS framework which is used to create responsive websites. 
			Materialize framework is basically built on google’s material design concept. Materialize 
			framework is created with HTML, CSS and JavaScript.
			Materialize CSS is a UI	component library which is created 
			with HTML, CSS and JavaScript. It is created and designed by Google. Materialize CSS is known as Materialize Design.
			Google’s goal is to develop a system of design that allows for a unified user experience across all their products on 
			any platform. It is used to construct attractive, consistent, and functional web pages and web apps.
			Material design in its purest form: shadows, layers, flat icons, bright colors, and conservation of space for mobile. Bebber’s Gooey Menu offer
			something new and unique without sacrificing the best advantages of Google’s design style. It is a modern responsive front-end framework based on Material Design. 
 
		          Figure 2.1 Materialize Css      	

			2.1.2	Materialize Design Lite (MDL)
	
				Today we are releasing our effort to bring this to websites using vanilla CSS, HTML, JavaScript.
				We’re calling it Material Design Lite. MDL makes it easy to add a material design look and feel to your websites. 
				MDL includes a rich set of components including material design buttons, text-fields.






                                              (a)
   



				                                            
                                	       (b)
				
				Figure 2.2 Materialize Design Lite(MDL)
       
       
		2.2 Use of Software Applications

			2.2.1 Pycharm
		                     Pycharm is an integrated development environment (IDE) used in computer programming specifically for the Python language.
				     It is specially for the Python language. It is developed by Czech company JetBrains. It provides code analysis, a graphical debugger,
				     an integrated unit tester, integration with Version control system (vcses) and supports web development with Django.
                    	If you’re using macOS or Linux your computer already has Python installed. You can get Python from Python.org.

			2.2.2 What is Heroku?
				
				Heroku is the following:
						A Web Application Deployment Model
						A Platform-as-a-Service
						A Polyglot Platform
						A Cloud Platform
				
				Benefits of the Heroku platform are:
				
				1.Cost: Heroku’s platform-as-a-service helps companies make tremendous cost savings because it eliminates the need for expensive 
				infrastructure and all the time and money it takes to manage servers.
				2.Productivity: From start to finish, every detail of Heroku is designed to maximica efficiency and save developers time. It is intultiv,
				powerful, and easy to use.
				3.Support: The Heroku Operational Experience(Opex)lends immense support, with troubleshooting tips and quick diagnostic tools to help you 
				get to the root of the problem fast and fix it even faster.
				4. The Ecosystem: With Heroku Elements, developers can extend apps using a wide variety of add-ons from third party cloud services. So the
				options are nearly endless.
 


 	
			      Figure 2.3 Example of Heroku App Account



				2.3Project Plan
 


 
		 						CHAPTER 3
                                                
											
								PROJECT DEVELOPMENT
			3.1 Designs
				
				3.1.1 Learn Python 
  


  	
        				Figure 3.1 Python Exercises run on GitBash 

		3.1.2 Python Exercises
 
        Figure 3.2 Python Exercises run on PyCharm

		3.1.3 Flask	
		
			Flask is a small and powerful web framework for Python. It's easy to learn and simple to use, enabling you to
			build your web app in a short amount of time.
			   Before getting started, we need to install Flask. Because systems vary, things can sporadically go wrong during these steps.
			   If they do, like we all do, just Google the error message or leave a comment describing the problem
  
		
	
		
		
		Figure 3.3 Learn Flask run on GitBas
		
		
		
		3.1.4 Personal Page On Heroku
  



			
			
			Figure3.4 Example of Personal Page On Heroku
	
		
		
		3.1.4 Gmail App Design
 
			
			(a)	Gmail App Design Example
 
		        (b)After Click Menu Item
     
               		(c)After press enter create icon
			
			
			Figure 3.5 Gmail App Design
		
		
		
		3.1.5 Lost Footsteps Design Example
 


		\Figure 3.6 Example of Lost Footsteps Design

	
		
		
		3.1.6 Online Shopping Design 
   
  Figure 3.7 Example of UI/UX Design for Online Shopping

 3.1.7 Who Is Who In Myanmar
 
           (a)Home Page of Who Is Who In Myanmar

 
                      (b)After Click Menu Bar

 
(c)Footer
 
              (d) After Click About In Footer 
   
          (e)After Click Contact Us In Footer
Figure3.8 Example of UI/UX Design for “Who Is Who In
                         Myanmar”
Link      https://purple5.herokuapp.com

 
                                          CHAPTER 4  
                   EVALUATIONS AND CONCLUSION
4.1 Conclusion	
	The project provides simple and complete functions to be easily search for viewers who want to know all about people in this project.
	Admin can also change and add data easily about updating news in Myanmar.
 	Thus project “Who Is Who In Myanmar” will be a convenient way for the viewers.

4.2 Advantages of the Project
	That project offers the following advantages:
•	It helps from “lack of cost and time” for viewers.
•	It provides “faster and easier” way because of using this project only needs mobile tablets, etc.
•	And so, it is better than by paper work.
•	It is a User Friendly system for all viewers.

4.3 Disadvantages
•	The cost of computer hardware and software programs can be expensive.
•	As mobile tablets use wireless networks, they can connect with network if Wifi fails.

 4.4 Limitations and Future Work
This project is suitable for not only the Myanmar nations but also for tourists and visitors from many other countries. Since the analysis, part is modular, more updated analysis data can be implemented.In fact, one can also have multiple analysis data in different files which can be used according to the requirement.


Reference
1.	https://www.codecademy.com/learn/learn-the-command-line
2.	https://www.codecademy.com/learn/learn-git
3.	https://github.com
4.	https://github.com/mayeedwin/profile
5.	https://vim-adventures.com
6.	https://mockery 1-1.herokuapp.com
7.	https://purplemc2.herokuapp.com
8.	https://purple5.herokuapp.com

