<!-- ============================================================
     RED HOOD // perfil de vitortuness
     ============================================================ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0a0a0a,60:5c0000,100:b3001b&text=VITOR%20ANTUNES%20%2F%2F%20DEV&fontColor=f2f2f2&fontSize=50&fontAlignY=38&desc=back-end%20%C2%B7%20Python%20%C2%B7%20FastAPI%20%C2%B7%20PostgreSQL&descAlignY=60&descSize=18&animation=fadeIn" alt="Red Hood dev banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=E0102E&center=true&vCenter=true&width=640&lines=%3E+sinal+recebido+de+Crime+Alley...;%3E+identidade%3A+back-end+developer;%3E+c%C3%B3digo+limpo.+regras+claras.+zero+baixas.;%3E+deploy+autorizado." alt="typing" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/foco-back--end-b3001b?style=for-the-badge&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/Python-Flask%20%7C%20FastAPI%20%7C%20Django-b3001b?style=for-the-badge&labelColor=0a0a0a" />
  <img src="https://img.shields.io/badge/c%C3%B3digo-de%20conduta-b3001b?style=for-the-badge&labelColor=0a0a0a" />
</p>

> **Gotham tem leis. Eu tenho as minhas — e todas passam nos testes.**

---

## `01 // Ficha`

Sou dev **back-end** e trabalho principalmente com **Python** (**Flask**, **FastAPI** e **Django**), com **PostgreSQL** guardando o que importa e **Pandas** e **NumPy** quando o assunto é dado.

Faço o serviço que ninguém quer pegar: a regra de negócio confusa, o sistema legado sem testes, a API que "funciona, mas ninguém sabe como". Entro, entendo o terreno e saio deixando código que o time consegue ler, testar e evoluir. Cuido do sistema do começo ao fim: modelo os dados, desenho a API, escrevo os testes, penso na segurança e coloco em produção.

```python
from dataclasses import dataclass


@dataclass(frozen=True)
class RedHood(BackendDeveloper):
    codename: str = "Red Hood"
    github: str = "vitortuness"
    base: str = "Crime Alley, Gotham"

    languages: frozenset[str] = frozenset({"Python 3", "SQL", "TypeScript"})
    frameworks: frozenset[str] = frozenset({"Flask", "FastAPI", "Django"})
    data: frozenset[str] = frozenset({"PostgreSQL", "Pandas", "NumPy", "JSON"})
    tools: frozenset[str] = frozenset({"Docker", "Git", "GitHub"})

    code_of_conduct: tuple[str, ...] = (
        "CLEAN_CODE",
        "SOLID",
        "TESTED_BUSINESS_RULES",
        "SECURE_BY_DEFAULT",
        "NO_COLLATERAL_DAMAGE",
    )

    def motto(self) -> str:
        return "Todo deploy merece uma segunda chance. Por isso existe rollback."
```

---

## `02 // Código de conduta`

| Regra | Na prática |
| :-- | :-- |
| 🩸 **Rastro limpo** | Nomes que revelam intenção, funções curtas com uma responsabilidade só, nada de número mágico. Se o código precisa de comentário pra ser entendido, eu reescrevo o código. |
| 🎯 **Mira certa** | Type hints em tudo, imutabilidade por padrão, composição em vez de herança e validação que falha cedo (Pydantic na borda). |
| 🧱 **SOLID** | Injeção de dependências, dependência de abstrações, módulos coesos e baixo acoplamento. |
| 🚫 **Sem baixas colaterais** | Testes automatizados em cima da regra de negócio, integração com banco real e cenários de erro tratados como cidadãos de primeira classe. |
| 📡 **Informante confiável** | REST com recursos bem nomeados, JSON consistente, status HTTP corretos, erros padronizados com Problem Details (RFC 9457), paginação e versionamento. |
| 🪖 **Capacete sempre** | Autenticação com JWT ou sessão + CSRF, senhas com hash forte, validação na borda, rate limiting e segredos fora do código. |
| 🗺️ **Conheça o terreno** | Migrações versionadas, modelagem pensada nas consultas, índices certos e zero N+1. |

---

## `03 // Mapa do esconderijo`

