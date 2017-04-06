# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Web Development + Data Science Hackathon

WDI, meet DSI. DSI, WDI. Let's build some stuff.

You and your team will take a dataset and build an application (or website) that:
- visualizes the data in an interesting way
- prompts the user for inputs and make predictions based on the data
- is deployed and publically accessible

![](http://pppre.s3.amazonaws.com/2e5adf67004f3eea/5bf13f68c7e34663baf32d1e22cb4fef.jpg)

## Group Assignments:


# WDI groups FIRST DRAFT 

| Group # | DSI Students | WDI Students | Dataset |
|---------|--------------|--------------|---------|
| 1 | Carlo, Adrian, Annamaria | 'Deise', 'Sam', 'Anthony' | [Data to forecast weekly sales at Wal-Mart](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data) |
| 2 | Avneet, Dex, Adam |'Jamal', 'Jason', 'Ryan' | [Taxi Trips in NYC](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) |
| 3 | Bobby, Han, Ryan | 'Bilal', 'Axel', 'Tunde' |  [MTA's subway turnstile data](http://web.mta.info/developers/turnstile.html) |
| 4 | Aaron, Shiyang | 'Geny', 'Brian', 'Kaitlyn' | [AirBnB listings data](http://insideairbnb.com/get-the-data.html) OR [AirBnB's user session data](http://databits.io/challenges/airbnb-user-pathways-challenge) |
| 5 | Connor, Kristina, Chris |'Amanda', 'Brett' | [Uber Trips](https://github.com/fivethirtyeight/uber-tlc-foil-response) |
| 6 | Anthony, Mark, Tetyana | 'Adrian', 'Rob', 'Jackie' | [Data to forecast weekly sales at Wal-Mart](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data) |
| 7 | Sean, Sidra |'Caroline', 'Crae' , 'Sabrina'  | [Taxi Trips in NYC](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) |
| 8 | Thierry, Schmidt | 'Samantha', 'Paul', 'Joel' | [MTA's subway turnstile data](http://web.mta.info/developers/turnstile.html) |

## Approach
- Whiteboard an outline of what you want the final product to look like
- Set up a Git Organization with two repos - one for a Python server and one for a web full-stack app. Agree on a git workflow to share code
- Decide on the tools you want to use. For Python, we recommend Flask. For Web, express.
- Double check package installation. If you need any of the following, make sure they're installed: Node, Anaconda, Flask
- Build out something quick that can connect between the two apps! Start testing locally!
- Build out your MVP!
- Deploy!

## Tips for DSI Students
- Start by creating dummy outputs so your WDI team members have something to work with. For example, after reviewing your dataset if your model will output a json object with three key, value pairs, start by building a Flask app that returns a json object of 3 random values to a route. Building this **minimum viable product** and passing it along to the WDIers in the early-going will be important. As an example, please review the Flask app in the [my_flask_api](./my_flask_api/) folder.
- Only once you've built your m.v.p. and the infrastructure is in place should you get iteratively more complex (engineer your features, try different models, tune hyperparameters...)
- Discuss with your team where your predictions will route and what parameters they'll need.
- Do your data cleaning, EDA, and model tuning in a Jupyter notebook. Export the fitted model as a pickled file to save on processing time.
- It is **strongly encouraged** that your output contains a visualization.
- Deploy on AWS!

## Tips for WDI Students
- Split up the workflow.
- Make sure you have Python and dependencies installed - you should be able to run a Python Flask server locally and make calls to it.  
- Make sure your server and the Python server are running on different ports! Both need to be open locally at the same time for testing.
- Use graphing libraries! Look up Chart.js (use a CDN to require it directly into your HTML).  We haven't taught you this explicitly, but it's fairly simple and they have loads of examples.  Work with your DSI compadres to determine what type of graph fits their data the best.
- Build something that sends requests to the Python server quickly! Don't worry that the Python server is returning no data or dummy data - get it ready for when the Python route is complete.
- Deploy on Heroku! How does the connection to the Python server (on AWS) change in deployment? Can you just treat it like an external API?
