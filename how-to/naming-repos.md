## Naming Repos

It's easy to name a GitHub repository. You just need something like this:

- Descriptive
- Readable
- Consistent
- Contextual
- Future-friendly
- Extensible
- Reusable
- Brief (short / succinct)

There is no wrong way to name a repository, but some names are better than others. Here are some considerations for choosing an awesome name for your GitHub repository.

### Follow Conventions
Following the naming conventions established for a particular project, code language, or team is a good place to start. Where possible, keep the lowercase and dashes pattern:

    star-wars.git
    the-empire-strikes-back.git
    return-of-the-jedi.git

### What about CamelCase?
The issue with the camel case is that words can be interpreted differently, for instance, checkinService versus checkInService. Also, it is difficult with auto-completion if you have many similarly named repos to have to constantly check if the person who created the repo you care about used a certain breakdown of the upper and lower cases. It's also best to avoid all-upper-case; No one likes to be yelled at.

### Be specific
It is possible that you will need to distinguish between similar concepts in the future, so always choose a name that is more specific.

- Use user-locator-rest-service instead of locator-service or user-rest-service or user-service.
- Be consistent. 
- How do you want your repositories to be sorted/grouped?

    sapien-tests v/s tests-sapien

Remember that a git repo can be cloned into any root directory of your choice:

    git clone https://github.com/user/repo.git myDir

Here, `repo.git` would be cloned into the myDir directory.

So even if your naming convention for a public repo ended up to be slightly not to your taste, it would still be possible to have your favourite name on the client side.

### Avoid Organization Monikers
Once established, it's a simple task to change repo names, BUT it can have unintended consequences such as breaking downstream links - so think about a name that can be stable over a longer period of time.  Company names, Supplier names, Office location, Department, Team names, etc are subject to change, so it’s best to avoid including them as part of repo names.  Putting “RM” or "NB" in the name is fine to provide the context, but it can make sorting and searching a pain.

### Use topics
Classifying your repository with topics, to help others find and contribute to your project. Add topics related to your project's intended purpose, subject area, affinity groups, or other important qualities.
