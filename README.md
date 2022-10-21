# little-bobby-tables

This is an example website that uses express, liquid templates, and sqlite3 and 
has a really cool feature of being totally insecure! 

**NOTE:** This example does NOT sanitize user input as that is left as an
exercise :) so don't use this code in production!

## How to run

```bash
npm install
DEBUG=myapp:* npm start
```

Visit [localhost:3000](http://localhost:3000)

## Little Bobby Tables

If you want to HACK your website enter the text below into the **blog to delete**
field! YOLO SEND IT!

```txt
1'; drop table blog; --
```

Congrats! You are now on the CIA's watch list! 

![bobby tables](public/images/exploits_of_a_mom.png)

Enjoy!
