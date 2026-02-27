# Web App Java API e Deploy

**Objetivo**  
API REST em Java para gerenciamento de recursos com deploy em servidor Linux.

**Tecnologias**  
Java, Spring Boot, Maven, PostgreSQL, Nginx, Docker (opcional).

**Funcionalidades**  
- Endpoints CRUD para recurso exemplo.  
- Autenticação básica com JWT.  
- Conexão com PostgreSQL.  
- Configuração de Nginx como reverse proxy.  
- Script de deploy para servidor Linux.

**Como executar localmente**  
1. Clonar repositório.  
2. Configurar `application.properties` com credenciais do banco.  
3. `mvn clean package`  
4. `java -jar target/app.jar`

**Deploy no servidor**  
- Provisionar servidor Linux.  
- Instalar Java, PostgreSQL, Nginx.  
- Configurar reverse proxy e SSL.  
- Executar script de deploy incluído.

**Evidências**  
- Prints de logs e configuração Nginx.  
- Script de provisionamento e checklist de segurança.
