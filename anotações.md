sistemas embarcados:

    - sistemas completos, independentes e que executam uma única função;
    - requisitos específicos - a execução deste requisito é repetitiva;
    - não tem flexibilidade, não executa aquilo que não foi pré-delimitado (recebem apenas updates);
    - há sistema embarcado em tudo;
    
    conceitos básicos:
     - plataforma de desenvolvimento (hosts), onde será executada as ferramentas de criação - programa e envia para o target;
     - plataforma alvo (target), plataforma onde as aplicações serão executadas - funciona sozinho;
     - linked setup: conexão via cabo entre host com target, depuração de código remotamente - JTAGs;
     - removable storage setup: atualiza o sistema por meio de pendrive;
     - standalone setup: dentro da plaquinha tem uma IDE embutida;

    sistemas operacionais para embarcados:
     - tinyOS;
     - contiki;
     - VirtuOS;
     - QNX;
     - Windows CE;

    arquitetura do sistema embarcado (ASH):
     - camada do hardware; h
     - camada de sistema software (opcional); s
     - camada de aplicação software (opcional); a

    CPU: realiza cálculos para o computador funcionar, trabalha com o sistema binário, entrada - processamento - saída, ULA (unidade de lógica e aritmética) - trabalha com pontos flutuantes;

    gm