# FIES Auditor

Página para auditar o abatimento do saldo devedor do FIES a partir do extrato da Caixa ou do Banco do Brasil.

- **Caixa:** conta as linhas consecutivas de "Desconto de 1%" e usa o "Valor Saldo Teórico" antes e depois do bloco.
- **Banco do Brasil:** encontra o dia com o bloco de créditos de CAPITAL; os meses são o percentual de redução do saldo, arredondado.

O PDF é lido no navegador de quem usa e não é enviado a nenhum servidor. Só aceita PDF digital (não escaneado).
