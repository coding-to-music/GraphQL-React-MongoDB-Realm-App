# GraphQL React MongoDB Realm App 

graphqlreactapp-sgnlb.mongodbstitch.com

https://coding-to-music.github.io/GraphQL-React-MongoDB-Realm-App/

https://github.com/coding-to-music/GraphQL-React-MongoDB-Realm-App

https://docs.mongodb.com/realm/manage-apps/create/create-with-realm-ui/#std-label-create-a-realm-app


## Get the Front-End code for your Template via CLI
If you enabled access to Github during app creation, your front-end code will be in your repository.

## Download the CLI Client
Learn more about exporting via CLI  https://docs.mongodb.com/realm/deploy/export-realm-app/#export-with-realm-cli

Learn more about using the Realm CLI Client  https://docs.mongodb.com/realm/deploy/realm-cli-reference

```java
npm install -g mongodb-realm-cli
```

## Create a Programmatic API key
Use this API key associated with your MongoDB Cloud account to authenticate your realm-cli session. To create or use an existing API key, view and manage your API keys here. https://cloud.mongodb.com/v2/6146f93a165852010c2e7399#access/apiKeys



Create API key

```java
Public Key
ShortXXXXX

Copy
Private Key
Longxxxxxx
```

## Authenticate to the realm-cli
```java
realm-cli login --api-key zdhxckqm --private-api-key 7058f36e-a0c3-491e-b086-6cbc73f41392
```

## Select a Front-End Language
Choose a language for the front-end code for your template.

### Javascript (React + Apollo Client)
### Download via realm-cli

Download the files into your current directory via cli command. https://docs.mongodb.com/realm/deploy/realm-cli-reference

Set up your CLI.

```java
realm-cli pull --remote graphqlreactapp-sgnlb --template web.graphql.todo
```
