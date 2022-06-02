# sequential_pattern_mining_association_rules

A patient’s journey is often not straightforward. For example, a patient with rheumatoid arthritis may take years to figure out the correct diagnosis and treatments. Initially, she experiences pain, but she does not know what causes the pain. She may see a family doctor first, who then refers her to a physical therapist, before she eventually sees a rheumatology specialist. She may get vague diagnoses first, such as sciatica, myalgia, pain, fibromyalgia, before eventually narrowing down to rheumatoid arthritis. The doctors may request a series of testing, including ultrasound, radiograph, MRI, blood count etc. Finally, she may try different treatments, including methotrexate, Humira, and Enbrel etc.

Using claims data and association rules, we can uncover the most common sequence of events.

**WARNING: sequential pattern mining and association rules are actually different. cSPADE from R can handle temporal data. But packages such as apriori and association rules from python DOES NOT take into account temporal information.**

**R file and outputs:**
* sequential_pattern_mining_ra.R
* top_results.csv
* all_results.csv

**Python file and output:**
* association_rules.ipynb
* association_rules_results.csv
