---
title: Graphql platform
description: "More about Hoppscotch Graphql"
position: 3
category: Getting started
---

<video loop playsinline controls>
  <source src="/Graphql/GraphQlDemoSpaceX.webm" type="video/webm" />
  <source src="/Graphql/GraphQlDemoSpaceX.mp4"  type="video/mp4"  />
</video>

If you’re just starting to learn about GraphQl ,here are a few useful links:

1. <nuxt-link to='/quickstart/graphql'> Graphql (Quickstart Guide) </nuxt-link>
2. <a href="https://www.howtographql.com/">howtographql.com</a>
3. <a href="https://graphql.org/learn/">howtographql.com</a>

Lets go over the features provided by the hoppscotch GraphQl Editor and how to use them.

### URL

<img src="/Graphql/GraphqlURL-dark.png" class="dark-img" height="1280" width="640" alt="graphqlURL"/>
<img src="/Graphql/GraphqlURL-light.png" class="light-img" height="1280" width="640" alt="graphqlURL"/>

Enter The URL of the GraphQl End point here.

### Headers

<img src="/Graphql/GraphQlHeaderHighlight.png" class="dark-img" height="1280" width="640" alt="History Sidepanel"/>
<img src="/Graphql/GraphQlHeaderHighlight-light.png" class="light-img" height="1280" width="640" alt="History Sidepanel"/>

The editor lets you add header-value pairs to your GraphQl Request.
Use case:
Accessing a secure endpoint may need Authentication.

### Schema

<img src="/Graphql/GraphqlSchema-dark.png" class="dark-img" height="1280" width="640" alt="History Sidepanel"/>
<img src="/Graphql/GraphqlSchema-light.png" class="light-img" height="1280" width="640" alt="History Sidepanel"/>

You can view the schema of GraphQl Endpoint that you’ve connected to in this panel. The Schema can be downloaded as a JSON file or copied to your clipboard.

### Queries

<img src="/Graphql/graphqlQuery-dark.png" class="dark-img" height="1280" width="640" alt="History Sidepanel"/>
<img src="/Graphql/graphqlQuery-light.png" class="light-img" height="1280" width="640" alt="History Sidepanel"/>

Any Queries to be made to the GraphQl endpoint are typed out in this section , there is an inbuilt formatter that Prettifies the Query, this can be accessed in the top right corner of the Query Pane or with the shortcut  `Ctrl` + `P`.

To keep the Query uncluttered or to help easy debugging, you can use the variables section as shown below figure.


<img src="/Graphql/GraphQlVar-dark.png" class="dark-img" height="1280" width="640" alt="History Sidepanel"/>
<img src="/Graphql/GraphQlVar-light.png" class="light-img" height="1280" width="640" alt="History Sidepanel"/>

### Response

<img src="/Graphql/GrapQlResponse-dark.png" class="dark-img" height="1280" width="640" alt="History Sidepanel"/>
<img src="/Graphql/GrapQlResponse-light.png" class="light-img" height="1280" width="640" alt="History Sidepanel"/>

The response returned by the endpoint on your query is displayed at the end of the page , this can be copied to your clipboard or exported as a JSON file.

### Schema Documentation

<img src="/Graphql/schemadocs-dark.png" class="dark-img" height="400" width="640" alt="History Sidepanel"/>
<img src="/Graphql/schemadocs-light.png" class="light-img" height="400" width="640" alt="History Sidepanel"/>

In the right sidebar you can view the documentation of the GraphQl endpoint you are working with.
The documentation is searchable and documentation for Queries, Mutations, Subscriptions and Types are present in the Tabs below the search bar.

### History

<img src="/Graphql/GraphQlHistory-dark.png" class="dark-img" height="400" width="340" alt="History Sidepanel"/>
<img src="/Graphql/GraphQlHistory-light.png" class="light-img" height="400" width="340" alt="History Sidepanel"/>

All your recent Requests can be accessed from the History tab, and you can pick up right were left it.

### Collections

Just Like Rest API collections , Hoppscotch lets you organize your GraphQl queries in collections.

<img src="/Graphql/GraphQlcollectionHighlight.png" class="dark-img" height="300" width="440" alt="History Sidepanel"/>
<img src="/Graphql/GraphQlcollectionHighlight-light.png" class="light-img" height="300" width="440" alt="History Sidepanel"/>

You can Import existing collections(JSON) to replace current collection ,or preserve current collection as well as add new collection from your sources.
Collections can be Exported as JSON as well


<img src="/Graphql/importOrExportGraphqlCollection.png" class="dark-img" height="1000" width="640" alt="History Sidepanel"/>
<img src="/Graphql/importOrExportGraphqlCollection-light.png" class="light-img" height="1280" width="640" alt="History Sidepanel"/>