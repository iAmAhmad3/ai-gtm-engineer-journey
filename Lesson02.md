# Clay 101 - Lesson 02

**Topic:** The Jigsaw Framework for Data Enrichment

---

## Objective

This lesson introduces the **Jigsaw Framework**, a structured methodology for building data enrichment workflows in Clay.

The framework compares data enrichment to solving a jigsaw puzzle. Instead of trying to gather every piece of information at once, you first identify the most important identifiers, enrich them with core data, and then fill in the remaining details based on your specific use case.

---

## Why the Jigsaw Framework?

When working with large datasets, it's easy to become overwhelmed by the number of available enrichment options.

The Jigsaw Framework provides a repeatable process that helps you build complete and accurate datasets efficiently.

Rather than asking:

> "What data should I enrich first?"

You simply follow three sequential steps.

---

## The Jigsaw Framework

### Step 1 — Find Your Corner Pieces

Every puzzle begins with the corner pieces.

Similarly, every Clay workflow starts with the minimum identifiers required to uniquely identify a company or a person.

### Company Identifiers

- Company Domain
- LinkedIn Company Profile URL

### Person Identifiers

- Full Name
- Personal LinkedIn Profile URL

If these identifiers are unavailable, they can often be discovered using:

- Google Search
- Claygent
- Other search providers

**Goal**

Establish reliable identifiers before attempting enrichment.

---

### Step 2 — Enrich Your Edges

Once the identifiers are available, use Clay's native enrichment actions.

Common actions include:

- Enrich Company
- Enrich Person

These actions automatically retrieve foundational information.

### Company Enrichment

Examples include:

- Company name
- Industry
- Employee count
- Headquarters
- Website
- Company description

### Person Enrichment

Examples include:

- Full name
- Job title
- Bio
- Company
- Location
- Social profiles

**Goal**

Create a strong foundation of company and contact information before performing advanced enrichment.

---

### Step 3 — Fill in the Puzzle

After the core information has been collected, gather additional data based on your business objective.

Clay allows you to extend your dataset using:

- AI
- Web scraping
- Third-party data providers
- API integrations
- Clay's native integrations

Examples of additional enrichment include:

- Recent funding
- Technologies used
- Hiring activity
- Company news
- Buying signals
- Personalization data
- Contact verification

**Goal**

Collect only the information needed for your workflow or outreach campaign.

---

## Workflow Overview

```text
Find Corner Pieces
        ↓
Enrich Core Data
        ↓
Fill Remaining Data
```

---

## Real-World Example

Suppose you want to build a list of SaaS founders for outbound sales.

### Step 1

Collect:

- Company Domain
- Founder LinkedIn URL

↓

### Step 2

Run:

- Enrich Company
- Enrich Person

Retrieve:

- Employee count
- Industry
- Job title
- Company description

↓

### Step 3

Add custom enrichments:

- Funding stage
- Technologies used
- Recent hiring activity
- AI-generated personalization
- Verified email address

↓

Export the completed dataset into your CRM or outreach platform.

---

## Key Takeaways

- Every enrichment workflow starts with reliable identifiers.
- Company domains and LinkedIn URLs are the most valuable starting points.
- Native enrichment actions should be completed before adding custom enrichments.
- Advanced enrichment should always be driven by the specific business objective.
- The Jigsaw Framework helps simplify complex enrichment workflows.

---

## Client Use Cases

- Sales prospecting
- Lead enrichment
- CRM data enhancement
- Account-based marketing (ABM)
- Market research
- Personalized cold outreach
- Lead qualification
- Revenue operations

---

## Key Terms

| Term | Description |
|------|-------------|
| Jigsaw Framework | A three-step process for building data enrichment workflows |
| Corner Pieces | The minimum identifiers needed to identify a company or person |
| Enrich Company | Clay action that retrieves company information |
| Enrich Person | Clay action that retrieves individual contact information |
| Claygent | Clay's AI assistant for discovering and enriching information |

---

## Relationship to Lesson 01

The Jigsaw Framework fits naturally within the **FETE Framework** introduced in Lesson 01.

| FETE Stage | Jigsaw Stage |
|------------|--------------|
| Find | Find Your Corner Pieces |
| Enrich | Enrich Your Edges |
| Transform | Clean and prepare enriched data |
| Export | Send completed data to downstream tools |

The Jigsaw Framework provides a practical methodology for executing the **Find** and **Enrich** stages of the FETE Framework.

---

## Lesson Summary

The Jigsaw Framework provides a simple, repeatable approach to building high-quality datasets in Clay.

Instead of enriching random fields, begin with reliable identifiers, enrich them using Clay's native actions, and then add only the additional information required for your business use case.

Following this approach results in cleaner data, more efficient workflows, and better automation outcomes.

---

## Action Items

- [x] Complete Lesson 02
- [ ] Practice identifying company and person identifiers
- [ ] Experiment with the "Enrich Company" action
- [ ] Experiment with the "Enrich Person" action
- [ ] Continue to Lesson 03

---

## Metadata

| Field | Value |
|------|-------|
| Course | Clay 101 |
| Lesson | 02 |
| Status | Completed |
| Date | 2026-07-13 |
