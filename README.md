# Exemplo de uso do DocFX

Instalar o docfx globalmente:

```
dotnet tool update -g docfx
```

Na pasta do projeto executar o comando abaixo para criar a estrutura do site estatico com o docfx:

```
docfx init --quiet
```

Para executar o site realizar o comando abaixo:

```
docfx docfx_project/docfx.json --serve
```

Exportar um template do docfx:

```
docfx template export default
```

## Fonte de referência

https://dotnet.github.io/docfx/index.html

