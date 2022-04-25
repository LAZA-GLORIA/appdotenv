Write a small Node.js application that will just display this message : I am <name>, wilder in <city>, and I love <language>.

The values <name>, <city> and <language> must be replaced by those of the environment variables MY_NAME, MY_CITY and MY_LANGUAGE.

These variables must be loaded from an .env file via the dotenv package.

In order not to share it, write a "template". .env.sample It must indicate the different key-value pairs to be entered in the.env with dummy values.

This will allow a developer using your application to recreate a .env file with the right values.

Share your solution on a Gist containing :

The JavaScript code
The .env.sample file contents
The .gitignore file contents
