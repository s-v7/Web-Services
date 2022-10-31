## Web-Services  
### Sistema Nota Fiscal Eletrônica  
>>
> ### Sistema em Desenvolviemento
>>
>> - **Módulos**
>>
>> - **Web Service – NfeAutorizacao**
>> - Função: serviço destinado à recepção de mensagens de lote de NF-e;
>> - Processo: assíncrono/síncrono.
>> - Método: nfeAutorizacaoLote
>>
>> - **Web Service – NfeRetAutorizacao**
>> - Função: serviço destinado a retornar o resultado do processamento do lote de NF-e.  
>>   A mensagem de retorno poderá ser utilizada pela SEFAZ para enviar mensagens de interesse da 
>>   SEFAZ para o emissor.
>> - Processo: assíncrono.
>> - Método: nfeRetAutorizacao
>>
>> - **Web Service – NfeInutilizacao**
>> - Função: serviço destinado ao atendimento de solicitações de inutilização de numeração.  
>> - Processo: síncrono.  
>> - Método: nfeInutilizacaoNF
>>
>> - **Web Service – NfeConsultaProtocolo**  
>> - Função: serviço destinado ao atendimento de solicitações de consulta da situação atual da NF-e na 
>>   Base de Dados do Portal da Secretaria de Fazenda Estadual.  
>> - Processo: síncrono.  
>> - Método: nfeConsulta
>>
>> - Tecnologias **(u,v,w) => "Java OOP 8+ and Spring Boot(MVC + ... +)";**
>
>  - Material disponível em => https://www.nfe.fazenda.gov.br/portal/principal.aspx
