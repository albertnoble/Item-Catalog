<h1>Catalog Project</h1>
A sports equipment catalog that displays items retrieved from a database.
Authorized users can add, edit, or remove items.  This application utilizes
the Flask python framework.

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
	Inside the vagrant subdirectory run <code>vagrant up</code> and then <code>vagrant ssh</code>
    Run <code>python database_setup.py</code> to create the database
    Run <code>addItems.py</code> to populate the database with dummy data
    (Populated Database is already included)
	
<h2>Run</h2>
	Run <code>python application.py</code> and go to <code>http://localhost:8000</code> in your preferred browser
    
<h2>Sources Used</h2>
    Full Stack Web Developer http://www.udacity.com
    https://github.com/udacity/ud330/tree/master/Lesson4/step2