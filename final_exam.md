######Class started: Aug 05, 2014

######Note: MongoDB University change the answers slightly so please don't copy these answers

#####Question 1

######Same question and answer as M101JS

```javascript
"3"
```

#####Question 2

######Same question and answer as M101JS

```javascript
"susan.mara@enron.com to jeff.dasovich@enron.com"
```

#####Question 3

######Same question and answer as M101JS but the email address is @10gen.com vs @mongodb.com

```javascript
db.messages.update({"headers.Message-ID":"<8147308.1075851042335.JavaMail.evans@thyme>"},{$addToSet:{"headers.To":"mrpotatohead@10gen.com"}})
```

#####Question 4

Add

```java
postsCollection.update(new BasicDBObject("permalink", permalink), new BasicDBObject("$inc", new BasicDBObject("comments." + ordinal + ".num_likes", 1)));
```

to

```java
"BlogPostsDAO.java"
```

#####Question 5

######Same question and answer as M101JS

```javascript
"a_1_b_1"
"a_1_c_1"
"c_1"
"a_1_b_1_c_-1"
```

#####Question 6

######Same question and answer as M101JS

```javascript
"Remove all indexes from the collection, leaving only the index on _id in place"
"Set w=0, j=0 on writes"
```

#####Question 7

######Same question but different answer to M101JS

```javascript
44,787
```

#####Question 8

```javascript
1
```

#####Question 9

######Same question and answer as M101JS

```javascript
"patient_id"
```

#####Question 10

######Same question and answer as M101JS

```javascript
"The query did not utilize an index to figure out which documents match the find criteria."
"The query used an index for the sorting phase."
"The query performed a full collection scan."
```
