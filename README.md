# databricks-notebooks
Databricks Spark notebooks (SQL, MLlib)

Here are some of the notebooks from my Databricks CE account. Posted for _reference_, and _convenience_,
otherwise I have to log into community edition every time to view them.

## Spark Core
- Investigation on saving an `EmptyRDD` vs. empty `RDD`.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/2570565789387396/4413065072037724/latest.html)

- Extended Twitter utils from Spark.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3219325578842745/4413065072037724/latest.html)

## Spark MLlib
- Classification of subset of GitHub pull requests using numeric features only.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3005916244706183/4413065072037724/latest.html)

- Extended classification of a subset of **apache/spark** pull requests, includes text and numeric features.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/2852671231283180/4413065072037724/latest.html)

- Notebook attempt to use Multilayer Perceptron Classifier on Iris dataset.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/1019862370390522/4413065072037724/latest.html)

- Notebook attempt to do collaborative filtering on test dataset.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/1723574684687027/4413065072037724/latest.html)

- One of the Databricks examples on Spark MLlib LDA - Topic Modeling (added for reference).
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3783546674231782/4413065072037724/latest.html)

- One of Databricks examples on Spark MLlib Naive Bayes (added for reference).
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3783546674231736/4413065072037724/latest.html)

## Spark SQL and Catalyst
- Custom rule to resolve `select count(*) from table`,
inspired by [SAP HANA-Vora Spark extension](https://github.com/SAP/HANAVora-Extensions).
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/505581245614988/4413065072037724/latest.html)

- How logical plan optimizations work in Catalyst. Also showcases an example of improving filter
folding rule.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/4201913720573284/4413065072037724/latest.html)

- Simple exploratory notebook for function code generation.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/477777207529411/4413065072037724/latest.html)

- Reading NetFlow files in Spark.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/1307960336794218/4413065072037724/latest.html)

- Reading GitHub pull requests in Spark.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/2852671231283150/4413065072037724/latest.html)

- Reminder notebook on saving DataFrames with `SparkSession` and creating new database.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/746590022235754/4413065072037724/latest.html)

- Reminder notebook on `StringType` to `TimestampType` conversion for DataFrames.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3696710289009770/4413065072037724/latest.html)

## Spark GraphX / GraphFrames
- Scala version of GraphFrames notebook with some slight modifications.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/3065536941249190/4413065072037724/latest.html)

- GraphX shortest paths to use edge weight.
[notebook](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3741049972324885/1494815129692969/4413065072037724/latest.html)
