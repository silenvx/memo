# git関連
### gitのcommitユーザー修正
```
git filter-branch -f --env-filter "GIT_AUTHOR_NAME='silenvx'; GIT_AUTHOR_EMAIL='czvziwzx@gmail.com'; GIT_COMMITTER_NAME='silenvx'; GIT_COMMITTER_EMAIL='czvziwzx@gmail.com';" HEAD
```
