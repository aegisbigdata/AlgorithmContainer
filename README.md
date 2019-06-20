# Algorithm Execution Container
Algorithm Container for Jupyter and Zeppelin Notebooks


# Jupyter Version #
# Set-up and run instructions

1. Download the '.ipynb' file from the current repository and import it in Jupyter.

2. Open the downloaded 'AEC notebook'. Select and run the first paragraph of the notebook. An initialisation button (labelled 'Initialise') should appear as an output of the paragraph's execution.

3. Press the initialisation button and wait for the following paragraphs to run. You can monitor the kernel state shown in the upper right part of the notebook to know when the execution is finished.

4. Once all paragraphs have finished running, you should see the main AEC UI, which includes five tabs.

5. From the 'Input File' tab select the Dataset and then the file that contains the data to be used in the analysis. You may also select the appropriate separator, as AEC only works with delimited files (csv). 

6. From the 'Algorithm Selection & Configuration' tab select the algorithm family and then the specific algorithm you want to apply. Once an algorithm is selected, a configuration form will appear. Configure all algorithm parameters here before proceeding.

7. From the 'Output File; tab select the Dataset and choose a name for the folder where the analysis results should be saved. 

8. From the 'Overview' tab you can have a quick view of the current selections across the previous three tabs. If everything looks ok, press the 'Execute' button and wait for the algorithm to be applied. Once the analysis is finished, results will appear in this tab.

9. From the 'Model Analyis' tab you can re-run a classification or a regression based on the model just created


# Zeppelin Version - deprecated #
# Set-up and run instructions

1. In the AEGIS Data Store `Project Datasets`, locate the dataset to be used, `select` it and `copy its hdfs path` (upper right corner)

2. Invoke the Container by choosing `Analytics` on the right sidebar. If Anaconda is not enabled, choose to enable it and wait until all installation scripts are performed

3. Create a Zeppelin notebook by

3. Copy the dataset's dhfs URL into the field `Set Dataset path`

4. Select the `Separator`

4. Select the desired `Analysis Type` and then the actual `Algorithm`

5. Trim the algorithm's `configuration parameters` as needed

6. `Run` the Analysis

7. You may view the analysis results in the predefined Zeppelin visualisation charts. Also the results of the analysis are stored back in the AEGIS Data Store in your project's folder


