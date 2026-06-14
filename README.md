# Mark Mordvin

**Software engineer. I build complete systems end to end, from data architecture to deployment.**

I lead technical development at epoint, a digital transformation agency, where I rebuilt the company's ERP (Odoo) and corporate website and deliver client projects end to end. I also build my own products. My work spans full-stack development, applied AI, and business and ERP automation.

I have delivered for institutions and companies including the Ayuntamiento de Orgaz, the Ayuntamiento de Belmonte, FEDETO, Cereales Alcamancha, and the Bono Comercio Toledo program (40+ local businesses). I care about correctness: atomic database operations, automated tests, and security reviews of my own code.

## Tech

|   |   |
| --- | --- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Frameworks** | ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native_(Expo)-000020?style=flat-square&logo=expo&logoColor=white) |
| **Data and infrastructure** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Neon](https://img.shields.io/badge/Neon-00E599?style=flat-square&logo=neon&logoColor=black) ![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **AI** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square) ![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Vercel AI SDK](https://img.shields.io/badge/Vercel_AI_SDK-000000?style=flat-square&logo=vercel&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square) |
| **Platforms and integrations** | ![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white) ![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) |

## Selected systems

Most of my strongest work is private or client-owned. A representative sample:

**Applied AI**
- **AI document-to-Excel SaaS** - turns invoices, statements and photos into structured spreadsheets with vision models, plus a Spanish tax engine (VAT 21/10/4, modelo 303/130) and subscription billing.
- **Legal RAG assistant** - answers grounded in the official Spanish state gazette (BOE) with citations; pgvector with an HNSW index.
- **Multi-tenant AI chatbot platform** - white-label assistants configured per client, each with its own RAG knowledge base, moderation and embeddable widget.
- **AI short-form video studio** - generates vertical videos end to end (script, voice, animated visuals and programmatic render) across five TTS providers.

**Systems and integrations**
- **Biometric attendance into an ERP** - streams data from facial-recognition terminals into an ERP in real time by reverse-engineering the terminal push protocol; includes payroll e-signing over WhatsApp.
- **Omnichannel inbox** - email, WhatsApp and WeChat unified in a single inbox with AI triage and assisted replies.
- **Industrial ERP integration** - mirrors a 33,000-record ERP into Postgres over an undocumented SOAP API, cutting a full sync from 30s to about 3s.
- **Apple and Google Wallet loyalty** - a loyalty-card platform issuing native Apple and Google Wallet passes in production.

**Fintech and quant**
- **Fiscal-grade POS and invoicing** - Spanish tax-compliant: atomic gap-free numbering, immutable rectifying invoices, modelo 303/130, full audit log.
- **Quantitative trading platform** - four parallel strategies across crypto and US equities, a custom technical-indicator library, and several LLMs evaluated head-to-head; every rule backed by peer-reviewed research.

## Public projects

<table>
  <tr>
    <td width="22%" valign="top">
      <a href="https://github.com/MarkMdvn/aidoo">
        <img src="https://raw.githubusercontent.com/MarkMdvn/aidoo/main/public/images/products-example.png" width="100%" alt="Aidoo" />
      </a>
    </td>
    <td width="78%" valign="top">
      <a href="https://github.com/MarkMdvn/aidoo"><b>Aidoo - natural-language Odoo assistant</b></a>
      <br /><br />
      Query an Odoo ERP in plain language. Agentic RAG over the live ERP schema with vector search (pgvector), strictly read-only.
      <br /><br />
      <b>Stack:</b> Next.js, TypeScript, Vercel AI SDK, PostgreSQL/pgvector
    </td>
  </tr>
  <tr>
    <td width="22%" valign="top">
      <a href="https://github.com/MarkMdvn/uallapop">
        <img src="https://raw.githubusercontent.com/MarkMdvn/uallapop/main/WallapopClient/public/github-images/main-img.png" width="100%" alt="Uallapop" />
      </a>
    </td>
    <td width="78%" valign="top">
      <a href="https://github.com/MarkMdvn/uallapop"><b>Uallapop - second-hand marketplace</b></a>
      <br /><br />
      Full-stack marketplace with a decoupled API, JWT authentication, a polymorphic product model with per-category forms, search and seller ratings.
      <br /><br />
      <b>Stack:</b> Java, Spring Boot, React, MySQL, Docker
    </td>
  </tr>
  <tr>
    <td width="22%" valign="top">
      <a href="https://github.com/MarkMdvn/aws-web-chatbot">
        <img src="https://raw.githubusercontent.com/MarkMdvn/aws-web-chatbot/main/docs/assets/3-both-cases.jpg" width="100%" alt="Embeddable AI chat widget" />
      </a>
    </td>
    <td width="78%" valign="top">
      <a href="https://github.com/MarkMdvn/aws-web-chatbot"><b>Embeddable AI chat widget</b></a>
      <br /><br />
      A chat assistant that drops into any website (configured for epoint.es): serverless, backed by an AWS Bedrock agent, with streaming responses.
      <br /><br />
      <b>Stack:</b> Next.js, TypeScript, AWS Bedrock, Vercel AI SDK
    </td>
  </tr>
  <tr>
    <td width="22%" valign="top">
      <a href="https://github.com/MarkMdvn/qr-discount-wp">
        <img src="https://raw.githubusercontent.com/MarkMdvn/qr-discount-wp/main/public/github-readme-images/2-transacciones-realizadas.png" width="100%" alt="QR Discount Platform" />
      </a>
    </td>
    <td width="78%" valign="top">
      <a href="https://github.com/MarkMdvn/qr-discount-wp"><b>QR Discount Platform</b></a>
      <br /><br />
      Discount-campaign system for a local program of 40+ businesses: per-user QR issuance by email, single-use in-store verification, and transaction dashboards.
      <br /><br />
      <b>Stack:</b> WordPress, PHP, MySQL
    </td>
  </tr>
</table>

## Currently

Going deeper into electronics and embedded systems.

## Also

A couple of marketing sites I built: [mordvina.com](https://mordvina.com) and [vkulyk.com](https://vkulyk.com).

## Connect

[LinkedIn](https://www.linkedin.com/in/markmdvn/) · mark.mdvn@gmail.com
