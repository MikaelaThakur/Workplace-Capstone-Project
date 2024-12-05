# Workplace Capstone Project

## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

This project demonstrates the use of machine learning models for predicting sales-related metrics.

## 2. Dataset <a class="anchor" id="dataset"></a>
The dataset used for this analysis provides transactional data related to customer orders. Below is a summary of the dataset's key features:

- **Row ID**: Unique identifier for each row.
- **Order ID**: Unique identifier for each order.
- **Order Date**: The date on which the order was placed.
- **Ship Date**: The date on which the order was shipped.
- **Ship Mode**: The mode of shipping selected by the customer (e.g., Standard, Expedited).
- **Customer ID**: Unique identifier for each customer.
- **Customer Name**: Name of the customer placing the order.
- **Segment**: The customer segment (e.g., Consumer, Corporate, Home Office).
- **Country**: The customer's country of residence.
- **City**: The customer's city of residence.
- **State**: The customer's state of residence.
- **Postal Code**: The postal code associated with the customer.
- **Region**: The region to which the customer belongs (e.g., East, West, Central).
- **Product ID**: Unique identifier for the product.
- **Category**: The category of the product (e.g., Furniture, Office Supplies, Technology).
- **Sub-Category**: The sub-category of the product (e.g., Chairs, Binders, Phones).
- **Product Name**: Name of the product ordered.
- **Sales**: The sales value of the product.
- **Quantity**: The quantity of the product ordered.
- **Discount**: The discount applied to the product.
- **Profit**: The profit generated from the sale.
## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:
+ `Pandas 2.2.2` and `Numpy 1.26`
+ `Matplotlib 3.8.4`
 

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for your projects, there are many ways to do this; we've outlined one such method below. Make sure to regularly update this section. This way, anyone who clones your repository will know exactly what steps to follow to prepare the necessary environment. The instructions provided here should enable a person to clone your repo and quickly get started.

### Create the new evironment - you only need to do this once

```bash
# create the conda environment
conda create --name <env>
```

### This is how you activate the virtual environment in a terminal and install the project dependencies

```bash
# activate the virtual environment
conda activate <env>
# install the pip package
conda install pip
# install the requirements for this project
pip install -r requirements.txt
```

## 5. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Thavaagh Pillay](https://github.com/thavaagh)                                | thavaagh@gmail.com
| [Mikaela Thakur](https://github.com/MikaelaThakur)                                                 | thakur.mikaela@gmail.com

GitHub uploading and management done by Mikaela as Thavaag was unable to access from work laptop. Contribution to project was equal. 
## 6. Steps to recreate the enviroment:<a class="anchor" id="team-members"></a>

Steps to Recreate the Environment

Clone the repository:

git clone https://github.com/yourusername/crwp.git
cd crwp

Create the Conda environment:

Create a new Conda environment with Python (specify the desired version if needed):

conda create --name crwp-env python=3.x

Replace 3.x with the version of Python you need (e.g., 3.8).

Activate the environment:

conda activate crwp-env

Install dependencies:

Install the required packages from the requirements.txt file:

pip install -r requirements.txt

Verify the installation:

Ensure all packages are installed correctly by checking the installed packages:

conda list

Additional Commands

Deactivate the environment:

To deactivate the current environment, use:

conda deactivate

Remove the environment:

If you need to remove the environment:

conda remove --name crwp-env --all

    Replace crwp-env with the name of the environment you want to remove.

Troubleshooting

Common issues:

    If you encounter any issues related to package conflicts, try updating Conda:

    conda update conda

If you still face issues, you can create a new environment from scratch and install the required packages manually.

#### Additional Resources to create a README file:
- [Make a README](https://www.makeareadme.com/)
- [GitHub Docs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
- [FreeCodeCamp](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
This README file provides instructions on how to recreate the Python environment for this project using Anaconda.
Prerequisites

    Anaconda installed on your system. You can download and install it from Anaconda Distribution.
