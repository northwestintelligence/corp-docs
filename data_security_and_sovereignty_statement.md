# Data Security & Sovereignty Assurance

**Vendor:** Northwest Intelligence Solutions LLC

**Location:** Bellevue, Washington, USA 

**Compliance Alignment:** NIST SP 800-171 (Basic), CMMC Level 1, OCIO 141.10

## 1. Executive Summary: Zero-Trust & Data Isolation

Northwest Intelligence Solutions LLC provides AI-driven proposal development services using privately hosted, on-premise infrastructure. Unlike cloud-native AI solutions (e.g., OpenAI, Anthropic) where data is processed on shared public servers, our architecture ensures that **Client Data never leaves our physically controlled environment.**

## 2. Data Sovereignty & Residency

- **Physical Location:** All data processing, inference, and storage occur physically within Bellevue, Washington, USA.
- **No Offshore Processing:** No data is transmitted to, stored in, or processed by foreign sub-processors.
- **No Third-Party Model Training:** Client data is **strictly isolated**. It is used solely for the generation of the specific project deliverables. Client data is **never** used to train, fine-tune, or improve our foundational models for other customers or public use.

## 3. Infrastructure Security (Private Compute)

Our infrastructure is designed to meet the "Basic Safeguarding" requirements for Federal Contract Information (FCI).

- **Air-Gapped Capabilities:** Our inference servers are capable of operating without active internet uplinks during sensitive processing tasks to prevent data exfiltration.
- **Physical Security:** Server hardware is housed in a secured, access-controlled facility. Physical access is restricted to authorized personnel only, with logged entry/exit.
- **Encryption:**
    - **At Rest:** All client data is encrypted using disk encryption.
    - **In Transit:** Local network traffic is secured at the perimeter by a firewall; no data is transmitted over unencrypted public networks.

## 4. AI Transparency & Human-in-the-Loop

In compliance with Washington State WaTech interim guidelines for Generative AI:

- **Verifiable Output:** All AI-generated content is subject to mandatory human review for factual accuracy and hallucinations prior to delivery.
- **Audit Trails:** We maintain logs of prompts, ensuring full traceability of how specific proposal content was derived.

## 5. Data Lifecycle & Destruction

- **Retention:** Client data is retained only for the duration of the client relationship + 30 days (or as specified by contract).
- **Sanitization:** Upon conclusion of the client relationship, client data is securely erased.
