<div align="center">

# Fujii Advocacia & Consultoria Jurídica

### Site institucional · Desenvolvimento por ZTech Solutions

Uma apresentação digital das áreas de atuação, do escritório e dos seus canais de atendimento.

[![Fujii Advocacia — desktop e mobile](docs/images/fujii-mockup.png)](https://fujiiadvogados.vercel.app/)

[🌐 Acessar o site](https://fujiiadvogados.vercel.app/) · [💻 Código-fonte](https://github.com/zenaldo-oliveira/fujii-advocacia) · [👨‍💻 Meu portfólio](https://zenaldo-portfolio-react.vercel.app/#projetos)

**React · TypeScript · TanStack Start · Tailwind CSS**

</div>

---

## O projeto

Site institucional desenvolvido e personalizado para a Fujii Advocacia & Consultoria Jurídica.

O projeto combina uma identidade visual em azul-marinho, off-white e dourado com navegação organizada por áreas do Direito. O conteúdo apresenta o escritório e facilita o acesso aos canais de contato em computadores e dispositivos móveis.

## Áreas de atuação

- Direito Tributário.
- Direito Agrário e do Agronegócio.
- Direito Previdenciário.
- Direito Civil.
- Direito do Consumidor.
- Direito do Trabalho.

## Recursos da interface

- Carrossel de apresentação.
- Páginas com áreas de atuação e subáreas.
- Menu adaptado para dispositivos móveis.
- Formulário de contato com validação.
- Acesso ao WhatsApp e às redes sociais.
- Mapa e links de localização.
- Componentes com navegação por teclado e foco visível.
- Suporte à preferência por movimento reduzido.

## Tecnologias utilizadas

| Finalidade | Tecnologias |
|---|---|
| Interface | React e TypeScript |
| Aplicação e navegação | TanStack Start e TanStack Router |
| Estilização | Tailwind CSS e shadcn/ui |
| Formulários e validação | React Hook Form e Zod |
| Carrossel | Embla Carousel |
| Ícones | Lucide React |
| Build | Vite e Nitro |
| Backend de contato previsto | PHP e SMTP |

## Executar o projeto

Com Node.js, npm e Git instalados:

```bash
git clone https://github.com/zenaldo-oliveira/fujii-advocacia.git
cd fujii-advocacia
npm ci
npm run dev
```

Abra o endereço informado no terminal.

### Comandos

```bash
npm run dev      # Desenvolvimento
npm run build    # Build de produção
npm run preview  # Prévia local
npm run lint     # Análise estática
npm run format   # Formatação
```

## Organização e manutenção

| Arquivo ou pasta | Responsabilidade |
|---|---|
| `src/assets/` | Imagens e arquivos da marca |
| `src/components/` | Componentes reutilizáveis |
| `src/routes/` | Páginas e rotas |
| `src/lib/site.ts` | Contatos, redes sociais, endereço e mapa |
| `src/lib/areas.ts` | Áreas de atuação e subáreas |
| `src/components/brand-mark.tsx` | Apresentação da marca |
| `src/components/contact-form.tsx` | Interface do formulário |
| `public/api/contato.php` | Endpoint PHP de contato |

## Formulário de contato

O envio utiliza um endpoint PHP com configuração SMTP própria.

O Vite não executa PHP. Para testar o envio localmente, é necessário disponibilizar um servidor PHP e configurar o encaminhamento da API.

A publicação da interface na Vercel não garante o funcionamento do endpoint. O backend precisa de hospedagem compatível ou adaptação para a plataforma escolhida.

Consulte [DEPLOY-HOSTINGER.md](./DEPLOY-HOSTINGER.md) e `docker-compose.dev.yml` para os detalhes do ambiente previsto.

**Nunca envie senhas, tokens ou credenciais SMTP ao repositório.**

## Demonstração

🔗 **https://fujiiadvogados.vercel.app/**

Após publicar alterações, confira o commit implantado, o carregamento das páginas e o funcionamento dos canais de contato.

## Desenvolvedor

**Zenaldo Pereira de Oliveira**  
**ZTech Solutions — Desenvolvimento Web**

Projeto apresentado como parte do meu portfólio de desenvolvimento.

[Portfólio](https://zenaldodev.com.br/) · [GitHub](https://github.com/zenaldo-oliveira)

## Direitos de uso

A marca, os textos institucionais e as imagens pertencem aos respectivos titulares.

A disponibilização pública deste repositório não concede automaticamente licença para reutilização do código ou dos materiais. As dependências utilizadas seguem suas respectivas licenças.
