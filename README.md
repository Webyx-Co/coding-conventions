# Webyx's Coding Conventions 

## Table of Contents
1. [HTML](#html)
2. [CSS](#css)
3. [JavaScript](#javascript)
4. [TypeScript](#typescript)
5. [React and NextJS](#react-and-nextjs)
6. [Storybook](#storybook)
7. [GraphQL](#graphql)
8. [Jest](#jest)
9. [SQL](#sql)
10. [Git](#git) 
11. [Strapi](#strapi)
12. [JSON](#json)
13. [YAML](#yaml)
14. [Batch Files](#batch-files)
15. [Logs](#logs)
16. [VSCode Snippets](#vscode-snippets)
17. [Documentations](#documentations)
18. [Other Good Practices](#other-good-practices)

## Preferred Tools

Our default code editor is the Visual Studio Code. As the most well evaluated editor, we prefer to use his.

### Custom Extension Packs

We also have some own extensions packs with the intention to increase our productivity and simplify our work.

 - [WebDev Extension Pack](https://marketplace.visualstudio.com/items?itemName=WebyxCo.vscode-webdev-pack)
 - [Useful Tools Extension Pack](https://marketplace.visualstudio.com/items?itemName=WebyxCo.vscode-usefultools-pack)
 - [Git & GitHub Extension Pack](https://marketplace.visualstudio.com/items?itemName=WebyxCo.vscode-gitandgithub-pack)


## HTML

## CSS

### Ids

### Classes

## JavaScript

### Constants
- **Case:** Upper Case Snake Case

> `MY_AWESOME_CONSTANT`
    
### Variables: Camel Case
- **Case:** Camel Case

> `myAwesomeVar`
    
### Classes: Pascal Case
- **Case:** Pascal Case

> `myAwesomeClass`
    
    
## TypeScript

## React and NextJS

## Storybook

## Jest

## Strapi

### Collection Types and Single Types

- **Display name:** Title case and singular
- **Collection name:** Snake case and plural
- **Fields:** Snake case

> If you want to change the default plural name displayed at the left menu, you can go into api\yourType\models\yourType.settings.json located inside your Strapi project and add a "displayName" key with the desired name into the info object.

### Components

- **Name:** Title case and singular
- **Collection name:** snake case and plural
- **Fields:** snake case

## GraphQL

## SQL

### Databases

- **Case:** Snake Case

> `main_database`

### Tables

#### Table names

- **Case:** Snake Case

```main_database```

> Always preffer plural nouns

#### Table fields

- **Case:** Snake Case

> `awesome_table`

#### Table constraints

- **Case:** Snake Case

> `awesome_constraint`

### Functions

- **Case:** Snake Case

> `awesome_function`

### Procedures

- **Case:** Snake Case

> `awesome_procedure`

### Views

- **Case:** Snake Case

> `awesome_view`

### Triggers

- **Case:** Snake Case

> `awesome_trigger`

### Users

- **Case:** Snake Case

> `awesome_user`

## Git

### Branches
We use as our default branch name the word "main". Ir order to your `git init` always use that terminology, just run the command bellow on your machine.

    git config --global init.defaultBranch main

Use snake case

### Commits
In order to better organize our commits, we use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) pattern.  The commits have two required fields and three optional ones, that are:

 - Type: 
 - Scope: 
 - Short description:
 - Body:
 - Footer:
 
 > We recommend to always commit your code as your code, whether fixing bugs or developing new features, so our changelog may be more organized and the maintenance more easier.

### Tags & Releases
We use [Semantic Version](https://semver.org/) to versionate our project, using the pattern X.Y.Z-release.build.

> Our recommendation to new projects is to only start versioning when your pass from proof of concept / prototype to your first product code.

### Pull Requests

### Packages

## JSON

## YAML

## Batch Files

## Logs

## VSCode Snippets

## Documentations

We use the Markdown text for all our documentations and convert it to Word or PDF files as needed.

We always write our internal and external documentations in English and Portuguese, but we translate de external documentations as needed to your customers.

## Other Good Practices
<!--stackedit_data:
eyJoaXN0b3J5IjpbODgxMDE4OTQ5LDE0ODkxMzAwNDQsLTE1ND
E2NDUxNTQsLTQxMTQwODk2OSwtODcwMzY3MDE5XX0=
-->