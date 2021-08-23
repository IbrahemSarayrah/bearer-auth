# bearer-auth

## LAB - 07

### Author: Ibrahem Sarayrah

### LINKS

* [github action](https://github.com/IbrahemSarayrah/bearer-auth/actions)

* [github action test](https://github.com/IbrahemSarayrah/bearer-auth/runs/3402414570)

* HEROKU Prod : [https://ibrahem-bearer-auth.herokuapp.com/](https://ibrahem-bearer-auth.herokuapp.com/)

* pull request : [https://github.com/IbrahemSarayrah/bearer-auth/pull/1](https://github.com/IbrahemSarayrah/bearer-auth/pull/1)

### Setup

* **.env** requirements:
>
> PORT=3000
>
> DATABASE_URL=postgres://localhost/lab07
>
> SECRET=super-secret
>
### Running the app

* npm start / nodemon

* Endpoint: `/signin`
* Endpoint: `/signup`
* Endpoint: `/users`
* Endpoint: `/secret`

* Returns Objects

```

{
    "user": {
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImlicmFoZW0iLCJpYXQiOjE2Mjk3Mzc3ODJ9.QShYT7Ho5yvkFKQrZ3_8SM-U6Zv7ybPQSBis2DRdFbE",
        "id": 1,
        "username": "ibrahem",
        "password": "$2b$10$zfTqBTtCljc8nXK4//83LeNQGxprZr7GE1NrfP53mmlyyv6Kl8FUW",
        "createdAt": "2021-08-23T16:16:29.871Z",
        "updatedAt": "2021-08-23T16:16:29.871Z"
    },
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImlicmFoZW0iLCJpYXQiOjE2Mjk3Mzc3ODJ9.QShYT7Ho5yvkFKQrZ3_8SM-U6Zv7ybPQSBis2DRdFbE"
}

```

### UML

![UML](uml-img/bearer-auth-lab07.png)
