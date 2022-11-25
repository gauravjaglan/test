# Stats

[Back to README](./README.md)

#### /api/stats (GET)

#### Description

Return stats of ontologies read in the application.

#### Example Response

```json
{
   "stats":{
      "@viewer.stats.numberOfDomain":10,
      "@viewer.stats.numberOfModule":9,
      "@viewer.stats.numberOfClass":2186,
      "@viewer.stats.numberOfObjectProperty":995,
      "@viewer.stats.numberOfDataProperty":247,
      "@viewer.stats.numberOfAnnotationProperty":106,
      "@viewer.stats.numberOfIndividuals":1867,
      "@viewer.stats.numberOfAxiom":39656,
      "@viewer.stats.numberOfDatatype":21,
      "@viewer.stats.numberOfOntologies":146
   },
   "labels":{
      "@viewer.stats.numberOfDomain":"Number of domains",
      "@viewer.stats.numberOfModule":"Number of modules",
      "@viewer.stats.numberOfClass":"Number of classes",
      "@viewer.stats.numberOfObjectProperty":"Number of object properties",
      "@viewer.stats.numberOfDataProperty":"Number of data properties",
      "@viewer.stats.numberOfAnnotationProperty":"Number of annotation properties",
      "@viewer.stats.numberOfIndividuals":"Number of individuals",
      "@viewer.stats.numberOfAxiom":"Number of axioms",
      "@viewer.stats.numberOfDatatype":"Number of datatypes",
      "@viewer.stats.numberOfOntologies":"Number of ontology modules"
   }
}
```
