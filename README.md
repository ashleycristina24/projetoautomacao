# Projeto Automação Escola Maria Helena Faria Lima e Cunha
automação em phyton desenvolvida como projeto final para a escola Maria Helena Faria Lima e Cunha onde cursei o 3° ano técnico.

# Tutorial de execução do código

- Primeiro Passo
  - Acessar o site https://replit.com/
  - Fazer login na plataforma;
  - Criar um template Python
 
- Segundo Passo
  - Instalar os módulos pandas e openpyxl usando o Shell do ambiente;
  - <code> pip install pandas</code>
  - <code> pip install openpyxl</code>

- Terceiro Passo
  -  Copiar o código do arquivo [main.py] (main.py) que está neste repositório para main.py do ambiente Relp.it.

- Quarto Passo
  - Editor valor da variável email_user da linha 23 com seu e-mail do gmail;
  - Editar valor da variável email_pass da linha 24 com a senha que será gerada na verificação de duas etapas do gmail;
    - Para obter a senha da verificação de duas etapas: acesse as configurações de sua conta Google>Segurança>Como você acessa o seu e-mail>Verificação de duas etapas>Ativar verificação>Senhas de App>Outros>Nomear>Gerar;
    - Copiar a senha gerada para a linha 24;
  - Editar, na linha 75, o valor da variável receiver_email. Atualizar com o e-mail do destinatário.

- Quinto Passo
  - No Repl.it vá em Files>Upload file e faça o upload da tabela [Vendas.xlsx] (Vendas.xlsx) que se encontra neste repositório.

- Sexto Passo
  - No Shell do ambiente Repl.it executar o comando <code> python main.py</code>
   
# Considerações Finais
O objetivo deste código é a manipulação dos dados da tabela Vendas.xlsx, Impressão desses dados manipulados no Shell e envio deles por e-mail para algum destinatário. A automação envia um e-mail formatado por meio de tags html com as informações manipulados.
