# projeto-pratico

## Funcionalidade: Filtro avançado com processamento natural de linguagem (NLP)

### Visão Geral
Esta funcionalidade permite que os usuários pesquisem e filtrem grandes conjuntos de dados utilizando frases em liguagem natural, eliminando a necessidade de configurar múltiplos filtros manuais e acelerando a navegação.

### Detalhes
- **Busca Contextual:** Interpreta comandos como "projetos atrasados do mês passado" e aplica automaticamente os filtros de data e status correspondentes.
- **Sugestões em tempo real:** Conforme o usuário digita, a barra de busca exibe sugestões inteligentes de termos, categorias e parâmetros frequentes.
- **Histórico de buscas:** Salva as consultas mais recentes e permite fixar termos de pesquisa favoritos para acesso rápido.

### Critérios de aceite
1. O campo de busca deve aceitar consultas de texto livre de até 150 caracteres.
2. A conversão de consulta em filtros aplicados na tela deve levar no máximo 2 segundos.
3. Caso a consulta não seja compreendida, a interface deve exibir uma mensagem clara oferencendo a opção de busca simples por palavras-chave.