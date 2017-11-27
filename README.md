# StackYourCode

## Backend
Microservices build in javascript with nodejs, express, mongoose, graphql.

### Models
#### User
```json5
{
  username: "John",
  password: "pass123",
  email: "john@doe.com",
  createdAt: ISODate("2017-11-27T22:40:40.020Z"),
  role: "Developer",
  githubId: "123"
}
```
#### Code
```json5
{
  title: "http get nodejs",
  language: "javascript",
  folder: "nodejs",
  description: "How to make http request in nodejs",
  createdAt: ISODate("2017-11-27T22:40:40.020Z"),
  author: "12345678",
  contributors: [],
  validatedAt: ISODate("2017-11-27T22:40:40.020Z"),
  validate: true,
  public: true,
  code: "https://github.com/StackYourCode/stackyourcode/blob/master/javascript/vanilla/getRandomString/getRandomString.js",
  rawCode: "https://raw.githubusercontent.com/StackYourCode/stackyourcode/master/javascript/vanilla/getRandomString/getRandomString.js",
  views: [],
  upvotes: [],
  downvotes: []
}
```
#### Language
```json5
{
  name: "nodejs",
  parent: "javascript"
}
```
#### Issue
```json5
{
  codeId: "12345",
  issueNumber: 5
}
```

## Frontend
Build with ReactJS and styled-component.
