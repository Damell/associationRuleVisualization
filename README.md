# Association Rules Visualization

## Goals
  * Compute association rules from provided data
  * __Visualize those rules in a non-standard way__
  * Accessible as an online tool

## Dataset and preprocessing
  * data needs to be in CSV format
  * datasets from http://repository.seasr.org/Datasets/UCI/csv/ can be used
  * support only for nominal values and custom coded binomial values support; all other values are also handled as nominal

## Association Rules Mining
  * the Apriori algorithm used for rules mining
  * open source Apriori Algorithm implementation in JavaScript used to run in NodeJS environment

## Postprocessing
  * the Apriori.js open source project only provides confidence for rules and support for item sets
  * my custom postprocessing step computed support, lift and conviction for all rules

## Technologies
  * IBM Bluemix - for cloud NodeJS environment
  * Node-RED tool - for quick prototyping and visual data flow scaffolding
  * D3.js - for creating visualizations in the browser
  * Apriori.js - for extracting rules from a dataset

## Solution URLs
  * UI - http://association-rules.eu-gb.mybluemix.net/ui/
  * Node RED - http://association-rules.eu-gb.mybluemix.net/red/#
  * Presentation - https://docs.google.com/presentation/d/1nK3FydLWRTjP_7R4pVElk4-Mz3RkiRV60EyYw7cR-iY/pub?start=false&loop=false

## Sources
  * https://console.ng.bluemix.net/
  * http://nodered.org/
  * https://d3js.org/
  * https://github.com/seratch/apriori.js
  * https://en.wikipedia.org/wiki/Association_rule_learning
  * https://en.wikipedia.org/wiki/Apriori_algorithm
