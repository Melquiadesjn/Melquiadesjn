# José Melquíades Neto

**Desenvolvedor fullstack com foco em segurança e análise forense digital.**
Teresina, PI · Brasil

Construo sistemas para o setor público e ferramentas que cruzam dados abertos
para encontrar o que não está evidente — risco societário, vínculos entre
empresas, inconsistência documental. Também trabalho com análise forense
digital: tratamento de evidência e cadeia de custódia.

---

### Em que trabalho

| Área | O que faço |
|---|---|
| **Backend** | NestJS · Node · Python · PostgreSQL — arquitetura em camadas, sem exceção |
| **Frontend** | Next.js · React · TypeScript |
| **Segurança** | OSINT, análise de superfície, forense digital, LGPD |
| **IA aplicada** | RAG, fine-tuning (LoRA/QLoRA), pipelines de inferência |

---

### Projetos em destaque

**[Analisador de Risco CNPJ](https://github.com/Melquiadesjn/Busca-de-CNPJ-)**
Ferramenta OSINT que consulta Receita Federal, Portal da Transparência, DataJud,
PNCP e listas de sanções (CEIS, CNEP, CEPIM, CEAF), calcula score de risco por
empresa e exporta relatório. Feita para due diligence e apoio a investigação.
`Python` · `OSINT` · `dados abertos`

**[Pipeline RAG + QLoRA](https://github.com/Melquiadesjn/Pipeline-Definitivo-)**
Pipeline ponta a ponta para geração de relatórios clínicos: recuperação de ~15k
tokens de contexto, LLM quantizado e FlashAttention-2 + KV Cache para evitar OOM.
`Python` · `RAG` · `QLoRA`

**[Alinhamento com DPO](https://github.com/Melquiadesjn/LAb-8-)**
Implementação de Direct Preference Optimization — a alternativa ao RLHF que
deriva a política ótima direto dos dados de preferência, sem reward model.
`Python` · `LLM` · `alinhamento`

---

### Estudos em IA — série de laboratórios

Implementações do zero, do mecanismo de atenção ao pipeline completo de
especialização de LLM. Cada uma documenta a lógica matemática por trás.

`Self-Attention` → `Encoder` → `Decoder + Cross-Attention` → `Transformer completo`
→ `Treinamento fim-a-fim` → `Tokenizadores BPE/WordPiece` → `LoRA e QLoRA`
→ `DPO` → `Pipeline RAG completo`

---

<sub>Alguns repositórios de laboratório tiveram partes geradas ou complementadas
com apoio de IA, sempre revisadas e validadas por mim — está declarado em cada um.</sub>
