# API Pass-In

O pass.in é uma aplicação de gestão de participantes em eventos presenciais.<br><br>
•	A ferramenta permite que o organizador cadastre um evento e abra uma página pública de inscrição.<br>
•	Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.<br>
•	O sistema fará um scan da credencial do participante para permitir a entrada no evento.<br><br>

## 📋 Requisitos Funcionais
•	O organizador deve poder cadastrar um novo evento;<br>
•	O organizador deve poder visualizar dados de um evento;<br>
•	O organizador deve poder visualizar a lista de participantes;<br><br>

• O participante deve poder se inscrever em um evento;<br>
•	O participante deve poder visualizar seu crachá de inscrição;<br>
•	O participante deve poder realizar check-in no evento;<br><br>


## 📋 Regras de Negócio
•	O participante só pode se inscrever em um evento uma única vez;<br>
•	O participante só pode se inscrever em eventos com vagas disponíveis;<br>
•	O participante só pode realizar check-in em um evento uma única vez;<br><br>


## 📋 Requisitos Não-Funcionais
•	O check-in no evento será realizado através de um QRCode;<br><br>


## ⚙️ Diagrama do Banco de Dados
![erd](https://github.com/lindson25/API-PassIn/assets/146979305/0c45ab6d-11f6-4967-ace2-f60340b5cfea)<br><br>


## 🛠️ Construído com
• Java<br>
• Spring Boot<br>
• Maven<br>
• API Rest<br><br>


## 📦 Dependências Utilizadas
• Spring Web<br>
• Flyway<br>
• Dev Tools<br>
• Lombok<br>
• JPA<br>
