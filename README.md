<div align="center">

# 🎓 Cadastro Acadêmico — Python CLI
### Alunos, disciplinas e notas no terminal

![Python](https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CLI](https://img.shields.io/badge/Interface-Terminal-334155?style=for-the-badge)

</div>

## 🎯 Visão geral

Projeto de estudo em **Python** com menu interativo para cadastrar e listar alunos, disciplinas e notas. Os registros são armazenados em listas e dicionários **na memória durante a execução**.

## ✨ Funcionalidades

| Recurso | Descrição |
|---|---|
| 👩‍🎓 Cadastro de alunos | Nome, matrícula numérica e data de nascimento |
| 📋 Consulta de alunos | Listagem dos registros cadastrados |
| 📚 Disciplinas | Cadastro e listagem de professor, turno e sala |
| 📝 Notas | Registro e consulta das avaliações |
| ✅ Validação | Verificações simples de campos e formato de data |

## 🏗️ Estrutura

```text
Sistema_Cadastro_test/
├── main.py       # Menu, validações e lógica
└── README.md
```

## 🚀 Execução

Sem dependências externas além de Python 3:

```bash
git clone https://github.com/WalterMatheusgg/Sistema_Cadastro_test.git
cd Sistema_Cadastro_test
python3 main.py
```

## 🔧 Limitações conhecidas

- Dados não são persistidos após encerrar o processo.
- O cálculo de idade utiliza **2025 como ano fixo**; é um exercício, não uma rotina adequada à produção.
- As validações e o tratamento de erros podem ser ampliados.
- Não há banco de dados, testes automatizados ou interface web neste repositório.

Para conhecer uma versão mais elaborada com interface e SQLite, veja o [**Sistema de Gestão Escolar**](https://github.com/WalterMatheusgg/Sistema_de_Gestao_Escolar).

## 👨‍💻 Autor

**Walter Matheus Soares da Silva** · [GitHub](https://github.com/WalterMatheusgg)
