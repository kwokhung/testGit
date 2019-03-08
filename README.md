1. Init Repo (VSCode)

2. Commit Repo (VSCode)

3. Create Repo (GitHub REST API)
-> curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"testGit"}'

4. Remote Add Origin
-> git remote add origin https://github.com/kwokhung/testGit

5. Push Origin Master
-> git push -u origin master