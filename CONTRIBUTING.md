# Como trabalhamos

1. **Nunca commitar direto na `main`.** Crie uma branch: `feat/...`, `fix/...`, `perf/...`.
2. Abra um Pull Request para a `main` com o modelo preenchido. Pelo menos 1 pessoa da equipe revisa antes de mesclar.
3. **Rode os testes antes e depois** e mostre no PR que nao houve regressao.
4. **Sem segredos no git:** senha, token, chave de API, login de conta MT5 e `.env` nunca entram em repo. Use o cofre da Mesa.
5. Codigo que opera (executor, BE/trailing, risco) so muda com teste. Os repos de execucao reiniciam sozinhos no VPS quando a `main` muda.
6. Nada de terminal MT5 ao vivo, EA anexado ou conta real sem o dono (Lucas).
7. Commits curtos e claros, no imperativo ("corrige gate de promocao").
