# Thesis Template
[![pipeline status](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/thesis-template/badges/master/pipeline.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/thesis-template/commits/master)

## Download Thesis
[![latest proposal](https://img.shields.io/badge/Download-Proposal-blue.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/thesis-template/-/jobs/artifacts/master/file/proposal/text/proposal.pdf?job=build-thesis-text)
[![latest proposal slides](https://img.shields.io/badge/Download-Proposal%20Presentation-blue.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/thesis-template/-/jobs/artifacts/master/file/proposal/presentation/slides.pdf?job=build-thesis-slides)

Replace `{YOUR_PROJECT}` with your Gitlab Project name.
Update from proposal to thesis once you reached this stage. 

Proposal:
```markdown
[![latest proposal](https://img.shields.io/badge/Download-Proposal-blue.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/{YOUR_PROJECT}/-/jobs/artifacts/master/file/proposal/text/proposal.pdf?job=build-thesis-text)
[![latest proposal slides](https://img.shields.io/badge/Download-Proposal%20Presentation-blue.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/{YOUR_PROJECT}/-/jobs/artifacts/master/file/proposal/presentation/slides.pdf?job=build-thesis-slides)
```
Thesis:
```markdown
[![latest thesis](https://img.shields.io/badge/Download-Thesis-blue.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/{YOUR_PROJECT}/-/jobs/artifacts/master/file/thesis/text/thesis.pdf?job=build-thesis-text)
[![latest thesis slides](https://img.shields.io/badge/Download-Thesis%20Presentation-blue.svg)](https://git.dbis.rwth-aachen.de/ACIS_BA_MA/{YOUR_PROJECT}/-/jobs/artifacts/master/file/thesis/presentation/slides.pdf?job=build-thesis-slides)
```

Also update the [.gitlab-ci.yml](.gitlab-ci.yml##L6) and change `proposal`to `thesis`

## Configuration
Adjust the [config.tex](preamble/config.tex). 
