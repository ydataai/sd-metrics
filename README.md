![](https://img.shields.io/badge/python-3.9%20%7C%203.10%20%7C%203.11-blue)
![](https://img.shields.io/github/license/ydataai/sd-metrics)

# SD-Metrics

Generating synthetic data lays a crucial role in addressing reliable and privacy-preserving data-sharing. As a Privacy-Enhancing Technology, synthetic data can be used to support several use-cases in the real of data sharing and access:

- For AI and data science projects
- Software testing
- Proof of concepts and innovation
- Open data & data science
- Enabler of hackatons and data competitions

A repository that collects different metrics evaluate the quality of synthetic data under the scope data democratization. The metrics evaluate the quality of the synthetic data under the following pillars: *utility*, *fidelity* and *privacy*.

## The different dimensions of synthetic data quality

### Fidelity
  The fidelity of synthetic data is determined by two factors: how closely the generated data matches the original data points and how much diversity is preserved in the newly created synthetic points.
Fidelity metrics assist us in determining how closely the generated data matches the original data, thus instilling confidence in its suitability for exploration and analysis.

### Utility
  The utility score measures how useful synthetic data can be in replacing real data for downstream applications, such as analytics or even machine learning models.
  
### Privacy
  Privacy indicates the level of confidentiality of synthetic data. When validating the privacy of generated synthetic data, it is important to classify the different bits of information according to the identification risk and value they hold for the downstream application. 

### Important aspects that we consider for the desing of synthetic data quality metrics
- *Scalability*
- *Interpretability* and last but not the least
- *Business applicability*

## Data types to be supported
- *Tabular data*
  By the definition from statistics, tabular data refers to data that is organized in a table composed by columns and rows. Within the table the rows describe the observations like customers, products etc and the columns represent attributed for those observations. 

- *Time-series*
  Time-series data, also referred as sequential data, is a sequence of data points that have a time dependency, meaning they are index in time order. These data points typically consists of successive measurements made from the same source over a fixed time interval and are used to tranck and change over time. Because of the dependecy in between records, this changes the way the synthetic data quality (aka similarity to the real data) is calculated. 

## The teams behind the package
  This project is a collaborative initiative between [YData](https://ydata.ai/) and [Fraunhoffer Portugal](https://www.aicos.fraunhofer.pt/en/home.html) under the scope of the [Center for Responsible AI](https://www.linkedin.com/company/center-for-responsible-ai/). 

