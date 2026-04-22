# Configuração do DBeaver para Acessibilidade

Instruções técnicas para configurar o DBeaver de forma acessível para pessoas com deficiência visual. Testado com NVDA.

> Este arquivo é um resumo navegável. A versão completa e oficial está disponível em PDF, na seção de releases deste repositório. Licença: CC BY-NC-ND 3.0 BR.

---

## Pré-requisitos

- DBeaver Community (versão gratuita) instalado
- Leitor de tela NVDA ativo
- Java instalado (o DBeaver exige JVM)

## Passo a Passo: Primeira Conexão

1. **Abrir o DBeaver**
   - Localize o atalho do DBeaver no menu Iniciar
   - Execute com `Enter`

2. **Navegar pelos menus**
   - Pressione `Alt` para ativar a barra de menus
   - Use as setas para navegar
   - `Alt + F` abre o menu Arquivo

3. **Criar nova conexão**
   - `Ctrl + N` abre a janela "New Connection"
   - Digite o nome do banco (ex: `PostgreSQL`)
   - Navegue com `Tab` até os campos de configuração

4. **Preencher dados de conexão**
   - Host, porta, banco de dados, usuário e senha
   - Use `Tab` para avançar entre campos

5. **Testar conexão**
   - Navegue até o botão "Test Connection"
   - Pressione `Enter` para testar

6. **Salvar conexão**
   - Navegue até "Finish" e pressione `Enter`

## Ajustes de Interface

- **Tema escuro:** Menu Janela > Preferências > Aparência > Tema > Dark
- **Zoom:** `Ctrl +` aumenta, `Ctrl -` diminui
- **Fonte do editor SQL:** Preferências > Editores > Editor de Texto > Fonte

## Notas de Acessibilidade

- O painel "Database Navigator" é navegável com `Tab` e setas
- Resultados de consulta são apresentados em grade navegável por teclado
- Mensagens de erro e confirmação são anunciadas pelo NVDA
