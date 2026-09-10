```python
class Profile:

    def __init__(self, nome: str, idade: int, loc:str):
        self.nome = nome
        self.idade = idade
        self.loc = loc
        self.tech = [
            "python",
            "c++",
            "c",
            "java",
            "js",
            "html",
            "css",
            "bash",
            "github",
            "git"
        ]
        self.nick = "Luiirye"
        
    def apresentacao(self):
        print(f'Nome:         {self.nome}')
        print(f'Idade:        {self.idade}')
        print(f'Localização:  {self.loc}')
    
        print(f'==' * 33)
        print(f'Bem-vindo ao meu perfil!! Eu sou o {self.nick}!')
        print(f'Atualmente estudando desenvolvimento Web, POO e melhorando Lógica.')
        print(f'Cursando Engenharia de Computação pela Uniderp.')
        print(f'==' * 33)
        
    def tecnologias(self):
        print(f'Tecnologias:')
        
        for i in self.tech:
            print(f' - {i}')
            
def main():
    luii = Profile("Luis Felipe", 22, "Campo Grande MS, Brasil")
    luii.apresentacao()
    luii.tecnologias()

if __name__ == "__main__":
    main()
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
    <br>
    <a href="https://open.spotify.com/user/21nrt6znecxe4ppk26pb33diq?si=ec457bf197834631"><img src="https://skillicons.dev/icons?i=spotify" alt="Spotify" width="40"/></a>
  </div>
</blockquote>
