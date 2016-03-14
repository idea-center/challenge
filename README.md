# IDEA Interview Code Challenge

IDEA works with a lot of different types of data related to surveys. One type that is important is classification of that survey data. For example, a survey is associated with this institution, this discipline, this type of program, or this demographic sub-group. The goal of this Code Challenge is to build either a front-end User Interface (UI) or a back-end API to manage the classification data.

# Types of Data
This project contains CSV files that have sample institution, discipline, and program data. Pay attention to the fact that programs are mapped to disciplines (using the discipline code). In addition, there is a parent/child relationship for demographic groups.

# Instructions
- Before you get started, ask questions to be sure you understand the goals of this challenge.
- Once you start, you should spend about 1 hour implementing what you can; we do NOT expect that you will finish all features so take care in choosing what you spend time on.
- During your implementation, you should keep track of any assumptions that you make so you can communicate those during the review.
- Once you complete the implementation, you should be prepared to walk us through your solution explaining what you did and why.
- You can choose whatever language, tools, and frameworks you want to get the job done. If you are comfortable, we suggest using tools that are familiar to us (AngularJS on the front-end or Grails on the back-end).

# Files
There are several CSV files in this project that have some sample data.

- demographics.csv
  - This file contains columns for the ID, the name of the sub-group, the abbreviated name of the sub-group, and the parent ID.
- disciplines.csv
  - This file contains columns for discipline code, name, and abbreviated name.
- institutions.csv
  - This file contains columns for the institution name, FICE (Federal Interagency Committee on Education code), state, and zipcode.
- programs.csv
  - This file contains columns for the program code, name, abbreviated name, and associated discipline code.