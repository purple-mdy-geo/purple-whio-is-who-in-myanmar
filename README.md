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
 Roll No  	Name                         Signature/Date
5cs-160   	Ma Yu Yu Lwin		
5cs-61	    Ma Myat Kaythi Aung		
5cs-145  	  Ma Phyu Thwe Soe		
5cs-151 	  Ma Thaim Mwae Lwin		
5cs-162	    Ma Mu Di Ta		

Supervisor Name                                           Signature/Date and time
Dr.Nwe Nwe Hlaing





















CONTENT
                                                                    Page Number
Abstract   	                                                              	i
Acknowledgement	                                                        	 ii
Declaration	                                                              iii
CHAPTER 1 
INTRODUCTIONS                                                              1                       
1.1 Introduction                                                           2
1.2 Background of the project                                              2
1.3 GitHub                                                                 2
   1.3.1 What is GitHub?		                                               3
     (i)Details of the GitHub                                              3
     (ii)Learn GitHub                                                      3
     (iii)How To Create Github Account                                     3
1.3.2 Details Git Bash                                                     4
   (i)Git            							                                         5
   (ii)Bash                                                                5
1.4 Objectives of the project 				                                     6
CHAPTER 2                                                                  6
2.1 Requirement Analysis                                                   6
   2.1.1 Materialize CSS                                                   7
   2.1.2 Material Design Lite                                              9
2.2 Use of Software Applications                                          10
   2.2.1 PyCharm                                                          10
   2.2.2 Heroku                                                           10
2.3   Project Plan                                                        10
CHAPTER 3      Project Designs                                            13
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
     Our project  “Who is Who in Myanmar” is a  one kind of searching  from in Myanmar.This project shows the biography of famous people among in our Country.

    Famous people such as Candidate from parties,Members of parliament,Business leader,Celebrity (They are  Beauty Pageant ,Models,Actor,Vocalist,Directors,Promoter, and so on) and also can know the unique popular people (such as Historical figures,freedom fighter ,Regional leader from  parliament and very important to know about the  famous people.So user can find the about the people who live in Myanmar .  

    This system describe information that user required who takepart in which part.This system just only show the information  system.













                                                                                                          i
                                                                                                          
                                                             Acknowledgements
                                                             
   Firstly, we would like to express my heartfelt thanks to  U Kyaw Zwar Soe, Rector, ComputerUniversity(Mandalay), For  his permission to do this project.

   We should like to express our deep appreciatioin to ours director  U Ravi Chhabra,Director of GEO Mandalar Co.Ltd,for his guidance and suggestion for this project.

   We would like to express our deep appreciation to ours supervisor Dr.Daw Nwe Nwe Hlaing, From Software Department ,Computer University(Mandalay),for her close supervision,helpful advice, encouragement,numerous invaluable suggession and comments.

  We were also grateful to all my teachers from Computer University (Mandalay) who have taugh and guided us during the period of study.
  Finally,we also thanks everyone for supporting  in various ways.











                                                                                                                       ii
                                                                                                                       
                                                       DECLARATION
                                                       
   We declare that this project report or part of it was not a copy of a document done by any organization, university any other institute or a previous student project group at University of Computer Studies, Mandalay and was not copied from the Internet or other sources.

   The interpretations are based on reading and understanding of the original texts and they are not published anywhere in the form of books, monographs or articles. The other books, articles and websites, which I have made use of are acknowledgement at the respective place in the text. For the present thesis, which we are submitting to the University, no degree on me before, either in this or in any other University.

Project Details

Project Title	Who Is Who In Myanmar

Project ID	GEO Mandalar Investment & TechnologyCompany





                                                                                                                                iii.List of Figures
                                                                                                                            Figure                                  Page
                                                                                                                            
Figure 1.1  Example of GitHub Account     23                                                                                                         
Figure 2.2 Materialize Design Lite(MDL)   24                                                                                     
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
         Myanmar is one of the most interesting places in South East Asia. The world 'Myanmar' represents all the ethnic groups living in the country. The population of Myanmar is 60 million people The project is “Who Is Who In Myanmar” .Many kinds of partitions in Myanmar.Among them,describe any five partitions in Myanmar.It include 
               i.Candidates from Parties,
               ii.Member of Parliament(Union,State,Region),
               iii.Business Leaders,
               iv.Modern Historical Figures         (33Comrades,Freedom,Fighters,Regional Leaders,etc….)    and v.Celebrities(BeautyPageants,Models,Actors,Vocalists,Directors,Promoters,Socialites,Social Media Influence,etc...).We used UI/UX update design for our project.We can also used Javascript,Materialize CSS and Materialize Design Lite(MDL).


1.2	Background of the Project
    People has received  personalities of each famous person by a project.
    When the viewers search on the main menu, the project displayed their personalities with photos and texts.
     There are many processes to develop manual system and it may be more cost and time waste. So we decided to develop the project to reduce the problems.

1.3	GitHub
1.3.1	Details of the GitHub
             GitHub is a web-based hosting service for version control using Git. It is mostly used for computer code. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.
  GitHub offers plans for both private repositories and free accounts which are commonly used to host open-source software 
projects. As of June 2018,  GitHub reports having over 28 million users and 57 million repositories (including 28 million public repositories.

(i)What is GitHub
•	 GitHub is at heart a Git repository hosting service, i.e. a
 cloud-based source code management or version control system, but that’s just the beginning. In addition, GitHub implements features for code review (pull requests, diffs, and review requests), project management (including issue tracking and assignment), integrations with other developer tools, team management, documentation, and “social coding.”
•	Something like a social networking site for programmers, GitHub is an open environment where programmers can 
freely share and collaborate (even ad hoc) 
on open source code. GitHub makes it easy to find useful code, copy repositories for your own use, and submit changes to others’ projects. As a result, GitHub has become home to virtually every open source project of any importance.
(ii)Learn GitHub	
Why learn Git? Ever have a "I lost all my work and I have a                                                  deadline the next day" moment? Git is the most popular version control tool - something that developers use to save all relevant versions of their work to avoid moments like those.
                                                     
                                                         








 
