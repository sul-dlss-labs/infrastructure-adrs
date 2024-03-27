---
layout: default
title: ADR-0021
nav_order: 25
permalink: records/0022
---
# Non-required Derivative File Generation in SDR (OCR/Transcription)

* Status: [proposed]
* Decider(s): <!-- required -->
  * Peter Mangiafico
  * Ed Summers
  * Justin Coyne
  * Justin Littman
  * Alan Lundgard
  * Niqui O'Neill
  * Mike Giarlo
  * Andrew Berger
  * Dinah Handel
* Date(s):
  * Proposed: 2024-03-27
  * ...

## Context and Problem Statement <!-- required -->

Automated OCR (from images/PDFs) and transcription (from video/audio) are desired for a subset of content deposited in SDR in order to improve accessibility and discoverability.  Current processes for generating these derivative files are manual and require operator intervention.  This process will automate the generation of these derivative files via various mechanisms (either on-demand or by other requests made by operators).  This addresses "non-required" derivatives (though may be referred to simply as "derivatives" throughout this ADR, which are defined as derivative files which add value to the delivery of content, but are not required for delivery itself.

## Decision Drivers <!-- optional -->

* Derivatives should be able to be created by an automated process.
* Users should be able to supply pre-created derivatives; the automated generation should be skipped when a pre-created derivative is present.
* Users should be able to re-accession items by providing only changed files.
* Users should be able to review generated derivatives before proceeding.
* Users should be able to replace / edit / update generated derivatives as part of the review process.
* Users should be able to regenerate existing derivatives.
* Generation of non-required derivatives should not delay accessioning.
* Derivative generation failure should be handled
* Derivatives should be versioned and there should be a single system from which all files can be retrieved.

## Considered Options <!-- required -->

* Workflow driven solution
* Messaging driven solution
* Combination of the two

## Decision Outcome <!-- required -->

After discussions (with notes and original proposals linked below), we propose to use a combination of messaging and new workflow(s) to produce non-required derivatives.

[SUMMARY HERE]

### TBD

Some issues are known to be outstanding and will be decided later:

*

## Links <!-- optional -->

* [Running notes](https://docs.google.com/document/d/1H1zy-yCDErMTf2IWK1PdN9r_6IjqRqiREc0yYnaiYvo/edit)
* [High level overview of options by Andrew](https://docs.google.com/document/d/10MzjOjwmuijHD5rgO5QxxuLKFwv94Lq29vDy0Y_xDUg)
* [Deriviative Generation Proposal](https://docs.google.com/document/d/1JLJwio7xVDDh75KY3dZJIFPDep-92hoQJ5p9EgFKabY)
