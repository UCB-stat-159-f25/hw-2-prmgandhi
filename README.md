[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/y12QcJaO)
# HW 2: From Notebooks to Research Packages

_This repository is public so that Binder can find it. All code and data is based on the original [LIGO Center for Open Science Tutorial Repository](https://github.com/losc-tutorial/LOSC_Event_tutorial). This repository is a class exercise that restructures the original LIGO code for improved reproducibility, as a homework assignment for the [Fall 2025 installment of UC Berkeley's Stat 159/259 course, _Reproducible and Collaborative Data Science](https://ucb-stat-159-f25.github.io/site/). Authorship of the original analysis code rests with the LIGO collaboration._

To run the notebook click the badge → [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/UCB-stat-159-f25/hw-2-prmgandhi/HEAD?urlpath=%2Fdoc%2Ftree%2FLOSC_Event_tutorial.ipynb)

`LOSC_Event_tutorial.ipynb` is an IPython notebook from the LIGO Scientific Collaboration as a tutorial for educational purposes.

`environment.yml` is used by conda to create the appropriate environment for this notebook; it describes version numbers for Python, Jupyter, and all necessary packages.

The `ligotool` folder contains a companion script, `readligo.py` with some data reading utilities for the tutorial notebook and is foldered so that it works as a proper Python package.

`BBH_events_v3.json
GW150914_4_template.hdf5
H-H1_LOSC_4_V2-1126259446-32.hdf5
L-L1_LOSC_4_V2-1126259446-32.hdf5`
All of the above are additional files from the original LIGO repository; we focused only on the GW150914 event, to keep the repository a smaller and so we didn’t include the data for other events.

`ai_documentation.txt` describes the usage of AI/LLMs to complete this assignment.
