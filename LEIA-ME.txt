EDUKAI AFRICA — Tutor v0.4

CONFIGURAÇÃO PEDAGÓGICA
- Público: todos os estudantes (primário, secundário, técnico-profissional, superior e formação/estudo autónomo).
- Disciplinas: Matemática, Biologia, Química, Física, Língua Portuguesa, Enfermagem, História, Geografia e Inglês.
- Método do Tutor IA: explicações passo a passo, exemplos resolvidos, resumo e exercícios.

O QUE ESTÁ IMPLEMENTADO
- Interface web responsiva.
- Selecção de nível, classe/ano/curso, disciplina e língua.
- Chat ligado a backend Node.js.
- Backend chama endpoint compatível com OpenAI Chat Completions.
- Instruções pedagógicas e salvaguardas específicas para Enfermagem.
- Nove aulas de demonstração e exercícios com correção.
- Progresso dos exercícios guardado localmente no navegador.
- Chave API guardada no servidor, não no frontend.

REQUISITOS
- Node.js 18+.
- Ollama local (gratuito, mas requer computador com recursos suficientes) ou fornecedor de IA compatível com API OpenAI (pode ter limites/custos).

EXECUÇÃO LOCAL COM OLLAMA
1. Instalar Node.js 18+: https://nodejs.org/
2. Instalar Ollama: https://ollama.com/
3. Abrir terminal e executar: ollama pull llama3.2:3b
4. Copiar .env.example para .env.
5. Na pasta do projecto, executar: node server.js
6. Abrir: http://localhost:8787

Se o computador não tiver memória/recursos suficientes, escolher um modelo mais pequeno compatível com o Ollama ou usar um fornecedor cloud, verificando custos e limites.

PUBLICAÇÃO ONLINE
- É necessário alojar a aplicação e backend num serviço que suporte Node.js e HTTPS.
- Não colocar a chave API no HTML/JavaScript do navegador.
- Configurar limites de utilização, protecção contra abuso, monitorização e política de privacidade.
- A versão ainda não inclui contas, pagamentos, sincronização, APK Android ou integração WhatsApp.

SEGURANÇA E QUALIDADE
- Não recolher dados pessoais de estudantes nesta versão.
- Antes de testar com menores, obter autorizações adequadas e definir protecção de dados.
- As respostas de IA podem conter erros; professores devem validar conteúdos e alinhamento curricular por país/nível.
- Em Enfermagem, conteúdo apenas educativo; não substitui supervisão clínica, protocolos, diagnóstico ou prescrição.
- Verificar os termos e políticas de dados do fornecedor antes de enviar perguntas de utilizadores.

Versão 0.4 — protótipo funcional de desenvolvimento, não serviço público pronto para lançamento.
