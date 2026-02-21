# Instruções para Agentes de IA - Exercício ex014

## Visão Geral do Projeto

Este é um exercício educacional do curso "HTML e CSS" de Gustavo Guanabara, focado em demonstrar **estilos CSS internos** (inline styles no `<style>` tag). Contém uma página HTML única com conteúdo estruturado em capítulos e subcapítulos.

## Arquitetura

- **Arquivo único**: `index.html` - página completa com HTML + CSS embarcado
- **Estrutura**: Demonstração de semântica HTML básica + aplicação de estilos CSS
- **Escopo**: Exercício didático, sem build tools ou dependências externas

## Estrutura e Padrões

### Convenções HTML
- **Idioma**: Português brasileiro (`lang="pt-br"`)
- **Charset**: UTF-8 (obrigatório para caracteres especiais)
- **Responsividade**: Meta viewport presente para suporte mobile
- **Hierarquia de títulos**: `<h1>` (capítulos principais) → `<h2>` (subcapítulos)

### Padrões CSS

**Localização**: Estilos internos dentro da tag `<style>` no `<head>`

**Convenções observadas**:
- Seletores simples por elemento (`body`, `h1`, `h2`, `p`)
- Propriedades agrupadas semanticamente (cores, fonts, alignment)
- Exemplo de padrão: body recebe contexto geral (fundo, fonte, tamanho)

### Exemplo de Padrão Existente
```html
<style>
    h1 {
        color: darkblue;
        background-color: lightblue;
    }
    p {
        text-align: justify;
    }
</style>
```

## Fluxo de Trabalho

- **Edição**: Modifique o arquivo `index.html` diretamente
- **Preview**: Abra em navegador (clique duplo ou arraste para o browser)
- **Sem build**: Nenhum pré-processamento necessário

## Pontos Chave

1. **CSS Interno vs Externo**: Este exercício demonstra CSS interno; não misture com arquivos `.css` externo sem propósito didático claro
2. **Estrutura Semântica**: Mantenha hierarquia de títulos e uso apropriado de tags
3. **Português**: Mantém textos em português (Lorem ipsum com contexto educacional)
4. **Accessibilidade Básica**: Viewport e charset já configurados

## Próximos Passos Típicos

- Adicionar mais estilos CSS (cores, fontes adicionais)
- Refatorar CSS para arquivo externo (ex015+)
- Adicionar elementos interativos (HTML5)
