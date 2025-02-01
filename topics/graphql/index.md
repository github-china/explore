---
aliases: graphql-client, graphql-api, graphql-schema, graphql-query, graphql-server
created_by: Facebook
display_name: GraphQL
github_url: https://github.com/graphql
logo: graphql.png
released: 2015
related: api, rest, graphiql, sparql, sql
short_description: GraphQL 是一个用于 API 的查询语言，相较于REST更加高效、强大和灵活。
topic: graphql
url: http://graphql.org/
wikipedia_url: https://en.wikipedia.org/wiki/GraphQL
---
**GraphQL** 是一个用于 API 的查询语言，由 Facebook 开源。它为 REST API架构提供了一种替代方案，相较于REST更加高效、强大和灵活。
它允许客户端定义所需数据的结构，服务器返回完全相同的数据结构。

例如POST请求:
```
{
  project(name: "GraphQL") {
    tagline
  }
}
```
响应结果
```
{
  "project": {
    "tagline": "A query language for APIs"
  }
}
```