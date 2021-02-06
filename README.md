# Capstone Project - Loan Classification

## Background
Peer to peer lending, or P2P lending, has been around for more than a decade. Loans are made out to a variety of borrowers by individuals through online platforms. It has seen a huge surge in take-ups in the past years, as P2P lending bloomed into a multi-billion industry. Such form of lending removes the traditional players, which are the banks, from equation. In Singapore, there are platforms such as:

* CoAssets
* Minterest
* Seedin
* Funding Societies
* Capital Match
* Moolah Sense
* Validus

P2P lending is considered a high risk product due to the lack of regulation and enforcement. Individual investors might not comprehend the level of risk entered when lending out to the loanees. This can be seen from the reviews of the various platforms.

<Insert images of google reviews>

## Problem Statement

The problem of investors making loans out to borrowers beyond their risk appetite, puts the investors at risk of not recouping their funds, which discourages investors from disbursing loans and causes genuine good borrowers from obtaining the necessary funds, so a good starting point would be to have tool assess and classify loans according to risk levels.

## Executive Summary

### Context and Motivation
P2P lending has seen a boom in the past decade or so. It basically connects individual lenders with spectrum of borrowers, with the lenders earning interest on the funds loaned. As this does not go through the banking system, it makes it easier for borrowers to obtain the loans. This also leaves out the stringent forms of checks made by the financial institutions.

As individual lenders lack the capabilities that a financial institution has in assessing borrowers, they might face difficulties in choosing the right loan to ‘invest’ in. While a plethora of data might be available to them, they still cannot evaluate if the loan is something that they can afford to risk. 

Hence, the objective behind this initiative, is to build a robust model that can assist individual investors/lenders in gauging the riskiness of the loan. Then they can assess if they would take the plunge in making out the loan to the loanee.

### Primary and Secondary Stakeholders
Primary - Investors
Secondary - P2P platforms

### Data Science Process
As data from the Singaporean platforms were not readily available, I have turned to the data from ’The Lending Club’, which was available on Kaggle. The data holds accepted loans from 2007 to 2018. To keep the data more current and to a more manageable size, only 10 years of data, from 2009 to 2018, will be used.

#### 1) Data processing and cleaning
The data holds about 2.26 million rows and 151 columns. This require a strenuous review of the columns to see which columns can be dropped, based on the data dictionary provided. The criteria to drop columns will be based on whether the features has bearings on the riskiness of the loans. The review is also to see if additional feature engineering is required. There will also be columns which require changes to the values. An example of this would be ‘term’ which is the term of the loan in months. Columns which has more than 50% null values will be dropped as the majority of the data is missing and will not be useful.

#### 2) Exploratory Data Analysis

#### 3) Model Selection

#### 4) Model Optimisation

#### 5) Model Evaluation
