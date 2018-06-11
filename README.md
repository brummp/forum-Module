# forum-Module
InformationPlatform Forum Module

## Database Struct

list data
```json
{
  "post_time" : 1528720726,
  "post_title" : "somestring",
  "tag" : ["sometag"],
  "author" : "someone",
  "reply_count" : 10,
  "visited" : 10,
  "last_comment" : "someone",
  "last_comment_time" : 1528720726
}
```

detail data
```json
{
  "post_title" : "somestring",
  "post_content" : "long string",
  "tag" : ["sometag"],
  "reply_count" : 10,
  "visited" : 10
}
```

comment data
```json
{
  "comment_time" : 1528720726,
  "comment_author" : "someone",
  "comment_content" : "long string",
  "reply_to_comment_id" : -1
}
```
*reply_to_id means reply to a specific floor, while "-1" means reply to post author*