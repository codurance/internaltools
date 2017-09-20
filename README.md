# Internal Tools Repository

This is the single *proposed* repo to manage all services for our internal tools. At the high-level each service will master the data that it owns and refer to other services for the data that it doesn't own. It may keep view only copies of that data, however, for now the service that maintains the copy will be responsible for refreshing it.

The initial proposed services are:

| Service         | Responsibility |
|-----------------|----------------|
| Authentication | Centerally manage a User's identity, We will used Google Directory with OAuth2 |
| User | Keep user data in a single place, Will keep name, privilages/roles associated with the identitry, date-created, and active/inactive flag.|
| Memento | Keep track of time spent by individuals against activities (for now outside the repository - to be moved in) |
| Monitor | Keeps track of accounts and provides dashboard view on financials (for now outside the repository - to be moved in) |
| Expenses| Allow everyone to easily submit and process expenses | 
| Projects| Keeps track projects (internal/external), activities within those projects duration etc. | 
| Merlin  | Allocation of people to projects, allows us to effectively manage project commitments. |
| Clients | Allow us to manage our relationship with clients |

## Documentation

All documentation for the internal tools should be managed in the wiki for this repository


## Planning and Coordination

We propose to create a Trello Board for the internal tools features
