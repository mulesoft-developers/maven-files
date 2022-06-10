# DataWeave Library in Exchange tutorial

This `settings.xml` file is created for the [DataWeave Library in Exchange tutorial](https://developer.mulesoft.com/tutorials-and-howtos/dataweave/dataweave-libraries-in-exchange-getting-started/).

To use this file, you can either download it or copy the content and paste it on your own file. Make sure it's inside the `.m2` folder.
- For Windows: `C:\Users\<user>\.m2`
- For Mac: `${user.home}/.m2`

Once you have it in your local computer, replace the following credentials in the `server` section:
1. For `MuleRepository`, replace the `username` and `password` fields with your Mule EE Nexus repository credentials.
3. For `exchange-server`, replace the `username` and `password` fields with your Anypoint Platform credentials.

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