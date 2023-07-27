<div align="center">

  ![GRUPO-HCM](https://github.com/HeihachiKaneko/TSA/assets/38951768/12796911-e3a9-4703-a285-f1e987377e9e)

  <br>

  <h1>Projeto de Gerenciamento de Dispositivos - Projeto (TSA)</h1>

  <p>
    Use este documento como um guia de instação e sempre que se sentir perdido.
  </p>
  
</div>

<br><br><br>

<div>
  <h2>:traffic_light:Andamento</h2>
  <br>

  ![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

</div>

<br>


<div>
  <h2>:book:Descrição</h2>
  
  <p>
    O objetivo principal do projeto é desenvolver um software que possa se comunicar com qualquer dispositivo eletrônico estilo REP       
    (Relógio Ponto).
  </p>
</div>

<br>

<div>
  <h2>:hammer:Funcionalidades</h2>
  <br>

  <p>Escrever tópico</p>
</div>

<br>

<div>
  <h2>:file_folder:Acesso ao Projeto</h2>
  <br>

  <p>Você pode acessar o código fonte do projeto inicial fazendo uma cópia do servidor local (\\netuno) e copiando a pasta raiz do   
     projeto para a sua máquina. (Verificando possibilidade de subir para o GitHub ou GitLab)
  </p>
</div>

<br>

<div>
  <h2>:wrench:Instalações Necessárias</h2>
  <br>

  <p>
    Após baixar ou copiar o projeto para o seu diretório, você deve instalar os seguintes programas:

    * Visual Studio Code (IDE)
    * Python 3.8.10 (32bits)
    * Pythonnet 2.5.2
    * Flask Framework
    * MySQL
  </p>
  <br>
  <p>
    É importante que a versão do Python seja de 32bits para ser possível a conexão com a DLL do REP. Caso tente optar por 64 bits terá        problemas durante a execução, pois a DLL também está em 32bits. Caso durante a instalação o Path do Python não tenha sido definido em     sua máquina o processo deverá ser feito manualmente indo em Menu Iniciar > Configurações > Sobre > Variaveis de Ambiente > Definindo      o
    Path Python conforme o caminho onde ele foi instalado na máquina.
  </p>
  <p>
    Efetuando a instalação do Visual Studio Code (VSCode) e do Python, abra o terminal da própria IDE para instalar o Pythonnet e as         demais dependencias caso ainda não tenha instalado. Utilize os seguintes comandos:

    * pip install pythonnet==2.5.2
    * pip install flask
    * pip install python-dotenv
    * pip install pyodbc
  </p>
</div>


















