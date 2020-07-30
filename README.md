# GroupL
BU RISE(practicum) Group L Project

# Research Question:

Can a machine learning program be used to identify individuals having sleepwalking (somnambulism) episodes and those who have normal sleep cycles by monitoring their EEG data during sleep?

# How we plan to carry out our project:

- (1) We plan to find existing EEG data for people with normal sleep cycles and for individuals undergoing sleepwalking episodes.
- (2) Then, we plan to find a similar existing machine learning model for diagnosing sleep disorders to adapt our model from. Or if no such model is available, we plan to write our own based on the methods of similar existing studies.
- (3) After completing our model, we plan to have the model learn both sets of data and to be able to differentiate between them and identify the sleepwalking episodes when fed new data. 
- (4) Finally, we will determine the percent accuracy of the algorithm.

# Links to model templates and journal articles:

EEG Data: these are EEG data sets we have found so far, but we still need sleepwalking specific EEG data (with the exception of one article with this data) as well as more sleep cycle specific EEG’s. 

- http://bnci-horizon-2020.eu/database/data-sets (Has the EEGs of people doing specific tasks (I didn’t really see any sleep-specific ones, but has a lot of data)
- https://www.physionet.org/content/sleep-edfx/1.0.0/
- https://physionet.org/content/capslpdb/1.0.0/
- https://github.com/meagmohit/EEG-Datasets
- https://sccn.ucsd.edu/~arno/fam2data/publicly_available_EEG_data.html 
- https://sleepdata.org/datasets
- https://ieee-dataport.org/documents/datasets-graph-analysis-single-channel-sleep-stage-eeg-different-electrode-placements

Potential Machine Learning Models:
- https://github.com/psifrous/Sleep_Disorder_Detection
 
Articles:
- https://scholarspace.manoa.hawaii.edu/bitstream/10125/64138/0320.pdf (Machine learning model diagnosing REM Sleep Behavior Disorder using EEG datasets) 
- https://www.sciencedirect.com/science/article/pii/S1388245715000681 (EEG current density imaging prior to sleepwalking episodes) (Contains EEG data on sleepwalking)
- https://pubmed.ncbi.nlm.nih.gov/30725708/ (EEG of normal sleep and sleep stages) 
- https://link-springer-com.ezproxy.bu.edu/content/pdf/10.1007%2F978-3-030-30581-9.pdf (this book has helpful information on EEG’s and machine learning) 
- https://pubmed.ncbi.nlm.nih.gov/31591021/ (Electroencephalogram abnormalities in patients with NREM parasomnias)

# Questions/Thoughts
- Is there any specific type of machine learning method that you think would be best for our type of project?
- There is a very similar study using a machine learning model to diagnose the sleep disorder RBD using EEG datasets that was published earlier this year. How can we differentiate our project and build on their existing study? 
- Is sleepwalking a feasible sleep disorder to use for the objectives of this project? If not, or should we look at various kinds of parasomnias in general or a different sleep disorder entirely? 
- There is significant EEG data on sleepwalking episodes in one of the articles. Are we allowed to use their data for our project  even though it is from an already published study?
- Is there a specific sleep stage we should be monitoring? And should the stage being monitored be the same for the subjects who are undergoing a sleep-walking episode and those who are not?
- Should we try our model to identify spans of time where a person is sleepwalking or just identify whether or not the person had a sleepwalking episode at all during their EEG reading? (or both?)
- EEG data is often in the form of graphs. How can we design a program to take in data in this form? Should we first convert the graphs into numerical values, such as amplitudes, periods, etc.?
- How many sources can we retrieve our data from? Can we pull data from multiple sources? Or do we have to get all the control data from one source and all the sleepwalking data from another source? Or do we have to get all the data of every type from a singular source/database? 
- Will sleep EEG data of sleepwalkers differ to that of regular people?
- How can we acount for different potential factors such as age or gender?

