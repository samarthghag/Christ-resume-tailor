# CHRIST Resume Tailor

A Claude skill that turns a CHRIST (Deemed to be University) student's resume into a one-page, job-tailored, ATS-friendly resume using the **official CHRIST template**.

> **CHRIST students only.** This is not a general-purpose resume builder.

## What it does

- Collects your resume, facts, and the target job description.
- Rewrites and reorders content to match the role, **without inventing facts**.
- Keeps the official CHRIST layout, branding, fonts, spacing, and required education details.
- Outputs a ready-to-submit `.docx`, PDF, or both.
- Always one page, Indian English spelling.

## Install

1. Download this repo as a ZIP (Code → Download ZIP).
2. Zip the `skills/christ-resume-tailor` folder.
3. In Claude: Settings → Capabilities → Skills → Upload skill.
4. Start a chat and say: *"Tailor my resume for this job"*, then attach your resume and the JD.

## Usage

Provide:
1. Your current resume, or your details
2. The job description or a link to it
3. Output format: `.docx`, PDF, or both

## Example

| Before | After |
|---|---|
| _Add anonymised sample resume_ | _Add tailored output screenshot_ |

## Templates

The official template lives in [`Template/`](./Template):
- `CHRIST_Resume_ATS_Template.docx`

The CHRIST template is always the default. To add another template, put all its source files in `Template/` first and add its layout and selection rules to the skill. The skill never reconstructs a missing template.

## Guarantees

- Only facts you supply are used. Missing details are asked for, not guessed.
- One page, with overflow trimmed starting from the lowest-value bullets.
- JD keyword match check before final output.

## About the creator

This skill was created and is maintained by **Samarth Ghag**, a BCA (Honours & Research) student at **CHRIST (Deemed to be University), Bengaluru**, graduating in 2027.

- **Co-Founder & CTO, College Circle AI**: a personalised learning platform for college students.
- **Founder, Vault Vortex**: a fintech education club at CHRIST.
- **Student leadership**: IEEE and BYC Student Council at CHRIST.
- **Experience**: AI Research & Outreach Intern at The Builder Club; Chief of Staff at GuideHero.

**Connect:** [GitHub](https://github.com/samarthghag) · [LinkedIn](https://www.linkedin.com/in/samarth-ghag/) · [Open an issue](https://github.com/samarthghag/Christ-resume-tailor/issues)

## License

MIT. The CHRIST name, logo, and template layout remain the property of CHRIST (Deemed to be University).
