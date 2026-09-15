```python
from rich import print
from rich.panel import Panel
from rich.console import Console

class Profile:

    def __init__(self, nome: str, idade: int, loc:str):
        
        self.nome    = nome
        self.idade   = idade
        self.loc     = loc
        self.nick    = "Luiirye"
        self.tech    = ["python", "c++", "c", "java", "js", "html", "css", "bash", "github", "git"]
        self.cores   = ["#2563EB", "#6C59D5", "#E3AA2D", "#F7F7F8", "#E8E9EE", "#1B212C"]
        self.console = Console()
        
    def apresentacao(self):
        
        info  = f'[{self.cores[3]}]Nome[/{self.cores[3]}]        : [{self.cores[0]}]{self.nome}[/{self.cores[0]}]\n'
        info += f'[{self.cores[3]}]Idade[/{self.cores[3]}]       : [{self.cores[0]}]{self.idade}[/{self.cores[0]}]\n'
        info += f'[{self.cores[3]}]Localização[/{self.cores[3]}] : [{self.cores[0]}]{self.loc}[/{self.cores[0]}]'
        
        mensagem =  f'[{self.cores[4]}] - Bem vindo ao meu perfil!![/{self.cores[4]}]\n'
        mensagem += f'[{self.cores[4]}] - Eu sou o [{self.cores[0]}]{self.nick}![/{self.cores[0]}][/{self.cores[4]}]\n'
        mensagem += f'[{self.cores[4]}] - Estudando desenvolvimento web, POO e melhorando minha programação lógica.[/{self.cores[4]}]\n'
        mensagem += f'[{self.cores[4]}] - Estudante de Engenharia de Computação pela Uniderp.[/{self.cores[4]}]'

        pInfo = Panel(
                   info, 
                        title=f"[bold {self.cores[2]}]Info[/bold {self.cores[2]}]", 
                        width=85, 
                        style=f'{self.cores[3]}', 
                        border_style=f'{self.cores[1]}', 
                        padding=(1,2)
                    )
        
        pMensagem = Panel(
                        mensagem, 
                        title=f"[bold {self.cores[2]}]Olá![/bold {self.cores[2]}]", 
                        width=85, 
                        style=f'{self.cores[3]}', 
                        border_style=f'{self.cores[1]}', 
                        padding=(1,2)
                    )
    
        self.console.print(pInfo)
        self.console.print(pMensagem)
                
    def tecnologias(self):
        
        stack = f''
        
        for i in self.tech:
            stack += (f' [{self.cores[5]}]->[/{self.cores[5]}] [bold {self.cores[0]}] {i} [/bold {self.cores[0]}]\n')
            
        pStack = Panel(
                        stack, 
                        title=f'[bold {self.cores[2]}]Tecnologias[/bold {self.cores[2]}]',
                        width=50, 
                        style=self.cores[3],
                        border_style=self.cores[1],
                        padding=(1,2)
                    )
        
        self.console.print(pStack)
            
def main():
    luii = Profile("Luis Felipe", 22, "Campo Grande MS, Brasil")
    luii.apresentacao()
    luii.tecnologias()

if __name__ == "__main__":
    main()
    
# Sasaki Kojiro
# Miyamoto Musashi
# Ken Kaneki
# Chihiro Rokuhira
```
---
 <div align="center">
    <img src="https://raw.githubusercontent.com/Luiirye/Luiirye/output/pacman-contribution-graph.svg" alt="Pac-Man Contribution Graph" width="94%" />
</div>

---

<blockquote>
  <div align="">
    <a href="https://www.linkedin.com"><img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn" width="40"/></a>
    &nbsp;&nbsp; 
    <a href="https://open.spotify.com/user/21nrt6znecxe4ppk26pb33diq?si=ec457bf197834631"><img src="https://skillicons.dev/icons?i=spotify" alt="Spotify" width="40"/></a>
  </div>
</blockquote>
