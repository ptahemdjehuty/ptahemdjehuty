###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        shadowcompiler= {
        "fullName": "Salaou-Deen Henri-Joël Abiodoun PARAISO",
        "stack": { "languages": ['Python', 'Php', 'JS', 'Kotlin'],
                   "tools": ['Django', 'DRF', 'VueJS', 'NuxtJS', 'Bulma', 'Beufy'],
                   "databases": ['Mysql', 'Postgresql', 'Sqlite'],
                   "architectures": ["MVC", "MVT", "REST", "PWA", "SPA"]},        
        "roles": ["Web & Mobile dev as freelance", "Blogger", "Founder at @henrid3v", "Mentor"],
        "askMe": ['Food', 'Manga', 'Science', 'Comics', 'NaturalHair', 'Photography', 'Tech', 'Programming'],
        "contacts": { 'Telegram': 'imsadi',
                       'Linkedin': 'henri-dev',
                       'Discord': 'ShadowCompiler#2596',
                       'Mail':'pariso03henri@gmail.com',}}
        return Response(shadowcompiler, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-23%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 299 Contributions in the Year 2022
 > 
> 📦 36.3 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 23 Public Repositories 
 > 
> 🔑 10 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    238 commits    █████████░░░░░░░░░░░░░░░░   35.84% 
🌆 Daytime    196 commits    ███████░░░░░░░░░░░░░░░░░░   29.52% 
🌃 Evening    163 commits    ██████░░░░░░░░░░░░░░░░░░░   24.55% 
🌙 Night      67 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.09%

```
📅 **I'm Most Productive on Monday** 

```text
Monday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.17% 
Tuesday      70 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.54% 
Wednesday    92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.86% 
Thursday     101 commits    ███░░░░░░░░░░░░░░░░░░░░░░   15.21% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.17% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.66% 
Sunday       69 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.39%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      10 hrs 16 mins      █████████████████░░░░░░░░   69.09% 
HTML                     4 hrs 18 mins       ███████░░░░░░░░░░░░░░░░░░   29.0% 
CSS                      11 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.28% 
SCSS                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.58% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.05%

🔥 Editors: 
VS Code                  14 hrs 52 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
Unknown Project          10 hrs 28 mins      █████████████████░░░░░░░░   70.42% 
lift-store               4 hrs 23 mins       ███████░░░░░░░░░░░░░░░░░░   29.58%

💻 Operating System: 
Linux                    14 hrs 52 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ████████████░░░░░░░░░░░░░   50.0% 
CSS                      5 repos             ███░░░░░░░░░░░░░░░░░░░░░░   14.71% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.82% 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.88% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   2.94%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 22/04/2022 18:54:48 UTC
<!--END_SECTION:waka-->
