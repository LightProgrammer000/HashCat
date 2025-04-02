# HashCat

**HashCat** é uma ferramenta avançada de recuperação de senhas que utiliza técnicas de cracking para testar a segurança de senhas por meio de ataques de força bruta e dicionário. Compatível com diversos algoritmos de hashing, como MD5, SHA-1, SHA-256, entre outros, o HashCat é projetado para ser rápido, eficiente e fácil de usar.

## Funcionalidades

- **Suporte a Múltiplos Algoritmos de Hash**: Suporta uma ampla gama de algoritmos, incluindo MD5, SHA-1, SHA-256, SHA-512, bcrypt, entre outros.
- **Ataques de Força Bruta e Dicionário**: Permite a realização de ataques de força bruta e dicionário para testar a robustez de senhas.
- **Identificação Automática de Tipos de Hash**: Detecta automaticamente o tipo de hash fornecido, facilitando o processo de cracking.
- **Modo Offline**: Opera sem necessidade de conexão com a internet, utilizando ferramentas como o HashCat para ataques locais.
- **Extensibilidade**: Fácil adição de novos algoritmos e funcionalidades conforme necessário.

## Como Usar

### Requisitos

- **Sistema Operacional**: Linux (testado no Kali Linux)
- **Dependências**:
  - [HashCat](https://hashcat.net/hashcat/)
  - [John the Ripper](https://www.openwall.com/john/)
  - [Wordlist](https://github.com/danielmiessler/SecLists/tree/master/Passwords/)

### Instalação

1. **Clone o Repositório**:

   ```bash
   git clone https://github.com/LightProgrammer000/HashCat.git
   cd HashCat
