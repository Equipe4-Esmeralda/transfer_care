## Documento de Casos de Uso: Sistema Médico de Transferência de Pacientes

Este documento de casos de uso fornece uma visão geral das funcionalidades do sistema e das interações entre os atores. Ele serve como base para o desenvolvimento do sistema, garantindo que as necessidades de todos os usuários sejam atendidas.

Atores:

    Médico Requisitante da Transferência
    Coordenadora Administrativa Hospitalar
    Médico da Unidade de Destino
    Médico Regulador

Casos de Uso:

1. Solicitar Transferência (Médico Requisitante):

    Descrição: O médico requisitante preenche um formulário com informações sobre o paciente, incluindo histórico médico, exames e motivo da transferência. O sistema verifica a elegibilidade do paciente e sugere unidades de destino adequadas.
    Fluxo Básico:
        Médico acessa o sistema.
        Preenche o formulário de solicitação.
        Sistema verifica elegibilidade e sugere unidades.
        Médico seleciona a unidade desejada e envia a solicitação.
    Fluxos Alternativos:
        Se o paciente não for elegível, o sistema informa o motivo e encerra a solicitação.
        Se não houver unidades disponíveis, o sistema informa o médico e oferece alternativas.

2. Avaliar Solicitação (Médico da Unidade de Destino/Médico Regulador):

    Descrição: O médico da unidade de destino ou o médico regulador avalia a solicitação, considerando o histórico do paciente, a disponibilidade de recursos e os critérios da unidade.
    Fluxo Básico:
        Médico acessa o sistema.
        Visualiza a solicitação e o histórico do paciente.
        Avalia a adequação da transferência.
        Aceita ou recusa a solicitação, justificando a decisão.
    Fluxos Alternativos:
        Se houver dúvidas, o médico entra em contato com o médico requisitante.
        Se a transferência for aceita, o médico planeja a recepção do paciente.

3. Acompanhar Transferência (Todos os Atores):

    Descrição: Todos os atores envolvidos podem acompanhar o status da transferência em tempo real, incluindo informações sobre o transporte, a chegada do paciente e a alta hospitalar.
    Fluxo Básico:
        Ator acessa o sistema.
        Visualiza o status da transferência.
        Recebe notificações sobre cada etapa do processo.
    Fluxos Alternativos:
        Se houver algum problema durante a transferência, o sistema alerta os atores envolvidos.
        Se a transferência for cancelada, o sistema informa o motivo e encerra o processo.

4. Gerar Relatórios (Coordenadora Administrativa):

    Descrição: A coordenadora administrativa gera relatórios sobre o número de transferências, tempo de espera, taxa de ocupação de leitos e outros indicadores.
    Fluxo Básico:
        Coordenadora acessa o sistema.
        Seleciona o tipo de relatório desejado.
        Define os parâmetros do relatório.
        Gera o relatório e o visualiza ou exporta.

