**Assignment 1
**
assignment1/
│
├── classes/
├── D184MB/                # Project Gutenberg dataset (.txt files)
├── path/
├── src/
│
├── input.txt
├── output_q7.txt
├── test.txt
│
├── q10_spark.py           # Metadata extraction & analysis
├── q11_spark.py           # TF-IDF & similarity
├── q12_spark.py           # Author influence network
│
└── WordCount.jar

**Environment Setup**

Activate virtual environment:
source venv/bin/activate


**Check Spark installation:**
spark-submit --version

**Run Question 10:**
spark-submit q10_spark.py


**Run Question 11:**
spark-submit q11_spark.py

**
Run Question 12:
**
spark-submit q12_spark.py

**Dataset Location
**
All book files are stored in:
assignment1/D184MB/


**The Spark scripts load data using:**
D184MB/*.txt

**Platform**
macOS
Python (venv)
Apache Spark 4.x
PySpark

