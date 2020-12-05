# Ad Auris Audio Widget

Audio widget for Ad-Auris customers. This customized solution is full stack with key data analytics.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.txt.

```bash
Follow instructions dependending on what hosting service, python version, and etc.

Heroku and Python 3.8 recommended.

```
## Development - Production

Instructions for running the app locally and in production


Follow instructions dependending on what hosting service, python version, and etc.

Heroku and Python 3.8 recommended.
Ensure that app.debug = False for production and app.debug = True during local development

```bash    
    app.debug = True
    Can delete the bottom 3 lines here for local development
    from waitress import serve
    port = int(os.environ.get('PORT')
    waitress.serve(app, port=port)

    Use this command to run app locally:
    *flask run*
```


## Contents

```python


Audio Player
Backend that serves the necessary audio files
Google Tag Manager and Google Analytics Integration (Outside of this package)
```

## Contributing
Pull requests are welcome by the Ad-Auris Dev Team. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)