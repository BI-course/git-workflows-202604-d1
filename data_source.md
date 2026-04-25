## Overview

A **data source** is any origin point from which data is collected, stored, or generated within a business context.

---

## Categories of Data Sources

### 1. Internal Data Sources

These are generated within the organisation and are typically the most reliable and well-understood.

| Source Type | Examples | Notes |
|-------------|----------|-------|
| Transactional Databases | Sales records, inventory systems, CRM | Structured; high volume |
| ERP Systems | SAP, Oracle ERP | Integrated business process data |
| HR Systems | Employee records, payroll | Sensitive – may contain PII |
| Financial Systems | Accounting ledgers, invoicing | Regulated; audit trail required |
| Web & App Logs | Clickstream data, API logs | Semi-structured; high velocity |

### 2. External Data Sources

Data originating outside the organisation used to enrich internal datasets.

| Source Type | Examples | Notes |
|-------------|----------|-------|
| Third-Party APIs | Weather APIs, social media APIs | Requires licensing/agreements |
| Open Data | Government portals, World Bank | Publicly available |
| Purchased Data | Market research, demographic data | May have usage restrictions |
| Partner Data | Supplier feeds, partner CRM exports | Shared under data agreements |

### 3. Streaming / Real-Time Data Sources

Data that arrives continuously and must be processed with minimal latency.

- IoT sensors and devices
- Financial market feeds
- Real-time event logs 

### 4. Unstructured Data Sources

Data that does not conform to a predefined schema.

- Documents 
- Emails and chat messages
- Images, audio and video
- Survey free-text responses

---

## Data Source Formats

| Format | Description | Common Use |
|--------|-------------|------------|
| CSV / TSV | Flat files with delimiters | Batch data exports |
| JSON | Key-value, nested structure | APIs, web apps |
| XML | Tag-based structure | Legacy systems, EDI |
| SQL Tables | Relational database rows | Transactional systems |

---

## Data Source Considerations

1. **Reliability** - Is the source consistently available and accurate?
2. **Latency** - How frequently is the data updated (batch vs. real-time)?
3. **Volume** - How much data is generated and at what rate?
4. **Schema Stability** - Does the structure change frequently?
5. **Governance & Compliance** - Does the data contain PII or regulated information? 
6. **Ownership** - Who is responsible for the data and its quality?

---