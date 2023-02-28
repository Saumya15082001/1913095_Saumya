# 1913095_Saumya

//This is an implementation of Apriori Algorithm

Apriori is an algorithm for frequent item set mining and association rule learning over relational databases. It proceeds by identifying the frequent individual items in the database. Here, we can provide minimum support at runtime.

### Input

The input format should be csv file in following format:

A,B <br>
A,B,C <br>
C,D <br>
B,C,D so on..

For uploading csv file, We have used following method:

df=pd.read_csv(io.BytesIO(uploaded['datasetname.csv']),header=None)

Here, enter the csv file name in the method or rename the csv file name as dataset.csv.

### Output
The output will show the most frequent itemsets from the given dataset.

Submitted by: SAUMYA
              1913095
              BTBTC19209
