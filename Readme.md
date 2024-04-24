# ECO-AGRIC BACKEND SUB-DOCUMENTATION

NOTE: This repo focuses on the recent scrum development. For more documentations please refer to the __main repo__

## _Introduction_

You are welcome, please explore the documentation and satiate your query. Also this is subject to continous modifications, For *PM*, any changes or conflicts should be first communicated with the team lead. 

## _Routes_

#### BOOKMARKS

## Endpoint: /api/v1/users

---

--
`   POST /api/v1/bookmark/
  `

- User majorly creates a new bookmark record. One record per user

--
`   POST /api/v1/bookmark/:id
  `

- User updates bookmark stored on database.

--
`   DELETE /api/v1/bookmark/:id
  `

- User deletes their entire bookmarks, for any _un-bookmark_ please use the update api url 

<!-- ### Rooms

## Endpoint: /api/v1/rooms

---

--
`   GET /api/v1/rooms
  `

- Fetches all rooms | Optional query parameters to filter the rooms by name, roomType and price.

--
`   GET /api/v1/rooms/:id
  `

- Fetches a single room by ID.

--
`   POST /api/v1/rooms/
  `

- Creates a new room. Required: name, roomType and price. Protected route (ONLY ADMIN)

--
`   PATCH /api/v1/rooms/
  `

- Updates a room. Required: id. Optional: name, roomType or price. Protected route (ONLY ADMIN)

--
`   DELETE /api/v1/rooms/
  `

- Deletes a room. Required: id.

## Endpoint: /api/v1/roomsTypes

---

--
`   GET /api/v1/roomsTypes
  `

- Fetches all types of rooms.
 
--
`   POST /api/v1/roomsTypes
  `

- Creates a new type of room. Only possible options to create are: ["Single", "Double", "Triple", "Studio", "Suite", "Presidential Suite"]. Protected route (ONLY ADMIN)

 -->
## License

MIT