# PersonalChef1

<!---Esses são exemplos. Veja https://shields.io para outras pessoas ou para personalizar este conjunto de escudos. Você pode querer incluir dependências, status do projeto e informações de licença aqui--->
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
<img src="exemplo-image.png" alt="exemplo imagem">
> Uma aplicação web de receitas chamada PersonalCheff desenvolvida durante o curso de Python no Senac Americana. A aplicação listará receitas e clicando em cada nome de receita você pode ver a receita completa.
### Lista de tarefas
Segue a lista de tarefas a serem desenvolvidas no projeto:
- [X] Pré-requisitos
    - [X] Instalar o Python
    - [X] Instalar Visual Studio Code

-[X] Criar e ativar o ambiente virtual
``` istó é um markdown
Utilizar o CMD
python -m venv .\venv\
venv\Scripts\activate
```

- [X] Instalar o Django

```python -m pip install django==3.2
    pip freeze 
    //verifica se todos os pacotes foram instalados
```

- [x] Criar o projeto PersonalCheff

```
django-admin.py startproject PersonalCheffProject
```

- [x] Subir o servidor de testar o projeto 

entrar na pasta do projeto 
```cd PersonalCheffProj
```
Comando foi subir e executar o servidor
```
pythom -manage.py runserver 
```


apertar o control e criar no enderço do servidor para abrir

- [X] Altear o idoonma do projeto para 'pt-br'
Abrir o arquivo setting.py e na linha 106 alterar en-us para pt-br

- [] Alterar o timezone do projeto para 'America/São_Paulo'
 - [] Criar app receitas 
 - [] Registrar o app receitas
 - [] Configurar a rota inicial(index)
 - [] Criar a vies para a rota inicial
 - [] Registrar a rota inicial 
 - [] Criar o arquivo index
 
## 📝 Licença
Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
