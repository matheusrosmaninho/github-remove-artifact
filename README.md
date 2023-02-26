# Github remove artifact

## Example usage

```
uses: oobatousai/github-remove-artifact@v1
with:
    retention-days: 7
    project-name: "hello-actions"
    owner-account: "oobattousai"
    access-token: ${{ secrets.myToken }}
```

## Makefile

The Makefile was created to helpfull the dev with commands

* `make tag_version=v1 tag-remove`: Remove tag called v1
* `make commit_message="Message test" tag_version=v1 commit-by-tag`: Commit with message of tag called v1
* `make git-push-with-tags`: Push on remote repository with all tags