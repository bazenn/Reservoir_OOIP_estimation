# Reservoir OOIP Estimation Project

This is a repo of my data science project where I estimate the original oil in place (OOIP) of a reservoir using different methods. The OOIP is the total amount of oil that is initially contained in a reservoir before any production or injection operations. Estimating the OOIP is an important task for reservoir engineers and managers, as it helps them plan and optimize the development and production of the reservoir.

## Data Science Skills

In this project, I demonstrate various data science skills and techniques, such as:

- Data collection and preparation: I use Python, pandas, and numpy to read, manipulate, and explore the Excel files that contain the reservoir parameters and measurements. I also evaluate the dataset for completeness and accuracy, and identify potential biases or errors in the data.
- Data analysis and modeling: I use matplotlib and seaborn to visualize the data, and apply the right statistical techniques and machine learning models for the data to answer the research questions. I use Monte Carlo simulation to generate random and uniform samples for the uncertain parameters, and calculate the OOIP distribution and statistics for each sample using the volumetric method. I also use the material balance equation (MBE) to derive a relationship between the OOIP and the reservoir pressure, and solve the equation for a given pressure value.
- Data communication and presentation: I support my analysis with clear and informative visualizations, such as histograms, boxplots, scatterplots, and line plots. I also summarize the main takeaways and insights from my project, and explain the assumptions and limitations of the methods I used.

## Data

The data for this project are stored in Excel files that contain various parameters and measurements of the reservoir, such as porosity, permeability, pressure, oil saturation, and oil formation volume factor. The Excel files are the dataset reading by the projects. The data are real and from Canada Alberta oil field.

## Methods

In this project, I use three different methods to estimate the OOIP of the reservoir:

- Monte Carlo simulation with random sampling: This method involves generating random values for the uncertain parameters of the reservoir, such as porosity and oil saturation, and calculating the OOIP for each sample using the volumetric method. The OOIP distribution and statistics are then obtained from the sample results.
- Monte Carlo simulation with uniform sampling: This method is similar to the random sampling method, except that the values for the uncertain parameters are generated from a uniform distribution within a specified range, rather than from their original distributions. This allows for a more robust and conservative estimation of the OOIP.
- Material balance equation (MBE): This method involves using the pressure and production data of the reservoir to derive a relationship between the OOIP and the reservoir pressure, known as the material balance equation. The OOIP can then be estimated by solving the equation for a given pressure value.

## How to Run the Code

To run the code for this project, you need to have Python and Jupyter Notebook installed on your machine. After installing Python and Jupyter Notebook, you need to install the required libraries for this project, such as numpy, pandas, matplotlib, and scipy. 

Once you have the libraries installed, you need to download the Excel files and the Jupyter Notebook files from this repo and save them in the same folder. There are three different Jupyter Notebook files for each method:

- Reservoir estimation (Monte Carlo Random).ipynb
- Reservoir estimation (Monte Carlo Uniform).ipynb
- Calculation of Original Oil In Place by Using MBE.ipynb

You can open any of these files in Jupyter Notebook and run the code cells to see the results and plots. You can also modify the code and the data as you wish.
