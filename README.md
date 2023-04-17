## Linguagens utilizadas nos meus repositórios

$ curl -s "https://api.github.com/users/AdrianoHebreu/repos?per_page=1000" | jq '.[].language' | sort | uniq -c | sort -nr | awk '{print "* " $2 ": " $1 " repo(s)"}'
