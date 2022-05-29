# API Index

These APIs can be used to programatically interact with ZincSearch.

All APIs must have an authorization header. Authorization header can be created using base64 encoded values of user id and password. For the sake of simplicity it is HTTP basic authentication mechanism.



Header creation mechanism:

> Authorization: Basic base64("userId:password")

e.g. Header:

> Authorization: Basic YWRtaW46Q29tcGxleHBhc3MjMTIz

Make sure that you are sending the requests over HTTPS.

## API List

1. [CreateIndex](create-index)
1. [DeleteIndex](delete-index)
1. [ListIndexes](list-indexes)
1. Search
    + [Basic Search](search/1_search)
    + [Aggregation](search/aggregation)
    + [Search - Elasticsearch compatible](search/seacrh-es)
    + [Search types](search/search-types)
6. [UpdateDocumentWithId](update-document-with-id)
7. [UpdateDocument](update-document)
8. [DeleteDocument](delete-document)
9. [UpdateDocumentsBulk](update-documents-bulk)
10. [UpdateIndexMappings](update-index-mappings)
11. [GetIndexMappings](get-index-mappings)
12. [Version](version)
13. [Metrics](metrics)
14. [CreateUpdateUser](create-update-user)
15. [DeleteUser](delete-user)



