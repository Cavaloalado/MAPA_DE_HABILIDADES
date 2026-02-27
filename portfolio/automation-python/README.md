# Automação Python Relatórios e ETL

**Objetivo**  
Scripts Python para extração, transformação e geração de relatórios automatizados com consultas SQL.

**Tecnologias**  
Python, pandas, SQLAlchemy, PostgreSQL/MySQL, cron, Git.

**Funcionalidades**  
- Script ETL que executa query SQL, transforma dados e gera CSV/Excel.  
- Agendamento via cron e logs de execução.  
- Integração exemplo com envio de e‑mail para relatórios.

**Como executar**  
1. Configurar `config.yaml` com string de conexão.  
2. `python etl_report.py --start 2026-01-01 --end 2026-01-31`  
3. Verificar `output/` para arquivos gerados.

**Evidências**  
- CSV de exemplo gerado.  
- Logs de execução e entrada cron.
