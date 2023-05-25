# Babylonian Talmud Case Data
Data accompanying investigation of case narratives of the Babylonian Talmud as social network.   

### Documents
* **BabTalmudCases.csv**: A list of cases from the Babylonian Talmud. Column headings:    
    * **sortable**: Citation scheme that is sortable to canonical order.    	
    * **citation_engl**
    * **citation_heb**	
    * **attribution_chain**: Narrative is introduced by attribution	
    * **attributions_cited_in_story**: Narrative contains attributed statements
    * **rabbis_mentioned_in_sequel** 	
    * **party_or_parties**: Persons coming for judgment	
    * **party_ids**: Unique identifiers for parties. (Where known rabbis, use Satlow-Sperling ids)	
    * **judge**	
    * **sper_sat_id**: Unique identifiers for judges (generally following Satlow-Sperling ids).
    * **judge_gen**: Conventional assignment to generations (after Albeck 1969)	
    * *Legal areas:* **Ri**(itual); **Pu**(rity); **St**(atus); **Pr**(operty); **Vows**; **Oth**(er)	
    * **rabb_actor**: Whether parties to case include members of rabbinic circles
    * **explicit_case**: Whether the matter at issue is derived from context or stated in the narrative. 
* **CasesSupplementaryData.md**: Supplementary data on cases
* **CasesNodes.csv**: Working node list for SNA analysis of Babylonian Talmud cases
* **CasesEdges.csv**: Working edge list for SNA analysis of Babylonian Talmud cases
