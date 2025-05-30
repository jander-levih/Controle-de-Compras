# Controle de Compras

Este projeto é um sistema web simples para controle de compras pessoais, com autenticação de usuário via Firebase, cadastro de compras, listagem, edição, exclusão e geração de uma "Nota Fiscal" simplificada para impressão.

## Funcionalidades

- **Login seguro:** Apenas usuários cadastrados no Firebase Authentication podem acessar o sistema.
- **Cadastro de compras:** Informe valor, descrição e data.
- **Listagem:** Visualize todas as compras cadastradas.
- **Edição e exclusão:** Edite ou exclua compras existentes.
- **Resumo da dívida:** Veja o total geral e do mês atual.
- **Geração de NF:** Gere e imprima uma nota fiscal simplificada das compras.

## Tecnologias utilizadas

- HTML5, CSS3 e JavaScript (ES6)
- [Firebase Realtime Database](https://firebase.google.com/products/realtime-database)
- [Firebase Authentication](https://firebase.google.com/products/auth)
- [Chart.js](https://www.chartjs.org/) (opcional, para gráficos)
- [jsPDF](https://github.com/parallax/jsPDF) (opcional, para PDF)

## Como usar

1. **Clone ou baixe este repositório.**
2. **Configure seu projeto Firebase:**
   - Crie um projeto no [Firebase Console](https://console.firebase.google.com/).
   - Ative o Authentication (método E-mail/Senha).
   - Ative o Realtime Database e defina as regras de leitura/escrita conforme necessário.
   - Substitua as chaves do objeto `firebaseConfig` no arquivo `index.html` pelas do seu projeto.
3. **Cadastre usuários manualmente no painel do Firebase Authentication** (já que o botão de criar conta foi removido).
4. **Abra o arquivo `index.html` em seu navegador.**
5. **Faça login com o e-mail e senha cadastrados.**
6. **Utilize o sistema normalmente.**

## Observações

- O botão "Gerar NF" gera uma nota fiscal simplificada para impressão, apenas para fins de controle pessoal (não é uma NF-e oficial).
- O sistema é responsivo e pode ser usado em dispositivos móveis.
- Para produção, ajuste as regras de segurança do Firebase Database e Authentication.

## Exemplo de tela

![Exemplo de tela do sistema](https://user-images.githubusercontent.com/your-image-link.png)

---

Desenvolvido com 💜 usando Firebase e JavaScript.
