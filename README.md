# A/B Testing: Library Website Homepage

## 1. Project Objectives & Overview

### 1.1. Business Problem

The Library of Montana State University has a website that students use to find books and articles. Below is an image of what the homepage looks like:

<img width="749" alt="Screenshot 2023-04-20 at 16 03 15" src="https://user-images.githubusercontent.com/120720780/233407298-dc314f9a-38c0-4c5d-8f35-387cc6d241ce.png">

The homepage features a search bar and three prominent items: “Find”, “Request”, and “Interact”. Each provides access to vital information and services offered by the library. However, website analytics indicate minimal interaction with the “Interact” button:

<img width="744" alt="Screenshot 2023-04-20 at 16 03 58" src="https://user-images.githubusercontent.com/120720780/233407499-c41369f6-cd82-476a-9e17-c3612d5dd279.png">

The homepage features a search bar and three prominent items: “Find”, “Request”, and “Interact”. Each provides access to vital information and services offered by the library. However, website analytics indicate minimal interaction with the “Interact” button:

### 1.2. User Reaseacr

Feedback from students revealed confusion and preferences regarding the terminology used:

-"A sophomore student found “Services” and “Help” more clear and intuitive compared to “Interact” and “Connect”. They also found “Learn” inappropriate and placed “Floor maps” as an odd inclusion."
-"A junior student, not a native English speaker, favored strong, clear words like “Help” and “Services”."
-"A senior student echoed similar thoughts, preferring “Help” and “Services” for their clarity and relevance."

### 1.3 A/B Test

The website team decided to test four new versions against the original “Interact” button: Connect, Learn, Help, and Services. The experiment aimed to determine which version yields a higher click-through rate (CTR).

## 2. Results

### 2.1. Questions

The decision was made to test only “Help” and “Services”, based on student feedback disfavoring “Learn” and “Connect”. The broader strategy aims to enhance the student experience by making it easier to access necessary resources and potentially improve their overall experience and perception of the university.

The main metric for the experiment is the Click Through Rate.

The hypotheses are:
    
 **Null Hypothesis: No difference in CTR among the versions.**
 **Alternative Hypothesis: Significant difference in CTR among the versions.**

A statistical significance threshold (alpha) of 0.1 was set.


### 2.2. Conclusion

Since the p-value is smaller larger than alpha, we reject the Null Hypothesis.

|index|Interact|Connect|Learn|Help|Services|
|---|---|---|---|---|---|
|CTR|0\.40|1\.93|0\.76|1\.13|2\.18|
|Click|42\.0|53\.0|21\.0|38\.0|45\.0|
|No\_click|10241\.0|2689\.0|2726\.0|3142\.0|2019\.0|
|Website\_visits|10283\.0|2742\.0|2747\.0|3180\.0|2064\.0|

The comprehensive analysis conducted through Chi-squared tests has effectively illuminated the variations in click-through rates (CTR) among different versions of the library website's homepage. By meticulously comparing these versions pairwise, we have been able to discern statistically significant differences in user click behavior. The standout result from this analysis is the clear superiority of the "SERVICES" version, which demonstrated a remarkable increase in its CTR by 2.18%. This figure not only signifies an impressive enhancement but also translates to a staggering 433.79% increase compared to the original "INTERACT" version.

This significant uplift in CTR for the "SERVICES" version underscores the importance of clear and intuitive labeling on websites, particularly in contexts where user engagement is crucial. The findings advocate for a strategic shift towards employing more straightforward and user-friendly terminology on the Montana State University Library's website. Implementing "SERVICES" in place of "INTERACT" aligns better with user preferences and behavior, as evidenced by the data. This change is expected to not only improve user experience but also enhance the overall effectiveness of the library’s digital interface in meeting the needs of its student users.
