# ETL Pipeline

This repository presents an ETL (Extract, Transform, Load) pipeline implemented in Python using Jupyter Notebook on IBM Skills Network Lab. The pipeline demonstrates the processing of two JSON files containing market capitalization data and a CSV file containing currency exchange rates. It performs various transformations, including converting the data from USD to GBP using the provided exchange rate and rounding the values, before storing the results in a new CSV file.

## Project Structure

- `ETL_Engineer_Peer_Review_Assignment_BAL.ipynb`: Is a Jupyter notebook containing the code for the entire ETL process.
- The Root folder: Contains the notebook and an MIT License.
- The input and output data used in the ETL process can be found in the notebook.

## Running the Pipeline

To execute the ETL pipeline, follow the steps below:

1. Clone this repository to your local machine.
2. Ensure that you have Jupyter Notebook installed.
3. Open Jupyter Notebook and navigate to the cloned repository.
4. Open the `ETL_Engineer_Peer_Review_Assignment_BAL.ipynb` notebook.
5. Run the notebook cells to execute the ETL pipeline.

## Pipeline Phases

### Extraction

The pipeline begins by extracting data from a JSON file and a CSV file using the pandas library.

### Transformation

During the Transformation phase, the pipeline applies several operations:

- Conversion of market capitalization data from USD to GBP using the exchange rate provided in the CSV file.
- Rounding the converted market capitalization values to three (3) decimal places.
- Renaming a specific column.

### Loading

In the Loading phase, the pipeline writes the transformed data into a new CSV file.

## Logging

The ETL process is logged via messages for each step of the process.

Please feel free to explore the notebook and modify it to suit your specific requirements. If you encounter any issues or have any questions, do not hesitate to reach out. Enjoy working with the ETL pipeline!
