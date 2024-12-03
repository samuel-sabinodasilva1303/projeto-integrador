## **Tecnologia Usada**  
- **Backend:** Laravel 10 Framework  
- **Processamento de Arquivos:** Pacote Maatwebsite Excel para Laravel  

---

## **Instalação**  

### **Pré-requisitos**  
- **PHP:** >= 8.0  
- **Composer**  
- **PostgreSQL**  
- **Node.js e npm** (opcional para rodar o Laravel Mix)  

---

## **Configurando o Projeto**  

### 1. Clone o Repositório  
```bash
git clone <url-do-repositorio>
```

2.	Install Dependencies:
composer install<br></br>
npm install<br></br>
npm run dev<br></br>
3.	Environment Configuration<br></br>
Copy .env.example to .env
<br></br>
cp .env.example .env<br></br>
Set up your database credentials in the .env file
env <br></br>

DB_CONNECTION=pgsql  <br></br>
DB_HOST=127.0.0.1  <br></br>
DB_PORT=5432 <br></br>
DB_DATABASE=your_database_name <br></br>
DB_USERNAME=your_database_username <br></br>
DB_PASSWORD=your_database_password <br></br>
<br></br>

4.	Generate Application Key<br></br>
php artisan key:generate<br></br>

5.	Run Migrations
php artisan migrate<br></br>

6.	Run the Application
**php artisan serve**

The application will be accessible at http://127.0.0.1:8000.
<br></br>


## Registro e Login de Usuário  
1. **Registrar:** Navegue até a página de registro e preencha o formulário de cadastro.  
2. **Login:** Use o e-mail e a senha cadastrados para fazer login.  

## Carregando um Arquivo Excel  
1. **Ir para a Página de Upload:** Após fazer login, navegue até a página de upload de arquivos.  
2. **Carregar:** Selecione um arquivo Excel (.xlsx) e faça o upload.  

## Visualizando os Dados Carregados  
1. **Dashboard:** Após o upload do arquivo, você será redirecionado para o painel (dashboard), onde os dados do arquivo Excel serão exibidos em formato de tabela.  


