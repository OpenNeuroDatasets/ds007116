# Penn LEAD: Penn Longitudinal Executive functioning in Adolescent Development - Task Contrast Map Derivatives

Penn LEAD (Penn Longitudinal Executive functioning in Adolescent Development) is a data resource designed to investigate transdiagnostic executive function during development.

This repository contains task contrast maps from running Nilearn. We provide task contrast maps for the 2back > 0back contrast, as well as the 2back > baseline and 0back > baseline contrasts. Note, however, that baseline contrasts are not interpretable, as our task design did not allow for a robust estimation of baseline.

The link to the accompanying raw dataset is here: https://openneuro.org/datasets/ds007116 [accession number ds007116].
The link to the accompanying fMRIPrep derivatives is here: https://openneuro.org/datasets/ds007088 [accession number ds007088].
The link to the accompanying XCP-D derivatives is here: https://openneuro.org/datasets/ds007402 [accession number ds007402].

Note that we did not run the first-level analyses on any subject/session if there is no nback data for that session, that session did not pass QC, there was not a corresponding events.tsv for that session, or the participant did not respond on any trial in the n-back task (indicating a complete lack of attention or the subject fell asleep in the scanner). This left 107 subjects with first-level task contrast maps that were then used for the second-level group analysis.
