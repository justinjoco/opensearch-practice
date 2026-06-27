# opensearch-practice
Java 21 practice with Opensearch

Planned features:
- REST APIs for searching and saving
  - Search does fanout with virtual threads
  - Saving goes to a specific opensearch "regional cluster" or all
- Simulated multi-region opensearch clusters with multiple opensearch containers with different localhost ports and passwords
- Indexes with read and write aliases; index templates with time-based backing indexes
- Schema mappings with migrations
- Use of Opensearch Java client for querying and searching
- Dockerized app that connects to docker-compose Opensearch container
