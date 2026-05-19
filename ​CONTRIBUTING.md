Guia de Contribuição do JavaScript OS (JSOS)
​Bem-vindo ao ecossistema do JavaScript OS. O JSOS é mantido pela Equipe PythonSL e prioriza segurança, modularidade e performance.
​1. Regras de Ouro
​Segurança Primeiro: O JavaScript Kernel não tolera falhas de segurança. Qualquer contribuição que contorne o UAC ou o Firewall do JSN será rejeitada.
​Modularidade: Novas funções devem ser adicionadas como módulos ou drivers, nunca modificando o núcleo do index.js sem revisão da Equipe PythonSL.
​Formato de App: Todos os aplicativos devem seguir estritamente o padrão .japp.
​2. Processo de Submissão
​Fork o repositório da Equipe PythonSL.
​Crie uma Branch baseada no componente que você está alterando (ex: feature/novo-driver-gl).
​Submeta um Pull Request para a branch develop.
​O código passará por revisão da equipe para validar a integração com o JavaScript Kernel.
​3. Código de Conduta
​Seja respeitoso e profissional.
​Toda alteração no JavaScript Kernel exige documentação técnica clara.
​O uso de bibliotecas externas deve ser evitado para manter o JSOS leve e "puro".
