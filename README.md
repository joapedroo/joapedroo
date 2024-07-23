```Q#
namespace HelloQSharp {
    open Microsoft.Quantum.Intrinsic;
    open Microsoft.Quantum.Canon;

    operation WelcomeMessage() : Unit {
        Message("Seja bem vindo ao meu perfil!");
    }

    @EntryPoint()
    operation Main() : Unit {
        WelcomeMessage();
    }
}
```
```Q#
namespace PessoaExample {
    open Microsoft.Quantum.Canon;
    open Microsoft.Quantum.Intrinsic;

    newtype Pessoa = (Nome : String, Idade : Int, Formacao : String, CursandoFacu : Bool, CursandoBoot : Bool);

    operation GetNome(pessoa : Pessoa) : String {
        body {
            let (nome, _, _, _, _) = pessoa;
            return nome;
        }
    }

    operation GetIdade(pessoa : Pessoa) : Int {
        body {
            let (_, idade, _, _, _) = pessoa;
            return idade;
        }
    }

    operation GetFormacao(pessoa : Pessoa) : String {
        body {
            let (_, _, formacao, _, _) = pessoa;
            return formacao;
        }
    }

    @EntryPoint()
    operation Main() : Unit {
        body {
            // Criando uma instância de Pessoa
            let pessoa = Pessoa("João", 25, "Cyber Security", false, false);

            // Usando as operações para obter informações
            Message("Nome: " + GetNome(pessoa));
            Message("Idade: " + IntAsString(GetIdade(pessoa)));
            Message("Formacao: " + GetFormacao(pessoa));
        }
    }
}



```
<h1></h1>
  <h2><b>♦ STATISTICS ♦</b></h2>
  <a href="https://github.com/joapedroo">
  <img height="150em" src="https://github-readme-stats.vercel.app/api?username=joapedroo&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true"/>
  <img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=joapedroo&layout=compact&langs_count=7&theme=github_dark"/>
</div>
<div style="display: inline_block"><br>
  <h2><b>♦ HARD SKILLS ♦</b></h2>
  <img align="center" alt="João-C" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg">
  <img align="center" alt="João-Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
  <img align="center" alt="João-C++" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg">
  <img align="center" alt="João-Perl" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/perl/perl-original.svg">
  <img align="center" alt="João-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">     
  <img align="center" alt="João-Bash" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg">
  <img align="center" alt="João-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="João-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="João-JS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
  <img align="center" alt="João-React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="João-Node" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
  <img align="center" alt="João-Next" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg">
  <img align="center" alt="João-Vue" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg">
  <img align="center" alt="João-PHP" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-plain.svg">
  <img align="right" alt="João-Madalorian" width="25%" height="25%" src="https://c.tenor.com/rarynTvGJaUAAAAM/cicada3301-glitch.gif">
</div>
 <h1></h1>
<div style="display: inline_block border-style: solid}"><br>
  <h2 style="color:red" ><b>♦ IDE | TOOL | SO ♦ </b></h2>
  <img align="center" alt="João-vscode" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg">
  <img align="center" alt="João-Docker" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
  <img align="center" alt="João-Debian" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/debian/debian-original.svg">
  <img align="center" alt="João-Raspberrypi" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/raspberrypi/raspberrypi-original.svg">
  <img align="center" alt="João-Linux" height="40" width="50" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg">
 <table>
  <img align="center" alt="João-Win" height="40" width="50" border="solid 1px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg">
  </table>
</div>
 <h1></h1>
 <div style="display: inline_block">
  <a href="https://github.com/joapedroo/Ramsonware">
  <img height="100em" src="https://github-readme-stats.vercel.app/api/pin/?username=joapedroo&repo=Ramsonware&theme=github_dark"/>
  <a href="https://github.com/joapedroo/Parsing-html">
  <img height="100em" src="https://github-readme-stats.vercel.app/api/pin/?username=joapedroo&repo=Parsing-html&theme=github_dark"/>
</div>
 <h1><h1>
<div> 
  <a href="https://www.instagram.com/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/joapedroo/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  
 ![Snake animation](https://github.com/joapedroo/joapedroo/blob/output/github-contribution-grid-snake.svg)
