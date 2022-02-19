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
![Profile Views](http://img.shields.io/badge/Profile%20Views-4-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-872%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 108 Contributions in the Year 2022
 > 
> 📦 30.9 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 9 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    182 commits    ████████░░░░░░░░░░░░░░░░░   35.14% 
🌆 Daytime    165 commits    ████████░░░░░░░░░░░░░░░░░   31.85% 
🌃 Evening    141 commits    ██████░░░░░░░░░░░░░░░░░░░   27.22% 
🌙 Night      30 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   5.79%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       76 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.67% 
Tuesday      60 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.58% 
Wednesday    71 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.71% 
Thursday     76 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.67% 
Friday       107 commits    █████░░░░░░░░░░░░░░░░░░░░   20.66% 
Saturday     84 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.22% 
Sunday       44 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.49%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Python                   10 hrs 47 mins      ████████████████████████░   99.13% 
Bash                     5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.85% 
Other                    0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01% 
Git Config               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0% 
Vue.js                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

🔥 Editors: 
VS Code                  10 hrs 29 mins      ████████████████████████░   96.4% 
PyCharm                  23 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   3.6%

🐱‍💻 Projects: 
schoolman                10 hrs 52 mins      █████████████████████████   99.99% 
Unknown Project          0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.01% 
henri-front              0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

💻 Operating System: 
Linux                    10 hrs 52 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ███████████░░░░░░░░░░░░░░   46.67% 
HTML                     4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   13.33% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.0% 
C++                      1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.33%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 19/02/2022 18:46:51 UTC
<!--END_SECTION:waka-->
