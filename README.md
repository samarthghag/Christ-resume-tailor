# CHRIST Resume Tailor

This skill creates job-tailored resumes **only for students of CHRIST (Deemed to
be University)**. The default output is a CHRIST-branded, one-page resume based
on the official template stored in the [`Template/`](./Template/) folder.

## What it does

- Collects the student's resume, facts, and target job description.
- Tailors the wording and ordering to the target role without inventing facts.
- Preserves the official CHRIST layout, branding, fonts, spacing, and required
  education details.
- Produces a ready-to-submit `.docx`, PDF, or both, depending on the student's
  request.

This is not a general-purpose resume builder. Do not use it to create resumes
for students who are not from CHRIST University.

## About the creator

This skill was created and is maintained by **Samarth Ghag**, a fourth-year
student at the **CHRIST (Deemed to be University), Yeshwanthpur Campus**.
Samarth created it to help CHRIST students prepare focused, accurate,
job-tailored resumes while preserving the university's official resume format.

- GitHub: [samarthghag](https://github.com/samarthghag)
- LinkedIn: [Samarth Ghag](https://www.linkedin.com/in/samarth-ghag/)

## Templates

The official CHRIST template currently available is:

- [`Template/1785318356914CHRIST_Resume_ATS_Word.docx`](./Template/1785318356914CHRIST_Resume_ATS_Word.docx)

The CHRIST template is the default and must be used unless another template is
explicitly requested. If support for additional resume templates is needed,
place **all necessary source template files** in [`Template/`](./Template/)
first. The skill must use a template that exists in that folder; it must not
invent or reconstruct a missing template. Add each new template's layout,
branding, and selection guidance to the skill before using it.

## Usage

Provide:

1. The current resume, or the student's resume details.
2. The job description or a link to it.
3. The requested output format: `.docx`, PDF, or both.

The resulting resume remains one page, uses Indian English spelling, and
contains only facts supplied by the student.
