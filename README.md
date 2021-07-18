# Pregnancy_Infomation_Needs_Ontology
Pregnancy Infomation Needs Ontology (PINO)

PINO contains information across all stages of pregnancy (pre-pregnancy, during pregnancy, and postpartum). To develop PINO, one researcher first enumerated important terms about pregnancy information needs based on the 34 papers about pregnancy-related information needs published between 2009 and 2019. The goal of the enumeration was to obtain a comprehensive list of the terms. As certain terms may overlap with others in the meaning they represent, the researcher then synthesized these terms that convey similar meanings.  In the next step, the researcher developed class hierarchy using a top-down approach and the resulting hierarchy organizes information into themes and sub-nodes. The last step defined the properties of terms. PINO consists of 267 classes, 555 axioms, and 271 subclass relationships.

To review the ontology through human evaluators, we utilized Hootation (Amith, et al., 2017) that transforms ontology axiom statements from an OWL or RDF file to natural language. For example, an encoded rdfs:SubclassOf axiom like "Morning_sickness ⊑ Maternal_complication" would be translated to "every morning sickness is a maternal complication" (Figure 8). As human friendly language, evaluators who are not necessarily ontology experts could potentially give feedback on accuracy of the ontology. 

For this initial work, we enlisted four evaluators to independently review the statements on a spreadsheet. Out of four evaluators, two are ontologists and informaticists, three are health consumers, one is a medical student. Evaluators were asked to label the accuracy of the statement, either as Y for "Yes" (statement is accurate), N for "No" (statement is inaccurate), or X for "don't know" (unsure if the statement is accurate). They were also instructed to make any special notes for clarification or feedback if necessary. In the evaluation with the first version of PINO, out of 307 natural language statements, 55 were marked “N” by at least 2 evaluators. We used their feedback to remove certain concepts and improve the concept labelling and categorization. For example, most children of “Gestational diabetes” were deemed problematics so they were removed from PINO

For more information about PINO, please contact Dr. Zhe He at zhe@fsu.edu
