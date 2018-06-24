## Create User

http://localhost:3000/explorer/#!/User/User_create

```
{
  "realm": "adminz",
  "username": "adminz",
  "email": "adminz@gmail.com",
  "emailVerified": true,
  "password": "123123"
}
```

## Login

http://localhost:3000/explorer/#!/User/User_login

```
{
  "email": "adminz@gmail.com",
  "password": "123123"
}
```

## Create Post

http://localhost:9999/explorer/#!/Post/Post_create

```
{
  "title": "test post 1 create with swagger ui",
  "body": "test post 1 content which created on web"
}
```

```
{
  "title": "test post 2 create with swagger ui",
  "body": "test post 2 content which created on web"
}
```

## List Post

http://localhost:9999/explorer/#!/Post/Post_find
http://localhost:9999/api/posts
