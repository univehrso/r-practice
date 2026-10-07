A short practice project to keep my R skills current, using open
data from a study of toddlers' pretend play and executive function.

## Data

The data is not included in this repository. It comes from the OSF
project for "Pretend play is not an 'extra'" [Constien, T., Kelly, J., & Downes, M. (2026, September 17). Sleep, Cartoons and Everyday Play in Toddlers Study. https://doi.org/10.17605/OSF.IO/A5473]:

- OSF project: https://osf.io/a5473
- Paper: [https://osf.io/a5473/overview]

To run the script, download the CSV from OSF and place it in the
same folder as the script.

## What I did

- Imported the data (224 rows, 54 columns) and fixed a header row
  that had been read in as data
- Counted missing values and found two patterns: 8 children missing
  the whole pretend play survey, and scattered single skipped items
- Summarized pretend play scores by age band
- Plotted pretend play (EPS) against cognitive executive function (CEF)

## What I found

- Pretend play scores rose with age, with a larger gain between the
  two younger bands than the two older ones
- Pretend play and cognitive executive function were positively related
- Many toddlers scored near the top of the pretend play scale, so a
  ceiling effect is possible

![Pretend play and executive function](<img width="1199" height="1337" alt="eps_cef_plot" src="https://github.com/user-attachments/assets/244bc2c8-64e6-44b2-aa9e-d3d68dc72b98" />

## Tools

R, tidyverse
