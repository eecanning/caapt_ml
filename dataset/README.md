# Critical cataloguing annotation dataset

This dataset contains annotations for 5,000 V&A Museum records containing 5 potentially problematic terms. 
Each record is annotated by 2-3 annotators. 

Columns: 
- classification_id: unique ID of the classification (zooniverse) 
- user_id: unique ID of the annotator (zooniverse)
- subject_id: unique ID of the field+text+term (zooniverse)
- object_id: unique ID for the object
- object_field: name of the record field the text is pulled from
- object_text: text
- term: potentially problematic term present in the object_text
- form: form of the potentially problematic term present in the object_text
- TSC: annotation of what the term is naming, describing, or referring to
- TSC - other: annotation contents when the TSC option selected was "other"
- TSD: annotation of the sense meaning of the potentially probleamtic term as it is being used in object_text
- TSD - other: annotation contents when the TSD option selected was "other"
- RLP: annotation of whether or not the use of the term is problematic and requiring of review of revision
- RAP: annotation of what action to take next when the RLP option selected was "yes"
- CWP: annotation of whether or not a content warning is rquired when the RLP option selected was "yes"
