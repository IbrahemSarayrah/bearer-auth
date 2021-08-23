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
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImlicmFoZW0xMiIsImlhdCI6MTYyOTczNDUxN30.zGlEodUHiKFeKqLrOJdm2Z8H-WLHLNU1SQoOkgfwD4g",
        "id": 27,
        "username": "ibrahem",
        "password": "$2b$10$g8vbbAS6aTq.SydKekA2POm0/WWpWzv/wJHNUNZ6osrxukhVsREi6",
        "createdAt": "2021-08-23T12:47:22.153Z",
        "updatedAt": "2021-08-23T12:47:22.153Z"
    },
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6ImlicmFoZW0xMiIsImlhdCI6MTYyOTczNDUxN30.zGlEodUHiKFeKqLrOJdm2Z8H-WLHLNU1SQoOkgfwD4g"
}

```

### UML

![UML](uml-img/bearer-auth-lab07.png)