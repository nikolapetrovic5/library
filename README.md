# Library analysis

Books are being checked out and then returned late way too often.
This project will analyze library data in order to build model,
to predict likelihood of a late return of any book at checkout time.

Books are considered late if they are not returned within 28 days of checkout.

## The analysis process consist of the following:
* Read raw data.
* Spot and resolve irregularities (data cleaning).
* Merge data into single table.
* Do analysis.

## Prerequisites:
* Python 3 (3.10.4 is used for the development).
* Visual Studio Code.
* Jupyter extension (VS Code).
* Python Debugger (VS Code).
* Python extension (VS Code).
* Pylance (VS Code).

## Usage

First step is to update 'source_dir' parameter in dev_config.yaml file.
This parameter holds path to directory where your source data lays.

![alt text](config_yaml_img.png)

Next step will be to press button 'Run All' and wait for results to show up,
at very bottom of the notebook.

![alt text](run_all_notebook_img.png)

If any error appears, restart kernel and press button 'Run All' again.

![alt text](restart_kernel_img.png)