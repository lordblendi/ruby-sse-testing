# Test application for server sent events
Code is based on [this article.](http://jessecravens.com/blog/2013/04/21/push-notifications-to-the-browser-with-server-sent-events/)


## Usage
Run the webserver (written in Ruby using Sinatra and Thin) then visit both pages in different tabs or windows. Use this command to start the webserver:

```bash
ruby server.rb
```

### Index page
Open [http://localhost:4567/](http://localhost:4567/) and wait for messages to appear!

### Admin page
The admin pages provides an input field, where you can create notification messages. Open [http://localhost:4567/admin](http://localhost:4567/admin) and add your messages!
