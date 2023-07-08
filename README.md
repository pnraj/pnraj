
<!--
**pnraj/pnraj** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
### ABOUT ME
I am An Aspiring Data Engineer With <strong>Strong</strong> Problem-Solving Aptitude For Designing Efficient Data Pipelines, Optimize Query Performance and Create <strong>Robust</strong> Data Models. Driven by a passion for delivering <strong>high-quality</strong> data solutions, while learning new emerging trends and technologies in the field of data engineering. I am enthusiastic about leveraging my skills to contribute to the success of <strong>data-driven</strong> initiatives and make a <strong>meaningful</strong> impact.
<hr></hr>
<h3 align="left">LANGUAGE AND TOOLS</h3>
<p align="left"> <a href="https://aws.amazon.com/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-ar21.svg" alt="AWS" width="80" height="40"/>
    </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://hadoop.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hadoop/apache_hadoop-icon.svg" alt="hadoop" width="40" height="40"/> </a> <a href="https://spark.apache.org/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/apache_spark/apache_spark-ar21.svg" alt="Spark" width="80" height="40"/>
    </a>
    <a href="https://databricks.com/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/databricks/databricks-ar21.svg" alt="Databricks" width="80" height="40"/>
    </a>
    <a href="https://airflow.apache.org/" target="_blank" rel="noreferrer">
      <img src="https://static-00.iconduck.com/assets.00/airflow-icon-512x512-tpr318yf.png" alt="Airflow" width="40" height="40"/>
    </a>
<a href="https://kafka.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="kafka" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a>
<a href="https://www.streamlit.io/" target="_blank" rel="noreferrer">
      <img src="https://streamlit.io/images/brand/streamlit-logo-primary-colormark-darktext.png" alt="streamlit" width="40" height="40" />
    </a>
    <a href="https://plotly.com/" target="_blank" rel="noreferrer">
      <img src="https://res.cloudinary.com/crunchbase-production/image/upload/c_lpad,f_auto,q_auto:eco,dpr_1/vgay5hqdvszlmvud3hwu" alt="plotly" width="40" height="40" />
    </a>
    <a href="https://powerbi.microsoft.com/" target="_blank" rel="noreferrer">
      <img src="https://w3skillset.com/wp-content/uploads/2021/09/PowerBI-Logo.png" alt="Power BI" width="40" height="40" />
    </a>
</p>
<hr></hr>
<h3 align="left">PROJECTS</h3>

