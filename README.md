<div align="center">
  <img src="icon.png" alt="Lyrian App Icon" width="120" style="border-radius: 26px; box-shadow: 0 10px 30px rgba(181, 136, 247, 0.3);" />
  <h1>Lyrian — Support, Privacy & Terms</h1>
  <p><strong>Transforming sound into a multisensory voyage of light, motion, and touch.</strong></p>
  <p><em>Página oficial de suporte, termos de uso, política de privacidade e licenças do aplicativo Lyrian.</em></p>
</div>

---

## 🌟 Sobre o Lyrian (About Lyrian)

**Lyrian** é um aplicativo imersivo para **iPhone** e **Apple Watch** que transforma a experiência musical em algo multissensorial. 

Utilizando modelos de inteligência artificial de última geração para separação de fontes sonoras executados **100% localmente no dispositivo (on-device via CoreML)**, o app isola instrumentos e vocais (*vocals, drums, bass, other*), convertendo frequências e ritmos em **vibrações táteis sincronizadas (Haptic Feedback)** e **visualizadores dinâmicos reativos em tempo real**.

---

## 📂 Estrutura do Repositório (Pages Structure)

Este repositório contém as páginas estáticas oficiais disponibilizadas publicamente (compatíveis com o **GitHub Pages**) para atender às exigências das diretrizes de revisão da Apple App Store, Google Play e legislações de proteção de dados (como LGPD e GDPR):

| Página | Arquivo | Descrição |
|---|---|---|
| **Suporte & FAQ** | [`index.html`](index.html) | Central de suporte ao usuário, apresentação das funcionalidades, perguntas frequentes e canal direto de e-mail (`lyrianapp@gmail.com`). |
| **Política de Privacidade** | [`privacy.html`](privacy.html) | Documentação detalhada sobre tratamento de dados, processamento estritamente local de IA, integrações Apple (ShazamKit, CloudKit, Apple Music, WatchConnectivity) e direitos LGPD. |
| **Termos de Uso** | [`terms.html`](terms.html) | Condições gerais de uso, licença do software, responsabilidade de direitos autorais sobre áudios importados, limitações da IA e avisos de segurança/bem-estar sensorial. |
| **Código Aberto & Licenças** | [`licenses.html`](licenses.html) | Cumprimento das exigências da **Licença MIT** para os modelos neurais **HTDemucs** e **SCNet**, além do aviso sobre faixas demo livres de royalties (CC0 / Domínio Público). |

---

## ✨ Destaques de Implementação (Web Design & Features)

- **Suporte Bilíngue Instantâneo:** Todas as páginas contam com alternador dinâmico de idiomas (**Inglês** e **Português**) sem recarregamento da página.
- **Identidade Visual Temática:** Estilo moderno *dark mode* (`#08080a`) com realces em lavanda/violeta luminoso (`#b588f7` e `#c084fc`), harmonizado com a iconografia de partículas sonoras do app.
- **Ícones Vetoriais SVG Coesos:** Navegação rápida padronizada entre todas as páginas com ícones SVG inline responsivos.
- **Design Responsivo & Acessível:** Layout fluido e tipografia limpa (*Plus Jakarta Sans*), otimizado tanto para dispositivos móveis quanto desktop.

---

## 🔒 Princípios de Privacidade & IA (Privacy Highlights)

1. **Separação por IA 100% On-Device:** Toda a inferência dos modelos **HTDemucs** e **SCNet** é executada no processador do próprio dispositivo do usuário. Nenhum arquivo de áudio ou gravação pessoal é enviado para a nuvem para fins de inferência ou treinamento.
2. **Reconhecimento Musical via ShazamKit:** As consultas utilizam apenas assinaturas acústicas (hashes matemáticos), sem transmissão do áudio original gravado.
3. **Catálogo Público CloudKit:** Download estritamente unidirecional para cache local. O app não faz upload de músicas pessoais para o banco público.
4. **Zero Rastreamento:** Ausência de bibliotecas de anúncios invasivos, rastreamento comportamental de terceiros ou venda de dados.

---

## 🚀 Como Publicar no GitHub Pages (Deployment)

Para servir as páginas através do GitHub Pages:
1. Acesse o repositório no GitHub: **Settings > Pages**.
2. Em **Source**, selecione **Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`.
4. Clique em **Save**. O site estará disponível em `https://<seu-usuario>.github.io/Lyrian---Support/`.

---

## 📬 Contato & Suporte (Contact)

Dúvidas, sugestões ou suporte técnico:
- **E-mail:** [lyrianapp@gmail.com](mailto:lyrianapp@gmail.com)

---

<div align="center">
  <sub>&copy; 2026 Lyrian. Todos os direitos reservados.</sub>
</div>
