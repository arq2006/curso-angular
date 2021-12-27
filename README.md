# CursoAngular

# Adicionar SSH no GitHub

```
ssh-keygen -t ed25519 -C "arthurrquintanilha@gmail.com"
```

***senha

```
eval $(ssh-agent -s)
```

```
ssh-add ~/.ssh/id_ed25519
```

```
clip < ~/.ssh/id_ed25519.pub
```


Depois abra o github painel, adicione nova chave e cole o conteúdo nela.

Teste a conexão com este comando:

```
ssh -T git@github.com
```

Fonte:

[https://dev.to/dxwebster/como-conectar-ao-github-com-chaves-ssh-1i41](https://dev.to/dxwebster/como-conectar-ao-github-com-chaves-ssh-1i41)