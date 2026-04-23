# iaEste documento apresenta o registro do raciocínio estratégico para o desenvolvimento de uma IA de busca de vagas e o **Miniguia de Estudo** consolidado conforme solicitado.

### 1. Registro do Processo de Raciocínio e Troubleshooting

Para chegar à solução de uma IA voltada ao LinkedIn, foram elaboradas perguntas estratégicas e testadas variações de comandos para garantir precisão técnica e ética.

*   **Pergunta Estratégica Inicial:** "Como automatizar a busca de vagas usando IA?"
    *   **Variação Testada:** "Quais ferramentas de IA (LLMs) e linguagens de programação são necessárias para filtrar descrições de vagas?".
    *   **Resposta Obtida:** A necessidade de integrar **Python**, **NLP (Processamento de Linguagem Natural)** e APIs de modelos como **Gemini** ou **GPT-4**.
*   **Troubleshooting (Dificuldades e Soluções):**
    *   **Alucinações:** Durante os testes, notou-se que IAs genéricas podem inventar requisitos de vagas ou "confabular" informações que parecem plausíveis, mas são factualmente imprecisas. **Solução:** Utilizar o **NotebookLM** alimentado por fontes fixas (PDFs de descrições reais) para mitigar erros.
    *   **Privacidade:** O risco de enviar dados sensíveis do currículo para treinamento de modelos públicos. **Solução:** Configurar o chat para modo privado ou usar modelos que garantam a não retenção de dados.
    *   **Vieses:** Modelos podem priorizar visões do "Norte Global", afetando a interpretação de vagas no mercado brasileiro. **Solução:** Revisão humana constante (**human-in-the-loop**).

---

### 2. Miniguia de Estudo (Entrega Final)

#### **Resumos Estruturados**
1.  **Fundamentos da IA Generativa:** Baseia-se em **Grandes Modelos de Linguagem (LLMs)** que usam cálculos probabilísticos para prever a próxima palavra, mas não "raciocinam" como humanos. São úteis como assistentes de pesquisa, mas exigem supervisão rigorosa.
2.  **Uso Ético e Responsável:** A integridade acadêmica e profissional exige **transparência** no uso de IA. A IA nunca deve ser listada como autora, pois a autoria exige responsabilidade moral e legal.
3.  **Ferramenta NotebookLM:** Diferencia-se por responder **apenas com base nas fontes fornecidas**, permitindo citações diretas e maior confiabilidade. É ideal para organizar conhecimentos complexos e gerar resumos, áudios e mapas mentais.
4.  **Markdown e Documentação:** Para apresentar projetos no GitHub, utiliza-se a linguagem de marcação **Markdown** (.md), essencial para criar arquivos README atrativos que funcionam como porta de entrada para recrutadores.

#### **Glossário de Conceitos Chave**
*   **Prompt:** Comando em linguagem natural dado à IA para obter uma resposta específica.
*   **Alucinação (ou Confabulação):** Erro estatístico onde a IA inventa fatos ou referências inexistentes.
*   **Human-in-the-loop:** Princípio de manter a supervisão humana central em todas as decisões e saídas da IA.
*   **Agente de IA:** Ferramenta treinada para tarefas específicas, capaz de agir de forma autônoma em seu escopo.
*   **Markdown:** Linguagem de marcação simples para formatar textos na web através de símbolos.
*   **Engenharia de Prompts:** Processo de refinar instruções para extrair o melhor desempenho do modelo.

#### **Conjunto de Prompts Reutilizáveis**
*   **Para Análise Profunda:** *"Responda como especialista em [Área]. Faça um documento acadêmico/técnico do conteúdo, destacando ideias importantes. Seja aprofundado e adicione citações diretas do texto."*.
*   **Para Simplificação (Técnica de Feynman):** *"Explique este material para mim em profundidade usando a técnica de Feynman, como se você fosse o autor."*.
*   **Para Organização de Estudos:** *"Crie um resumo em tópicos sobre os principais conceitos desta fonte e monte um plano de estudo de 5 dias dividido por prioridade."*.
*   **Para Troubleshooting Técnico:** *"Qual é o comportamento esperado vs. o atual? Identifique o gatilho do erro seguindo o padrão S.T.E.P. (Status, Trigger, Evidence, Payload)."*.
