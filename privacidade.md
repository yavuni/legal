# Política de Privacidade

> **Versão de piloto.** Vale durante o teste fechado do Assistente Yavuni, a partir de 1º de novembro de 2026. Este texto está em revisão jurídica e pode mudar; avisaremos antes de qualquer mudança relevante.

Última atualização: 1º de novembro de 2026

## 1. Quem somos

O **Assistente Yavuni** (“Yavuni”) é um assistente pessoal de agenda, tarefas, gastos, hábitos e leitura de
boletos, usado pelo aplicativo Android e pelo Telegram.

O responsável pelos seus dados (controlador, na LGPD) é Erick Vinicius Valadares dos Santos, pessoa física responsável pelo piloto. Contato para assuntos de privacidade: yavuni.assistente@gmail.com.

## 2. Quais dados tratamos

| Dado | Para quê | Por quanto tempo |
|---|---|---|
| **Identificação**: identificador do Telegram e, se você pedir acesso, nome e @usuário do Telegram; fuso horário e hora do resumo | Saber quem você é e agendar seus avisos | Até você apagar a conta |
| **Conversas**: o texto que você digita ou fala (a voz é transformada em texto) e as respostas | Dar contexto ao assistente (ele só lê as últimas 24 horas) | **30 dias** |
| **Agenda e tarefas**: títulos, datas, observações, recorrência, prazos | Lembretes e organização | Até você apagar ou excluir a conta |
| **Gastos e orçamentos**: valor, categoria, descrição, data, limites mensais | Controle financeiro e alertas | Até você apagar ou excluir a conta |
| **Hábitos e registros**: nomes, metas, horários, anotações | Cobranças e acompanhamento | Até você apagar ou excluir a conta |
| **Documentos (foto ou PDF)**: lemos beneficiário, valor, vencimento e linha digitável. **A imagem ou o PDF não são guardados**, só os campos lidos | Criar lembrete de boleto ou registrar gasto | Campos lidos e não confirmados: **7 dias**. Linha digitável e valor do boleto: **7 dias após o vencimento** |
| **Avisos** gerados pelo sistema (lembretes, resumos) | Entregar ao app | 30 dias |
| **Uso de IA**: tipo, modelo, quantidade e custo, **sem o conteúdo** | Medir custos e limites | Mantido; ao excluir a conta, perde o vínculo com você |
| **Aparelho do app**: nome do aparelho, identificador criptografado (hash) do acesso e data do último uso | Autenticar o app | Até você excluir a conta ou revogar |
| **Token de notificação (push)** do aparelho, um código que o Google (Firebase Cloud Messaging) gera para o app no seu celular | Acordar o app para buscar um aviso novo na hora, sem esperar | Até você excluir a conta ou sair do app; apagado antes se o Google informar que o aparelho não existe mais |

Não guardamos: a imagem ou o PDF enviados, o áudio da sua voz (só o texto transcrito) nem sua senha de nenhum serviço.

## 3. Dados de saúde

**O serviço não foi feito para dados de saúde.** Você pode criar lembretes genéricos como "Consulta às 15h" ou
"Remédio às 8h", mas o assistente é instruído a não registrar nome de medicamento, doença, diagnóstico, sintoma, exame,
especialidade ou nome de médico. Pedimos que **não informe** esse tipo de dado.

Mesmo assim, o assistente conversa em texto livre: se você escrever esses dados, o texto da conversa é guardado por
30 dias e enviado ao provedor de IA (seção 5), embora não seja usado na sua agenda. Se você escrever, pode pedir a
exclusão a qualquer momento (seção 7).

## 4. Por que podemos tratar seus dados (bases legais)

A base principal é a **execução do serviço que você pediu** (LGPD, art. 7º, V): sem os
dados, o assistente não consegue agendar, lembrar nem registrar. Para o envio a provedores de IA no exterior e para o uso
da câmera e do microfone, usamos o seu **consentimento**, dado ao usar cada recurso e que você pode retirar a qualquer
momento. Também guardamos dados mínimos para **segurança, prevenção a fraudes e cumprimento de obrigações legais**.

## 5. Com quem compartilhamos

- **OpenAI** (modelo de linguagem): recebe o texto das últimas mensagens, os resultados das consultas à sua agenda e
  gastos, e as imagens ou PDFs de documentos que você enviar, para gerar as respostas. A retenção e o uso desses
  dados seguem as regras da OpenAI para a sua API, que podem mudar.
- **OpenAI** (transcrição de voz): recebe o áudio das mensagens de voz para transformá-lo em texto. Nós não guardamos
  o áudio, só o texto transcrito.
- **Telegram**: se você usa o bot, o Telegram transporta o que você troca com ele, segundo a política do próprio Telegram.
- **Google (Firebase Cloud Messaging, FCM)**: no app Android, o servidor pede ao Google que envie ao seu aparelho um
  sinal de que há aviso novo. **O texto do lembrete não passa pelo Google**: o sinal não leva conteúdo, e o app busca o
  aviso no nosso servidor. O Google recebe o token do aparelho, um identificador da instalação do app, o endereço IP e
  os horários dos sinais, segundo a política do próprio Google. O app usa só o módulo de mensagens, sem Analytics nem
  Crashlytics. Se você não quiser, negue as notificações; os avisos continuam chegando pelo app quando ele busca
  (até cerca de 15 minutos) e pelo Telegram.
- **Hospedagem** (Oracle Cloud, região Brasil Leste, São Paulo): onde ficam o servidor e o banco de dados.

Não vendemos seus dados nem os usamos para publicidade.

**Transferência internacional.** A OpenAI e o Google (FCM) podem tratar dados fora do Brasil, como nos Estados Unidos. Fazemos esse envio para prestar o serviço que você pediu e com o seu consentimento ao usá-lo; você pode retirá-lo a qualquer momento excluindo a conta. As regras de cada provedor estão nas políticas deles.

## 6. Segurança

O app fala com o servidor por conexão criptografada (HTTPS) em rede privada; o acesso é protegido por um token guardado
de forma criptografada no aparelho. As chaves dos provedores ficam fora do código. Fazemos cópias de segurança
diárias do banco, **cifradas**. Nenhum sistema é totalmente seguro: em
caso de incidente que possa causar dano relevante, avisaremos você e a ANPD nos termos da lei.

## 7. Seus direitos e como exercê-los

| Você quer | Como fazer |
|---|---|
| Ver ou baixar seus dados | Telegram: `/meusdados`. Ou escreva para yavuni.assistente@gmail.com |
| **Excluir a conta e todos os dados** | App: menu ⋮ → **Excluir minha conta**. Telegram: `/apagarconta`. Ou por e-mail |
| Corrigir | Peça ao assistente para alterar ou apagar o item |
| Saber com quem compartilhamos | Seção 5 deste documento |
| Retirar o consentimento | Excluir a conta |

Ao excluir a conta, apagamos os seus dados do banco de dados. **Cópias de segurança já feitas saem do sistema em até 14
dias**, por rotação, e não são usadas para outra finalidade. Respondemos aos pedidos feitos por e-mail em até
15 dias. Você também pode reclamar à ANPD (gov.br/anpd).

## 8. Crianças e adolescentes

O serviço é destinado a maiores de 18 anos. Se soubermos que uma criança usa o serviço, excluiremos a
conta.

## 9. Mudanças nesta política

Se mudarmos o que fazemos com seus dados, atualizamos esta página e, em mudanças relevantes, avisamos pelo app ou pelo
Telegram.

## 10. Encarregado e contato

Erick Vinicius Valadares dos Santos, responsável pelas questões de privacidade: yavuni.assistente@gmail.com.
