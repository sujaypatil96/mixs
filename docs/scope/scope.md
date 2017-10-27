The MIxS is a specification of sequence metadata descriptors. It consists of a core, checklist-specific metadata descriptors, and environment-specific descriptors.

Throughout the development of MIGS, MIMS, MIMARKS, and various environmental packages, the GSC followed these criteria:
* Should be technologically neutral
* Should allow the establishment of practical, user-friendly, flexible sequence and sequence metadata submission systems
* Should be based on metadata descriptors that are most relevant for the community
* Should include clearly defined pieces of information using values selected from controlled vocabularies/ontologies
* Should be an appropriate extension of existing INSDC contextual data qualifiers 
* Should be objective facts about sequences (data that, ideally, the generators of a sequence can best provide)
* Collaborate with INSDC and other relevant repositories to define the modus of sequence & contextual data submission

The core consists of most commonly used and accepted minimum metadata to ensure sequence data comparison, analysis, and interoperability.

<img src="http://gensc.org/files/2015/07/Slide1.jpg"/>

It is expected that in most situations, researchers would use the MIxS core exclusively and the sequence metadata would not contain any additional elements. However, in some cases, researchers, or projects may want to extend MIxS core with additional metadata to provide more context for their sequences. This can be achieved by using checklist specific metadata descriptors and environmental package metadata descriptors. 

<img src="http://gensc.org/files/2015/07/migs.jpg" width=500/>
<img src="http://gensc.org/files/2015/07/mims.jpg" width=500/>

While additional metadata descriptors included in the MIxS specification are very extensive, some cases might require additional specific metadata requirements. These specific requirements can be implemented using information elements that extend the MIxS metadata descriptors. Any such extension needs to respect the semantic definitions of the MIxS specification. 
Depending on the researcher or project needs, there are several ways to extend the MIxS specification. There are explained in detail in the following sections:
* [Environmental package](https://github.com/GenomicsStandardsConsortium/MIxS/wiki/env_package)
* [Checklist](https://github.com/GenomicsStandardsConsortium/MIxS/wiki/env_package)
* [Profile](https://github.com/GenomicsStandardsConsortium/MIxS/wiki/env_package)