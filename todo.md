# 🚀 TodoJs - Seu Gerenciador de Metas em CLI! 📝

![CLI Demo](https://img.shields.io/badge/CLI-Interactive-blueviolet) ![Node Version](https://img.shields.io/badge/Node.js-%3E%3D14.0.0-success) ![License](https://img.shields.io/badge/License-MIT-green)

Gerencie suas metas de forma simples e eficiente diretamente no terminal! Com **TodoJs**, você pode organizar suas tarefas com estilo usando uma interface interativa e colorida. ✨

## 🔥 Funcionalidades Incríveis
- ✅ **Cadastro Rápido** de novas metas
- 📋 Listagem interativa com **checkboxes**
- � Marcar metas como **concluídas**
- 🔍 Filtros para metas **realizadas** e **abertas**
- 🗑️ Deleção segura de múltiplas metas
- 💾 Salvamento automático em arquivo JSON
- 🎨 Interface intuitiva e amigável

## ⚙️ Instalação
1. Certifique-se de ter [Node.js](https://nodejs.org) instalado (versão 14+)
2. Instale as dependências:
```bash
npm install @inquirer/prompts
```

## 🕹️ Como Usar
Inicie o programa com:
```bash
node todo.js
```

**Menu Principal:**
```
1. Cadastrar meta      ➕
2. Listar metas        📜
3. Metas realizadas    🏆
4. Metas abertas      🔓
5. Deletar metas      🗑️
6. Sair               👋
```

### Exemplos de Uso:
**Cadastrar nova meta:**
```
> Digite a meta: Aprender Node.js avançado
Meta cadastrada com sucesso!
```

**Marcar metas concluídas:**
```
[ ] Estudar TypeScript
[x] Fazer exercícios diários
```

**Visualizar realizadas:**
```
🏆 Metas Realizadas: 2
1. Completar curso CLI:Command-Line Interface
2. Organizar workspace
```

## 💾 Persistência de Dados
Todas as metas são automaticamente salvas em `metas.json`:
```json
[
  {
    "value": "Publicar projeto no GitHub",
    "checked": true
  },
  {
    "value": "Escrever testes automatizados",
    "checked": false
  }
]
```

## 🤝 Contribuição
Contribuições são bem-vindas! Siga estes passos:
1. Fork o repositório
2. Crie sua branch (`git checkout -b feature/incrivel`)
3. Commit suas mudanças (`git commit -m 'Add incrivel feature'`)
4. Push para a branch (`git push origin feature/incrivel`)
5. Abra um Pull Request

## 📜 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

**Transforme sua produtividade com MetaMaster!** ✨  
*Nunca foi tão divertido organizar suas metas!* 🚀
