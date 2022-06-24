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
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-1-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-57%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 324 Contributions in the Year 2022
 > 
> 📦 40.2 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 22 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    231 commits    █████████░░░░░░░░░░░░░░░░   36.15% 
🌆 Daytime    178 commits    ███████░░░░░░░░░░░░░░░░░░   27.86% 
🌃 Evening    167 commits    ██████░░░░░░░░░░░░░░░░░░░   26.13% 
🌙 Night      63 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.86%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       99 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.49% 
Tuesday      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.7% 
Wednesday    91 commits     ███░░░░░░░░░░░░░░░░░░░░░░   14.24% 
Thursday     102 commits    ████░░░░░░░░░░░░░░░░░░░░░   15.96% 
Friday       119 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.62% 
Saturday     105 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.43% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.55%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
PHP                      2 hrs 20 mins       ███████████░░░░░░░░░░░░░░   43.87% 
Twig                     1 hr 42 mins        ████████░░░░░░░░░░░░░░░░░   32.01% 
HTML                     45 mins             ███░░░░░░░░░░░░░░░░░░░░░░   14.1% 
JavaScript               16 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   5.2% 
Vue.js                   5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   1.77%

🔥 Editors: 
VS Code                  5 hrs 21 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
crispy-eureka            2 hrs 58 mins       ██████████████░░░░░░░░░░░   55.71% 
Performance              1 hr 54 mins        █████████░░░░░░░░░░░░░░░░   35.77% 
lemocontrol              27 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.53%

💻 Operating System: 
Linux                    5 hrs 21 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   17 repos            ███████████░░░░░░░░░░░░░░   43.59% 
CSS                      7 repos             ████░░░░░░░░░░░░░░░░░░░░░   17.95% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   10.26% 
Kotlin                   3 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   7.69% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.13%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 24/06/2022 18:55:26 UTC
<!--END_SECTION:waka-->
