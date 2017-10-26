# TPCHBenchmark
Xcalar's TPCH Benchmark files. To run these batch dataflow files, follow these
steps:
1. Deploy a Xcalar cluster. Size it according to the SF that you want to run. If
you need help sizing your cluster, please contact support@xcalar.com or post on
our discourse at https://discourse.xcalar.com
2. Upload the batch dataflow files into your cluster
3. Parameterize the import nodes to point to where your TPCH files are located.
For example, if your files are located on s3, type
s3://yourbucketname/yourfolder/customer. If your files are located on Azure
blob storage, type azblob://yourbucket/yourpath/part
4. We recommend you start with SF=1 to ensure all datasources are accessible by
Xcalar first

Xcalar can run all TPCH queries on all Scaling Factors (1-30000)

For more information, please contact us via our discourse or via info@xcalar.com
