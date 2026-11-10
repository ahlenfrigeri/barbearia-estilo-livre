# Barbearia Estilo Livre

Site de uma barbearia fictícia feito com **Bootstrap 5**: moderno, responsivo e com componentes interativos. Exercício do Módulo 14 (Bootstrap) do curso de Front-End da EBAC.

## Seções

Navbar · Home (banner com chamada para ação) · Sobre Nós · Serviços (cards) · Depoimentos (carousel) · Contato (formulário)

## Bootstrap usado

- **Navbar** responsiva (`navbar-expand-lg` + `collapse`): vira menu hambúrguer no celular e fecha ao clicar num link
- **Grid System**: `container`, `row`, `col-md-6`, `col-lg-5/7` e `row-cols-1 row-cols-sm-2 row-cols-lg-3` nos serviços
- **Cards** para os 6 serviços, com `h-100` para ficarem da mesma altura
- **Carousel** nos depoimentos, com setas e indicadores
- **Formulário** com validação do Bootstrap (`needs-validation`, `was-validated`, `invalid-feedback`)
- **Utilitários**: espaçamento (`py-5`, `mb-3`, `g-4`), flex (`d-flex`, `gap-3`), cores e tipografia (`display-3`, `fw-bold`, `lead`)

## Estrutura

```
index.html
css/estilos.css   → customizações (cores da marca, botão dourado, banner, efeito nos cards)
img/              → logo.svg, hero.svg, sobre.svg
```

O formulário não envia dados de verdade (não há backend): ao enviar com tudo preenchido, mostra uma mensagem de confirmação.
