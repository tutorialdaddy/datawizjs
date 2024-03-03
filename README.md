# DataWizJS

A JavaScript library for data manipulation, analysis, and visualization in machine learning and data science projects.

## Installation

Install DataWizJS with npm:

npm install datawizjs


## Usage

To use DataWizJS, import the library and call its functions:

javascript
const DataWizJS = require('datawizjs');

const data = [1, 2, 3, 4, 5];
const analysis = DataWizJS.analyze(data);
console.log(analysis);

DataWizJS.visualize(data, 'output.png').then(console.log);

## Features
Provides basic statistical analysis (mean, median, mode).
Generates box plot visualizations of data.