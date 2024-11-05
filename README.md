# Adjusting For Code Proficiency when Using Large Language Models

This repository is a research project when I was an internship at Nara Institute of Science and Technology(NAIST), Nara, Japan in Software Engineering Laboratory.

This research made to know how LLms can be reduce the proficiency of the Python code or not.

## Method
### Data Library
Get data from the [Requests](https://github.com/psf/requests) library. Can be used by 

```
git clone https://github.com/psf/requests.git Data/requests
```

## Data
### From ChatGPT
Can look the ChatGPT response in `/ChatGPT_response`

### Data Summary
Can look in the excel file `request-data-table.xlsx` or from [this link](https://docs.google.com/spreadsheets/d/1px5YnVHgK_BBj-M66L4PQTcTG6jCtYO1t27kI919Y1U/edit?usp=sharing)

- Data from the pycefr tools 
  - DC-c-level-pycefr:original
- Data from the pycefr that already check with ChatGPT
  - DC-pycefr
- Data for answer each reasearch question
  - DC-forRQ1
  - DC-forRQ2
- Data that ChatGPT can find but pycefr tools can't find
  - DC-forRQ1-chatgenmore
- Data Summary
  - rq1-sum-stat
  - rq2-summary-score
- Confusion Matrix for RQ1
  - rq1.1-conf
  - rq1.2-conf
