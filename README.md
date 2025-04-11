> 📌 This GitHub profile was created solely for the purpose of anonymous sharing during the peer review process. 
> The repository contains supplementary material for a manuscript currently under review.

# Synthetic Users in Human-Centred Design
> 📝 **Note:** This search strategy and dataset were prepared to support the manuscript  
> _"AI Systems as Synthetic Users in Human-Centred Design: A Systematic Review"_  
> currently under review for presentation at [MIPRO 2025](http://www.mipro.hr/).  
> Due to length limitations in the manuscript, the full search query is shared here as supplementary material.

## Search Strategy (Scopus & WoS)

This repository contains the search queries and strategies used in a systematic literature review on synthetic users in human-centred design (HCD). The search was conducted on 20 February 2025 across two major databases: Scopus and Web of Science Core Collection.

Due to character and formatting limitations in the submitted manuscript, the full search string is provided here for transparency and reproducibility.

The review investigates how artificial intelligence (AI) systems—including **large language models (LLMs)**, **generative agents**, and **agent-based simulations**—are used as **proxies or surrogates for real users** across different stages of the **human-centred design (HCD) process**.

📚 Included Databases
	•	Scopus
	•	Web of Science Core Collection (WoS CC > SCI-EXPANDED, SSCI, A&HCI, CPCI-S, CPCI-SSH, ESCI

Queries were tailored to match each database’s syntax, with a focus on retrieving peer-reviewed articles and conference papers in English, published between 2018 and 2025.

Due to the emerging and interdisciplinary nature of this field, the query includes:
	•	Terms from HCD, HCI, design, and UX research
	•	AI concepts (e.g. LLMs, generative AI, agent-based models)
	•	Functional verbs indicating user substitution (e.g. simulate, mimic, replace)
	•	Proximity operators to capture relevant conceptual pairings

To ensure comprehensive coverage, the search was conducted across titles, abstracts, and keywords, as well as source titles and conference names.

### Scopus Query

```
(TITLE-ABS-KEY ( "human-centered design" OR "human-centred design" OR "human-centric" OR "user-centered design" OR "user-centred design" OR "user-centric" OR ucd OR hcd OR "user experience" OR "experience design" OR "ux research" OR "user research" OR "ux design" OR "interaction design" OR "user interaction" OR usabilityor AND accessibility OR "ui design" OR "user interface design" OR "user interface*" OR hci OR "human-computer interaction" OR "comp* human interact*" OR "human-centred comput*" OR "human factor?" OR "double diamond" OR "design process" OR "design thinking" OR "participatory design" OR "co-design" OR "co-creation" OR "service design" OR "human-ai interaction" OR prototyp* OR "user study" OR "software engineering" ) OR SRCTITLE ( "human-centered design" OR "human-centred design" OR "human-centric" OR "user-centered design" OR "user-centred design" OR "user-centric" OR ucd OR hcd OR "user experience" OR "experience design" OR "ux research" OR "ux design" OR "interaction design" OR usability OR accessibility OR "ui design" OR "user interface design" OR "user interface*" OR hci OR "human-computer interaction" OR "human factor?" OR "participatory design" OR "co-design" OR "co-creation" OR "service design" OR "human-ai" ) OR CONFNAME ( "human-centered design" OR "human-centred design" OR "human-centric" OR "user-centered design" OR "user-centred design" OR "user-centric" OR ucd OR hcd OR "user experience" OR "experience design" OR "ux research" OR "ux design" OR "interaction design" OR usability OR accessibility OR "ui design" OR "user interface design" OR "user interface*" OR hci OR "human-computer interaction" OR "human factor?" OR "participatory design" OR "co-design" OR "co-creation" OR "service design" OR "human-ai" )) AND (TITLE-ABS-KEY ( ( synthetic* OR "synthetic user*" OR "synthetic data*" OR ai OR "artificial intelligence" OR "ai driven" OR "ai based" OR "ai agent*" OR "ai model*" OR "human-ai" OR "ai-human" OR "generative artificial intelligence" OR "generative ai" OR genai OR llm OR "llm driven" OR "llm based" OR "llm chatbot?" OR "large language model*" OR "language model*" OR "neural language model*" OR "generative pretrained transformer*" OR chatgpt* OR gpt* OR "generative adversarial network*" OR gan OR "agent-based" OR "agent-based model*" OR "rl agent*" OR "reinforcement learning agent*" OR "chat-based" OR "chatbot*" OR "generative agent*" W/3 "act* as" OR augment* OR automate OR build* OR built OR created OR creating OR creation OR "data driven" OR develop* OR emulate* OR generate* OR generating OR mimic* OR mirror* OR "play* role*" OR produced OR producing OR production OR proxy OR proxies OR represent* OR replicat* OR replac* OR simulat* OR simulacr* OR speculative OR substitut* OR supplement* OR surrogate* ) W/3 ( human* OR participant* OR people OR respondent* OR stakeholder* OR subject* OR user* OR "user archetype*" OR "user data" OR "user group*" OR "virtual user*" OR persona* OR protopersona* OR "focus group*" OR interview* OR survey* OR questionnaire OR prototyp* OR "heuristic evaluation" OR "usability evaluation" OR "usability test*" OR "card sorting" OR "diary stud*" OR "journey map*" OR "accessibility evalution" OR "research data" OR "self-report*" ) )) 

AND PUBYEAR > 2017 AND PUBYEAR < 2026
AND ( LIMIT-TO ( DOCTYPE, "cp" ) OR LIMIT-TO ( DOCTYPE, "ar" ) )
AND ( LIMIT-TO ( LANGUAGE, "English" ) )

```

### WoS Query

```
TS=(((( synthetic* OR "synthetic user*" OR "synthetic data*" OR AI OR "artificial intelligence" OR "AI driven" OR "AI based" OR "AI agent*" OR "AI model*" OR "human-ai" OR "ai-human" OR "generative artificial intelligence" OR "generative AI" OR genAI OR LLM OR "LLM driven" OR "LLM based" OR "LLM chatbot?" OR "large language model*" OR "language model*" OR "neural language model*" OR "generative pretrained transformer*" OR chatgpt* OR GPT* OR "generative adversarial network*" OR GAN OR "agent-based" OR "agent-based model*" OR "RL agent*" OR "reinforcement learning agent*" OR "chat-based" OR "chatbot*" OR "generative agent*") NEAR/3 ( "act* as" OR augment* OR automate OR build* OR built OR created OR creating OR creation OR "data driven" OR develop* OR emulate* OR generate* OR generating OR mimic* OR mirror* OR "play* role*" OR produced OR producing OR production OR proxy OR proxies OR represent* OR replicat* OR replac* OR simulat* OR simulacr* OR speculative OR substitut* OR supplement* OR surrogate*)) NEAR/3 ( human* OR participant* OR people OR respondent* OR stakeholder* OR subject* OR user* OR "user archetype*" OR "user data" OR "user group*" OR "virtual user*" OR persona* OR protopersona* OR "focus group*" OR interview* OR survey* OR questionnaire OR prototyp* OR "heuristic evaluation" OR "usability evaluation" OR "usability test*" OR "card sorting" OR "diary stud*" OR "journey map*" OR "accessibility evalution" OR "research data" OR "self-report*")))
AND 
TS=("human-centered design" OR "human-centred design" OR "human-centric" OR "user-centered design" OR "user-centred design" OR "user-centric" OR ucd OR hcd OR "user experience" OR "experience design" OR "UX research" OR "user research" OR "UX design" OR "interaction design" OR "user interaction" OR usability OR accessibility OR "UI design" OR "user interface design" OR "user interface*" OR hci OR "human-computer interaction" OR "comp* human interact*" OR "human-centred comput*" OR "human factor?" OR "double diamond" OR "design process" OR "design thinking" OR "participatory design" OR "co-design" OR "co-creation" OR "service design" OR "human-ai interaction" OR prototyp* OR "user study" OR "software engineering") OR SO=("human-centered design" OR "human-centred design" OR "human-centric" OR "user-centered design" OR "user-centred design" OR "user-centric" OR ucd OR hcd OR "user experience" OR "experience design" OR "UX research" OR "UX design" OR "interaction design" OR usability OR accessibility OR "ui design" OR "user interface design" OR "user interface*" OR hci OR "human-computer interaction" OR "human factor?" OR "participatory design" OR "co-design" OR "co-creation" OR "service design" OR "human-ai") OR CF=("human-centered design" OR "human-centred design" OR "human-centric" OR "user-centered design" OR "user-centred design" OR "user-centric" OR ucd OR hcd OR "user experience" OR "experience design" OR "UX research" OR "UX design" OR "interaction design" OR usability OR accessibility OR "ui design" OR "user interface design" OR "user interface*" OR hci OR "human-computer interaction" OR "human factor?" OR "participatory design" OR "co-design" OR "co-creation" OR "service design" OR "human-ai")
AND 2024 or 2023 or 2022 or 2021 or 2025 or 2020 or 2019 or 2018 (Publication Years) 
AND English (Languages) 
AND Proceeding Paper or Article (Document Types)
```

