# Reject It Demo application

[![Build Status](https://travis-ci.com/maximgorbatyuk/RejectItDemo.svg?branch=master)](https://travis-ci.com/maximgorbatyuk/RejectItDemo)

This project was created as a demo repository for my blog post ['How to reject invalid code'](https://maximgorbatyuk.github.io/development/how-to-reject-invalid-code.html).

The repository was set to reject invalid code using 'fails fast' principle. For more information, please, read the post.

## Tech stack

- .NET Core 3.1
- Angular 8+
- [Travis CI](https://travis-ci.com/maximgorbatyuk/RejectItDemo)

## Useful links

- [Repository rules](/docs/repository-rules.md) - how we develop the product.
- [I am a newbie in .NET, what should I do](/docs/i-am-a-newbie-in-dotnet.md)
- https://docs.travis-ci.com/user/languages/csharp/#xunit
- https://habr.com/ru/post/334576/

## How to...

### Run SQL Server via Docker

- Go to `/scripts` folder and run `database_run.ps1` script
- Do not close it, because the server works while the script is being opened

### Run ElK stack via Docker

We use ELK stack (Elasticsearch-Logstash-Kibana) to store logs of the application. The application can work without the ELK, but if you want to use the ELK, you should:

- go to `/scripts` folder and run `elk_run.ps1` script
- Do not close it, because the ELK erver works while the script is being opened
