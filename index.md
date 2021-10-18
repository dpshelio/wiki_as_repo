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

And code gets highlighted by writing something like: 

```bash
ssh ssh.rc.ucl.ac.uk
```

##### ⚠ 

Some tools may accept markup text as an input... <br>
but then once get rendered you lost what was used to created it.


## Automation

Either is just for searching a term (`rg`, `grep`, ...), search and replace a
word (`sed 's/master/main/g/'`) or test that links are still available
(`lychee`)... you'd like to do so quickly, being sure you are not missing
anything.

Having plain text files where you can run these operations will make your life easier.

## Review

Code gets reviewed in all our projects, why shouldn't the documentation deserve the same honours?

Documentation under a git repository would benefit of the git-flow process.

## Contribution

For me, a wiki is a wiki if anyone can edit it. If I need to be in a particular
team and I can't update something I see it's wrong or outdated, then... what's the point?

Any git hosting platform provides ways to create contributions via pull or merge requests.

But... what about the unfamiliar with `git`? You can edit it from the website!

## Format




## Summary

We use tools to write code (and sometimes documentation), the closer these tools
are to us, the biggest chances we will use it.

- close to us
- familiar format
- 
