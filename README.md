# UPA Animais – Site oficial

Site da **UPA Animais**, clínica veterinária 24 horas em Poços de Caldas (MG).

## Estrutura

```
upa-animais/
├── index.html          → página do site (HTML, CSS e JavaScript)
├── README.md
└── assets/
    └── img/            → fotos, logo e ícone do site
```

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `upa-animais`).
2. Envie todos os arquivos desta pasta (botão **Add file → Upload files**), mantendo a pasta `assets`.
3. Vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`. Clique em **Save**.
5. Em alguns minutos o site estará no ar em `https://SEU-USUARIO.github.io/upa-animais/`.

## Como trocar as fotos

Substitua os arquivos em `assets/img/` mantendo **o mesmo nome**:

| Arquivo | Onde aparece |
|---|---|
| `veterinario-golden.jpg` | Início do site |
| `emergencia.jpg` | Destaque de Emergência 24h |
| `consulta.jpg` | Cartão de Consultas |
| `vacinacao.jpg` | Cartão de Vacinação |
| `exames.jpg` | Cartão de Exames |
| `cirurgia.jpg` | Cartão de Cirurgias |

Dica: use fotos na horizontal, com até 1.300 px de largura, para o site carregar rápido.

## Contatos usados no site

- Telefone e WhatsApp: (35) 3714-8074 → no código aparece como `553537148074`
- Instagram: @upaanimais
- Endereço: Rua Pedro Bertozzi, 200, Vila Olímpica, Poços de Caldas – MG, CEP 37704-375

Para trocar o número do WhatsApp, procure por `553537148074` no `index.html` e substitua em todos os lugares. Para trocar o telefone de ligação, procure por `+553537148074`.
