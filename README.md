## README

### Demo
[Demo](http://apis.expaenergy.lclients.ru/login)
*demo:demo*

You can seed testing data on your local project. Enter `rake db:seed` in terminal for create demo user and/or seed posts for him. 

### API
`your_key` - it's your api key in the system. You can find it on the API page.

#### Posts
Get posts list `/api/posts?api_key=your_key`

Get a specific post `/api/posts/:id?api_key=your_key`

Search posts by tags `/api/posts?api_key=your_key&tags=rails,ruby`

#### Users
Tags of user(on the Settings page): `/api/tags?api_key=your_key`

Avatar: `/api/avatar?api_key=your_key`
