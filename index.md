# md Documentation (wiki) as a repository

Why I think is an **awesome** idea!

😎


## Keep your code close and your documentation closer

When writing documentation for code as a different task then it becomes outdated
very quickly. That's one reason of why we prefer have the documentation closer
to the code.

e.g., as docstrings in Python

```python
def greet(name):
    '''
    Generate a greeting string for a person.
    
    Parameters
    ----------
    name: str
       name you want to greet
       
    Returns
    -------
    string
      Just a greeting
    '''
    return f"Hey, {name} how are you doing?"
```

Let's now see how this small fits with the rest of the decisions for tools and
processes.


## Format

Though it may seem silly, a familiar format to all makes a difference on its adoption.

I propose markdown, but all that I'm posting here works with any of the simple
markup languages. The best part of it is that they are human readable!


```markdown
# This is a title

## and this a subtitle 

Where you **can** _write_ whatever ~~you want~~, 
and create [links to any page and within the document](#summary).
```

And when writing code snippets 👆, it gets highlighted


##### ⚠ 

Some tools may accept markup text as an input... <br>
but then once get rendered you lost what was used to created it.


## Automation

Either it is just
- for searching a term (`rg`, `grep`, ...), or
- search and replace a word (`sed`) or
- test that links are still available (`lychee`)... 

you'd like to do so quickly, being sure you are not missing anything.

Having plain text files where you can run these operations will make your life easier.

## Review

Code gets reviewed in all our projects, why shouldn't the documentation deserve the same honours?

Documentation under a git repository would benefit of the [git-flow process](https://guides.github.com/introduction/flow/).

![Explanatory image from GitHub to explain GitHub flow](https://i.imgur.com/uZB2BjY.png)

## Contribution

For me, a wiki is a wiki if anyone can edit it. If I need to be in a particular
team and I can't update something I see it's wrong or outdated, then... what's the point?

Any git hosting platform provides ways to create contributions via pull or merge requests.

But... what about the unfamiliar with `git`? You can edit it from the website!

![](https://i.imgur.com/Bh9b7y2.png)

## Presentation

You may have guessed right already! This document is using markdown, and [lives on its own repository](https://github.com/dpshelio/wiki_as_repo/blob/main/index.md). And it can be converted easily to different types of output ([html](index.html), pdf, ...)

#### Did you know...?

![](https://i.imgur.com/OPmLorX.png)

## Issues to keep it up to date

Sometimes we spot typos, have new ideas, or need to update things... but many
times that happens when we don't have the time to add it to the documentation.

What do we do then? we keep it in our heads, we write it a post it, we keep it for ourselves!

Using issues for that not only helps us as a reminder to do it later, but it
also warns others that there's something that needs change and even maybe
someone updates it for you!

## Summary

We use tools to write code (and sometimes documentation), the closer these tools
are to us, bigger the chances we will use it.

**We want**
- something close to most of us,
- using a familiar format,
- that we can automate if needed,
- that's easy to review,
- and easy to contribute,
- that's portable (and presentable as we like)

Having any type of documentation as plain text (`md`) within a git repository
hits all these points.


## Suffering with UI?

**Presenting** the _Unofficial_ (and still WIP)

![Jira CLI](https://i.imgur.com/clexvRB.png)
![](https://raw.githubusercontent.com/ankitpokhrel/jira-cli/main/.github/assets/demo.gif)
