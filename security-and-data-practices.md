# Security & Data Practices (Prown)

**Effective date:** 2025-12-16

This document provides a high-level overview of Prown’s security and data handling practices.

## 1. Tenant isolation

Prown uses a multi-tenant authorization model designed so users can access only data belonging to their organization.

## 2. Data stored

Prown may store:
- Interview transcripts;
- Structured outputs (“debriefs”) derived from interviews;
- System logs and metadata required for operating and securing the service;
- Observability traces for model/prompt evaluation (see Subprocessors).

See: [Subprocessors](./subprocessors.md)

## 3. Access controls

Access to production systems is restricted to the minimum required for service operation.

## 4. Data deletion (current process)

Prown currently supports **manual** handling of data deletion and access requests.
- For self-serve/free use cases, requests can be submitted via the contact below.
- For customer/partner engagements, requests should be directed to the customer/partner (controller). Prown will assist under the applicable agreement.

## 5. Incident response

If we become aware of a security incident affecting customer data, we will take reasonable steps to investigate, mitigate, and notify affected customers/partners as appropriate.

## 6. Contact

Email: **marcossponton@gmail.com** 
