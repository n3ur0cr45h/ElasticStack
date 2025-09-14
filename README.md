
<div align="Center"> 
  

<h4>

███████╗██╗░░░░░░█████╗░░██████╗████████╗██╗░█████╗░
██╔════╝██║░░░░░██╔══██╗██╔════╝╚══██╔══╝██║██╔══██╗
█████╗░░██║░░░░░███████║╚█████╗░░░░██║░░░██║██║░░╚═╝
██╔══╝░░██║░░░░░██╔══██║░╚═══██╗░░░██║░░░██║██║░░██╗
███████╗███████╗██║░░██║██████╔╝░░░██║░░░██║╚█████╔╝
╚══════╝╚══════╝╚═╝░░╚═╝╚═════╝░░░░╚═╝░░░╚═╝░╚════╝░
</h4>
</div>

----

<details>
  <summary><b> 1. Fundamentos</b></summary>
<div align="Left"> 
<br>

E1.1 - O que é o "Elastic Stack"?  
 >  Conjunto de ferramentas criadas pela Elastic - visando coleta, armazenamento, busca, análise e visualização de dados;  
 >  Principalmente, dados de logs, métricas e eventos;  
 >  Usado para monitoramento, observabilidade, análise de segurança e business intelligence.   
  
E1.2 - Componentes do Elastic Stack:  
 > - Elasticsearch: Motor de busca e análise de dados - como se fosse um banco de dados orientado a documentos (JSON);  
 > - Logstash: Ferramenta de ETL (Extract, Transform, Load) - coleta os dados das fontes e envia ao Elasticsearch;  
 > - Kibana: Interface de Visualização do Elastic Stack;   
 > - Beats: Agentes que coletam os dados diretamente...  
 >   - Filebeat: Logs;  
 >   - Metricbeat: Métricas;  
 >   - Packetbeat: Rede;  
 >   - Auditbeat: Processos, Auditoria;  
 >   - Heartbeat: Serviços e Tempo de Resposta;  
 >     - Journalbeat: systemd journal (Depreciado).
 > - Elastic APM: Performance de Aplicações;  
 > - Elastic Security: Monitoramento e Análise de Segurança.
  
E1.3 - Diferença entre ELK e EFK  
 > ELK: Stack com o uso do Logstash - "L" - Pipelines complexos de dados e transformações avançadas (Mais pesado);  
 > EFK: Stack com o uso do Fluentd - "F" - Fácil integração com Pods e Clusters, usado muito com Containers e Kubernetes (Mais leve).  



</div> 
</details>

----
