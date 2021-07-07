## Estamos anunciando a versão 1.6.1.0

Essa versão tem várias correções de pontuação, algumas sugestões adicionadas, a adição da System.Diagnostics em C# e a proibição de novas palavras em seus códigos (como "dll" e "unityengine").

Além disso, estamos atualizando nosso motor gráfico da versão 2019 -> 2020 para corrigir alguns problemas visuais que surgiram na atualização de abril. Essa atualização não deve impactar performance (e se impactar, impacta positivamente), entretanto muda um pouco a iluminação, resultando em possíveis calibrações em seus robôs (calibrações são previstas pela própria OBR, logo decidimos manter a atualização gráfica).

Sobre bugs gráficos infelizmente a versão 2020 do nosso motor gráfico não corrigiu as funções do "pincel", que seguem quebradas. Não pretendemos mais atualizar nada relacionado a gráficos até a OBR Estadual, apenas pequenas correções, então não se preocupem em relação a isso (infelizmente o pincel vai ter que esperar).

A prioridade da equipe agora será exclusivamente da OBR (devido a proximidade), então na reimplementação da visualização de rodada (antigamente feita pelo gif) e pequenas alterações relacionadas a pontuação, falhas de progresso e falhas visuais. O desenvolvimento de funções como imagens nos ladrilhos, ladrilhos customizáveis, objetos na arena, robôs customizados e entre outras foram realocadas para pós-OBR estadual.