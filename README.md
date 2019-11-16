# Fannie Mae Loan Project
 
## How far away we are from the next credit crisis? 
#### Exploring a decade-long single-family loan from Fannie Mae

It’s been more than 10 years since the 2008 American Subprime Mortgage crisis during which millions of Americans lost their homes, their jobs, or both. Following the collapse of Lehman Brothers, the S&P 500 fell by 28 percent in the 22 trading days. The unemployment rate jumped from 6.1 percent in August 2008 to 9.5 percent two years later in August 2010. 

Many more regulations have been put in place to increase oversight with the hope of preventing or at least lowering the possibility of next alike credit crisis. For instance, the Dodd-Frank financial reform created entities such as the Consumer Financial Protection Bureau (CFPB) and put in place new regulations and tools for banking supervision and oversight by entities such as FDIC.

However, financial crises are sometimes inevitable.

***“Regardless of improvements in law and regulation, every financial system is vulnerable to a possible crisis. Throughout history, financial crises have emerged from many types of assets, from Dutch tulips to US subprime mortgages.”*** ---Aaron Klein, a fellow at the Brookings Institution

While there are many articles and experts discussing the coming of the next financial crisis, like [this one](https://www.vox.com/2018/9/18/17868074/financial-crisis-dodd-frank-lehman-brothers-recession) which provide us a lot of insights into the core of the financial crisis, in this project, I would like to take a data analysis approach to this topic. In the following I will introduce the data, followed by data cleaning, some exploratory data analysis and proposal for deeper investigation.

## Data:

Fannie Single family loan data, which is avaliable [here](https://www.fanniemae.com/portal/funding-the-market/data/loan-performance-data.html). The data records loans that are acquired by Fannie Mae from 2000 to 2018 at a quarterly basis. It contains both static infomation of loans and their later performance like forceclosure status. The originial files don't include headers. You can find headers info [here](https://loanperformancedata.fanniemae.com/lppub-docs/FNMA_SF_Loan_Performance_File_layout.pdf). If you are not familiar with the terminology, you may find the glossory very helpful, [glossory](https://loanperformancedata.fanniemae.com/lppub-docs/FNMA_SF_Loan_Performance_Glossary.pdf)

After unziped, the data is 190.35 GB. The size of the data imposes computational challenge for analysis but I have addressed it with some ad hoc method which I will discuss later.  

## Data Cleanning!

As always, in dealing with real world data, the first step is to clean up the data. While the single family loan data published by Fannie Mae is relatively clean reading and combining all the files together are time-consuming. Ideally, I would like to read in all the acquisition file then combine them into a single file and do the same thing to performance data. However, the data (especially the performance data) is so huge that this is simply not doable on my computer. So I clean and combine them piece by piece. 

## Exploratory Data Analysis
see the code in the Jupyter Notebook

## Machine Learning to predict Loan Default
see the code in the Jupyter Notebook
