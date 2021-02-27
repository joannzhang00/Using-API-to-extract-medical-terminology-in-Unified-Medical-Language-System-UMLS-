# Using-API-to-extract-medical-terminology-in-Unified-Medical-Language-System-UMLS-

1. About UMLS
Unified Medical Language System (UMLS):https://www.nlm.nih.gov/research/umls/index.html
The UMLS integrates and distributes key terminology, classification and coding standards, and associated resources to promote creation of more effective and interoperable biomedical information systems and services, including electronic health records.

2. This repository
Using API key to extract medical synonyms from the language system for a bag of words/phrases. The result could be used for natural language analysis in medical research. 

3. How it works
input: 
  phrases = ['memory impairment', 'fatigue']
output:
  {'fatigue': {'decrease in energy',
   'decreased energy',
   'energy decreased',
   'energy loss',
   'extreme fatigue',
   'fatigue',
   'fatigue (diagnosis)',
   'fatigue (finding)',
   'fatigue (lassitude)',
   'fatigue (symptom)',
   'fatigue - symptom',
   'fatigue extreme',
   'fatigue nos',
   'fatigue symptom',
   'fatigue symptoms',
   'fatigued',
   'fatigues',
   'fatiguing',
   'feeling of total lack of energy',
   'lack (of);energy',
   'lack of energy',
   'lack of energy (finding)',
   'lacking energy',
   'lacking in energy',
   'loss of energy',
   'rndx fatigue',
   'rndx fatigue (diagnosis)',
   'symptom fatigue',
   'tatt',
   'time tired',
   'tired',
   'tired all the time',
   'tired out',
   'tired time',
   'tiredness',
   'weariness'}})
