# AuraVision  

**Descrição**  
AuraVision é uma plataforma de dashboards que simplifica a visualização, análise e gerenciamento de dados, proporcionando insights estratégicos para empresas.  

## 📁 Estrutura dos Repositórios  

Cada repositório dentro da organização representa uma empresa e segue a seguinte estrutura:  

```
/[Empresa]
│── ETL/                # Contém os arquivos SQL para criação das views
│   ├── view_nome.sql  
│   ├── view_outro.sql  
│── POWERBI/            # Contém os relatórios no formato PBIP (TDML e PBIR)
│   ├── [Relatório 1]/  
│   ├── [Relatório 2]/  
│── .gitignore
│── README.md
```

## 📜 Regras  

1. **Estrutura dos repositórios**:  
   - Cada repositório corresponde a uma empresa.  
   - Dentro de cada repositório, existem duas pastas principais:  
     - **ETL/**: Cada view deve ser salva como um arquivo `.sql`.  
     - **POWERBI/**: Relatórios salvos no formato **PBIP** (com **TDML** e **PBIR** ativados), organizados em pastas.  

2. **Padrões de versionamento**:  
   - Sempre usar commits descritivos para facilitar o rastreamento das mudanças.  
   - Manter a organização dos arquivos conforme o padrão definido.  

3. **Arquivo `.gitignore`**  
   O `.gitignore` deve conter:  
   - Padrões para arquivos do **Python**  
   - **localSettings.json**  
   - **cache.abf**  

Exemplo de `.gitignore`:  

```
# Power BI
localSettings.json
cache.abf
```
