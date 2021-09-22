<h1 align="center">🧮 Calculadora de IMC</h1>

<h4 align="center"> 
	🚧  Status do Projeto 🚀 Em construção...  🚧
</h4>

<p align="center">
 <a href="# Descrição">Descrição</a> •
 <a href="# Pré-Requisitos">Pré-Requisitos</a> •
</p>

# Descrição
Nosso projeto é uma calculadora para descobrir o Índice de Massa Corporal(IMC). Através do valor encontrado é possível avaliar se a pessoa se encontra dentro do seu peso ideal em relação à sua altura.

# Pré-Requisitos (Windows)
1. Instalar o [Android Studio](https://developer.android.com/studio/)  
Através do link disponibilizado é possível baixar o software e depois partir para sua instalação.  
Ela é bem simples, basta ir apertando Next, Next, Next .... e depois Finish.

2. Baixar o [SDK](https://flutter.dev/docs/get-started/install/windows) do Flutter  
Após baixar o SDK, você precisa criar uma nova pasta no diretório raiz do seu sistema. Se desejar pode executar o seguinte comando no CMD.
    > cd C:\ & mkdir src    
    
    Depois disso, basta extrair o SDK na pasta src criada anteriormente.
  
3. Criando uma variável de ambiente do Flutter  
Pesquisar no Windows por Variáveis de Ambiente. Vai na aba Avançado, depois Variáveis de Ambiente... Em variáveis de usuário procurar por PATH e apertar em editar. Vai em novo e colar o seguinte endereço.
    > C:\src\flutter\bin  

    Depois disso só apertar em OK, OK, OK ....

4. Configurar editor  
Atualmente existem vários editores que você pode estar utilizando, mas irei te mostrar como configurar alguns deles:  
    * Android Studio e [IntelliJ IDEA](https://www.jetbrains.com/pt-br/idea/):  
    Basta você ir em Plugins e na aba Marketplace pesquisar por Flutter e apertar no botão para instalar.
    * [Visual Studio Code](https://code.visualstudio.com/)  
    Você pode apertar **Ctrl + Shift + X**, que ele irá te redirecionar para as extensões da IDEA. Daí basta pesquisar por Flutter e instalar o plugin.

5. Verificando instalação  
Depois de instalar tudo, abra o terminal e digite o seguinte comando:
    > flutter doctor  

    Ele vai verificar se está tudo ok. Provavelemente ele irá pedir para aceitar as licenças do Android SDK. Para isso basta digitar:
    > flutter doctor --android-licenses  

    