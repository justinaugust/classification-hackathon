# Friday Afternoon HACKATHON!
![HACK THE PLANET](https://media.giphy.com/media/14kdiJUblbWBXy/source.gif)

## This data comes from a [Kaggle Competition sponsored by StumbleUpon](https://www.kaggle.com/c/stumbleupon)
*It is located in `data/` and is in tab-separated format. Some cleaning may need to be done.*

### The goal is to classify URLs/Webpages as <span style="color:green">Evergreen</span> or old, outdated and janky
*(1 / 0 in `label`)*
### Where would this be useful?

You are a data scientist working for a company developing a product that suggests other websites to visit based on the webpage they are currently visiting. They take submissions and pay out money to those websites that people click through and visit.

***HOWEVER*** content creators have figured out a way to game the system. They're flooding the website submission form with all of their content. Even some that's already outdated, old and janky. No one will click on that! They want <span style="color:green">Evergreen</span> webpages! And if your company does suggest outdated, old and janky content then no one will want to use your technology and your startup will fold and your stock options will be worthless.

***YOUR JOB*** is to create a model that classifies new URL submissions as <span style="color:green">Evergreen</span> or outdated, old and janky. You've been given a dataset with labels (in the column `label`) - <span style="color:green">Evergreen</span> is `1`, outdated, old and janky is `0`. There are many features, all of which can be used to predict this.

***Important*** The metric of choice here should minimize False Positives. Serving a webpage that is outdated, old and janky instead of <span style="color:green">Evergreen</span> will be extremely bad for your company's bottom line.