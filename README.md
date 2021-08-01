# chatbot_watson - Chatbot que utiliza intenções, entidades e variáveis. 

Aplicação que disponibiliza um servidor temporário de API para a integração do chatbot Watson através de Webhooks. Código feito em Python e tunel exposto pelo Ngrok. 

watson_api_share.py - código que roda applicação capaz de reconhelher email digitado no chat e enviar confirmação para o usuário

google_watson_share.py - aplicação que é capaz de apoior ligação entre o serviço watson e o google actions para receber comandos por voz. 

skill-diálogo.json - backup do diálogo criado no console do chatbot

entities.csv - entidades criadas no console do chatbot

action.json - integra a aplicação e o actions ao webhook do watson

no site da google é necessario buscar: project id do robô criado
no site da IBM é necessário separar: URL do webhook do watson, API key, ID

gactions.exe - faz a integração ser autorizada. comando: 
gactions.exe update --action_package action.json --project "nomedorobô sem aspas"
