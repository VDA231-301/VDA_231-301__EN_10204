![EN 10204:2004](https://github.com/VDA231-301/VDA_231-301__EN_10204/blob/main/VDA-Logo%20EN%2010204.png)

# EN 10204 – Inspection Certificate Data
## JSON Subschema according to VDA 231‑301
🔗 This subschema is part of the **VDA 231‑301 open JSON standard ecosystem**
➡ https://github.com/VDA231-301

## Purpose and Scope

This repository provides a **specific JSON subschema for the digital exchange of data according to EN 10204**,  
including **inspection certificates such as type 3.1**.

The subschema defines a **machine‑readable representation of inspection certificate content** and supports the standardized, transparent, and interoperable exchange of material certification data along the supply chain.

It is based on the **VDA 231‑301 recommendation** and represents a specialized extension of the generic VDA 231‑301 JSON schema.

---

## Position within VDA 231‑301

Within the VDA 231‑301 ecosystem:
- the **generic schema** defines the common structure for digital material‑related test and certificate data,
- this **EN 10204 subschema** specifies the data elements required to represent inspection certificate information in a structured and system‑independent manner.

The subschema enables consistent digital transfer of inspection certificate data between material producers, suppliers, OEMs, laboratories, and IT systems.

---

## Relation to EN 10204

EN 10204 defines the **types and content of inspection documents** used to certify materials, including:
- inspection certificate **3.1**,
- inspection certificate **3.2**,
- and other certificate types defined by the standard.

⚠️ **Important clarification:**
- This repository **does not redefine or interpret EN 10204**.
- It does **not establish additional certification requirements, acceptance criteria, or responsibilities**.
- It provides a **technical data structure only** for representing the *content* of EN 10204 inspection documents in digital form.

The authoritative description of EN 10204 and its requirements is published by the responsible standards organizations.
- Standard source: https://www.dinmedia.de/en/standard/din-en-10204/59682782
  
---

## Documentation of Inspection Certificate Data

The subschema specifies the **format in which inspection certificate data shall be documented**.

This includes, for example:
- identification of materials, batches, and products,
- chemical composition and mechanical property values as stated in the certificate,
- references to applicable standards and test methods,
- issuer, signatory, and certificate metadata.

By enabling a structured digital representation of inspection certificate data, the subschema supports:
- automated processing of certificate information,
- improved traceability across the supply chain,
- and integration into material data management and quality systems.

---

## Relation to Other Subschemas

The EN 10204 subschema can be used **independently** or **in combination with other VDA 231‑301 subschemas**, for example:
- as a certificate‑based foundation complemented by more detailed test data (e.g. SEP 1240),
- as a reference for material approval workflows alongside emission or odour test results.

It is intended to **complement**, not replace, more detailed test‑specific data structures where additional depth is required.

---

## Applicability Beyond the Automotive Industry

Although widely used in the automotive supply chain, **EN 10204 inspection certificates are applied across many industries**, including:
- steel and metal production,
- mechanical and plant engineering,
- construction products,
- industrial equipment manufacturing.

The subschema is therefore **not limited to automotive applications** and can be used wherever EN 10204 inspection documents are exchanged in digital form.

---

## Example Files

This repository contains example files illustrating the usage of the subschema:
- JSON examples representing EN 10204 inspection certificate data
- the corresponding JSON Schema definition

These examples are provided for **illustration and implementation support only**.

---

## Important Note

> [!IMPORTANT]
> This subschema provides **structured inspection certificate data only**.  
> It does **not** perform material evaluation, conformity assessment,
> or acceptance decisions.
> Such decisions remain the responsibility of the applicable standards,
> contractual agreements, and quality processes.

---

## License 

The VDA 231‑301 JSON schemas, including this EN 10204 subschema, are released under the **MIT License**, allowing free use, modification, and distribution.


## Contributing & VDA Process

Contributions are welcome.  

Any changes intended to become part of the official VDA recommendation must follow the formal VDA committee and release process.
This repository hosts a subschema extending the generic VDA 231‑301 JSON schema.

GitHub is used as a platform for collaborative drafting, discussion, and technical refinement.  
Issues and Pull Requests are welcome.

⚠️ Please note:  
Only subschemas that have successfully passed the formal VDA committee and release process may become part of the official VDA 231‑301 recommendation.

Details on contribution rules, governance, and approval processes are described in the organization-wide Contributing Guidelines:  
https://github.com/VDA231-301/.github/blob/main/CONTRIBUTING.md
