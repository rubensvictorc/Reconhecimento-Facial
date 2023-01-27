# Reconhecimento-Facial
Este código usa a biblioteca OpenCV para detectar rostos em um fluxo de vídeo capturado pela webcam. Ele carrega um modelo de classificação de cascata de Haar chamado "haarcascade_frontalface_default.xml" e usa-o para detectar rostos em cada quadro capturado. Ele desenha retângulos em volta das faces detectadas e exibe a imagem com as faces marcadas.O que é o projeto: Uma breve descrição do projeto e o que ele faz (detecção de rosto usando Python e OpenCV). Como instalar e usar: Instruções detalhadas sobre como instalar e configurar o projeto, incluindo quaisquer dependências e como usá-lo (por exemplo, como iniciar a webcam e detectar rostos). Dependências: Lista de bibliotecas e pacotes Python necessários para rodar o projeto (por exemplo, OpenCV, NumPy).
Para executar esse aplicativo, você precisará ter o Python e o Flask instalados em seu computador. Além disso, você também precisará instalar as bibliotecas SQLAlchemy e Flask-SQLAIchemy, que são usadas para gerenciar o banco de dados do aplicativo.
 1. Instale o Python e o Flask em seu computador, se você ainda não tiver feito isso.
 2. Instale como bibliotecas SQLAIchemy e Flask-SQLAIchemy usando o gerenciador de pacotes do Python pip. Abra o terminal e digite: Python da importação do aplicativo db db.create all()
3. Baixe ou copie o código do aplicativo para uma pasta em seu computador.
 4. Abra o terminal e navegue até a pasta onde você colocou o código do aplicativo.
5. Inicialize o banco de dados executando o seguinte comando no terminal: Pythonda importação do aplicativo db db.create all()
6. Execute o aplicativo usando o seguinte comando:python app.py
 7. Abra o seu navegador e vá para o endereço http://localhost:5000 para acessar o aplicativo. Você deve ser capaz de ver a página inicial do aplicativo e usar as funcionalidades do aplicativo, como criar contas de usuário, criar projetos e tarefas, atribuir tarefas a usuários e visualizar tarefas e projetos.


Obs: Se você estiver executando o código em um ambiente diferente do seu computador, você precisará configurar as configurações do banco de dados de acordo com as necessidades do seu ambiente.
