To start using Meteor React template

```
meteor create simple-todos-react
```

Include ReactJS

```
meteor add react
```

To start a MongoDB terminal:

```
meteor mongo
```

And insert a task into database:

```
db.tasks.insert({ text: "Hello world!", createdAt: new Date() });
```

Deploy app:
```
meteor deploy todo-rosalia.meteor.com
```

Enable user accounts:
```
meteor add accounts-ui accounts-password accounts-facebook
```

Remove insecure package so that client code cannot modify database
```
meteor remove insecure
```

Autopublish comes by default that synchronizes all of the database contents to the client
```
meteor remove autopublish
```