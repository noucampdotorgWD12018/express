# Express Exercise 1

## Clone the Remote Repository

1.	Accept the GitHub Classroom invitation to this repository by following the link given on BlackBoard.

1.  View your private repo here [https://github.com/noucampdotorgWD12018](https://github.com/noucampdotorgWD12018)

1.	Copy the clone URL from your new repository called ``express-<YOURACCOUNT>``.  **Make sure it's your repository**

1.	Type these commands into your *Git Bash* client:

	```
	$ cd /<DRIVE>/xampp/htdocs   
	$ git clone <URL> express
	$ cd express
	$ ls
	$ git status

	```

Check your ``htdocs`` folder.  You should have a new folder called ``express`` with some files in it.

## Part 1 – Sample Applications

Change to the ``samples`` folder using the Command Prompt.

1.  Create a ``package.json`` configuration file using:

    ```
    $ npm init
    ```

1.  Install the _express_ module:

    ```
    $ npm install express --save
    ```

1.	Examine & run the first sample program – ``app.js``:

	```
	$ node app.js

	```

	and using your web browser open [http://localhost:3000/](http://localhost:3000/).

1.	Examine & run ``app2.js``:

	```
	$ node app2.js

	```

	and using your web browser open [http://localhost:3000/mary/](http://localhost:3000/mary/).

1.	Examine & run ``app3.js``:

	```
	$ node app3.js

	```

	and using your web browser open [http://localhost:3000/who/Bob](http://localhost:3000/who/Bob) and [http://localhost:3000/who/Bob/bob.smith@lyit.ie](http://localhost:3000/who/Bob/bob.smith@lyit.ie)

1.	Examine & run ``app4.js``:

	```
	$ node app4.js

	```

	and using your web browser open [http://localhost:3000/blah](http://localhost:3000/blah).
