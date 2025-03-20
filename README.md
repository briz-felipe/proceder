# Proceder Django

Este é um projeto desenvolvido com o framework **Django**.

## 🚀 Requisitos

- Python 3.10 ou superior
- Virtualenv 

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/briz-felipe/proceder.git
cd proceder
```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

No Linux/macOS:

```bash
python -m venv venv
source venv/bin/activate
```

No Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

## ⚙️ Configuração do Ambiente

1. Crie um arquivo `.env` na raiz do projeto e adicione as variáveis de ambiente necessárias. Exemplo:

```
DJANGO_SECRET_KEY=sua-chave-secreta
DEBUG=True
DATABASE_URL=postgres://usuario:senha@localhost:5432/seu_banco
```

2. Execute as migrações do banco de dados:

```bash
python manage.py migrate
```

## ▶️ Executando o Projeto

1. Inicie o servidor de desenvolvimento:

```bash
python manage.py runserver
```

Acesse no navegador: [http://localhost:8000](http://localhost:8000)

## 🧪 Rodando os Testes

```bash
python manage.py test
```

## 📚 Comandos Úteis

- Criar um superusuário para acessar o admin:

```bash
python manage.py createsuperuser
```

- Coletar arquivos estáticos:

```bash
python manage.py collectstatic
```

- Checar problemas comuns:

```bash
python manage.py check
```


## 📌 Contribuição

1. Crie uma branch com sua feature:

```bash
git checkout -b minha-feature
```

2. Faça o commit das suas alterações:

```bash
git commit -m 'Adiciona nova funcionalidade'
```

3. Envie para o repositório remoto:

```bash
git push origin minha-feature
```

4. Abra um Pull Request.

