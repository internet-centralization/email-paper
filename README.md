
# Email Centralization Artifacts

In this repository we provide the dataset collected and used in the paper: "**Examining the Centralization of Email Industry: A Landscape Analysis for IPv4 and IPv6**".

*Abstract*: Centralization of key Internet services, including email, can result in privacy and security concerns and increase the number of single points of failure. This paper measures and analyzes a large-scale dataset of email providers gathered from MX records of top-level domains. The findings reveal the concentration of email infrastructure providers for each TLD and identify the most significant providers in the market. The paper also demonstrates that the IPv6 adoption increased the centralization of email servers. The research contributes to the state-of-the-art by thoroughly examining email infrastructure centralization and identifying potential areas for future research.

We also provide enrichment datasets and scripts for dataset enrichment.

[Dataset available here:](https://github.com/internet-centralization/email-paper/)

## Dataset files

The dataset files are available in Parquet format. The .parquet file is a columnar data storage format in columns that are highly efficient in terms of storage and processing. These files are used to store large sets of data, mainly in big data and data analysis.

If you have a dataset in .parquet format, you can work with it in several programming languages, including Python, R and Java. To work with .parquet files in Python, you can use the PySpark library, which is a Python frontend to Apache Spark.

To start working with PySpark, you need to install both Spark and PySpark on your machine. The easiest way to do this is to download a pre-compiled version of Spark from the official Apache Spark website and unzip it into a folder on your machine. You can find the latest version of Spark at https://spark.apache.org/downloads.html.

Nós fornecemos os scripts PySpark para enriquecimento do dataset.
