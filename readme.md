# Clone o repositório junto com os submódulos

```bash
git clone --recurse-submodules https://github.com/jonascsilva/studynest
```

Caso tenha clonado somente o repostório principal, rode o seguinte comando:

```bash
git submodule update --init
```

# Inicie os containers

```bash
docker compose up
```

## Outros comandos

Atualizar submódulos

```bash
git submodule update --remote
```