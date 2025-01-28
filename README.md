# Nutri Lab

O **Nutri Lab** é uma aplicação web desenvolvida em Django, criada para atender nutricionistas que desejam realizar o acompanhamento completo de seus pacientes de forma organizada e eficiente. A aplicação oferece funcionalidades para gerenciar informações dos clientes, como dados pessoais, histórico de peso, gordura corporal, músculo, e parâmetros relacionados à saúde.

## Estrutura do Projeto
A estrutura do projeto está organizada para manter separação clara entre funcionalidades, autenticação, e templates:

- **autenticacao**: Módulo responsável pela autenticação de usuários, incluindo login e cadastro.
- **nutri_lab**: Diretório principal que contém configurações gerais da aplicação.
- **plataforma**: Módulo onde estão implementadas as funcionalidades principais da aplicação, como o gerenciamento de pacientes e o acompanhamento de dados.
- **templates**: Diretório que armazena os arquivos HTML usados na interface do usuário.
- **.gitignore**: Arquivo para ignorar arquivos e diretórios desnecessários no controle de versão.
- **README.md**: Documento descritivo do projeto.
- **manage.py**: Script de gerenciamento da aplicação Django.

## Funcionalidades

1. **Autenticação de Usuários**:
   - Cadastro e login para nutricionistas.
   - Proteção de rotas com autenticação obrigatória.

2. **Gerenciamento de Pacientes**:
   - Cadastro de novos pacientes.
   - Acompanhamento de dados como:
     - Peso
     - Altura
     - Percentual de gordura corporal
     - Percentual de massa muscular
     - Colesterol (HDL, LDL e total)
     - Triglicerídeos

3. **Interface Personalizada**:
   - Templates intuitivos para exibição e edição de dados dos pacientes.
   - Mensagens de feedback para usuários.

## Como Executar o Projeto

### 1. Clonar o Repositório
```bash
$ git clone https://github.com/seu-usuario/nutri_lab.git
$ cd nutri_lab
```

### 2. Criar e Ativar um Ambiente Virtual
```bash
$ python -m venv venv
$ source venv/bin/activate  # Linux/Mac
$ venv\Scripts\activate   # Windows
```

### 3. Instalar Dependências
```bash
$ pip install -r requirements.txt
```

### 4. Realizar Migrações
```bash
$ python manage.py migrate
```

### 5. Executar o Servidor
```bash
$ python manage.py runserver
```

Acesse a aplicação em [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Requisitos
- Python 3.11 ou superior
- Django 5.1.5

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para enviar issues ou pull requests.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---
**Nutri Lab • A solução completa para nutricionistas.**


