# JRA TECH – Ordem de Serviço

Aplicativo Android de gestão para assistência técnica de celulares.

## Recursos da versão inicial
- Ordens de serviço com numeração automática
- Cadastro de cliente e aparelho
- Registro de defeito, condição física, diagnóstico e serviço
- Fotos do aparelho vinculadas à OS
- Assinatura na entrada e na entrega
- Status de atendimento
- Controle de pagamentos, saldo e fiado/parcelamento
- Estoque básico de peças
- Garantia padrão de 90 dias após a conclusão
- Dados locais no aparelho e backup/restauração em JSON
- Impressão da OS pelo recurso de impressão do Android

## Gerar APK pelo GitHub Actions
1. Crie um repositório novo no GitHub, por exemplo `JRA-TECH-Ordem-Servico`.
2. Extraia este ZIP e envie todos os arquivos e pastas para a raiz do repositório.
3. Abra a aba **Actions** no GitHub e permita a execução de workflows, se solicitado.
4. Abra **Gerar APK Android - JRA TECH** e toque em **Run workflow** (ou aguarde a execução após enviar os arquivos).
5. Quando a execução terminar com sucesso, abra a execução e baixe o artefato **JRA-TECH-APK**.
6. Extraia o APK do artefato e instale no Android.

## Importante
Esta é uma primeira versão funcional para testes. Os dados ficam no armazenamento local do aplicativo. Exporte backups regularmente e guarde uma cópia fora do celular. Ao desinstalar ou limpar os dados do aplicativo, os dados locais podem ser apagados.

A garantia padrão de 90 dias é um campo de controle do sistema; informe ao consumidor as condições efetivas da garantia aplicável ao serviço.
