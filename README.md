# EV Charging Infrastructure
This repository contains code for simulating and analyzing the charging infrastructure of electric vehicles (EVs). The code is written in Python and uses the SimPy library for discrete-event simulation.

# Installation

Clone the repository:

git clone https://github.com/jaiswalnj/EV-charging-infra.git

# Install the required packages:

pip install -r requirements.txt

# Usage

To run the simulation, execute the main.py file:

python main.py

The simulation will run for a default duration of 24 hours, but the duration can be changed by modifying the SIM_DURATION constant in the config.py file.

The simulation generates output data in CSV format. The output files are saved in the output directory. The generated files include the following:

charging_events.csv: A log of all charging events that occurred during the simulation.
charging_stations.csv: A summary of the charging station usage during the simulation.
energy_demand.csv: A log of the energy demand by EVs during the simulation.

# Contributing

Contributions are welcome! Please see the CONTRIBUTING.md file for guidelines.

# License

This project is licensed under the MIT License - see the LICENSE file for details.
