<img width="1809" height="859" alt="image" src="https://github.com/user-attachments/assets/3952f610-cb23-41df-9613-d173e4ecbf92" />
# 📄 VagaMatch

Seu currículo ajustado para a vaga que você quer.  
Aplicativo desenvolvido no **Lovable** para marketing de vagas de emprego e criação de currículos **ATS-friendly**, totalmente funcional **sem necessidade de cadastro**.

---

## 🚀 Objetivo
O VagaMatch ajuda candidatos a:
- Importar ou criar currículos.
- Analisar descrições de vagas.
- Gerar versões otimizadas para sistemas ATS.
- Baixar e organizar currículos e candidaturas.

---

## 🎨 Design
- **Design System**: [ShadCN UI](https://ui.shadcn.com/)
- **Paleta de cores**:
  - Azul escuro `#0A1F44`
  - Branco `#FFFFFF`
- Estilo: Minimalista, moderno e confiável.

---

## 🔑 Principais Características
- **Zero fricção**: uso imediato sem login ou cadastro.
- **Armazenamento local**: dados salvos automaticamente via `localStorage` ou `IndexedDB`.
- **Privacidade**: dados permanecem no dispositivo do usuário.
- **Compatibilidade ATS**: geração de currículos adaptados às vagas.
- **Exportação**: currículos em PDF.
- **Dashboard intuitivo**: acesso rápido às funcionalidades.

---

## 📲 Fluxo do Usuário
1. **Página inicial** → CTA **Começar agora**
2. **Meu currículo** → Importar PDF ou criar do zero
3. **Analisar vaga** → Colar descrição da vaga
4. **Compatibilidade** → Score, requisitos, keywords, lacunas
5. **Criar currículo ATS** → Versão otimizada
6. **Revisar** → Editar informações
7. **Baixar** → Exportar currículo em PDF
8. **Registrar candidatura** → Empresa, cargo, data, status

---

## 🗂️ Menu
- Dashboard
- Meu currículo
- Encontrar vagas
- Analisar vaga
- Meus currículos
- Candidaturas
- Favoritos
- Configurações

---

## ⚡ Regra Fundamental
O aplicativo deve funcionar **sem autenticação**.  
Fluxo ideal: **Entrar → Usar → Gerar resultado**.

---

## 🔮 Futuro
Arquitetura preparada para opcional:
- **Criar conta** para sincronizar dados entre dispositivos.  
*(Funcionalidade futura, não obrigatória no MVP).*

---

## 📌 Aviso de Privacidade
> Seus dados permanecem neste dispositivo enquanto você utiliza a versão sem conta.  
> Importante: se você limpar os dados do navegador ou trocar de dispositivo, seus dados locais poderão ser perdidos.

---

## 🛠️ Instalação e Execução
Este projeto foi criado no **Lovable**.  
Para rodar localmente:
1. Clone o repositório.
2. Instale dependências:
   ```bash
   npm install
