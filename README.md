# Related Posts

## Usage

```
[related-posts]
```

## Potential arguments

- **limit**: Limit the number of pages you want to display. (*default*: 2)
- **strategy**: Depending on the value (*default*: best-match)
    - best-match: Will display the pages with most categories in common first, and then ordered by date DESC
    - default: Will display the pages from the same categories ordered by date DESC
- **shuffle**: Will shuffle the posts from each "weight" result, if used with "best-match" strategy. (*default*: true)


## Limitations

- Only displays pages that are linked to the same category for now