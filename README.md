# docker-solr-search_api_solr
Set up a Solr 5.x instance in Docker, automatically configured with search_api_solr's settings.

### Installation
1. Clone the repository: `git clone --recursive https://github.com/alan-ps/docker-solr-search_api_solr`;
2. Go to docker-solr-search_api_solr repository and build an image: `sudo docker build -t solr-search_api_solr .`;
3. Start a container from the image: `sudo docker run -p 8983:8983 -d solr-search_api_solr`;

### Usage
Solr will be available by the next address: http://localhost:8983.

After performing the operations above, two solr cores will be created (d7_collection and d8_collection). They can be used for your Drupal projects.

ref: https://github.com/mparker17/docker-solr-search_api_solr
