ES-Search
=========

Introduction
------------

Es-search is an web application using elasticsearch.
With essearch you can Send, Look for and find all your documents.
 

Installation
------------



Setup
-----


RESTFul API
-----------

### POST

```
curl -XPOST 'localhost:9200/doc/{index}/{type}/{id}/'      : Add a document to the search engine    					 
```

### GET
 
```
curl -XGET 'localhost:9200/doc/{id}/'  			 	       : Get a document in the default index/type  (doc/docs)    	 
curl -XGET 'localhost:9200/doc/{index}/{id}/'     		   : Get a document in a specific index with default type (docs) 
curl -XGET 'localhost:9200/doc/{index}/{type}/{id}/'       : Get a document in a specific index/type   			 	     
```

### DELETE

```
curl -XDELETE 'localhost:9200/doc/{id}/'  			 	   : DELETE a document in the default index/type  (doc/docs)        
curl -XDELETE 'localhost:9200/doc/{index}/{id}/'     	   : DELETE a document in a specific index with default type (docs) 
curl -XDELETE 'localhost:9200/doc/{index}/{type}/{id}/'    : DELETE a document in a specific index/type   			 	    
```

### GET
 
curl -XGET 'localhost:9200/doc/{id}/'  			 	       : Get a document in the default index/type  (doc/docs)    	 
curl -XGET 'localhost:9200/doc/{index}/{id}/'     		   : Get a document in a specific index with default type (docs) 
curl -XGET 'localhost:9200/doc/{index}/{type}/{id}/'       : Get a document in a specific index/type   			 	     
