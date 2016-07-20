## Commit Message Guidelines

We have very precise rules over how our git commit messages can be formatted.  This leads to **more
readable messages** that are easy to follow when looking through the **project history**.  But also,
we use the git commit messages to **generate the Angular change log**.

### Commit Message Format
Each commit message consists of a **header**, a **body** and a **footer**.  The header has a special
format that includes a **type (trans or review)**, a **scope** and a **subject**:

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

The **header** is mandatory and should contains **type**, **scope** and **subject**.

Any line of the commit message cannot be longer 100 characters! This allows the message to be easier
to read on GitHub as well as in various git tools.

Footer should contain a [closing reference to an issue](https://help.github.com/articles/closing-issues-via-commit-messages/) if any.

For example, if you are working on glossary full page translation, the commit message should be like: 

```
trans(Basics - Glossary): Full page
```

Or maybe working on some part of glossary tranlation:

```
trans(Basics - Glossary): M ~ R Itens
```

The same rule works for review commits:

```
review(Basics - Glossary): Full page
```

Or: 


```
review(Basics - Glossary): M ~ R Itens
```