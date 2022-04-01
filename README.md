## Hi, I'm JudeX  <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"> 👋 - Backend and Big Data Engineering Enthusiast.

### Currently - Backend Engineer at <a href="https://flutterwave.com">Flutterwave</a>

[![Linkedin: judex](https://img.shields.io/badge/-Onyekaba_Nzubechukwu_Jude-blue?style=flatsquare&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/nzubechukwu-onyekaba/)](https://www.linkedin.com/in/nzubechukwu-onyekaba/)

**What makes me tick you ask? 🤗:**
```
class Human:
    def __init__(self):
        self.pronouns = None
        self.code = None
        self.current = None
        self.email = None
        
    @property
    def current(self):
        return self.__current
       
    @current.setter
    def current(self,curr):
        if not curr:
            self.__current = 'learning new tech stack'
        else:
            self.__current = curr
            
        
    def __repr__(self):
        bio = f'''
            - 😄 Pronouns: {','.join(self.pronouns)}
            - 💻 Tech Stacks: {','.join(self.code)}
            - 🔭 I’m currently working on {self.current}
            - 📫 How to reach me: {self.email}
            - 👯 I’m looking to collaborate on exciting engineering projects
            - 🤔 I’m looking for help with learning Big Data Tech Stacks
            - 💬 Ask me about anything!.
               '''
        return bio
         
JudeX = Human()
JudeX.pronouns = ('He','His')
JudeX.code = ('Python','Django','Flask','Javascript','NodeJS','PostgreSQL','MySQL','Git')
JudeX.current = ''
JudeX.email = 'judexonyekaba@gmail.com'
print(JudeX)

Output:
    - 😄 Pronouns: He,His
    - 💻 Tech Stacks: Python,Django,Flask,Javascript,NodeJS,PostgreSQL,MySQL,Git
    - 🔭 I’m currently working on learning new tech stack
    - 📫 How to reach me: judexonyekaba@gmail.com
    - 👯 I’m looking to collaborate on exciting engineering projects
    - 🤔 I’m looking for help with learning Big Data Tech Stacks
    - 💬 Ask me about anything!.           
```
---
