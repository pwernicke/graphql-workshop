# Getting started with GraphQL on ASP.NET Core and Hot Chocolate - Workshop

If you want to browse the GraphQL server head over [here](http://workshop.chillicream.com/).

## Prerequisites

For this workshop we need a couple of prerequisites. First, we need the [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0).

Then we need an IDE/editor in order to do some proper C# coding, you can use [VSCode](https://code.visualstudio.com/) or if you already have it on your system, Visual Studio or JetBrains Rider.

Last but not least we will use our GraphQL IDE [Banana Cake Pop](https://chillicream.com/products/bananacakepop).

> Note: When installing Visual Studio you only need to install the `ASP.NET and web development` workload.

## What you'll be building

In this workshop, you'll learn by building a full-featured GraphQL Server with ASP.NET Core and Hot Chocolate from scratch. We'll start from File/New and build up a full-featured GraphQL server with custom middleware, filters, subscriptions, and Relay support.

**Database Schema**:

![Database Schema Diagram](docs/images/21-conference-planner-db-diagram.webp)

**GraphQL Schema**:

The GraphQL schema can be found [here](code/session-7/GraphQL.Tests/__snapshots__/SchemaTests.SchemaChanged.graphql).

## Sessions

| Session                                                    | Topics                                             |
|------------------------------------------------------------|----------------------------------------------------|
| [Session #1](docs/1-creating-a-graphql-server-project.md)  | Creating a new GraphQL server project.             |
| [Session #2](docs/2-understanding-data-loader.md)          | Understanding DataLoader.                          |
| [Session #3](docs/3-schema-design.md)                      | GraphQL schema design approaches.                  |
| [Session #4](docs/4-understanding-middleware.md)           | Understanding middleware.                          |
| [Session #5](docs/5-adding-complex-filter-capabilities.md) | Adding complex filter capabilities.                |
| [Session #6](docs/6-subscriptions.md)                      | Adding real-time functionality with subscriptions. |
| [Session #7](docs/7-testing-the-graphql-server.md)         | Testing the GraphQL server.                        |
