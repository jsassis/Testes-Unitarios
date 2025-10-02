# Extensão Testes Unitários - Validação de Formulários

Esta extensão foi desenvolvida para auxiliar desenvolvedores e equipes de qualidade na validação de formulários em páginas web de forma prática e automatizada.

---

## Funcionalidades

- Verificação de preenchimento e consistência dos campos de formulários.
- Checagem de máscaras, limites de caracteres e alinhamento.
- Validação ortográfica dos textos dos rótulos de campos usando a API pública do [LanguageTool](https://languagetool.org).
- Armazenamento local dos resultados dos testes no navegador (`chrome.storage.local`).

---

## Privacidade e Coleta de Dados

- A extensão acessa somente os elementos da página ativa para executar os testes.
- **Não coleta informações pessoais** nem dados de navegação.
- Textos curtos de rótulos podem ser enviados ao LanguageTool apenas para verificação ortográfica.
- Nenhum dado é compartilhado com terceiros, exceto pelo LanguageTool, que possui sua própria [política de privacidade](https://languagetool.org/legal/privacy).

---

## Segurança

- Não executa código remoto.
- Não coleta dados de abas não selecionadas pelo usuário.
