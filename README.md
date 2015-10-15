# Traffic Control
a way to better understand the work you've staged

## Why you should care?
When we work on web-builds there are constant pushes to a your staging environments and it can be difficult to track what has been staged and what is already on production. **Traffic Control** aims to mitigate these issues by providing a list of the commits that are currently being staged and an easier way to promote the current environment to production. It aims to help developers better understand what code they have staged, help QA know which features/issues they are meant to test and also help clients and non-technical participants more context around what they are looking at.

## Usage
Traffic Control is a bit of JavaScript that is injected into all views in your non-production environments. The JavaScript fixes a small visual button onto your site that can be clicked to expanded. Once expanded, it will list out the commits that have been staged that are currently not in the Production branch.

### Mockups
![](https://cldup.com/81LIBTC-LP-3000x3000.png)
![](https://cldup.com/hPP9833l0r-3000x3000.png)
