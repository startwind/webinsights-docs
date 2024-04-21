# Collections via File Upload

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


