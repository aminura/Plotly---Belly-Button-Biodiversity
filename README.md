Belly Button Biodiversity
![GitHub Logo](/Users/arunima_menon/Desktop/Plotly---Belly-Button-Biodiversity/bacteria_by_filterforgedotcom.jpg)
Format: ![Alt Text](url)

In this assignment, I built an interactive dashboard to explore the Belly Button Biodiversity DataSet.

Step 1 - Plotly.js
Used Plotly.js to build an interactive charts for the dashboard.

Created a PIE chart that used data from samples route (/samples/<sample>) to display the top 10 samples.

Used sample_values as the values for the PIE chart

Used otu_ids as the labels for the pie chart

Used otu_labels as the hovertext for the chart

PIE Chart

Created a Bubble Chart that used data from samples route (/samples/<sample>) to display each sample.

Used otu_ids for the x values

Used sample_values for the y values

Used sample_values for the marker size

Used otu_ids for the marker colors

Used otu_labels for the text values

Bubble Chart

Displayed the sample metadata from the route /metadata/<sample>

Displayed each key/value pair from the metadata JSON object somewhere on the page
Updated all of the plots any time that a new sample is selected.

Example Dashboard Page Example Dashboard Page

Step 2 - Heroku
Deployed Flask app to Heroku here: https://sleepy-scrubland-93985.herokuapp.com/

Used sqlite file for the database.
Advanced Challenge Assignment (Optional)
The following task is completely optional and is very advanced.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the Weekly Washing Frequency obtained from the route /wfreq/<sample>

You will need to modify the example gauge code to account for values ranging from 0 - 9.

Update the chart whenever a new sample is selected

Weekly Washing Frequency Gauge

Flask API
Use Flask API starter code to serve the data needed for your plots.

Test your routes by visiting each one in the browser.
Hints
Don't forget to pip install -r requirements.txt before you start your server.

Use console.log inside of your JavaScript code to see what your data looks like at each step.

Refer to the Plotly.js Documentation when building the plots.

