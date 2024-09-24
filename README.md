This is a repository that tracks works associated with https://github.com/doriantaylor .


```
preston history
```

yields: 
```
<hash://sha256/f2c1fe6dc2c006bc0ba5f2ae63627962916169482c480e4d4747eb9fa4dcb84f> <http://www.w3.org/ns/prov#wasDerivedFrom> <hash://sha256/90d878fba018c5936810d3f61537ef99be3aea61ea21597f575ad4fc548b48e9> .
<hash://sha256/90d878fba018c5936810d3f61537ef99be3aea61ea21597f575ad4fc548b48e9> <http://www.w3.org/ns/prov#wasDerivedFrom> <hash://sha256/1db02bf9e64f1acfee997fce733e29eb4fb7df1cf227692793e0dfbd0e70db84> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/pav/hasVersion> <hash://sha256/1db02bf9e64f1acfee997fce733e29eb4fb7df1cf227692793e0dfbd0e70db84> .
```

```
preston ls\
 --anchor hash://sha256/f2c1fe6dc2c006bc0ba5f2ae63627962916169482c480e4d4747eb9fa4dcb84f
```

yields: 
```
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#SoftwareAgent> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Agent> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<https://preston.guoda.bio> <http://purl.org/dc/terms/description> "Preston is a software program that finds, archives and provides access to biodiversity datasets."@en <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Activity> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <http://purl.org/dc/terms/description> "A crawl event that discovers biodiversity archives."@en <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <http://www.w3.org/ns/prov#startedAtTime> "2024-09-24T16:18:16.398Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <http://www.w3.org/ns/prov#wasStartedBy> <https://preston.guoda.bio> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/ns/prov#usedBy> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://purl.org/dc/dcmitype/Software> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<https://doi.org/10.5281/zenodo.1410543> <http://purl.org/dc/terms/bibliographicCitation> "Jorrit Poelen, Icaro Alzuru, & Michael Elliott. 2018-2024. Preston: a biodiversity dataset tracker (Version 0.9.8-SNAPSHOT) [Software]. Zenodo. https://doi.org/10.5281/zenodo.1410543"@en <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Entity> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/dc/terms/description> "A biodiversity dataset graph archive."@en <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<hash://sha256/90d878fba018c5936810d3f61537ef99be3aea61ea21597f575ad4fc548b48e9> <http://www.w3.org/ns/prov#usedBy> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> .
<hash://sha256/ce8683cd426447943e858c0c59848bd0a38cea99519fa54b485dba107439d81f> <http://www.w3.org/ns/prov#wasGeneratedBy> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<hash://sha256/ce8683cd426447943e858c0c59848bd0a38cea99519fa54b485dba107439d81f> <http://www.w3.org/ns/prov#qualifiedGeneration> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> <http://www.w3.org/ns/prov#generatedAtTime> "2024-09-24T16:18:17.178Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Generation> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> <http://www.w3.org/ns/prov#wasInformedBy> <urn:uuid:9e0d81f9-fe2d-4b48-a814-36d45bd3003b> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> <http://www.w3.org/ns/prov#used> <https://doriantaylor.com/summer-of-protocols/motivation-and-rationale> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<https://doriantaylor.com/summer-of-protocols/motivation-and-rationale> <http://purl.org/pav/hasVersion> <hash://sha256/ce8683cd426447943e858c0c59848bd0a38cea99519fa54b485dba107439d81f> <urn:uuid:5a6fc9ed-f04d-4936-8c5c-78c423eba325> .
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#SoftwareAgent> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Agent> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<https://preston.guoda.bio> <http://purl.org/dc/terms/description> "Preston is a software program that finds, archives and provides access to biodiversity datasets."@en <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Activity> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <http://purl.org/dc/terms/description> "A crawl event that discovers biodiversity archives."@en <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <http://www.w3.org/ns/prov#startedAtTime> "2024-09-24T15:11:28.509Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <http://www.w3.org/ns/prov#wasStartedBy> <https://preston.guoda.bio> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/ns/prov#usedBy> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://purl.org/dc/dcmitype/Software> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<https://doi.org/10.5281/zenodo.1410543> <http://purl.org/dc/terms/bibliographicCitation> "Jorrit Poelen, Icaro Alzuru, & Michael Elliott. 2018-2024. Preston: a biodiversity dataset tracker (Version 0.9.8-SNAPSHOT) [Software]. Zenodo. https://doi.org/10.5281/zenodo.1410543"@en <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Entity> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/dc/terms/description> "A biodiversity dataset graph archive."@en <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<hash://sha256/1db02bf9e64f1acfee997fce733e29eb4fb7df1cf227692793e0dfbd0e70db84> <http://www.w3.org/ns/prov#usedBy> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> .
<hash://sha256/182cd94f60de3b3ab9f4c86c930dfb29cd0b3fd13f3e37a5e153f8fb5bf98b32> <http://www.w3.org/ns/prov#wasGeneratedBy> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<hash://sha256/182cd94f60de3b3ab9f4c86c930dfb29cd0b3fd13f3e37a5e153f8fb5bf98b32> <http://www.w3.org/ns/prov#qualifiedGeneration> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> <http://www.w3.org/ns/prov#generatedAtTime> "2024-09-24T15:11:29.808Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Generation> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> <http://www.w3.org/ns/prov#wasInformedBy> <urn:uuid:a0e2d842-1a2d-4db4-9c97-fcdf00d753f0> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> <http://www.w3.org/ns/prov#used> <https://github.com/doriantaylor/rb-intertwingler/archive/refs/heads/main.zip> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<https://github.com/doriantaylor/rb-intertwingler/archive/refs/heads/main.zip> <http://purl.org/pav/hasVersion> <hash://sha256/182cd94f60de3b3ab9f4c86c930dfb29cd0b3fd13f3e37a5e153f8fb5bf98b32> <urn:uuid:acb77961-5c1d-4444-ad87-b86fef42c7a8> .
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#SoftwareAgent> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Agent> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<https://preston.guoda.bio> <http://purl.org/dc/terms/description> "Preston is a software program that finds, archives and provides access to biodiversity datasets."@en <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Activity> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> <http://purl.org/dc/terms/description> "A crawl event that discovers biodiversity archives."@en <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> <http://www.w3.org/ns/prov#startedAtTime> "2024-09-24T14:45:24.521Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> <http://www.w3.org/ns/prov#wasStartedBy> <https://preston.guoda.bio> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/ns/prov#usedBy> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://purl.org/dc/dcmitype/Software> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<https://doi.org/10.5281/zenodo.1410543> <http://purl.org/dc/terms/bibliographicCitation> "Jorrit Poelen, Icaro Alzuru, & Michael Elliott. 2018-2024. Preston: a biodiversity dataset tracker (Version 0.9.8-SNAPSHOT) [Software]. Zenodo. https://doi.org/10.5281/zenodo.1410543"@en <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Entity> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/dc/terms/description> "A biodiversity dataset graph archive."@en <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> .
<hash://sha256/7a81c3eec1624a88630bd567070999afb3273cccc070e7c97f20b0004d651d11> <http://www.w3.org/ns/prov#wasGeneratedBy> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
<hash://sha256/7a81c3eec1624a88630bd567070999afb3273cccc070e7c97f20b0004d651d11> <http://www.w3.org/ns/prov#qualifiedGeneration> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
<urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> <http://www.w3.org/ns/prov#generatedAtTime> "2024-09-24T14:45:26.413Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
<urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Generation> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
<urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> <http://www.w3.org/ns/prov#wasInformedBy> <urn:uuid:946a9753-ace2-49cc-bcb7-f5e1c5855404> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
<urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> <http://www.w3.org/ns/prov#used> <https://doriantaylor.com/summer-of-protocols/architectural-principles> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
<https://doriantaylor.com/summer-of-protocols/architectural-principles> <http://purl.org/pav/hasVersion> <hash://sha256/7a81c3eec1624a88630bd567070999afb3273cccc070e7c97f20b0004d651d11> <urn:uuid:f8d89052-e520-4651-b29d-2ca51c2b9bd1> .
```
