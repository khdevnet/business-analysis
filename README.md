# Business analysis
## The Language of Modeling
* Shorthand, symbols, standardized notation methods all common in modeling        
* Specific languages used vary by organization and project        
* Consistency is key, regardless of language 
* Develop definitions and use shapes and colors in commonly understood ways

## Scope Models
Used to organize thoughts on feature sets, functional capabilities, and scope of work       
Primarily focused on higher-level generation and understanding of requirements
### *Goal & Business Objective Models*
(Goals, Problems, Objectives, Success Metrics, High-Level Features)
Problems and objectives tied together to represent creation of value        
Value may be represented by increased revenues, decreased costs, higher quality, greater risk resilience, etc.      
Indicates why objectives are important, helpful in prioritizing selection/resources     
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-scope-models-goal-and-business.png)

### *Ecosystem Maps*
(Shows systems and their relationships, May indicate how data moves, Systems in scope and those impacted by or impacting data should be included)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-scope-models-eco-system-maps.png)

### *Context Diagrams*
(Shows both system and human interfaces, Indicates scope of project and where new work may be needed to meet objectives, System in development at center shown, as a circle; systems and people as boxes; lines indicate data movement)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-scope-models-context-diagrams.png)

### *Feature Models*
(Hierarchical representation of all features, Features may encompass several related requirements, Up to three levels typically used in model, Color differences may be used to represent current status of features)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-scope-models-feature-models.png)

### *Use Case Diagrams*
(Represents ways users interact with the system, and for what purposes; Typically, use cases in circles connect to figures representing types of users; Multiple users may be tied to multiple use cases)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-scope-models-use-cases.png)

## Process Models
Focused on how processes complete work and meet objectives      
Analyzes how stakeholders interact with, impact, and are impacted by, processes

### *Process flows*
(Illustrates how work is completed; Typically human focused; sometimes referred to as system flows when analyzing processes involving systems; May be used to model current or proposed workflows)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-process-models-process-flows.png)

### *Use cases*
(Description of how goals are achieved through a series of actions and processes; Typically text or table-based in nature; Focus on functional qualities of systems; Hones in on specific scenarios)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-process-models-use-cases-1.png)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-process-models-use-cases-2.png)

### *User stories*
(Narrative statement describing required functions and features of a solution; Written from user’s point of view, describing how they interact with a system, and for what purpose)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-process-models-user-stories.png)

#### Effective User Stories
##### Independent
* User stories should typically be independent of others, focusing on its own area with little overlap
* Stories should typically be focused enough in scope to be addressed in one iteration of an agile project
##### Negotiable
* Stories remain subject to change right up until implementation occurs
* Early drafts of stories can spark stakeholder engagement, lead to better solutions with broader support
* All elements of stories subject to changes
##### Valuable
* Must communicate how function or action solves problems and meets needs
* Well-crafted stories make a strong connection to value, illustrate value clearly
##### Estimable
* Should either include an estimation of resources expended or provide enough specificity to allow estimations to occur
* Stories may be revised closer to implementation to allow for better estimates
##### Small
* Must be large enough to offer value, yet small enough to be implemented within a single iteration of an agile project
* Stories too small may lead to questions of scope validity
* Stories too large may be better restructured as epics
##### Testable
* Value should be clear and story elements should be verifiable by others
* Weak verification may indicate weak traceability, raising questions about story’s benefit to meeting needs

## Rule Models
Focused on ensuring business policies are adhered to by defining and limiting acceptable actions        
Rules may be internal, contractual, Rule Models regulatory, legal, etc.

### *Business rules catalogs*
(Depict limitations on conduct of work; May be imposed on project, project’s result, or a combination; Rules may be internal, contractual, regulatory, or legal in nature; Source and context of rules key to understanding and adherence)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-rule-models-business-rules-catalogs.png)

### *Decision trees & tables*
(Visualize the results of a series of decisions; Helpful tool to model many possibilities, especially where each decision has an impact on those subsequent to it)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-rule-models-decision-tree.png)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-rule-models-decision-table.png)

## Data Models
Determines how, when, and where data is obtained        
Outlines how data is used in systems and processes      
### *Entity relationship diagrams*
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-data-models-entity-relationship.png)
### *Data flow diagrams*
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-data-models-data-flows.png)
### *Data dictionaries*
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-data-models-data-dictionaries.png)
### *State diagrams*
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-data-models-data-state.png)
### *State tables*
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-data-models-state-table.png)

## Interface Models
Focused on making specific systems morecomprehensible and relevant      
Addresses how systems are integrated and how they contribute to objectives
### Report tables
(Catalog of detailed requirements for a particular report; Useful when determining what type of reports can meet business needs, and
what information should be included; Very helpful to include a template or example of the report with the table;Includes all details regarding requirements for how systems are integrated)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-interface-models-report-table.png)
### System interface tables
(Outlines all requirements for specific system interfaces; Both source and target requirements usually included; Includes names, descriptions, and other useful attributes for each object)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-interface-models-sytem-interface-table.png)
### User interface flows
(Simulates or visualizes how users interact with a system; Models range from simple flowcharts to full-blown simulations; May focus on specific functionality or represent an entire system/application)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-interface-models-user-interface-flows.png)
### Wireframes + Display-action-response models
(Often accompanies user interface flows; Outlines all user-facing elements; Includes descriptive table for each user-facing object and function; Business analyst or specialist may be responsible for reviewing wireframes; Critical for wireframes to meet requirements while following best practices for design and usability)
![](https://github.com/khdevnet/business-analysis/blob/master/src/business-analysis-interface-models-wireframes.png)

