# Custom Policy Tutorial

This [settings.xml](/settings.xml) file is created for the [custom policy tutorial](https://developer.mulesoft.com/).

To use this file, you can either download it or copy the content and paste it on your own file. Make sure it's inside the `.m2` folder.
- For Windows: `C:\Users\<user>\.m2`
- For Mac: `${user.home}/.m2`

Once you have it in your local computer, replace the following credentials in the `server` section:
1. Replace the `username` field with your Anypoint Platform username.
2. Replace the `password` field with your Anypoint Platform password.

For example, if you access [Anypoint Platform](https://anypoint.mulesoft.com) with the username `maxthemule` and password `maxrocks`, then your credentials should look like this:

```xml
...
<server>
    <id>exchange-server</id>
    <username>maxthemule</username>
    <password>maxrocks</password>
</server>
...
```