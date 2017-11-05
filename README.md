<h1>Catalog Project</h1>

<h2>Prerequisites</h2>
    <ul>
        <li>Python</li>
        <li>application.py</li>
        <li>database_setup.py</li>
        <li>addItems.py</li>
        <li>Template files</li>
        <li>Virtual Machine</li>
    </ul>
	
<h2>Installing</h2>
	Download and install VirtualBox and Vagrant
	Inside the vagrant subdirectory run "vagrant up" and then "vagrant ssh"
    Run `python database_setup.py` to create the database
    Run `addItems.py` to populate the database with dummy data
    (Populated Database is already included)
	
<h2>Run</h2>
	Run `python application.py` and go to http://localhost:8000 in your preferred browser
    
<h2>Sources Used</h2>
    Full Stack Web Developer http://www.udacity.com
    https://github.com/udacity/ud330/tree/master/Lesson4/step2