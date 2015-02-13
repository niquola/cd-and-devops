## Deploy automation

### multi channel ssh, capistrano etc

### chef & ansible

### image as deploy artefact

### database migrations

Come from Ruby On Rails.

* Write incremental scripts, to update database schema.
* Keep metadata in database
* Dump schema for tests
* Seeds
* Write rollback scrip
* Pre and Post conditions
* Write tests on migrations
* Play migrations on staging

Special cases:
* two step migrations
* background processing
* lazy update

#### [flywhy](http://flywaydb.org/)

With techniques such as continuous delivery becoming more mainstream, automated database migrations are a baseline capability for many software teams. While there are many tools in this space,
we continue to recommend Flyway for its low-friction approach.
