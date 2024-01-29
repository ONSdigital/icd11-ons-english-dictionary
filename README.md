## Contents
This ICD-11 English dictionary product is made of 4 sets of txt files:
- Dictionary: entries and ICD-11 codes allocated by the Office for National Statistics (ONS) for use with the Iris software;
- Standardisation(0,1,2): standardisation rules applied by ONS for use with the Iris software;
- Separators: separator rules applied by ONS for use with the Iris software;
- TimeIntervals: time interval rules applied by ONS for use with the Iris software.

## Instructions for use
Files can be:
- imported individually into a database management system (e.g. Microsoft Access)
- combined to create a dictionary (e.g. using a Python script)

> [!TIP]
> Microsoft Access can have problems when importing regular expressions. If you see such an issue try copying and pasting the content of the problematic table over itself.

## Disclaimers
- This ICD-11 English dictionary is owned by the [Office for National Statistics](https://www.ons.gov.uk/) (ONS). It is developed by ONS based on the causes of deaths that have occurred in England and Wales. Neither the [Iris Institute](https://www.bfarm.de/EN/Code-systems/Collaboration-and-projects/Iris-Institute/_node.html) nor the [World Health Organization](https://who.int/) (WHO) are involved in this ICD-11 English dictionary design, creation and development.
- Some entries in the Separators file and all entries in the TimeIntervals file were created for the ICD-10 dictionary, as a result of a joint international effort. These records have been routinely used in all Iris versions ever since they were added to the product.
- [The International Classification of Diseases, Eleventh Revision (ICD-11)](https://icd.who.int/en/) is produced and owned by the World Health Organization. (International Classification of Diseases Eleventh Revision (ICD-11). Geneva: World Health Organization; 2022. License: CC BY-ND 3.0 IGO.)
- The Iris Institute owns the deployment, maintenance and development of the Iris software, an electronic system for automated coding of causes of death.
- The product is shared free of charge by ONS to aid Iris software testing in other countries.
- This ICD-11 English dictionary is provided on an "as is" and "as available" basis. It is ongoing work by ONS, and will be updated as and when deemed necessary. ONS does not commit to updating the product at regular intervals.
- ONS cannot offer support to other countries in terms of responding to queries, adding ad hoc entries, amending codes to suit a specific country need, etc.
- The "Comments" column in the Dictionary.txt file is empty, comments from the original ONS source have been removed as they are for internal use only. Some terms are mapped to codes that don’t yet exist, but are in the dictionary because ONS anticipate them being created before going into production. A proposal has been raised to WHO for each of these terms.
- If you find a dictionary or standardisation entry in these files that you believe is universally wrong, please log an issue using the [GitHub Issues](https://github.com/ONSdigital/icd11-ons-english-dictionary/issues) function from the repository and the [Issue template](https://github.com/ONSdigital/icd11-ons-english-dictionary/issues/new/choose) provided.
- As you are free to copy, adapt and re-distribute this product, you should consider forking this repository and customising it to suit your needs.
- The license used for the release of this ICD-11 English dictionary (see the following section) doesn’t cover personal data, therefore the only value present in the “UserIn”/“UserOut” columns (the owners of addition/removal of a file item) is NA (Not Available).

## License
This product is released under version 3 of the [UK Open Government Licence](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
