###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'Name': 'Abiodoun PARAISO',
            'Stack': {
                       'languages': ['Python', 'Php', 'JS', 'Kotlin'],
                       'tools': ['Django', 'VueJS', 'React', 'Jetpack Compose'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'Roles': ['freelance web and mobile developer', 'Content creator', 'Teacher', 'Mentor'],
            'AskMe': ['DIY', 'Food', 'Africa', 'Science', 'Comics', 'Photography', 'Tech', 'Programming'],
            'Contacts': {
                           'Telegram': 'baba_mandef',
                           'Mail':'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-992%20hrs%2032%20mins-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-270%20Thousand%20lines%20of%20code-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Dart                     15 hrs 6 mins       ████████████████████████░   96.01% 
YAML                     20 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.12% 
Markdown                 10 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.08% 
Git Config               3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.42% 
Other                    2 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.31%

🔥 Editors: 
VS Code                  15 hrs 44 mins      █████████████████████████   100.0%

🐱‍💻 Projects: 
ishiro                   15 hrs 44 mins      █████████████████████████   99.97% 
flutter                  0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.03%

💻 Operating System: 
Linux                    15 hrs 44 mins      █████████████████████████   100.0%

```


 Last Updated on 27/03/2024 18:38:45 UTC
<!--END_SECTION:waka-->
