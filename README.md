# ProcessAdminSettings

This module enables you to link the edit page of an existing page in your tree to the admin main menu. 

I use it to store theme related settings at a place where clients easily find it. E.g. you can use 

```
  $settings = $pages->get("id=12345") //Change ID to your own one
```

and refer to it all over your templates.
