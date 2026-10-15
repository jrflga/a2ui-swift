# Fork do jrflga

Base: o commit `16476ba` do [original](https://github.com/BBC6BAE9/a2ui-swift),
depois da v0.3.5. Usado pelo `jrflga/molde`.

O que muda do original:
- a dependência `swift-json-schema` aponta para o fork
  `jrflga/swift-json-schema`, numa versão exata (`0.13.2-jrflga.2`, com o swift-collections 1.2.1, que compila também no Xcode 16);
- o `Package.resolved` vai no Git.

Os testes do original rodam no original. Aqui, quem prova o uso é o
`jrflga/molde`.

Atualizar: `git fetch original --tags`, criar o ramo a partir do commit ou da
tag nova, reaplicar as mudanças acima, ler o diff do original e marcar
`<versão>-jrflga.1`. Nunca usar faixa de versão.
