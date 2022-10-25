# CovidPredictor
Predict Covid-19 spread using GNNs

# Relevant Projects/Frameworks to start off
- http://snap.stanford.edu/
- https://github.com/snap-stanford/graphgym (library for designing and evaluating GNNs which was done with snap)

# Timeplan
- Collect data and build a graph our of it: 25.11.2022
- Build a GNN and train it for predicting new Covid-19 data: 20.12.2022
- Maybe visualize the graph with some framework (still open what to do here): 20.01.2023

# Project Description / Thoughts / Ideas
So far Covid-19 data on https://github.com/CSSEGISandData/COVID-19 and https://health.google.com/covid-19/open-data/
available. Data shows which country/state has e.g. how many deaths (also as time-series data). Still unsure how I know
how to connect different countries/states/cities in a graph (any data for that available?).

For building a graph I would say each node represents a state/country with features like e.g. deaths. Countries are connected to each other.
Builded graph is input for GNN.

How does my training data would look like?
Maybe pairs of Graphs like G_t1 and G_t2 for different time points?
