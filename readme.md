## PlanQK Ontology
PlanQK ontology represents knowledge about quantum computing algorithms along with their implementations. The ontology serves as basis for the planqk platform (is under development)  - a collaborative platform for researchers and practitioners to support collection and development of knowledge on the field of quantum computing.

## Ontology Sources
The ontology is provided in different formats in the folder `sources`. You can open it with a text editor or using an ontology editor, f.e. [Protégé ](https://protege.stanford.edu/)
**After you load the QCO ontology into the editor, make sure you handle needed imports.**  
##### Imports:  
Import [SRAO](https://github.com/PlanQK/semantic-services/blob/master/sources/srao_edited.owl) and [SPDX](https://github.com/PlanQK/semantic-services/blob/master/sources/spdx.ttl) as local files by using tab "Ontology imports" in the Protégé-Editor:
   ![image](https://github.com/PlanQK/semantic-services/assets/63393143/6d040389-c409-4c05-b376-a3075a4b7540)

##### For a better readability:  
1) In Protégé-Editor open: "File" -> Preferences.
2) In the tab "Renderer" choose "Render by annotation property"


## Ontology Documentation
The documentation for the ontology can be started locally as a web application:
1. Install `http-server`. F.e using npm: 
  *  install Node.js
  *  run `npm install http-server -g`
2. Clone the project, go to the project directory `documentation`.
3. Run `http-server -p 8081 -c-1` and go to the http://localhost:8081/index-en.html (documentation) or http://localhost:8081/webvowl/ (visualization).

## License
PlanQK ontology is available for general use under a CC BY-SA 4.0 licence.

## Tools Used
[Protégé](https://protege.stanford.edu/) has been used to create and curate the OWL-file.
[Widoco](https://github.com/dgarijo/Widoco) has been used to create the ontology documentation.
[WebOWL](http://vowl.visualdataweb.org/webvowl.html) has been used to visualize the ontology.

## Contact Us
Please feel free to contact us at darya.martyniuk@fokus.fraunhofer.de.
