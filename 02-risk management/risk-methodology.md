# Risk Assessment Methodology

## Purpose

This document explains how cybersecurity risks are identified, scored, and prioritized for SecurePay Financial.

## Risk Scoring Approach

Each risk is evaluated using two factors:

* **Likelihood** – How likely the risk is to occur
* **Impact** – How serious the consequences would be if the risk occurred

The risk score is calculated using:

**Risk Score = Likelihood × Impact**

## Likelihood Scale

| Score | Rating      | Description                               |
| ----- | ----------- | ----------------------------------------- |
| 1     | Rare        | The event is very unlikely to occur       |
| 2     | Unlikely    | The event could occur but is not expected |
| 3     | Possible    | The event may occur                       |
| 4     | Likely      | The event is expected to occur            |
| 5     | Very Likely | The event is highly likely to occur       |

## Impact Scale

| Score | Rating   | Description                                                                                    |
| ----- | -------- | ---------------------------------------------------------------------------------------------- |
| 1     | Very Low | Minimal business impact                                                                        |
| 2     | Low      | Limited business disruption                                                                    |
| 3     | Medium   | Noticeable operational or security impact                                                      |
| 4     | High     | Major operational, financial, or data impact                                                   |
| 5     | Severe   | Significant business disruption, financial loss, regulatory impact, or sensitive data exposure |

## Risk Rating

| Risk Score | Risk Rating |
| ---------- | ----------- |
| 1–4        | Low         |
| 5–9        | Medium      |
| 10–16      | High        |
| 17–25      | Critical    |

## Inherent Risk

**Inherent risk** is the level of risk before existing security controls are considered.

Example:

Likelihood = 4
Impact = 5

Inherent Risk Score = **4 × 5 = 20**

Risk Rating = **Critical**

## Residual Risk

**Residual risk** is the level of risk remaining after existing security controls are considered.

For example, malware may initially have a Critical risk rating. Endpoint protection, antivirus, patching, and monitoring can reduce the likelihood or impact of the risk.

Example:

Residual Likelihood = 3
Residual Impact = 4

Residual Risk Score = **3 × 4 = 12**

Residual Risk Rating = **High**

## Risk Treatment Options

Risks may be handled using one of four approaches:

* **Mitigate** – Implement controls to reduce the risk
* **Accept** – Management accepts the remaining risk
* **Transfer** – Transfer part of the risk through insurance, contracts, or another party
* **Avoid** – Stop the activity creating the risk

## Risk Review

High and Critical risks should receive priority for remediation.

Risks should be reviewed when:

* New systems or applications are introduced
* Significant security incidents occur
* New vulnerabilities are identified
* Major business or technology changes occur
* Existing controls change

