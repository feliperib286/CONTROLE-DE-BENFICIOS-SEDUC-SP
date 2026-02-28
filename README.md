📋 Controle de Benefícios — Magistério SEDUC-SP
Ferramenta web para acompanhamento dos benefícios do servidor docente do Estado de São Paulo: Licença Prêmio, Quinquênio (ATS) e Sexta Parte.

Arquivo único HTML+CSS+JS — sem instalação, sem servidor, sem cadastro.
Funciona direto no navegador e salva os dados localmente.


🚀 Acesso
GitHub Pages:
👉 https://<seu-usuario>.github.io/<nome-do-repositorio>

✨ Funcionalidades

Múltiplos vínculos — Adicione quantos períodos de exercício quiser (afastamentos, rematrículas, retornos)
Cálculo automático — Dias brutos, dias efetivos, totais e blocos completos calculados em tempo real
Previsão com data exata — Data do próximo direito e contagem regressiva em dias corridos
Alertas de interrupção — Linhas com falta injustificada ou licença s/vencimentos ficam destacadas em vermelho
3 abas independentes — Cada benefício tem sua própria tabela de vínculos e cálculos separados
Dados persistentes — Salvos automaticamente no navegador (não perde ao fechar)
Exportar CSV — Baixe os vínculos de cada aba
Imprimir / PDF — Botão de impressão em cada aba


📖 Como usar

Abra o arquivo no navegador ou acesse pelo GitHub Pages
Clique na aba do benefício desejado: 🏅 Licença Prêmio, 📅 Quinquênio ou ⭐ Sexta Parte
Clique em + Adicionar Vínculo e preenche:

Início do período de exercício
Fim (deixe em branco se ainda estiver ativo — o sistema usa a data de hoje)
Cargo/Categoria
Faltas do período nas colunas correspondentes


Os totais e previsões atualizam automaticamente
Interrupção? Se houve falta injustificada ou licença s/vencimentos, encerre o vínculo na data do evento e crie um novo vínculo a partir da data de retorno


📐 Regras implementadas
🏅 Licença Prêmio
Base legal: Lei 10.261/68, Art. 209 | LC 1048/08 | LC 1361/2021 | LC 1374/2022
RegraDetalhePeríodo aquisitivo5 anos = 1.826 dias de efetivo exercícioDireito90 dias por bloco completoLimite de faltas25 dias por quinquênio (vigente desde LC 1.361/2021, a partir de períodos fechados em 01/01/2022)Faltas que contam no limiteFalta abonada + Falta médica/atestado + Licença Saúde DPME (própria e familiar)Interrompem o períodoFalta injustificada · Suspensão/Penalidade · Licença s/Vencimentos · Afastamento eleitoralNão interrompem e não contam no limiteFérias · Lic. Maternidade · Acidente de trabalho · Lic. Prêmio · Casamento (8d) · Óbito familiar · Doação de sangueRegra anterior (períodos fechados até 27/05/2020)Limite de 30 dias — faltas abonadas não computavam

⚠️ Falta médica (atestado particular): conta nas 25 faltas. NÃO interrompe o período.
⚠️ Licença Saúde DPME: conta nas 25 faltas. NÃO interrompe o período.
✅ Licença Saúde DPME acima de 90 dias: suspende a contagem (não interrompe — reinicia de onde parou).

📅 Quinquênio (ATS)
Base legal: Art. 129 do Estatuto do Magistério (CE-SP)
RegraDetalhePeríodoA cada 5 anos (1.826 dias) de efetivo serviçoAdicional+5% sobre o salário base por quinquênio completoMáximo12 quinquênios (60 anos de serviço)ConcessãoAutomática — sem necessidade de requerimentoInterrupçõesMesmas regras da Licença Prêmio
⭐ Sexta Parte
Base legal: Art. 129 CE-SP
RegraDetalheRequisito20 anos de efetivo serviço (7.305 dias)Adicional1/6 ≈ 16,67% sobre os vencimentos integraisAfastamentosDeduzem dias do período aquisitivoRestriçãoVedado efeito cascata com quinquênio

🔄 Mudanças da Nova Resolução (LC 1374/2022 + Res. SEDUC 97/2025)
CritérioNova regraRegra anteriorLimite de faltas25 dias30 diasFalta abonadaConta nas 25Não computavaFalta médica / atestadoConta nas 25Contava nas 30Lic. Saúde DPMEConta nas 25Contava nas 30Atestado entregue no diaMais flexível (Res. 97/2025)Mais restritivoFalta injustificadaINTERROMPEINTERROMPELic. s/ VencimentosINTERROMPEINTERROMPE

🗓️ Período de Pandemia (28/05/2020 a 31/12/2021)

O STF concedeu liminar (jul/2023) suspendendo o cômputo do período pandêmico para fins de Licença Prêmio, Quinquênio e Sexta Parte.
Esse período não conta como efetivo exercício para esses benefícios, salvo decisão judicial individual.


⚖️ Base Legal Completa

Lei nº 10.261/68, Art. 78, 209, 210, 213, 324
Lei Complementar nº 1048/08
Lei Complementar nº 1361/2021
Lei Complementar nº 1374/2022
Resolução SEDUC nº 97/2025
Estatuto do Magistério (CE-SP), Art. 129
Res. SE 89/2005


🛠️ Tecnologia

HTML5 + CSS3 + JavaScript puro
Arquivo único — sem dependências externas (exceto Google Fonts)
Armazenamento via localStorage do navegador
Compatível com Chrome, Firefox, Edge e Safari


📌 Como publicar no GitHub Pages

Crie um repositório no GitHub
Faça upload do arquivo controle-beneficios-seduc.html
Renomeie para index.html (ou acesse pelo nome completo na URL)
Vá em Settings → Pages → Source: main branch → Save
Aguarde ~1 minuto e acesse: https://<usuario>.github.io/<repositorio>


⚠️ Aviso
Esta ferramenta é um auxiliar de acompanhamento pessoal. Os cálculos são baseados nas leis e resoluções vigentes listadas acima. Em caso de dúvida ou contestação, consulte a Diretoria de Ensino ou o Departamento de Recursos Humanos da SEDUC-SP.

Desenvolvido  por FELIPE RIBEIRO DE LIMA
para uso dos servidores docentes do Estado de São Paulo.