[API TO RDS USING LAMBDA WITH SLACK ERROR MONITORING](https://github.com/pnraj/Projects/tree/master/AWS%3A%20Bulk%20%26%20Near%20Real-Time%20Pipelines/API%20TO%20RDS%20USING%20LAMBDA%20WITH%20SLACK%20ERROR%20MONITORING)

<p align="center">
  <img src="https://github.com/pnraj/Projects/assets/29162796/fe89c91f-a1ab-46e9-b589-4e9ef1bafa5a" alt="Project WorkFlow" width="690" height="390">
</p>

- Using _**AWS Lambda**_ Api is fetched from a link, processed and load into _**AWS RDS**_ with **15 seconds** Interval
- Two Lambda functions are used in these Pipeline where **First lambda** will be invoked by **Aws Step-Function** which is invoked by **Cloudwatch / EventBridge Rules**. For Every _One minute_ until the Rule gets disabled.
- **Second Lambda** Function is used to fetch Api and Loaded into AWS RDS.
- **Aws Step-Function** is Working Based _ASL(Amazon State Language)_ which is based on _Json_ file Structure
- If any _error or Database connction_ problem occurs notification is sent to **slack channel** using _slack_sdk_
- All internal Connections between AWS services are based on _**IAM Role and Policies**_.

[SPARK-ENABLED EXTRACTION AND LOADING INTO AWS RDS](https://github.com/pnraj/Projects/tree/master/AWS%3A%20Bulk%20%26%20Near%20Real-Time%20Pipelines/Spark-Enabled%20Extraction%20and%20Loading%20Into%20AWS%20RDS)

<p align="center">
  <img src="https://github.com/pnraj/Projects/assets/29162796/f6e07a28-dce6-4fb2-8795-ddb8f46b16b8" alt="Project WorkFlow" width="690" height="390">
 </p>
 
- There are **Two Part** in these Project.\n
- **Part1** is Getting Data from **SEC.gov**(**Zip** format) contains more than _8.5 lakh_ **Json files** around **6gb** after _uncompressing_.
- By Using _**Apache Spark(PySpark)**_ and _DataBricks_, Json files are converted into **Pyspark DataFrames** with _Each_ json File representing _single row_ in DataFrame.The _DataFrame_ is later converted into _Json file_ and uploaded into **AWS S3**.
- **Part2** is Getting Data from AWS S3, Do the Needed Transformation and upload into _**AWS RDS-Mysql Instance**_
- The Data From S3 is Converted into _PySpark DataFrame_ and Isolate needed Columns that needed to uplaoded into RDS
- Important Function Used for Transformation are _**join, posexplode_outer, udf, concat, to_date, struct and Row.**_

[YouTube Data Harvesting and Warehousing](https://github.com/pnraj/Projects/tree/master/YouTube_Data_Harvesting_and_Warehousing)

<p align="center">
  <img src="https://github.com/pnraj/Projects/assets/29162796/72ee83a0-501d-4fae-b474-bd42fb49e101" alt="Project WorkFlow" width="690" height="390">
 </p>


- Ability to input a **YouTube channel ID** and retrieve all the relevant data using **Google API**.
- Option to store the data in a **MongoDB database** as a _Data Lake_.
- Ability to collect data for up to 10 different YouTube channels and store them in the data lake based upon user Requirment.
- Option to select a _channel name_ and migrate its data from the data lake to a **Mysql(SQL) Database** as tables.
- Ability to search and retrieve data from the SQL database using different search options, including joining tables to get channel details.

[PhonePe Pulse Data Analysis 2018-2022](https://github.com/pnraj/Projects/tree/master/Phonephe_Pulse)

<p align="center">
  <img src="https://github.com/pnraj/Projects/assets/29162796/b97ce7b9-634a-4612-bef7-77369b4a89c6" alt="Phonepe" width="690" height="390">
</p>

- Getting the _**PhonePe Payment App-Data**_ in **Json format** from **Github** repo 
- The _Json files_ are separated for every _**3 Month / 1 Quarter**_ of years from **2018-2022** for every _states and districts_ in **India**.
- Using _Python_ **os module**, Pipeline is Built to **Iterate** to each folder and get data from _json file_ and convert into _**pandas DataFrame**_.
- Json Files Contains Details about _**Amount of Transactions**_ and _**Transaction Location**_ where Users Do that Transaction.
- Using The DataFrame, **Visualization** are made using **Plotly and Streamlit** on _Geo, Bar, line, Pie, Area_ chart are included.

[Twitter Scraping](https://github.com/pnraj/Twitter_scraping)

<p align="center">
  <img src="https://github.com/pnraj/Projects/assets/29162796/0266df32-e6db-4f80-b5a2-83da20db0c45" alt="Twitter scaping" width="690" height="390">
</p>

- Based on User needs **Twitter** _Tweets_ are **Extracted and Uploaded** into **Mongodb** using UI based upon **Streamlite** based app
- Users have to enter **Tweets topic or hashtag**, **Starting Date**, **Ending Date**, **Total Number of Tweets** needed to extracted in app and 
- App will _fetch_ the data by using **Snscrape** and convert the data into **Pandas DataFrame** and displayed as _Tabular Format_.
- After Checking the data users can have options to download the data as _**json**_, _**csv**_ or can be _**uploaded into Mongodb**_.


<h3 align="left">Profile Stats:</h3>
<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=pnraj&show_icons=true&locale=en" alt="pnraj" /> <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=pnraj&" alt="pnraj" /></p>
