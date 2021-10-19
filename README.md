# TSummarizer

An Online summarization tool built using Python and nltk. User can summarize their text data.

## Link

```bash
https://tsummarizer.herokuapp.com/
```

## Usage

User need to enter their text data into the "TEXTAREA" given on the homepage and then submit it. Submt button will take you to the new page "OUTPUT" where you will get the summarized text of your input data

## Deploying it on HEROKU

* First make a requirements.txt file in your project folder
* This can be done using pip freeze(but it will list out all the libraries installed in your environment
* So we can also user pipreqs(this will only list the libraries need for your current app) 
```bash
install pipreqs
pipreqs .
```
* Now we have a requirements.txt file of our project we need to add a Procfile(only need for heroku)
* After that we need make a github repository of our project with all these files
* Then, on heroku make a new app and link that with github and just deploy.
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
