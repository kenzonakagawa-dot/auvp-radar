# Painel do AUVP RADAR

**Este repositorio nao e editado a mao.** O `index.html` e gerado por
`radar\painel.ps1`, no projeto `avaliacao-clickup`, e sobrescrito a cada publicacao.

Para republicar, naquele projeto:

    powershell -File radar\painel.ps1
    powershell -File radar\publicar.ps1 -Enviar

Sem `-Enviar` o script so mostra o que iria. Ele aborta se achar chave de API, CPF ou
caminho local no HTML, e se o clone estiver atras do remoto.

## O que a pagina contem

Analise do canal do YouTube monitorado: regua de desempenho por formato, tendencia de
audiencia e engajamento, composicao das coletas de tema, custo de uso da API de IA, e as
pautas recomendadas com a interface onde a solicitante julga cada uma.

A pagina vai com `noindex`: funciona para quem tem o link, nao aparece em buscador.