# Instruções para Publicação do Site QAP TI no Netlify

Este documento contém instruções detalhadas para publicar o site da QAP TI na plataforma Netlify, que oferece hospedagem gratuita para sites estáticos com excelente performance.

## Método 1: Upload Direto (Mais Simples)

1. **Acesse o Netlify**
   - Vá para [https://app.netlify.com/](https://app.netlify.com/)
   - Faça login ou crie uma conta gratuita (pode usar sua conta Google, GitHub, GitLab, etc.)

2. **Inicie um Novo Site**
   - Na página inicial do Netlify, clique no botão "Add new site" e selecione "Deploy manually"
   - Ou simplesmente arraste e solte a pasta descompactada deste pacote na área indicada

3. **Configure o Site**
   - Após o upload, o Netlify detectará automaticamente as configurações necessárias
   - Clique em "Deploy site" para finalizar

4. **Personalize o Domínio (Opcional)**
   - Por padrão, o Netlify fornecerá um subdomínio aleatório (exemplo: happy-einstein-123abc.netlify.app)
   - Para personalizar, vá em "Site settings" > "Domain management" > "Custom domains"
   - Você pode usar um domínio gratuito do Netlify ou configurar seu próprio domínio

## Método 2: Conexão com GitHub (Para Atualizações Contínuas)

1. **Crie um Repositório no GitHub**
   - Acesse [https://github.com/new](https://github.com/new)
   - Crie um novo repositório (público ou privado)
   - Faça upload dos arquivos deste pacote para o repositório

2. **Conecte o Netlify ao GitHub**
   - No Netlify, clique em "Add new site" > "Import an existing project"
   - Selecione GitHub como provedor e autorize o acesso
   - Selecione o repositório que você criou

3. **Configure as Opções de Build**
   - Como este é um site estático já buildado, deixe os campos de comando de build vazios
   - Defina o diretório de publicação como "." (ponto, indicando a raiz)
   - Clique em "Deploy site"

4. **Atualizações Futuras**
   - Para atualizar o site no futuro, basta atualizar os arquivos no repositório GitHub
   - O Netlify detectará as mudanças e atualizará o site automaticamente

## Verificação e Testes

Após a publicação, verifique se:

1. O site está carregando corretamente
2. Todos os links internos funcionam
3. O formulário de contato está funcionando (o Netlify oferece funcionalidade de formulários)
4. O site está responsivo em dispositivos móveis

## Configuração de Formulário (Opcional)

Para que o formulário de contato funcione no Netlify:

1. Acesse "Site settings" > "Forms"
2. Ative a funcionalidade de formulários
3. Adicione o atributo `data-netlify="true"` ao formulário HTML se necessário

## Suporte

Se precisar de ajuda adicional:
- Consulte a documentação do Netlify: [https://docs.netlify.com/](https://docs.netlify.com/)
- Entre em contato com o desenvolvedor do site para suporte técnico

---

Desenvolvido para QAP TI - Soluções em Segurança Eletrônica
CNPJ: 57.910.047/0001-00
