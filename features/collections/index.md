# Collections

Collections are a group of domains. Those can represent your user base or any other meaningful collection. The important
thing is, that after you uploaded one collection you are able to create reports and analyses out of it.

## Examples

There are some standard use-cases that can inspire you but you are not limited by those.

- **List of the websites of your customers** - You want to know you customers better? Upload a list of domains they
  provided in your product. If customers do not hate to configure their website the email address is a pretty good place
  to start as well.
- **List of websites from a special industry** - There are lots of lists of domains for special industries at there.
  Upload those lists and find out what these industry websites have in common.
- **List of competitor websites** - You can define a domain list with the domains of your competitors. Normally those
  lists are short but can generate a lot of interesting insights. 


## CSV File

If you want to upload a collection you have to create a CSV file with the semicolon `;` as a separator. You are allowed to define a headline row but it is not requires. The only thing that is mandatory is, that the domain is the first element.

```text
Domain
https://pro.webinsights.info
www.leankoala.com
```

As you can see not all domains have the protocol added. This is not mandatory but still is recommended. If the protocol is not added we assume it is `https`. 

## Tags (business plan)

A very powerful addition to the simple domain upload comes with the `business` plan: tags. 

Sometimes it is important to add custom tags to a domain. This makes it easier to query the correct domains when creating a report. Adding tags is very easy and is also done via the CSV file. 

```text
Domain;Tags
https://pro.webinsights.info;customer_business
www.leankoala.com;customer_pro
www.koality.io;customer_lite
```

The example is again very simple. We add some customer information to the domain. Now we are able to query only `lite` plan customers for example.

Of course you can always upload separate lists as a `pro` customer and have the same effect. 

After the collection was uploaded and you select it in the builder interface a new field `Private Tags` will appear. Here you can use the tags you predefined.

It is important that only you can query those tags. They are bound to your collection and not visible for others.


