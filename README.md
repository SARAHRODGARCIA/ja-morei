# Já Morei 🏙️

Plataforma que utiliza comentários de pessoas que já moraram em um bairro ou rua
para descrever como é viver naquele local, combinando essas informações com as
preferências do usuário para recomendar os melhores lugares para morar.

A proposta é transformar experiências reais de moradores em sinais estruturados,
utilizados por um modelo de Machine Learning para gerar recomendações
personalizadas de moradia.

## 🎯 Problema
Informações sobre bairros e ruas costumam ser genéricas, incompletas ou enviesadas
por anúncios imobiliários. Falta uma visão realista baseada na vivência cotidiana
das pessoas que moraram ali.

## 💡 Solução
O Já Morei coleta e organiza comentários de ex-moradores sobre bairros e ruas,
classificando essas percepções (ex.: segurança, barulho, transporte, comércio,
qualidade de vida).

Essas classificações são combinadas com as preferências do usuário para alimentar
um modelo de Machine Learning que recomenda os locais mais compatíveis com seu
perfil.

## 🧠 Como funcionará:

1.Landing Page
O usuário conhece a proposta do Já Morei: entender como é viver em um bairro ou rua
a partir de comentários reais de pessoas que já moraram no local.

2.Login / Cadastro
O acesso à plataforma é feito por autenticação segura, permitindo salvar preferências
e histórico de buscas.

3.Questionário Inicial (5 etapas)
O usuário responde a um questionário rápido para definir suas preferências, como:

-segurança

-barulho

-acesso a transporte

- estilo de vida

Essas respostas são transformadas em pesos que serão utilizados pelo modelo de
recomendação.

4. Tela de Confirmação
O usuário revisa suas preferências antes de prosseguir, garantindo transparência
sobre como seus dados serão utilizados na recomendação.

5. Home / Pesquisa de Bairros
O usuário pode pesquisar bairros ou ruas específicas e visualizar sugestões iniciais
com base no seu perfil.

6. Página do Bairro (Freemium)
Exibe:

descrição geral do bairro

comentários públicos de ex-moradores

classificação resumida por critérios

Parte das informações é apresentada como preview gratuito.

7. Bloqueio Premium
Para acessar análises completas e recomendações personalizadas, o usuário é informado
sobre o plano premium e seus benefícios.

8. Página Premium (pós-pagamento)
O usuário tem acesso a:

análise detalhada dos comentários

score de compatibilidade com seu perfil

ranking de bairros e ruas recomendados

insights gerados pelo modelo de Machine Learning

## 🛠️ Tech Stack
- Frontend: Next.js + TypeScript
- Backend: Firebase (Auth + Firestore)
- Machine Learning: Python (pipeline de classificação e recomendação)
- Infra: Vercel
- Segurança: controle de acesso e anonimização de dados
- UX: foco em clareza e tomada de decisão

## 📂 Estrutura do Projeto
- `app/`: rotas e páginas da aplicação
- `components/`: componentes reutilizáveis
- `services/`: lógica de negócio
- `lib/`: integrações externas
- `ml/`: modelos de classificação e recomendação
- `types/`: tipagens TypeScript

## 📈 Status do Projeto
🟡 MVP em desenvolvimento  
Foco atual: estrutura do produto e definição do pipeline de dados para ML.

## 👩‍💻 Autora
Sarah Rodrigues Garcia
Data Scientist | Product & Machine Learning
