# BigQuery Lecture 1 Assignment

Author: Frank Renn

This folder contains the IC/CP-W04 BigQuery SQL Lecture 1 assignment organized
into the seven sections from the lecture.

## Files

- **Frank-Renn-lecture1-ga4.sql**: All Lecture 1 SQL queries, organized with comments.
- **Frank-Renn-lecture1-ga4.qmd**: Quarto notebook with seven H1 sections, explanations, and screenshots.
- **screenshots/**: Nine BigQuery result screenshots named img1.png through img9.png.

## What you still need to do

1. Confirm that each query runs without errors in BigQuery.
2. Confirm that the matching screenshot appears below each query in the QMD file.
3. Open the QMD file in RStudio or Positron.
4. Render the QMD file to create the HTML file.
5. Publish the HTML and SQL files with your GitHub repository.

## Render command

~~~bash
quarto render Frank-Renn-lecture1-ga4.qmd
~~~

This should create:

~~~text
Frank-Renn-lecture1-ga4.html
~~~

The HTML file is configured with embed-resources set to true, so images should
be embedded in the final HTML document.

## Final submission

Submit or publish these items:

- Frank-Renn-lecture1-ga4.html
- Frank-Renn-lecture1-ga4.sql
- GitHub Pages link
- GitHub repository link
