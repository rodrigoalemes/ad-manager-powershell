# Como funciona

## Etapas

1. **Entrada** — a equipe preenche um arquivo CSV com os dados das contas a criar.
2. **Validação** — o script confere a estrutura do arquivo e os dados de cada linha antes de qualquer alteração.
3. **Simulação** — no modo de simulação, o script mostra o que seria criado, sem alterar o Active Directory.
4. **Execução** — confirmada a prévia, as contas são criadas seguindo o padrão definido.
5. **Retorno** — linhas com problema são sinalizadas para correção.

## Boas práticas adotadas

- Sempre rodar a simulação antes da execução real.
- Manter o CSV como fonte única dos dados de entrada.
- Separar contas de usuário e contas de serviço no processo.

[← Voltar ao README](../README.md)
