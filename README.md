# Social Media App with Ruby on Rails

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

On this milestone, we finally deployed our app to Heroku so that it can be accessed everywhere. We managed to finish creating all the Social Network functionality and features for an MVP deployment with industry-standard style and high-quality code. You can access the live version of the website from [here](https://ancient-bastion-12309.herokuapp.com/users/sign_in).

![screenshot1](images/screenshot02.png)

![screenshot1](images/screenshot01.png)

![screenshot1](images/screenshot03.png)

![screenshot1](images/screenshot04.png)

## Live Version

https://ancient-bastion-12309.herokuapp.com/users/sign_in

## Built With

- Ruby v2.6.5
- Ruby on Rails v5.2.4

## Getting Started

To get started with the app, cd to the directory where you would like the repo to live by typing on your terminal:

```
$ cd <directory>
```

Clone the repo typing:

```
$ git clone git@github.com:shubham14p3/ror-social-scaffold.git
```

Install the needed gems:

```
$ bundle install
```

Next, initialize the pre-build database with seeds :

```
$ rake db:seed
```

and then

```
$ rake db:setup

```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, start server:

```
$ rails server
```

Open `http://localhost:3000/` in your browser.

### Prerequisites

Ruby: 2.6.3
Rails: 5.2.3
Postgres: >=9.5

### Run tests

```
  rpsec spec/features/users/users_spec.rb

  psec spec/features/users/friends_spec.rb

  rpsec spec/features/users/login_spec.rb
```

## Authors

👤 **Luis Angel Maldonado**

- Github: [@lmaldonadoch](https://github.com/lmaldonadoch)
- Twitter: [@LuisAngelMCh](https://twitter.com/LuisAngelMCh)
- LinkedIn: [lmaldonadoch](https://www.linkedin.com/in/lmaldonadoch)

👤 **Shubham Raj**

- Github: [@ShubhamRaj](https://github.com/shubham14p3)
- LinkedIn: [Shubham14p3](https://www.linkedin.com/in/shubham14p3/)

## Future Updates

- Will be re-degiging all the styling css to custom.
- Bootstrap needs some more working.
- More Logics will be added.
- The model will be divided into sub specific components.
- More Validation rules will be applied.

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/shubham14p3//ror-social-scaffold/issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Project requested by [Microverse Program](https://www.microverse.org/).

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/shubham14p3/members-only.svg?style=flat-square
[contributors-url]: https://github.com/shubham14p3/ror-social-scaffold/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/shubham14p3/members-only.svg?style=flat-square
[forks-url]: https://github.com/shubham14p3/ror-social-scaffold/network/members
[stars-shield]: https://img.shields.io/github/stars/shubham14p3/members-only.svg?style=flat-square
[stars-url]: https://github.com/shubham14p3/ror-social-scaffold/stargazers
[issues-shield]: https://img.shields.io/github/issues/shubham14p3/members-only.svg?style=flat-square
[issues-url]: https://github.com/shubham14p3/ror-social-scaffold/issues
