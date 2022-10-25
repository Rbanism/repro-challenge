---
name: Challenge submission template
about: Issue template for the Rbanism Reproducibility Challenge submission
title: ''
labels: ''
assignees: ''

---

# Rbanism Reproducibility Challenge submission 

The submission consists of the following steps:

1. Fill in the project information in the form below;
2. Submit this issue without deleting the text below;
3. Fill in the (self-)assessment checklist generated in the first comment;
4. Submit a separate comment in the same issue with a statement on the level of reproducibility of your project, elaborating especially on the challenges you encountered -- word limit: 300 words;
5. Add another comment letting @cforgaci know that the submission is ready for assessment.

## Project information
Project title:
Author(s): 
Type of work: [e.g., PhD thesis chapter, conference paper, research project report]
Status: work in progress / finished but not published / published

## (Self-)Assessment Checklist
The following checklist is used for the assessment of the level of reproducibility of your project. Note that the checklist serves as a tool to help you think about the reproducibility of the data analysis. Although many of the questions can be thought of as having a yes/no answer, we encourage you to see the questions as being open ended with the real question being, "What can one do to improve the status of their project on this bullet point?" With that in mind, one will never get 100% of the bullets right for their project, but they will always be improving.

### Organization
- [ ] Are all data, code, results, and documentation housed within a monophyletic folder structure?
- [ ] Is the project folder structured to separate your data, code, documentation, and results?
- [ ] Can the project be run from the project's root folder?
- [ ] Is the project under version control?
- [ ] Do files use a consistent naming scheme that indicates what they contain?

### Workflow and automation
- [ ] Is the workflow clearly documented (with or without code)?
- [ ] Is the workflow scripted, i.e., using code? 
- [ ] Is the code well documented?
- [ ] Is the code modular, i.e., does it use functions?
- [ ] Are unit tests available for the code?
- [ ] Does the repository make use of continuous integration tools to insure internal reproduciblity?

### Documentation
- [ ] Is there a README file that indicates
  - [ ] the purpose of the project, 
  - [ ] who to contact with questions, 
  - [ ] a map of the directory structure, and 
  - [ ] a description of what software and hardware is needed to reproduce your workflow?
- [ ] Are there README files in each folder describing the contents of the folder, how they were acquired/generated?
- [ ] Is there a CITATION file that tells users how to site the project, data, and code?
- [ ] Does the project have a LICENSE file?
- [ ] Is the project's repository publicly available?

### Publication
- [ ] Are papers and reports from the project generated using literate programming tools so that results are not hard-coded?
- [ ] Does the project have a persistent identifier?

### Data
- [ ] Is the data included or linked, with instructions on how to obtain the data?
- [ ] If data is not included, is this because it is not necessary or generated as part of the project?
- [ ] Are your raw data (if any) and processed data files separated?
- [ ] If data is not open:
  - [ ] Is it accessible via a protocol?
  - [ ] Is there synthetic data provided so the project can be run?
- [ ] Is citation information available for the data?
- [ ] Does the data use open formats, such as CSV and TXT?

### Software
- [ ] Is there a list of dependencies? 
- [ ] Is a container available to run the project?
- [ ] Are version number of every external application used in the process?
- [ ] Does the project use only open software?

This list was inspired by the more extensive [Checklist Questions to stimulate thought about a Project's Reproducibility](https://github.com/datacarpentry/rr-intro/blob/gh-pages/checklist.md).
