# Dataset for Fire Detection Campaign

This repository contains the datasets from three experiments carried out during a fire detection campaign.

## 1. INIA Experiment

The INIA experiment includes a folder named **"Data_per_day_2"**, which contains Excel files organized by day. Each file stores the data collected by the installed sensor.

Due to the large size of the dataset, the files are divided into four compressed subfolders (.zip).

## 2. Ávila Experiment

The Ávila experiment includes an Excel file named **"Medidas_Avila"**.
This file contains two sheets, one for each installed device:

* MOX02
* MOX03

## 3. Encinedo Experiment

The Encinedo experiment includes an Excel file named **"MedidasTruchas"**.
This file contains four sheets, corresponding to the four devices used in the experiment:

* MOX01
* MOX02
* MOX03
* MOX04

## Data Structure

All Excel files share the same variable distribution and structure.
Each column corresponds to a variable measured by a sensor.

The naming convention used is:

**variable_name (sensor_name)**

For example:

* **rs1 (ENS160)**

Where:

* **rs1** represents the variable
* **ENS160** indicates the sensor used to obtain that measurement

This consistent structure facilitates data analysis and comparison across experiments.

## Notes

* All datasets are provided in Excel format (.xlsx).
* Each sheet corresponds to measurements recorded by a specific device.

## Author

Cristina Brugera
