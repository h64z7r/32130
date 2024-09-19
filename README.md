java c
32130 
Assessment Task 2: Data exploration and preparation
Task details 
This assessment will give you prac!cal experience in data visualisation, explora!on, and prepara!on (preprocessing and transforma!on) for data analytics. This assignment is individual work. Each of you will be working with an individual dataset that you can download from the link below.
Objectives: 
This assessment task addresses the following subject learning objec!ves (SLOs): 2  4
This assessment task contributes to the development of the following Course Intended Learning Outcomes (CILOs): D.1
Scenario 
Nowadays, the Internet of Things (IoT) concept plays a pivotal role in society and brings new capabilities to different industries. The number of IoT solu!ons in areas such as transportation and healthcare is increasing and new services are under development. In the last decade, society has experienced a drastic increase in IoT connections. In fact, IoT connections will increase in the next few years across different areas. Conversely, several challenges still need to be faced to enable secure operations. Thus, efforts have been made to produce datasets composed of attacks against IoT devices. The main goal of this project is to foster the development of security analytics applications in real IoT operations.
In this task, the Head of the Analytics Unit asks you to use the collected dataset to do a 3-class (Mirai-greip_flood, Recon-OSScan, DictionaryBruteForce) intrusion type classification to help understand the behavior. of attacks. As you will see, this dataset is highly complicated and includes a lot of features that make this problem more challenging.
Your tasks include:
understanding the specifics of the dataset;
extracting informa!on about each of the attributes, possible associa!ons between them, and any other specifics of the dataset.
The tasks in the assignment are specified below.
Datasets 
For this dataset, you only have the attribute headings (here ) and a paper created a large version of this dataset sensors-23-05941-v2.pdf . Each student is assigned an individual table with the actual values of these attributes. You will find your individual dataset in the link below. Your dataset is the one with your student ID in the file name.
Individual Student Datasets: Student Datasets
Tasks 
1A. Initial data exploration 
1. Identify the attribute type of each attribute in your dataset. If it's not clear, you may need to justify why you chose the type.
2. For each attribute, conduct below studies for each of them: Identify the values of the summarising properties for the attributes, including frequency, location and spread (e.g. value ranges of the attributes, frequency of values, distributions, medians, means, variances, percentiles, etc. - the statistics that have been covered in the lectures and materials given). Note that not all of these summary statistics will make sense for all the attribute types, so use your judgement! Where necessary, use proper visualisa!ons for the corresponding sta!s!cs.
3. Using KNIME or Python, explore mul!ple attributes rela!onship of your dataset, and identify any outliers, clusters of similar instances, "interes!ng" attribu代 写32130 Assessment Task 2: Data exploration and preparationPython
代做程序编程语言tes and specific values of those attributes. Note that you may need to 'temporarily' recode attributes to numeric or from numeric to nominal. The report should include the corresponding snapshots from the tools and an explanation of what has been identified there.
Present your findings in the assignment report.
1B. Data preprocessing 
Perform. each of the following data prepara!on tasks (each task applies to the original data) using your choice of tool:
1. Use the following binning techniques to smooth the values of the following two attributes:
- Protocol Type
- Duration
For each attribute, you must apply:
I. Equi-width binning
II. Equi-depth binning
In the assignment report, for each of these techniques, you need to illustrate your steps. In your Excel workbook file place the results in separate columns in the corresponding spreadsheet. Use your judgement in choosing the appropriate number of bins - and justify this in the report.
2. Use the following techniques to normalise the following attribute:
- Weight
For this attribute, you must apply:
I. min-max normalization to transform. the values onto the range [0.0-1.0].
II. z-score normalization to transform. the values.
The assignment report provides an explanation of each of the applied techniques. In your Excel workbook file place the results in separate columns in the corresponding spreadsheet.
3. Discretise the flow_dura"on attribute into the following categories:
Small [0 -1]
Medium (1 — 10,000)
Large [10,000 - inf)
Provide the frequency of each category in your dataset.
Your assignment report should provide an explanation of each of the applied techniques. In your Excel workbook file place the results in a separate column in the corresponding spreadsheet.
4. Binarise the Header_Length variable [with values "0" or "1"].
Your assignment report should provide an explanation of the applied binarisation technique. In your Excel workbook file place the results in separate columns in the corresponding spreadsheet.
1C. Summary 
At the end of the report include a summary sec!on in which you summarise your findings. The summary is not a narrative of what you have done, but a condensed informative section of what you have found about the data that you should report to the Head of the Analytics Unit. The summary may include the most important findings (specific characteristics (or values) of some attributes, important informa!on about the distributions, some clusters identified visually that you propose to examine, associa!ons found that should be inves!gated more rigorously, etc.).
Deliverables 
The deliverables are:
A report, for which the structure should follow the tasks of the assignment, and
An Excel workbook file with individual spreadsheets for each task (spreadsheets should be labelled according to the task names, for example, "1A"). Each of the results of parts (a) to (d) in task 1B should be presented in a separate sheet (and respec!vely table in the assignment report).
In the report, include a section (starting with a section title) for each of the tasks in the assignment.










         
加QQ：99515681  WX：codinghelp
