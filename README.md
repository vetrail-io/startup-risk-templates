# Vetrail templates

Free templates for a startup or small business that needs a risk register and a way to assess its
vendors, without hiring a risk team. They are the same templates
[Vetrail](https://vetrail.io) uses inside the product.

| File | What it is | Rows |
|---|---|---|
| `vendor-security-questionnaire-short.csv` | A short vendor security questionnaire for most vendors, about 15 minutes for the vendor | 24 questions |
| `vendor-security-questionnaire-full.csv` | The full questionnaire for vendors that hold customer data or keep your product running | 54 questions |
| `startup-risk-register.csv` | A risk register filled in with the risks most startups share, each with a starting rating | 32 risks |

The files open in Excel, Google Sheets or Numbers.

## The vendor security questionnaire

Each row has the question, what a good answer looks like, whether the control is critical, its
weight, and columns for the answer and the evidence.

To score it:

- A Yes earns the question's full weight, a Partial earns half, and a No earns nothing. Not
  applicable is left out of the score, with a reason.
- The score is the weight earned as a share of the weight possible, out of 100.
- A No on any critical control caps a Low or Medium rating at High, and three or more critical
  Nos make it Critical, whatever the score.

A questionnaire records what a vendor says. It does not check it. For a vendor that holds
sensitive data, ask for independent evidence, such as a SOC 2 report or an ISO 27001 certificate.

Guide: https://vetrail.io/templates/vendor-security-questionnaire

## The startup risk register

Delete the risks that do not apply, change the ratings that are wrong for you, and give every risk
that is left a named owner. Rate likelihood and impact first as if you had no controls, then
again after the controls you really have. Review it on a fixed day each month.

Guide: https://vetrail.io/templates/risk-register

## Use

Free to use and adapt for your own company.

These templates are not advice on what any regulator, auditor, customer or investor requires of
you.
