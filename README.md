# Wrap-up BIDS and NIDM-E

It is a great milestone to foster the complementary of both standards with the mapping from JSON attributes in BIDS to NIDM-experiment URLs. Indeed, NIDM adds to BIDS the capability to track provenance and disambiguate experimental details and data elements. 

This document will discuss how close/different those representations are, what could be done in future work to make them closer and what are the issues (if any) that seem much harder to solve.

Currently, only a few numbers of attributes are commons between the two standards. 

According to the information provided in http://nidm.nidash.org/specs/nidm-experiment_dev.html and with analysis between BIDS and NIDM-Experiment we can assess that: 
    1. The definition of attributes is more complete and relevant in NIDM.
    2. There is a substantial number of attributes related to acquisition method, data and image acquisition device, image usage type, image contrast type and k-space traversal scheme that do not appear in BIDS.
    3. BIDS provides more information on the patient (age, ethnicity, sex, race...).

In the future, we could provide proper definitions to bids attributes as it was done for NIDM terms. Then, we must gather the information from both standards by adding the BIDS terms in an ontology file. Moreover, when two terms defined the same concept, we favour the bids term because nowadays the bids standard is more widely adopted by the neuroimaging community. 

