---
tipo: POP
status: Em revisão
tags: [#Fiscal, #NF-e, #EntregaFutura, #Modelo55]
---

# POP — Emissão de NF-e de Remessa para Entrega Futura (Modelo 55)

> **Nota:** este é um exemplo. Verifique legislação vigente da UF, CFOP aplicável e regras do cliente.

## Objetivo
Padronizar a emissão de **NF-e (Mod. 55)** para **remessa para entrega futura**, garantindo conformidade e rastreabilidade.

## Escopo
Inclui operações de remessa para entrega futura no ambiente NF-e (modelo 55).  
Não inclui: faturamento final / retorno, operações interestaduais específicas sem validação prévia.

## Responsáveis (RACI)
- R: Fiscal
- A: Coordenador(a) Fiscal
- C: Contábil / Comercial
- I: Cliente

## Pré-requisitos
- Cadastro de produtos/CFOP revisado.
- Parametrizações no sistema emissor (Athenas/ERP).
- Certificado digital válido.

## Passo a passo (visão geral)
1. **Confirmar CFOP** adequado à remessa para entrega futura (validar por UF/operação).
2. **Emitir NF-e (Mod. 55)** com natureza da operação correspondente.
3. **Informar destinatário, produtos e quantidades** (sem destaque de valores de faturamento final, quando aplicável).
4. **Verificar CST/CSOSN, ICMS/ST, IPI, PIS/COFINS** conforme cenário do cliente.
5. **Transmitir NF-e** e validar autorização.
6. **Arquivar XML e DANFE** no Drive do cliente, na pasta padrão.
7. **Registrar controle** para emissão da **NF-e de faturamento** quando ocorrer a entrega efetiva.

## Evidências
- XML autorizado e DANFE.
- Registro em planilha/controle interno.

## Padrões/Políticas
- Política de Gestão Documental (ver pasta de Políticas).
- Referências legais: consultar legislação da UF e orientações SEFAZ.

## Controles & Auditoria
- Checklist de conferência antes do envio.
- Log de alterações no cadastro do produto.

## Histórico
| Data | Versão | Autor | Mudança |
|---|---|---|---|
| 2025-09-26 | 1.0 |  | Criação de exemplo |
