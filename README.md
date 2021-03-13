# womensinternetfreedom.github.io
Women's Internet Freedom Static Site

The website is built using [Nikola](https://getnikola.com/) static site generator. [Jinja](https://jinja.palletsprojects.com/en/2.11.x/) template style is used.

# How to run the site

## Virtual environment
 Create a Python virtual environment if you haven't already.
 
 1. Create a new environment: `python3 -m venv venv`
 2. Activate it: `source venv/bin/activate`
 3. Install requirements: `pip install -r requirements.txt`
 
## Building and serving in dev-mode

 1. Go to the Nikola website directory: `cd wifa` 
 1. Build the static output: `nikola build`
 2. Serve the website using development server: `nikola serve`
 4. Go to your browser and navigate to the address the terminal has shown.
 
## Adding new pages

For the purpose of this website, it is the easiest to add your page's HTMLs to `wifa/pages` directory.
It's a good idea to have `<title>` and `<meta name="description" content="..." />` tags filled in.
