# 5 years of internal software validation in Roche

## Disclaimer

The authors of the talk will gradually supplement this repository with details on the topic, including graphics and documentation on Roche's internal software validation pipeline. Data required to reproduce the analysis will also be published, allowing exploration on their own.

## Abstract 

The process of software validation is a key part of analyses conducted in a regulatory environment, and it is crucial to document accuracy, reproducibility and traceability of the software used for clinical analyses. At Roche, we began with outsourcing this effort to an external partner. However, this was a solution far from ideal due to, among others, bottlenecks, a fixed release schedule, and difficulties with processing ad hoc and business-critical validations. Therefore, in 2021, Roche decided to internalize this process by developing entire validation pipelines, able to validate packages on demand and serve them in an internal validated packages repository.

In this presentation, we will walk the audience through this process. We intend to detail how the initial assumptions changed, what parts of that 5-year journey were the hardest, including design decisions, stakeholder alignment, and getting approval from people responsible for validation. We want to illustrate our progression and how it has positively affected the use of R across many parts of the company, and raise awareness about how good R code should be written.

Furthermore, we plan to show key performance indicators and how they have evolved over the past five years. Numbers of packages validated, the time required to validate a package, the number of pipelines run, etc., all tell a story of how this process improved and gradually replaced external validation. Our goal is to provide some insights into how the validation process can evolve in the company by sharing the experience we gained in the form of both successes and challenges that we had to overcome, which may be useful for companies seeking or already walking the same path.
