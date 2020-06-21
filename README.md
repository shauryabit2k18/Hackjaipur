# Single shot - Face verification System 

In these difficult times, working from home has been a real challenge to all of us. Verifying the identity of a user and authenticity of his work has become a really challenging feat to achieve.In these difficult times, password protected websites do not seem to be a full proof solution to verify the actual presence of the desired user. This project uses a user database which collects the username, password as well as a photo of the user and allows the user to sign in only when his live facecam image, username and password matches with that in the database.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Installing On MAC
<ol>
<li>Clone the repository to your local machine.</li>

<li>Run command : pip install virtualenv on the terminal window in your PC to install virtual environment.</li>

<li>Open the cloned repository through the terminal window.</li>

<li>Run command : source venv/bin/activate to activate the virtual environment.</li>

<li>Run command : pip install -r requirements.txt to install all the requirement files.</li>

<li>Through the terminal, open the HackJaipur folder and run the command : python manage.py runserver</li>

<li>Open your web-browser and enter the url : http://127.0.0.1:8000/ to get started.</li>
</ol>

## INSTALLING ON WINDOWS:
<ol>
<li>After downloading the repository to your PC, first make a virtual environment using the command prompt.
	<li>For that first install virtual environment:  
                         pip install virtualenv</li>

	<li>Now change the current working directory to        
     the   
     directory containing the content of the     
     repository u downloaded: cd directory_path</li>

	<li>Now create a virtual environment using    
    command :               virtualenv myenv
	and then activate you environment : 
                         myenv\scripts\activate</li>

<li>Now copy the requirements.txt file (saved in venv folder in the same directory you are working in) to the current directory(manually)  and install all packages required for the program to run : pip install -rrequirements.txt </li>
<li>After running the above command the your PC will start downloading all the packages mentioned in requirement.txt
(THIS MAY TAKE SOME TIME DEPENDING ON YOUR INTERNET SPEED)
</li>
<li>After you have installed all the required packages you can now use the server using command:python manage.py runserver
</li>
<li>You will get a URL and you are ready to go...</li>



## Milestones achieved

1.Creating a user database to store usernames, passwords, and a single    photo of each user for user-verification.

2.Enabling user identification through face cam and tracking his work to ensure work authenticity.

3.Preventing users from creating fake accounts and multiple accounts as their entry into the system is regulated through the database with their unique username and face-id.

## Scope

1.Completely digitalising user’s work profile.We can extend this project to completely digitalise a person’s work progress by creating a database to store their current work status and their past work history .

2.Enabling multiple organisations to load their databases into our website and helping them ensure user-verification through live face cam feed.

3.Enabling organisations to make multiple additions, removals and corrections to their database as per their needs.

## Authors

- Parag Mittal
- Shaurya Sinha
- Anil Muthigi


	
