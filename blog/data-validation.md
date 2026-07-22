# The Data Validation Framework I Use Before Any Analysis

Every dashboard, report, forecast, or recommendation ultimately depends on one thing:

**Can the data be trusted?**

I've found that many data projects focus heavily on visualisation and insight generation but spend too little time validating the underlying data.

As a Business Intelligence Developer, my goal is not simply to build reports. My goal is to build confidence in the information people use to make decisions.

Before beginning any analysis, I work through a Data Validation Framework designed to answer a single question:

> Is this data fit for decision-making?

The framework consists of five stages.

### Stage 1: Structural Validation

The first step is ensuring the dataset is structurally sound.

At this stage I'm asking:

- Does the data have a reliable primary key?
- Are records unique?
- Are data types correct?
- Are relationships between tables maintained?
- Are there duplicate records or entities?

This helps confirm that the dataset has been modelled and loaded correctly before any business analysis takes place.

If the foundation is unstable, every metric built on top of it becomes questionable.

### Stage 2: Completeness Validation

Next, I validate whether the dataset contains all expected information.

Typical checks include:

- Record counts versus source systems
- Missing dates in time series data
- Null values in mandatory fields
- Missing files, tables, or partitions
- Data arrival checks

A dashboard can be technically correct while still being misleading if 20% of the expected data never arrived.

Completeness validation ensures we're analysing the whole picture rather than a partial version of reality.

### Stage 3: Quality Validation

Once the data structure and completeness have been validated, I focus on data quality.

This includes:

- Range checks
- Outlier detection
- Date validation
- Consistency checks
- Referential integrity testing

At this stage, the question becomes:

> Does the data behave as expected?

Unexpected spikes, impossible values, broken relationships, and inconsistent categorisations often indicate issues that require further investigation.

### Stage 4: Business Validation

This is the stage that many technical validation processes miss.

Data can pass every technical check and still be wrong from a business perspective.

I validate whether:

- KPIs align with previous reporting periods
- Financial totals reconcile
- Calculations produce expected results
- Business rules are being applied correctly
- Report outputs match stakeholder expectations

This stage is crucial because businesses don't make decisions based on tables.

They make decisions based on business outcomes.

### Stage 5: Trust Validation

The final stage focuses on confidence and explainability.

I ask:

- Does the reporting layer reconcile back to the source?
- Can I explain how every metric is calculated?
- Has the latest data arrived?
- Do trends align with historical patterns?
- Would I confidently present these numbers to leadership?

This stage turns validated data into trusted data.

Because ultimately, the purpose of validation isn't finding errors.

It's establishing confidence.

## Why This Matters

The role of a BI Developer isn't to produce dashboards.

It's to create systems that help people make better decisions.

Data validation is one of those systems.

When done well:

- Stakeholders trust the numbers
- Data issues are detected early
- Reporting becomes more reliable
- Time spent investigating discrepancies is reduced
- Business decisions are based on evidence rather than assumptions

In my experience, the most valuable insight isn't always discovering something new.

Sometimes it's giving decision-makers confidence that what they're already seeing is accurate.

### The Principle Behind the Framework

My approach to data validation can be summarised in one sentence:

> Before analysing data, validate that the system producing the data can be trusted.

Because better decisions don't start with dashboards.

They start with trusted data.