- **Camadas com fronteiras claras:** entrada, aplicação, domínio e infraestrutura. O domínio não conhece framework.
- **Ferramenta certa pra cada missão:** Flask quando é leve, FastAPI quando é API assíncrona e tipada, Django quando o projeto pede tudo integrado.
- **DTOs na borda** e mapeamento explícito: model nunca vaza pela API.
- **Dados sob controle:** consultas SQL afiadas no PostgreSQL e análise com Pandas e NumPy.
- **Tudo em contêiner:** ambientes reproduzíveis com Docker, do desenvolvimento à produção.
- **Rastro versionado:** Git e GitHub com commits pequenos, branches curtas e code review.

---

## `04 // Arsenal`

| Categoria | Equipamento |
| :-- | :-- |
| **Linguagens** | ![Python](https://img.shields.io/badge/Python-0a0a0a?style=flat-square&logo=python&logoColor=e0102e) ![SQL](https://img.shields.io/badge/SQL-0a0a0a?style=flat-square&logo=postgresql&logoColor=e0102e) ![TypeScript](https://img.shields.io/badge/TypeScript-0a0a0a?style=flat-square&logo=typescript&logoColor=e0102e) |
| **Back-end** | ![Flask](https://img.shields.io/badge/Flask-0a0a0a?style=flat-square&logo=flask&logoColor=e0102e) ![FastAPI](https://img.shields.io/badge/FastAPI-0a0a0a?style=flat-square&logo=fastapi&logoColor=e0102e) ![Django](https://img.shields.io/badge/Django-0a0a0a?style=flat-square&logo=django&logoColor=e0102e) |
| **Dados** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0a0a0a?style=flat-square&logo=postgresql&logoColor=e0102e) ![JSON](https://img.shields.io/badge/JSON-0a0a0a?style=flat-square&logo=json&logoColor=e0102e) |
| **Análise** | ![Pandas](https://img.shields.io/badge/Pandas-0a0a0a?style=flat-square&logo=pandas&logoColor=e0102e) ![NumPy](https://img.shields.io/badge/NumPy-0a0a0a?style=flat-square&logo=numpy&logoColor=e0102e) |
| **Front-end** | ![TypeScript](https://img.shields.io/badge/TypeScript-0a0a0a?style=flat-square&logo=typescript&logoColor=e0102e) ![HTML](https://img.shields.io/badge/HTML-0a0a0a?style=flat-square&logo=html5&logoColor=e0102e) ![CSS](https://img.shields.io/badge/CSS-0a0a0a?style=flat-square&logo=css&logoColor=e0102e) |
| **Ferramentas** | ![Docker](https://img.shields.io/badge/Docker-0a0a0a?style=flat-square&logo=docker&logoColor=e0102e) ![Git](https://img.shields.io/badge/Git-0a0a0a?style=flat-square&logo=git&logoColor=e0102e) ![GitHub](https://img.shields.io/badge/GitHub-0a0a0a?style=flat-square&logo=github&logoColor=e0102e) |

---

## `05 // Rastros`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=vitortuness&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=e0102e&icon_color=e0102e&text_color=d9d9d9&rank_icon=github" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vitortuness&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=e0102e&text_color=d9d9d9" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=vitortuness&hide_border=true&bg_color=0a0a0a&color=d9d9d9&line=b3001b&point=e0102e&area=true&area_color=5c0000" />
</p>

---

## `06 // Sinal`

Quer trocar ideia sobre back-end, arquitetura ou um projeto? Acende o sinal:

<p>
  <a href="https://github.com/vitortuness"><img src="https://img.shields.io/badge/GitHub-vitortuness-b3001b?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0a0a" /></a>
  <a href="https://www.instagram.com/vitorantunes.dev/"><img src="https://img.shields.io/badge/Instagram-vitorantunes.dev-b3001b?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0a0a0a" /></a>
  <a href="https://www.youtube.com/@antunesprog"><img src="https://img.shields.io/badge/YouTube-@antunesprog-b3001b?style=for-the-badge&logo=youtube&logoColor=white&labelColor=0a0a0a" /></a>
</p>

> *"The biggest risk is not taking any risk... In a world that is changing really quickly, the only strategy that is guaranteed to fail is not taking risks."*
> — Mark Zuckerberg

<p align="center"><code>▌ fim do sinal // capuz desligado ▐</code></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:b3001b,40:5c0000,100:0a0a0a" />
</p>
