## Facebook like Feed Management

this will be feed api response to view all post of his friend. 

**Retrieve the user's feed, showing posts from friends and possibly others**
```
[
  {
    "post_id": "string",
    "user_id": "string",
    "content": "string",
    "created_at": "date",
    "comments": [
      {
        "comment_id": "string",
        "user_id": "string",
        "content": "string",
        "created_at": "date"
      }
    ]
  }
]

```

- Visibility Based on Friendship: Users can see posts from their friends.

- Limited Visibility for Non-Friends: Users can see posts from non-friends only if a friend has commented on them.