- in local project_repositories directory create template quarto website project called quarto_blog
    - this will create a local quarto_blog directory
- in local quarto_blog directory ```git init```
- on github create new empty public repository called quarto_blog
- add quarto_blog github remote to local quarto_blog directory

```
quarto render
git add docs
git commit -m "Publish site to docs/"
git push
```