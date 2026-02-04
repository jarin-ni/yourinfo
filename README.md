# yourinfo
Tell The Truth

Tagging the git and pushing ..
Check existing tag or latest version of tag
# git tag
status
v1.0.1
v1.0.2

then if you want to update the tag
# git tag v1.0.3
then to push the latest tag  

# git push origin v1.0.3


---
Main Git tag operation commands
- Create a tag (lightweight tag) :git tag v1.0
- Create a tag (annotated tag, recommended) :git tag -a v1.0 -m "メッセージ"
- Check the tags :git tag
- Push a specific tag :git push origin v1.0
- Push all tags :git push origin --tags
- Delete a local tag :git tag -d v1.0
- Delete a remote tag :git push origin :refs/tags/v1.0 
Points to note
- git pushdoes not send tags remotely by default.
- To share tags remotely, you must explicitly push them.
- It's a best practice to not change tag names once they've been pushed. 
