# AssinaDEJE

**AssinaDEJE** é um assinador de documentos PDF utilizado pelo **Diário Eletrônico da Justiça Eleitoral de Mato Grosso (TRE-MT)**. O projeto foi desenvolvido com o objetivo de garantir a integridade, autenticidade e validade jurídica dos documentos publicados digitalmente.

## 🔐 Funcionalidades

- Assinatura digital de arquivos PDF conforme padrões ICP-Brasil
- Compatível com certificados A1 e A3
- Validação de estrutura e metadados exigidos pelo sistema DEJE
- Geração de arquivos prontos para publicação oficial no Diário Eletrônico

## 🛠️ Tecnologias utilizadas

- **Delphi** (Embarcadero RAD Studio)
- **ACBr**: biblioteca para integração com certificados digitais e assinaturas
- **OpenSSL**: para suporte criptográfico (quando necessário)
- Outras bibliotecas auxiliares de PDF e manipulação de arquivos

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/bublitz/AssinaDEJE.git
