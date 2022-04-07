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

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written--2%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 293 Contributions in the Year 2022
 > 
> 📦 32.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 10 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    237 commits    ████████░░░░░░░░░░░░░░░░░   35.48% 
🌆 Daytime    194 commits    ███████░░░░░░░░░░░░░░░░░░   29.04% 
🌃 Evening    170 commits    ██████░░░░░░░░░░░░░░░░░░░   25.45% 
🌙 Night      67 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.03%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       113 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.92% 
Tuesday      72 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.78% 
Wednesday    92 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.77% 
Thursday     105 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.72% 
Friday       114 commits    ████░░░░░░░░░░░░░░░░░░░░░   17.07% 
Saturday     104 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.57% 
Sunday       68 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.18%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      10 hrs 14 mins      ██████████████████░░░░░░░   74.88% 
Python                   1 hr 34 mins        ███░░░░░░░░░░░░░░░░░░░░░░   11.5% 
JavaScript               52 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.41% 
HTML                     50 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   6.19% 
Markdown                 7 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.97%

🔥 Editors: 
VS Code                  13 hrs 40 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
Unknown Project          11 hrs 58 mins      ██████████████████████░░░   87.53% 
backend_test             1 hr 42 mins        ███░░░░░░░░░░░░░░░░░░░░░░   12.47%

💻 Operating System: 
Linux                    13 hrs 40 mins      █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            █████████████░░░░░░░░░░░░   51.52% 
CSS                      4 repos             ███░░░░░░░░░░░░░░░░░░░░░░   12.12% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   9.09% 
HTML                     2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.06% 
SCSS                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.03%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 07/04/2022 18:52:54 UTC
<!--END_SECTION:waka-->
