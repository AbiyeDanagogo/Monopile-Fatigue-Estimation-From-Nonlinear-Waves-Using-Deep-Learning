# Monopile-Fatigue-Estimation-From-Nonlinear-Waves-Using-Deep-Learning

This is project 2 of the Hackathon in AI for Sustainability organised by the University of Hull Computer Science Department and Energy and Environment Institute.

This project is based around the development of a machine learning model (meta-model) to predict the damage fraction (D) of an example offshore wind turbine monopile. Here, the damage fraction defines the amount of damage (loss of structural integrity) the monopile incurs over a give period (1-hour) and is dependent of the following 'environmental' or 'metocean' (wind and wave) variables:

- Significant wave height, Hs (m)
- Peak wave period, Tp (s)
- Mean hub height wind speed, Uw (m/s)
- Operational state of the turbine, State (-); whereby '1' is an operational turbine, '2' is a parked turbine.

The aim of this project is to:

- Benchmark the performance of a variety of different neural networks (e.g. recurrent neural networks, transformer networks, convolutional neural networks) to establish which family of deep learning model is the most suitable to this task and project
- Evaluate whether a reliable meta-model can be developed by using fewer inputs data points (i.e. randomly selecting less training data).

Finally, a third dataset is available for testing the model. 13 additional damage fraction values have been numerically simulated based on 'data lumping' methods (introduced in project overview presentation) - these can be used to provide a secondary validation of any meta-models by comparing the model outputs for these loading case inputs, and the model predicted damage fraction value.

