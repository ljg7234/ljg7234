
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=ljg7234)](https://solved.ac/ljg7234/) 

![K-Junyyy's GitHub stats](https://github-readme-stats.vercel.app/api?username=ljg7234&show_icons=true&theme=dracula)

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ljg7234&layout=compact"><br><br>

import requests # pip install requests

res = requests.get("https://github-readme-stats.vercel.app/api?username=ljg7234&show_icons=true&theme=dracula",
    allow_redirects=True, auth=(<ljg7234>,<repo>))
res.raise_for_status()
data = res.json()

print(data)
