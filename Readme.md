# ECO-AGRIC BACKEND SUB-DOCUMENTATION

NOTE: This repo focuses on the recent scrum development. For more documentations please refer to the __main repo__

## _Introduction_

You are welcome, please explore the documentation and satiate your query. Also this is subject to continous modifications, For *PM*, any changes or conflicts should be first communicated with the team lead. 

## _Routes_

#### BOOKMARKS

## Endpoint: /api/v1/bookmark

---

--
`   GET /api/v1/bookmark/
  `

- User majorly creates a new bookmark record. One record per user

--
`   PATCH /api/v1/bookmark/:id
  `

- User updates bookmark stored on database.

--
`   DELETE /api/v1/bookmark/:id
  `

- User deletes their bookmarks, for any _un-bookmark_ please use the update api url 

#### LIKE

## Endpoint: /api/v1/like

---


--
`   POST /api/v1/like/
  `

- Fetches all liked posts by user

--
`   DELETE /api/v1/like/:id
  `

- Deletes a like record.


#### COMMENT
## Endpoint: /api/v1/comment

---

--
`   POST /api/v1/comment
  `

- create a comment for a post

--
`   DELETE /api/v1/comment/:id
  `

- deletes particular comment using id

--
`   GET /api/v1/comment/
  `

- get all comments for display in comment component of a post

<!-- --
`   PATCH /api/v1/comment/:id
  `

- update edits to particular comment -->


<!--
 -->
## License

MIT