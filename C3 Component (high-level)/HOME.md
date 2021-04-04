# C3 Component (high-level)

![diagram](https://www.plantuml.com/plantuml/svg/0/hLRDZjis4BuRy3imUra7g29acrvwAEALdCJ0-gThfukU35hYscmeKH4fUzqYJzD37oGlrY4fIfHMrku20O8DnVdccvcFmw7V2ubpMIHiE1WEBk5Vk0ZGDEAfGEE_Yvp0pbxAJFpg-pigzyNsJSGJFsCuLKwUa36ZMrz3lQNQ_JoxKLIlQ1gn8YR8UkVu-COm58Ba442IL6eo7ESKfmTMP8KVlAjOV8Ob4HAsDY7963yboY7JgRwAoJrD2GedVqo3nNprZ2Yoo23GptNg5ApUFI0yaUKKGla95fBaVamEoYRgC1yMy_NuRh9Qp2O_D9BUmqSYU4AyNnpHR5q-JdS5mxaj-v7zBtp0PutPIUvvUjQSy7J7u-rvk_ZADb3RWJoAxmZYg_956_2qIlqjvEU44Io8V-MzzMCARQ3j0K-IggBwVBHj2Pi_FcvTKv6pEf0FcMI59CRzGv56aZwIkkaHOectG2riAIBX8jo-nEUMG4e1ZlRa9LwhhypkzBfDGQGy9N9nlzxJT5TwJ_dwKz6VvHqfPGp2-VE0i1XdMNysCPmObIVZC0Pz3oIaEOaapq_NLq6lyunlAIiFPyublQSHLWS4bOWdDTZb6bkA1_rF8t9TYAhhRiP_BZwlDtVJzQVDpUJZP1wENWy7IxW5F1r5Z4BUv2Tq4PZL1IpBJSJu3iSSfHZXZ45A4URAh6_G1N2iJZ0Mab5snB2xl1ih8tbGfuAPMfVJG467WpEwZB3UZm4-BbJNGvpl_tt_LqS2ktA-9MnpOyBKQ6He9weBO4m9ihdcHHhZ_3I2pmCa3g1oTV4Q_JCS8EGSvWXdLCLSJj4jZ6qLBUES8HW6OBaKXhrqgHjvbAkbaajzAIzjKsY4J9wQsCAGvJ5QrJd20MFGbry7ciny80zj5O3a9wI7m8CqgIk6PlhMVwpBi0GNfYIJJkbWRsxb4cu1DUTmpnIyD5ytVS9v1OUrWeLpJQwiI7sKS5LpsCoc4KT6cGkzQT8se7eO6l2tRj58b6Yz9i4Cf9gaEpLD0n0gXvERyRXWv0KI0fjHhuUkLr0Wq8a_uM_nhWwtLNHBKWhbn36ZJ05X1GZuMny1V22mEfmsdGgFUhNCy0whdoYc0vVswmNwLGn6nO_m--U8JwZQxjBE6UwrlwxVRYilGA6LVicRRTQCsFJlhnOkQ_I5fe7wZnVIt3hruT4K-SWimV2I6zYaB2zY1-TJEhI8dgr6Lm9TNFtAfELx0yDTgpAlly-AqPR2uJ0oM99gaZlrbmbC7gJhDyEKpN3-XKXuoy5XVQICQLTbGOarzREiPYib7XKPpdcMQt_OQqZVVc1T_sKXzgvTlGgmLLyxrrZVls_EMr6_m2DHBTLRLeYQfWGXjGaCshyyLFiWcrUrcedb1T1le9QuOIbVdUQZqFB57VtH0bvsDjPRvwfTFGlkADhb01FgwZp8oRQQq9NHcjiTrzD9BU8UJzCzpyTtT8kJg2gsyuussc8y-trffMdDj_EuTaxdaLR1JiHmy3Wzv7dURmuS3GTkLXtcPZ8T09D3sw32loTf3BzI_mS0)

**Level 2: Container diagram**

Depois de entender como seu sistema se encaixa no ambiente geral de TI, uma próxima etapa realmente útil é ampliar o limite do sistema com um diagrama de contêiner. Um "contêiner" é algo como um aplicativo da web do lado do servidor, aplicativo de página única, aplicativo de desktop, aplicativo móvel, esquema de banco de dados, sistema de arquivos, etc. Essencialmente, um contêiner é uma unidade executável / implementável separadamente (por exemplo, um espaço de processo separado ) que executa código ou armazena dados.

O diagrama do Container mostra a forma de alto nível da arquitetura do software e como as responsabilidades são distribuídas por ela. Também mostra as principais opções de tecnologia e como os contêineres se comunicam. É um diagrama simples e focado em tecnologia de alto nível, útil para desenvolvedores de software e equipes de suporte / operações.
**Scope**: A single software system.

**Primary elements**: Recipientes dentro do escopo do sistema de software.
Elementos de suporte: Pessoas e sistemas de software diretamente conectados aos containers.

**Intended audience**: Pessoal técnico dentro e fora da equipe de desenvolvimento de software; incluindo arquitetos de software, desenvolvedores e equipe de operações / suporte.

**Notes**: Este diagrama não diz nada sobre cenários de implantação, clustering, replicação, failover, etc.