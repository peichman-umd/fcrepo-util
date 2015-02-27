# fcrepo-util
Utility scripts for working with Fedora 4

## clearsolr

Delete all documents from a Solr core.

## deleteurls

Given a list of URLs, delete those resources.

## getchildurls

Given a list of N-triples on STDIN, or arguments to curl, gets a
list of the URLs that are the objects of ldp:contains statements.

## ldp-contains

Given a list of N-triples on STDIN, gets a list of the URLs that
are the objects of ldp:contains statements.

## reindex

Request a reindexing of the repository content via the JMS message
consumer service.
