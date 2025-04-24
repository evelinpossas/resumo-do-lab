Passo a Passo da Configuração

1. **Acesse o portal Azure**  
   → [https://portal.azure.com](https://portal.azure.com)

2. **Crie um recurso do tipo “Banco de Dados SQL”**  
   - Escolha uma **assinatura** e crie um novo **grupo de recursos**
   - Dê um nome ao banco de dados
   - Crie um novo **servidor lógico**
   - Configure usuário e senha

3. **Defina regras de firewall**
   - Permita acesso pelo seu IP local para poder se conectar

4. **Configure o escalonamento**
   - Escolha o plano de desempenho ideal (DTUs ou vCores)

5. **Testando a conexão**
   - Use o SQL Server Management Studio (SSMS) ou Azure Data Studio

---

##  Dicas e Boas Práticas

- Sempre use **nomes intuitivos** para recursos no Azure.
- **Evite liberar o acesso para todos os IPs** (regra 0.0.0.0).
- Utilize **tags** para organizar e facilitar a gestão dos recursos.
- Habilite **alertas de uso e performance** via Azure Monitor.
- Faça testes com **backup/restauração** antes de mover um banco para produção.



---

## Referências

- [Documentação oficial - SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/)
- [Guia de início rápido - Instância Gerenciada SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview)
- [DIO - Plataforma de Cursos](https://www.dio.me)
