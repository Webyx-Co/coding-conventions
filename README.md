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
10. [Strapi](#strapi)
11. [JSON](#json)
12. [YAML](#yaml)
13. [Batch Files](#batch-files)
14. [Logs](#logs)
15. [VSCode Snippets](#vscode-snippets)
16. [Other Good Practices](#other-good-practices)

## Main Software

Our default code editor is the Visual Studio Code. As the most well evalueted editor, we prefer to use his.

### Custom Extension Packs

We also have some own extensions packs with the intention to increase our productivity and simplify our work.

 - [WebDev Extension Pack](https://marketplace.visualstudio.com/manage/publishers/webyxco/extensions/vscode-webdev-pack/hub)
 - [Useful Tools Extension Pack](https://marketplace.visualstudio.com/manage/publishers/webyxco/extensions/vscode-usefultools-pack/hub)
 - [Git & GitHub Extension Pack](https://marketplace.visualstudio.com/manage/publishers/webyxco/extensions/vscode-gitandgithub-pack/hub)


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

> If you want to change the default plural name displayed at the left menu, you can go into api\yourType\models\yourType.settings.json and add a "displayName" key with the desired name into the info object.

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

```git config --global init.defaultBranch main```

Use snake case

### Commits
In order to better organize our commits, we use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) pattern.  The

### Tags & Releases
We use semantic version on our tags, using the pattern X.Y.Z-release.build.

### Pull Requests

### Packages

## JSON

## Batch Files

## Logs

## VSCode Snippets

## Other Good Practices
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTEzMDMwMjExLC00MTE0MDg5NjksLTg3MD
M2NzAxOV19
-->