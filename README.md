# Description
AppReaction is a small shell utility for setting up a React web application with either Node's Express or Python's Flask library. This project was inspired by numerous failures at bundling front-end javascript with rollup, browserify, and babel. At a certain point in my development journey, I realized I wanted to set up an application without remembering docs or having to use create-react-app.

This script will install React with a Babel/Webpack configuration for bundling.

![](https://github.com/gavinbarrett/app-reaction/workflows/Node%20Build/badge.svg) ![](https://github.com/gavinbarrett/app-reaction/workflows/Python%20Build/badge.svg)

# Usage
```bash
wget https://raw.githubusercontent.com/gavinbarrett/app-reaction/master/conjure-react
```

Then run:
```bash
./conjure-react node
```
to configure a project with Node and Express. Or, run:
```bash
./conjure-react python
```
to configure a project with Python and Flask.
