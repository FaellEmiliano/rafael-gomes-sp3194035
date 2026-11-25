# Ficha de entrega — trabalho final LP1

Nome do aluno: Rafael Gomes Emiliano
Prontuário completo: Sp3194035
Turma: 213 — Desenvolvimento de Sistemas
Data da entrega: 26/11/2026
URL estável de produção: https://rafael-gomes-sp3194035-lp1.vercel.app
URL de login (termina em /login): https://rafael-gomes-sp3194035-lp1.vercel.app/login
URL do repositório: https://github.com/FaellEmiliano/rafael-gomes-sp3194035
Commit/versão avaliada: código da aplicação em `2209926`

Conta administrativa para avaliação (e-mail): `admin@mercadoviva.example`
Conta de operador para testes (e-mail): `operador@mercadoviva.example`
Canal privado utilizado para entregar as senhas: README do repositório privado. O acesso do professor ainda precisa ser confirmado.

Não escreva senhas neste arquivo se ele for enviado ao GitHub. Não inclua SECRET_KEY, conexão Neon, token GitHub ou credencial da Vercel.

## Checklist

- [x] URL contém meu nome e prontuário completo.
- [x] Login é do supermercado; não exige conta Vercel do professor.
- [x] Banco PostgreSQL individual e migração aplicados.
- [x] Conta do professor funciona.
- [x] Operador, caixa, venda e pagamentos simulados testados.
- [x] Estoque, compras, financeiro, gráfico, Excel e ticket testados.
- [x] Os dois temas estão disponíveis.
- [x] Persistência confirmada após redeploy. O mesmo ticket foi aberto após a Vercel publicar o commit `77ee183`.
- [x] Testes automatizados executados; resultado registrado abaixo.
- [x] .env e bancos locais não foram enviados ao repositório.

Resultado dos testes: 20 testes automatizados aprovados; os mesmos 20 passaram com PostgreSQL 16 isolado. Playwright verificou os dois perfis em produção e os fluxos de operação em banco isolado. Em produção, a venda fictícia por Pix de R$ 27,90 gerou o ticket `/sales/1`, aberto após sair e entrar novamente.
Limitações/problemas conhecidos: o botão de logout fica oculto em telas de celular. A entrega de e-mail por SMTP não foi testada.
Alterações pessoais realizadas pelo aluno: a confirmar.
