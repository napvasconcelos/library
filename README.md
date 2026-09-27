# library — biblioteca de referências (BibTeX)

Repositório com a lista de referências bibliográficas, em BibTeX, dos artigos usados nos
projetos do Nivaldo. Pensado para ser incluído como **submódulo git** em outros repositórios
(vaults de disciplina, vaults de paper), em vez de duplicar `.bib` em cada um.

## Estrutura
- `references.bib` — base BibTeX principal.

## Uso como submódulo
Em outro repositório:
```bash
git submodule add https://github.com/napvasconcelos/library.git <caminho>/library
```
Ao clonar um repositório que já usa este submódulo:
```bash
git clone --recurse-submodules <url-do-repositório>
# ou, se já clonou sem isso:
git submodule update --init --recursive
```
