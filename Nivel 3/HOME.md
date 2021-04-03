# Nivel 3

![diagram](https://www.plantuml.com/plantuml/svg/0/hLRDRjiu4BuRy3kmljG5rXNY99SzrP7Sra3yWzZTO4y6BJ4sjnIfYfGTxw9FiuTzaBxOpb3_SYqdG8q08JdVDpFyE1pgWpOqDaaekfrkvotyUNENJ7mbDHdzdSGCLdR6HFftnzboiqisxtqLEf6W4aa3RGB1Duw53XQu-cLwZwxUSEcB960aPyVqy3xra6WMGm33fB7EQ11pAlSYYHB7lIcyE88QfWqihJqM2NKCaH3PLDy4x8bBHhpn7nDtFbk-88f98WXqNQREmJfu0iH0Hp67K4v8jM6n4x0zsdGPvkDyjXezZfVpwVYNHh9hzC2q2jdWjY9QlY-7ocqYQ9nl-yJ-5ztJiyReQ7PAdZM7IcvLi3blrz_46lQsPoVnAu8uk7tT15nMgRs4d9W9HZLpXeCh9-1G1jRkgZ0iTbIUZxKjOF7NnottbCIY3EH09b5YM4h_c4ZVy1EfwmoF6he1rphVYWwLzZQluJmmICcb_ewzXhNy9lALLje4H8ebC_EdrOxBRSQUgDNdf3tBHvR9w7gpbm5XC8gYzcm2E35kZYbX1FhkcSTZvXiL7--6RYjvgZPSP8SpKuO_SP_Y0S5ET54zzwC_vrzMwyV9wlFwVlnfFFFwxxgT1LIpadrVS8ZFVYCzDntrO9Wj4g6sD514Ka8Z0Qvzgj1iRq8FV2oFSBt3VdIWiBfu7A6HFQEwLE0ukzK8xNRExAzFxNe0y562rGjnVlpturyR2Un8Vc1YVP-6AT4aTJl6quHsezdwJYKoeF6n3zCz90wWRDHxH_xfTWWXbLFfquXZqCM4F43_nN2HKeB0hGRBMvswppbbIVPZ7A9WE4EQjI4Sm6cgrdME8uMdLAyoJpWi2XghA-ij7PC1sQ2TnKTYx_EpmUo9TL3BFsSFA-nUkgCi6LAxWGNX6a0p1TS5qPdrhaxnPWNw1a7Up7f66y591iRTUjL4gY6C7rLnzrMFLPpjPHdo-ncbc1-YI6Dt2lgCvHQxeGlgn71WKnKaWhNhLXCEd0tRdJLaREW8_ElB_1nUE44H7hBWcOjCecgKj0yX38M7MIayJ0ZOO5lmAvsMBc_IQYEjKaPqI_4JmrRT8f-ylEmAFchu2RvT3lH8YiMV5M2bCPTit7w-YYG0aQLzXEl5LGrN8vCB9GENq__AfOl_L6BmH70uu98u91t2yYkkMztVrHc7bmHek1c-K8RJw3znT4aIcJqHqCUlR0yefcTaE5MXuc9OSL5qxChMi-ZZPrDbuT6j3bm82vzIBaX8uw_Cm5FSpiJgzhYEQAoYsBANqsLDv-OJM6NVOdzFzAwyJbLqUgzILzz9zhFJRiUgcPr2_bgcJrxHkR9IjG-KVLLgbkmzgFRh1ZErdnPO0tQAg5t6Y-Z6uJNmQHjfnzX4i_vPc79ZdTeuyuQZizYRLs1lwrbyO3A0Rvx_0G00)

**Level 2: Container diagram**

Depois de entender como seu sistema se encaixa no ambiente geral de TI, uma próxima etapa realmente útil é ampliar o limite do sistema com um diagrama de contêiner. Um "contêiner" é algo como um aplicativo da web do lado do servidor, aplicativo de página única, aplicativo de desktop, aplicativo móvel, esquema de banco de dados, sistema de arquivos, etc. Essencialmente, um contêiner é uma unidade executável / implementável separadamente (por exemplo, um espaço de processo separado ) que executa código ou armazena dados.

O diagrama do Container mostra a forma de alto nível da arquitetura do software e como as responsabilidades são distribuídas por ela. Também mostra as principais opções de tecnologia e como os contêineres se comunicam. É um diagrama simples e focado em tecnologia de alto nível, útil para desenvolvedores de software e equipes de suporte / operações.
**Scope**: A single software system.

**Primary elements**: Recipientes dentro do escopo do sistema de software.
Elementos de suporte: Pessoas e sistemas de software diretamente conectados aos containers.

**Intended audience**: Pessoal técnico dentro e fora da equipe de desenvolvimento de software; incluindo arquitetos de software, desenvolvedores e equipe de operações / suporte.

**Notes**: Este diagrama não diz nada sobre cenários de implantação, clustering, replicação, failover, etc.