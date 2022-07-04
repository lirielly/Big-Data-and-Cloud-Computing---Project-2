# Big-Data-and-Cloud-Computing - Project-2


## Should this be a challenge?
File EVENTS.csv.gz contains records of several events of patients collected during their stay in the ICU (Intensive Care Unit). This file, compressed, occupies 4.2 Gigabytes. You need to perform a full data analysis and learning with this data, possibly using the machine learning pipeline we studied in class. You do not need to use Apache Beam, but you are required to use a suitable tool in order to efficiently process this data. Among the tasks you will perform are:
statistical analysis and visualization of data for each patient (SUBJECT_ID). Note: one patient can have more than one hospital admission (HADM_ID).

An example of visualization graph for patient items along the time (X-axis) is shown below. Times are shown as a fraction of a day. The Y-axis shows the values of items for this patient, since the patient was admitted to hospital. Each dot color corresponds to a different item (coded as 222000, 224000 etc).
![image](https://user-images.githubusercontent.com/17788854/177191359-c2d35e1e-567a-4121-bfbd-5ebf63465bc8.png)

Predict length of stay that you can find in ICUSTAYS.csv.gz. For this task you will need to choose a window size to train your data (too many days will delay decisions about patients when the system is deployed, too few days will probably produce a very shortsighted predictor. Choose with care).
You will need auxiliary tables that I will provide later.

Use wisely the resources you learned (map-reduce, pyspark, bigquery, multiprocessing, multithreading, pipelines etc) in order to analyze this data.
You should hand in a report of your work (it can be a pdf or a commented and annotated notebook).
