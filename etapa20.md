# ETAPA 20 – PROBLEMAS E SOLUÇÕES

## Problemas comuns no GitHub e como solucioná-los

### Push recusado
**Problema:** Não consigo enviar alterações.
**Possível causa:** O repositório está diferente do computador.
**Como identificar:** Aparece uma mensagem de erro no `git push`.
**Como solucionar:** Usar `git pull` e depois `git push`.

### Conflito de merge
**Problema:** Duas alterações estão no mesmo lugar.
**Possível causa:** O mesmo arquivo foi alterado por pessoas diferentes.
**Como identificar:** O Git mostra um conflito.
**Como solucionar:** Escolher a alteração correta e fazer o commit.

### Branch incorreta
**Problema:** Alterei a branch errada.
**Possível causa:** Eu estava em outra branch.
**Como identificar:** Usar `git branch`.
**Como solucionar:** Usar `git switch nome-da-branch`.

### Repositório desatualizado
**Problema:** Meu computador não tem as alterações mais recentes.
**Possível causa:** Houve mudanças no GitHub.
**Como identificar:** Comparar os arquivos.
**Como solucionar:** Usar `git pull`.

### Arquivo não aparece no GitHub
**Problema:** O arquivo não foi enviado.
**Possível causa:** Faltou adicionar ou enviar o arquivo.
**Como identificar:** Ele não aparece no repositório.
**Como solucionar:** Usar `git add`, `git commit` e `git push`.

### Problemas de autenticação
**Problema:** Não consigo acessar ou enviar alterações.
**Possível causa:** Problema no login ou acesso.
**Como identificar:** Aparece uma mensagem de erro.
**Como solucionar:** Conferir a conta e fazer login novamente.

### Alterações não sincronizadas
**Problema:** O computador e o GitHub estão diferentes.
**Possível causa:** As alterações não foram enviadas ou baixadas.
**Como identificar:** Os arquivos estão diferentes.
**Como solucionar:** Usar `git pull` e `git push`.
