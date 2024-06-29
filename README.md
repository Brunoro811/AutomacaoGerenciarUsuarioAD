# Power Platform User Management Automation

## Descrição

Este repositório contém um projeto de automação criado com a Power Platform, especificamente utilizando Power Automate para automações, SharePoint Online para armazenamento, Grupos do Office AD e Office 365 Outlook para solicitações por e-mail. O foco desta automação é adicionar ou remover usuários dos grupos do AD com base em solicitações recebidas via Outlook.

## Funcionalidades

- **Adição/Remoção de Usuários**: Adicionar ou remover usuários dos grupos do Active Directory conforme solicitado.
- **Armazenamento de Dados**: Utilização de listas do SharePoint para armazenar dados das solicitações.
- **Integração com Outlook**: Recebimento e processamento de solicitações enviadas por e-mail.
- **Feedback ao Solicitante**: Envio de respostas automáticas ao solicitante após o processamento das solicitações.
- **Log de Processamento**: Armazenamento do resultado de cada solicitação processada.

## Fluxo de Trabalho

1. **Recebimento de Solicitações**: Solicitações de adição ou remoção de usuários são recebidas via e-mail no Outlook.
2. **Entrada de Dados**: Os dados são inseridos em uma planilha Excel formatada como tabela e posteriormente inseridos na Lista do SharePoint.
3. **Processamento pelo Power Automate**: Os dados na Lista do SharePoint são processados pelo Power Automate, realizando as adições ou remoções conforme solicitado.
4. **Armazenamento de Resultados**: O resultado de cada operação é armazenado na Lista do SharePoint.
5. **Resposta ao Solicitante**: Ao final do processamento, uma resposta é enviada ao solicitante via e-mail.

## Sharepoint (Online)Requisitos

- **Power Automate**: Necessário para criar e gerenciar os fluxos de trabalho.
- **SharePoint Online**: Utilizado para armazenamento e gerenciamento dos dados.
- **Office 365 Outlook**: Utilizado para receber e responder às solicitações.
- **Grupos do Office AD**: Onde os usuários serão adicionados ou removidos.
  
## Requisitos
1.

## Requisitos Necessários
1.

1. Clone este repositório:
    ```sh
    git clone https://github.com/Brunoro811/AutomacaoGerenciarUsuarioAD.git
    ```
2. Baixe o arquivo ArbiGerenciarUsuriodoAD_1_0_0_2_managed.zip
3. Importe a solução no seu ambiente
4. Configure o Power Automate com os fluxos de trabalho fornecidos neste repositório.
5. Configure a Lista do SharePoint conforme as especificações fornecidas.
6. Certifique-se de que as permissões adequadas estão configuradas no Office 365 e no SharePoint.

## Uso

1. Envie uma solicitação via e-mail para o endereço configurado no Outlook.
2. Preencha a planilha Excel conforme o formato especificado e carregue-a na Lista do SharePoint.
3. O Power Automate processará a solicitação automaticamente.
4. Verifique a Lista do SharePoint para ver os resultados do processamento.
5. Aguarde o e-mail de resposta com o resultado da sua solicitação.

## Contribuição

Contribuições são bem-vindas! Por favor, siga as etapas abaixo para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nome-da-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para abrir uma issue ou enviar um e-mail para [ferreira.bruno.oliveira@gmail.com](mailto:ferreira.bruno.oliveira@gmail.com).

---

Feito com ❤️ por [Seu Nome](https://github.com/seu-usuario)
