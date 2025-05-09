📧 Sistema de Automação de E-mail para Novos Leads
Este projeto é um sistema de automação que envia uma notificação personalizada por e-mail ao cliente sempre que um novo lead é registrado. O diferencial desta solução é a integração entre um banco de dados MySQL, Google Sheets e envio automático de e-mails.

🔗 Como Funciona
Os leads são armazenados em um banco de dados MySQL

Os dados são exportados automaticamente para uma planilha no Google Sheets

Um script monitorando o Google Sheets detecta novas entradas

Ao identificar um novo lead, o sistema gera uma notificação personalizada por e-mail para o cliente

🚀 Funcionalidades
🔔 Notificação automática e personalizada por e-mail

🔄 Integração entre MySQL → Google Sheets → E-mail

📄 Mensagem com informações completas do lead (nome, e-mail, telefone, etc.)

⚙️ Configuração simples com Google Sheets API e SMTP

📊 Facilidade para visualizar e organizar os leads via planilha

🛠️ Tecnologias Utilizadas
Python 3.12: Linguagem principal do projeto

MySQL Connector (mysql-connector-python): Conexão e extração de dados do banco de dados MySQL

Google Sheets API via gspread: Leitura e monitoramento da planilha no Google Sheets

OAuth2Client: Autenticação com a API do Google

python-dotenv: Gerenciamento seguro de variáveis de ambiente (.env)

cryptography: Suporte a operações seguras e encriptação de dados sensíveis

